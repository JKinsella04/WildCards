# WildCards Driver Control and Autonomous Programs
**Intro Stuff**

README updated at 4/7/18

## Driver Control Programs
  1. [NewControl](https://github.com/JackKinsello/WildCards/blob/master/NewControl.c) (Our first driver control program)
  
  Our first driver control was a basic one that we used for the majority of the year.
  The drivers had to do everything and there was no automatic sorter or dumping.
  
  2. [AutoDrive](https://github.com/JackKinsello/WildCards/blob/master/autoDrive.c) (The advanced controls)
    
   We added a 
   **LOT**
   of improvments to the controls with this program. With this we now had an autosorter for the intake to make it easier to pick up rings.
   We also had made many movements into their own button instead of taking two buttons to go up and down.
   
   For example we used to have two buttons for the claw (One to go up and the other to go down). But with the new controls you only have to press one button for the claw to work.
   We did the same for dumping as well.
   
   One of the most important things we did in this control is that we put a 
   **__cheat code__**
   in it. We did this as a backup in case something with the new controls glitch out and can't be fixed mid-match.
   What the cheat code does is when the drivers press it, the robot stops doing the new controls and goes back to the old controls, while still staying in the same program
   
   
## Autonomous Programs

1. [AutoTim1](https://github.com/JackKinsello/WildCards/blob/master/autoTim1.c)

  This is the autonomous for picking up and scoring the blue rings off the wall. We use many functions and tasks that we have made. Such as our line counting function,
  our and our allign function. These two in particular are quite important because they are used throughout the entire program to help make the program more accurate.
  Some of the tasks we use are Fix Drift and drive. These two are important since some functions use them.
  
2. [AutoTim2](https://github.com/JackKinsello/WildCards/blob/master/AutoTim2.c) & [AutoTim2.1](https://github.com/JackKinsello/WildCards/blob/master/autoTim2.1.c)
 
  These two both are for picking up the green rings and dumping them. Currently we are using AutoTim2
  in competitions since it is more accurate. AutoTim2 and AutoTim2.1 both use functions and tasks from [AutoTim1](https://github.com/JackKinsello/WildCards/blob/master/autoTim1.c)
  The only difference in between AutoTim1 and AutoTim2 is that AutoTim2 scores on the low post instead of the horizontal post
  
3. [AutoTim3](https://github.com/JackKinsello/WildCards/blob/master/AutoTim3.c)
  
  AutoTim3 is just like AutoTim1 except it picks up the red rings instead of the blue rings.
  
  ## Functions and Tasks
  
  1. [ColorCheckOrg](https://github.com/JackKinsello/WildCards/blob/master/colorCheckorg.c) & [ColorCheck](https://github.com/JackKinsello/WildCards/blob/master/colorCheck.c)
    
    These are the original programs that we made for sorting colors automatically. 
    This is essentially AutoDrive but without the other driver controls
  
  
  
  
  
  
  
  
  
  
  
  
