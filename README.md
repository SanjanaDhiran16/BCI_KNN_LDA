# BCI_KNN_LDA
Its a classification  technique to detect emotion using brain waves and uses LDA and KNN . 

Following is the way it was done in the code
Step 1: Separate data from labels and create separate files for valence, arousal, dominance and liking.
Step 2: divide labels into classes so as to detrmine emotions later on.
Step 3: Split the data into training/testing sets
Step 4: Apply feature scaleing, LDA and KNN classifier.
Step 5: Apply Russell Circumplex model
Step 6: Display emotions using emoticons

Russell Circumplex model:
This model suggests that emotions are distributed in a two-dimensional circular space, containing arousal and valence dimensions. Arousal represents the vertical axis and valence represents the horizontal axis, while the center of the circle represents a neutral valence and a medium level of arousal.In this model, emotional states can be represented at any level of valence and arousal, or at a neutral level of one or both of these factors. Circumplex models have been used most commonly to test stimuli of emotion words, emotional facial expressions, and affective states.

DataBase used : Deap Database can be found at https://www.eecs.qmul.ac.uk/mmv/datasets/deap/ .
