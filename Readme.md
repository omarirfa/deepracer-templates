## Deepracer Templates
- Have added some normal templates (deepracer_follow_center, deepracer_stay_between_borders and deepracer_zigzag).
- Made a combined version with the existing templates (deepracer_combined) and one which tweaks the speed param directly (deepracer_combined_speed).











### Tips and tricks
- Model convergence and knowing how your model works is quite important before setting it up to run. The more complex the reward function the more time it will take to converge and you will subsequently need to tune the hyperparameters as well.
- Log analysis can further improve the reward function by using the custom waypoints parameter. You can find more details at [AWS-deepracer-workshops].
- Steering angle, steering threshold and closest_waypoints can be improved using math functions so that the car calculates the waypoints on the fly.




[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [AWS-deepracer-workshops]: <https://github.com/aws-samples/aws-deepracer-workshops>