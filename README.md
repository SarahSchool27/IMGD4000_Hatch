Sarah Hatch <br>
IMGD 4000 <br>
December 2025 <br>


## About
Greetings!
This repository holds the individidual tech submissions for WPI Class IMGD 4000 that Sarah Hatch finished.
There is a portfolio submission for the game Rubbish Rumble and an implementation of Boids algorithim in Unreal.

## File Structure

    Root
        Hatch_RubbishRumble_Portfolio.md        (Portfolio Submission)
        README.md                               (this file)   
        BoidsDemoVideo.mp4                      (video showcasing the Boids Algorithm)

        Folders:
        PortfolioImages                         (Images referenced in Hatch_RubbishRumble_Portfolio.md)
        Hatch_Unreal_Boids                      (The Unreal project for Boids)



## Boids Implementation Notes

[BoidsDemoVideo uploaded to OneDrive](https://wpi0-my.sharepoint.com/:v:/g/personal/smhatch_wpi_edu/IQBjn-9KcroZQJizZB1BCLhuAWvdEFy1VVqgQZaPLNivJak?e=VZyus9)  
    

A simple Boids implementation in Unreal utilizing the three main Boids rules as well as limiting max speed and
and keeping boids within a rectangular boundary box.

Contains two classes, a Boids class and a BoidManager class. 
    
The BoidManager class does the bulk of the work and updates velocities and positions every 0.03 seconds.

The Boids class stores the variable positions and velocities of individual boids, as well as determining and communicating
whether the object is out of bounds.

#### Boids Algorithim References:

http://www.kfish.org/boids/pseudocode.html
https://vanhunteradams.com/Pico/Animal_Movement/Boids-algorithm.html 


