# Rock-Paper-Scissors-BOT
This project is a Rock-Paper-Scissors (RPS) bot powered by Markov Chains, designed to predict and counter human moves by analyzing behavioral patterns.

Features
	•	Markov Chain Prediction:
	•	Utilizes a transition matrix to predict the player’s next move based on historical patterns.
	•	Dynamically updates probabilities during gameplay for real-time adaptation.
	•	Move History Tracking:
	•	Stores the last 10-15 moves using a deque to identify trends and improve predictions.
	•	Strategic Counterplay:
	•	Predicts the player’s next move and selects the optimal counter-move to maximize its chances of winning.
	•	Learning and Adaptation:
	•	Continuously learns from the player’s behavior, becoming smarter over time.
	•	Unpredictability:
	•	Introduces randomness when probabilities are close to avoid predictable patterns.

How It Works
	1.	Tracks the sequence of the player’s moves.
	2.	Updates a transition matrix to calculate the probability of each possible next move.
	3.	Selects the move that beats the predicted player move (e.g., predicts “Rock” → plays “Paper”).
	4.	Adapts dynamically as the game progresses, refining its predictions.
