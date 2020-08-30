# FIFA Machine Learning Project

This is the final project for machine learning class.

In the FIFA 19 dataset, each player contains numerous in-game attributes that distinguish them from one
another. The attributes of each player are carefully engineered by the game developers to accurately represent
their real-life counterparts. After extensive data cleaning, we conducted Principal Component Analysis before
implementing classification techniques to see if the players’ attributes showed any distinctive patterns based on
their positions. After conducting PCA analysis on players’ positions, classifying players according to their
positions alone seemed simpler than we expected. To complicate the classification process, we proceeded to
create a new set of classifiers that combined the players’ ages and positions, namely ‘pagegroup’ (Position + Age
group). The classification techniques we implemented include K-Nearest Neighbors, Random Forest, LDA, and
various methods through scikit-learn in Python. Fortunately, all classification techniques performed better than the
expected accuracy from random guessing, but certain classification techniques, such as XGBoosting, Gradient
Boosting, and Bagging, had significantly higher test accuracies than other classification methods.

In the second part of the project, we wanted to test how accurately the player attributes from FIFA 19
predict the players’ real-life performances. We imported another dataset that gave us the real-life performances of
the players across 5 major European Leagues. Based on the real-life performances of the players, we constructed
another classifier ‘perf’ that divided the players based on their performance ratings. Similar to our analysis done
on FIFA 19 attributes, we conducted Principal Component Analysis on players’ performances. Among the
classification techniques, XGBoosting, Logistic Regression, and LDA performed the best. Then, we used several
regression techniques such as PCR, Ridge, and Lasso to test how accurately the players’ attributes from FIFA 19
predicted the players’ real-life ratings.
