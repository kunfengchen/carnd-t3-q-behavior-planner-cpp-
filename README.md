# carnd-t3-q-behavior-planner-cpp-
This is an exercise cloned from the term 3 of the Self-Driving Car Nanodegree from Udactiy 

## Implement a Behavior Planner
In this exercise you will implement a behavior planner for highway driving. It will use prediction data to set the state of the ego vehicle to one of 5 values:

"KL" - Keep Lane
"LCL" / "LCR"- Lane Change Left / Right
"PLCL" / "PLCR" - Prepare Lane Change Left / Right
Instructions
Implement the update_state method in the vehicle.cpp class.
Hit Test Run and see how your car does! How fast can you get to the goal without colliding?

## Output examples
```
+Meters ======================+ step: 37
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     | 011 |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
300 - |     |     |     |     |
      |     | 012 |     |     |
      |     |     |     |     |
      |     | 013 |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     | *** |     |
      |     |     |     |     |
      |     |     |     |     |
      |     | 014 |     |     |
      |     |     | 015 |     |
      |     |     | 016 |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
320 - |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
      |     |     |     |     |
You missed the goal. You are in lane 2 instead of 0
```
