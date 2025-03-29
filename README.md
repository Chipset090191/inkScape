# inkScape
I developed SCADA HMI files using the Inkscape app. In these projects, I used SVG animation to bring them to life. I’ve attached screenshots below so you can see how it works.

### Explanation of how fan starts rotating

We use coordinates x and y as a center point of our rotation in Incscape. I also set the mark name "exaust_vent" to get an access to our object.

<img width="863" alt="Screenshot 2025-03-28 at 19 21 48" src="https://github.com/user-attachments/assets/d3081331-adde-47b4-a010-68aff26a8fda" />

Then, we simply open our SVG project file using a text editor and add the "animateTransform" block. The main options we can adjust are:

repeatCount – Defines whether the rotation is finite or infinite.
dur – Controls the speed of rotation in seconds.
from and to – Determines the direction of rotation and the center point (x and y coordinates) mentioned earlier.
type – Specifies the type of animation.

For example, if we link the "dur" parameter to equipment like a frequency control unit, the user or engineer can see real-time speed changes as they happen in reality. Similarly, if a relay signal is 0, indicating that the system is not functioning, the engineer will see this reflected on the screen. This example demonstrates how we can use signals from equipment to manipulate animations, visually representing real-time statuses from the PLC.

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













