#Facebook Friend Suggestion
This code uses NetworkX to analyze a social network graph and suggest a friend for a given user based on a similarity score. The program reads in an edgelist file, which contains the edges of the graph. It prompts the user to enter a node (i.e., a Facebook user), and then computes a similarity score between the user and all non-neighbors. Finally, it suggests a friend with the highest similarity score as a friend recommendation.

Requirements
To run this code, you will need to install the following packages:

pandas
numpy
networkx
matplotlib
You can install them using pip, a package manager for Python. To install them, run the following command:

Copy code
pip install pandas numpy networkx matplotlib
Usage
To use this program, you need to have a text file containing the edgelist of the social network graph. You can then run the following command to execute the program:

Copy code
python friend_suggestion.py
The program will prompt you to enter a node (i.e., a Facebook user) for which you want to suggest a friend. After that, it will prompt you to select a similarity score metric:

Common Neighbors
Jaccard's Coefficient
Preferential Attachment
The program will then compute the similarity score between the user and all non-neighbors, and suggest a friend with the highest similarity score.
