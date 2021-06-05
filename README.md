# SLAM Implementation
Simultaneous localization and mapping in python &amp; pytorch : ) 

## Approach : 
* Pragmatic 
* Delievery-based 
* Don't waste time around - store complicated useful information to come-back later to



## Plan of attack : 
#### *Current Stage - 1*
### Stage 1 - Learn, Understand & answer self-imposed questions:
  * Qs: 
    * What will be our Input? What exact form will it have? Do we care about colours ? Why (not)?
    * What will be our Output? What exact form will it have? 
    * What AI architecture should I use? Is U-Net any good here? 
    * Will I have enough computational power (training on videos seems heavy) - 
  * Resources I found most useful:
    * https://www.youtube.com/watch?v=7Hlb8YX2-W8 - George Hotz's SLAM implementation, a big part of my work was based on that man's genius
    * ...
### Stage 2 - Pre-Processing:
  * Get Data
  * Explore Data
  * Pre-Process & Transform Data into form You need 
  * If not enough data - data augmentation
### Stage 3 - Set-up AI Architecture :
  * Set-up Input Pipeline
  * Make sure Your ANN gets the input in the right, & outputs in the right form
  * Use best initializing methods for weights (was it normal distribution ?)
### Stage 4 - Train & Test :
  * Iterative process of Training & Testing 
### Stage 4 - Improvement 
  * How can I improve at least slightly upon that architecture? (Read through papers that used similar architecture but for different projects)
  * SWA any good ? 



