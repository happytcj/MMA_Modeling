**more notes in GoodNotes/Blog**

stats:
http://stattrek.com/matrix-algebra/covariance-matrix.aspx
https://onlinecourses.science.psu.edu/stat505/node/51
http://www.stat.yale.edu/Courses/1997-98/101/sigtest.htm
https://onlinecourses.science.psu.edu/stat504/node/150

extra:
https://www.reddit.com/r/MMA/comments/3p0y44/reach_advantagedisadvantage_doesnt_matter_in_an/

Data to pull:

- [x] On ufc.com, start at fighter rankings page: http://www.ufc.com/rankings?fb_comment_id=6086517324953#f10c8f9e6edcfe
- [x] for each fighter, pull their reach and the results of each fight with other fighters who are also on the list
- [x] should now have a dataset of reach differential and fight results between top competitors in order to feed into the logistic regression function
- [x] using selenium, click the form and pull bout info for all fighters in the top 10 page
- [x] In Analysis notebook, convert the fight results list into a deltas dataframe for top15 fighters
- [ ] Great! Now to do some preprocessing(scale, etc), transformations, look for more predictors, and tune the algorithms
- [ ] Bring back the use of clustering of fighters into 'styles' as another predictors
- [ ] Use hype/odds data ala www.filmawardwinners.com/
