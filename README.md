# Soccermatics_assignment_2

This my result for the second assignment of the open version of David Sumpter's course **Soccermatics - Mathematical Modelling in Football** of fall 2022.

The task was the following:

You are the working at a Premier League club in the summer break of 2018 and are tasked to recommend a new signing to improve the defence of your club. Choose 4-6 defensive metrics and create player radars to identify a weakness in your defense. Then find the top ten players in one of the metrics in another league, choose one of the players to recommend and create a radar for him.

Part of the assignment was to write a 3 page report and hold a 2 minute presentation.

The data used in this assignment is from wyscout, available as described here: https://soccermatics.readthedocs.io/en/latest/gallery/plot_UsingWyscout.html

To support my claim that shots and passes from free kicks are generally more dangerous than from open play i trained two expected threat models and visualized the difference as found on the last slide of my presentation. The code for training those models and for generating the visualization can be found in the notebooks **chains** and **xt_set_pieces**. The code for my radars and the creation of the defensive metrics can be found in the notebooks **defensive_metrics**, **radars** and **radars_germany**.
