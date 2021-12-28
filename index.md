## SLAM Beginner Resources
Disclaimer: TODO
## Text Book:
I could not find much in the real of text books for robotic vision with the exception of [Proabilisitc Robotics](https://docs.ufpr.br/~danielsantos/ProbabilisticRobotics.pdf). This covers more classicical mapping and planning methods (EKF, Particle Filters etc).

[Multi-View Geometry in Computer Vision](http://www.r-5.org/files/books/computers/algo-list/image-processing/vision/Richard_Hartley_Andrew_Zisserman-Multiple_View_Geometry_in_Computer_Vision-EN.pdf) is also very useful for those more interested in Computer-Vision (like myself). The text also has good notes on the mathematical tensor notation (which looks very scary), Matrix Properties and Decompositions as well as optimization methods in the appendix. 

## Starting/Tutorial Videos:
I found Cyrill Stachniss's vidoes ([his youtube channel](https://www.youtube.com/channel/UCi1TC2fLRvgBQNe-T4dp8Eg)) to be incredibly useful when trying to delve into this complex topic. His videos are short and succinct and provide good coverage of a lot of basics, without going into the maths too deeply. The following are the ones I found the most useful to start with. 
- [Introduction to SLAM](https://www.youtube.com/watch?v=0I30M6yTklo)
- [Graph-based SLAM using Pose Graphs](https://www.youtube.com/watch?v=uHbRKvD8TWg&t=2912s)
- [Probability Primer for Probilisitic Robotics](https://www.youtube.com/watch?v=JS5ndD8ans4)

## Conceptual/Current Work/Tutoriial Videos:
The next set of links are more useful if one already has a small grasp on some of the basic SLAM/Robotic Perception concepts. [Airlab](https://www.youtube.com/c/AirLab) has a fantastic set of vidoes including their [Tartan SLAM Series](https://www.youtube.com/playlist?list=PLpJxwrRy4QbvkeWEkSSBhny4C2FhvQ08i) (and the follow up [Fall Edition](https://www.youtube.com/playlist?list=PLpJxwrRy4QbsO3_0rPH9n6SkR55KaNF28)).

To quote the series aim: '_The goal of this series is to expand the understanding of those both new and experienced with SLAM._ '
 They are all very educational and most of the presenters cover the basicis of SLAM in their own way in each video at the start before going into their own work. The following a series of videos in those series that were highlights for me:

- [Factor Graphs and Robust Perception | Michael Kaess](https://www.youtube.com/watch?v=JmR2YpkLNt0&t=3608s)


## Tutorials and Papers
NOTE: I've tried to order them by what I think is the most useful as an introductory resource.  
- [Past, Present, and Future of Simultaneous Localization And Mapping: Towards the Robust-Perception Age](https://arxiv.org/abs/1606.05830) - A fantastic survey of the current state of SLAM (up to 2016), covering recent seminal works and short mathmatical coverage of the SLAM problem. 
- [Reducing Uncertantity about the uncertanties (Part 1 or 3)](https://gtsam.org/2021/02/23/uncertainties-part1.html) - This quick tutorial (from GTSAM Blog Posts) covers some general aspects of optimization-based state estimation methods and how to quantity uncertainties. Parts 2 and 3 introduce the idea of manifolds (eg. Special Euclidean Spaces, _SE(3)_ spaces) which come up all the time in robotics. 
- [Visual Odometry Tutorial](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjVjdqr-4X1AhXPS2wGHUd1BgMQFnoECAoQAQ&url=http%3A%2F%2Frpg.ifi.uzh.ch%2Fdocs%2FVO_Part_I_Scaramuzza.pdf&usg=AOvVaw3WBC4NwekCt620kHrdolAQ) - a short PDF summarising the Visual Odometry (VO) problem and common approaches to the problem. Great for conceptual udnerstanding without too much maths.


