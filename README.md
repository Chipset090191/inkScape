# inkScape
I developed files for SCADA HMI in InkScape app. In this projects I`ve used SVG-animation to make it life. I attached screenshots down below and there you can see how it works.

### Explanation of how fan starts rotating

We use coordinates x and y as a center point of our rotation in Incscape. I also set the mark name "exaust_vent" to get an access to our object.

<img width="863" alt="Screenshot 2025-03-28 at 19 21 48" src="https://github.com/user-attachments/assets/d3081331-adde-47b4-a010-68aff26a8fda" />

then we simply open our svg file project by using text editor and addign "animateTransform" block. So the main options we can adjust:
- repeatCount(definite or indefinite rotation)
- dur - the speed of or rotation in seconds
- to and from - direction of our rotation and center point that I`ve mantioned before x and y coordinates.  
- type - to determine the type of animation.

  So if we connect our parameter, for example "dur" to equipment like frequency control unit, the user or engineer in real time can see the change of speed as it work in reality. Or if the signal from relay is not positive and "0" means like system is not working, the engineer from the screen will see it too.  So the example shows how we can manipulate our animation by using signals from equipment showing statuses for user in real time from PLC.

<img width="436" alt="Screenshot 2025-03-28 at 19 19 43" src="https://github.com/user-attachments/assets/01399ddf-93f9-4128-8f05-38fd60872891" />
- 

### 1. Office inflow - exhaust ventilation

https://github.com/user-attachments/assets/d638f652-1341-47ec-8f98-5172c7c89b86

### 2. Boiler room for Logistic center

https://github.com/user-attachments/assets/2f4c4c50-8f3a-4721-99e2-a5ea863961a5

### 3. Refrigeration unit

https://github.com/user-attachments/assets/fbe7dba8-b3aa-4f00-b932-3052626c7706

### 4. Diesel-generator set

https://github.com/user-attachments/assets/1af4a151-6b88-45e2-9f13-7121ce523fa5













