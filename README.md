## Eric Martin's GitHub

These pages include background documents and supporting files related to the research titled Predicting Major League Baseball Strikeout Rates from Differences in Velocity and Movement Among Player Pitch Types. 

### Research Summary

Baseball enthusiasts frequently focus on how individual pitch characteristics like fastball velocity and curveball movement impact pitching results.  Studying these elements in isolation, however, fails to account for relationships among a pitcher’s different pitches.  The relationships among all pitches in a pitcher’s arsenal—rather than the characteristics of a single pitch—are a larger determinate of success.  

Using PITCHf/x information for over 2.5 million MLB pitches thrown by 402 pitchers from 2012 through 2017, model-based clustering techniques are used to group each pitcher’s pitches based on velocity, horizontal movement, and vertical movement.  The range of these measurements, the distance between clusters, and the distribution of pitch types are used in several machine learning models to predict annual pitcher strikeout percentages.  The best performing model has a mean absolute error of 2.94 percentage points from a pitcher’s actual strikeout percentage.  

Maximum pitch velocity and a pitcher’s strike rate are the most important predictors of strikeout percentage.  Both the maximum amount of vertical movement and the range of vertical movement among a pitcher’s pitches are the next most important predictors of strikeout percentage—more so than the ability to change speeds or a pitcher’s number of pitch types.  These insights may enable players to develop pitch characteristics most likely to increase strikeouts, assist coaches in identifying promising young pitchers, and ultimately help determine when pitchers should be removed from games.

### 2019 MIT Sloan Sports Analytics Conference Submission

An abbreviated summary of this research is available at
https://assets-global.website-files.com/5f1af76ed86d6771ad48324b/5f6d38971aa75c2f6af77911_Predicting-Major-League-Baseball-Strikeout-Rates-Update.pdf
