Text to SQL agent developed using smolagents library and Qwen2.5-72B-Instruct model.
The model can automatically create aggregate functions and join sql queries based on text description.

## Dataset

Dataset contianing behavior of Cafe Rewards members over a 30-day period, including their transactions and responses to promotional offers. The data is contained in three files: one with details on each offer, another with demographic information on each customer, and a third with the activity for each customer during the period. The activities are divided into offer received, offer viewed, offer accepted, and transaction. For a transaction to be attributed to an offer, it must occur at the same time as when the offer was "completed" by the customer.
