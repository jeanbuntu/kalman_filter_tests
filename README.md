# Kalman Filter Tests
I was getting nowhere with trying to learn the details of Kalman Filtering off the internet or I purely didn't know what to look for. I had a decent idea of what the filter is used for and I decided to try and build a simulator that does just that. 

##Steps
I'm going to jot down the steps of whatever I think I want to try so that I don't loose track along the way. 

*Make a pygame interface that simulates a car in a 1D motion, where I randomize the velocity is a controlled range
    *Needs a velocity randomizing function
    *Needs to monitor absolute position to keep track for ground truth
    *Needs to keep track of time 
    *Should just keep moving forward. 
    *Should print the distance in the right top corner.
    *should print the time right below that. 
    *Should have a box for the estimate to the left. 
    *Should have a box for the right below it.

*Make a Kalman Filter that predicts/estimates the position of car with respect to the start.
    *Estimator inputs
    *Dragon Radar:
        *Exact position with a *hypothetical dragon radar* of approximately 90% accuracy.
        *Create a fucntion that takes actual position as input and outputs a error infused(controlled_window/randomized) multiple 
    *Pre_error velocity of car. 

    *Estimator output
    * WELL ESTIMATE of position at any given time t
    
*Hot key kills simulation
*Plot of actual vs. Filter to measure convergence
*Build Unscented
*Build Extended
*Plot results



