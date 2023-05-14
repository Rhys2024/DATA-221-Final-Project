# Unintuitive Predictors of Success in Football (Soccer)


Full Paper is 'Unintuitive Predictors.pdf'

The sport of soccer has gained significant traction within the United States in recent years with the 
growing popularity of the MLS (Major League Soccer).  On a high-level, soccer is about scoring more than your opponent.  
The complexity of the game lies in the fact that the upper body cannot be used aside from the head (hence its original and 
more widely-used name “Football”).  Understanding how to create a goal and properly defend against the attack is no small feat, 
and all managers have their own theses on what types of actions are important for success.  
The goal of this project is to test the precision of machine learning techniques for predicting where teams will fall 
in the standings at the end of the year based on unobvious signals.  The results should give 1) an indication of how important 
the minutiae of soccer is in the success of professional teams and 2) an idea of which soccer actions,or features, 
are most predictive of performance--what should managers be focusing on if their team is having trouble scoring or defending?

Clearly, teams that score (and therefore assist) more while also conceding less goals will finish higher in the 
table -- these types of features have extremely strong correlations with league rank.  
Because we wanted to consider less obvious feature variables, we chose to leave out the more obvious predictors of 
league rank (a discussion of the removed features can be found in the appendix) in order to determine if there is meaningful 
predictive power in more granular features such as types of passes, tackles, clearances, headers won, dribbles, and much more.  

This project focuses on classification using Random Forest,  Neural Network, and SVM classification 
algorithms as well as a k-nearest neighbor algorithm, and predicts how well a team performed given the features considered.


Enjoy reading!
