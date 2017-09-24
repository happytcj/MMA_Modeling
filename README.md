**more notes in GoodNotes/Blog**

stats:
http://stattrek.com/matrix-algebra/covariance-matrix.aspx
https://onlinecourses.science.psu.edu/stat505/node/51
http://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html
http://stats.stackexchange.com/questions/35276/svm-overfitting-curse-of-dimensionality
http://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html
https://en.wikipedia.org/wiki/Logistic_regression
http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
http://www.stat.yale.edu/Courses/1997-98/101/sigtest.htm
https://onlinecourses.science.psu.edu/stat504/node/150

extra:
https://www.reddit.com/r/MMA/comments/3p0y44/reach_advantagedisadvantage_doesnt_matter_in_an/

Data to pull:

- [x] On ufc.com, start at fighter rankings page: http://www.ufc.com/rankings?fb_comment_id=6086517324953#f10c8f9e6edcfe
- [x] for each fighter, pull their reach and the results of each fight with other fighters who are also on the list
- [x] should now have a dataset of reach differential and fight results between top competitors in order to feed into the logistic regression function
- [] using selenium, click the form and pull bout info for all fighters in the top 10 page
