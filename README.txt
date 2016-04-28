############################################################################
# Data of Gaze-Mouse Coordination in tracing

# This dataset contains data from:

# Deng, S. et al. (2016) Gaze mouse coordinated movements and dependency
# with coordination demands in tracing. Behaviour & Information Technology.
# http://dx.doi.org/10.1080/0144929X.2016.1181209

# Data collector: Shujie Deng, e-mail: sdeng@bournemouth.ac.uk
#
# 15 Subjects
# 10 trial sets for each subject
# 9 trials in each trial set
# 1350 trials in total
#
# There are 3 trace shapes
# LD: a simple straight line
# MD: a simple curve
# HD: a complex curve
# In each trial set the subject did 3 times of each trace shape
# The order is LD MD HD MD HD LD HD LD MD
#
# Each trial set has one edf data file and one screen capture video
# Each trial has been splitted into 4 txt files
# eg. 
# t5e.txt for the eye movement data of the fifth trial in this trial set
# t5m.txt for the mouse movement data of the fifth trial in this trial set
# t5f.txt for the fixation data of the fifth trial in this trial set
# t5s.txt for the saccades data of the fifth trial in this trial set
#
# Each subject folder has a excel file
# It contains the trial starting and end timestamps
# It is for your convenience to split the trials from the edf file
###########################################################################
