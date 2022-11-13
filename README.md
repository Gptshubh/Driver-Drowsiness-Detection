# Driver-Drowsiness-Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.

# Logic of project
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.

![image](https://user-images.githubusercontent.com/91589008/201525346-7dd8e479-2fe5-4c04-802b-72e4816fa77d.png)

# The working of the project
1)As you can see the above screenshot where the landmarks aredetected using the detector.

2)Now we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'.

3)Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.

![image](https://user-images.githubusercontent.com/91589008/201525431-9d947e0b-4beb-4938-8066-801c797fa512.png)

![image](https://user-images.githubusercontent.com/91589008/201525496-d2e65155-ff1b-498a-a930-b112402c0133.png)

![image](https://user-images.githubusercontent.com/91589008/201525507-90979742-3e49-41b9-a27e-e2194ba34541.png)
