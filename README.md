## I letter Design

### Design Preview
![I-before](https://github.com/sadeem058/First-Week/blob/main/I-befor.jpeg)
![I-after](https://github.com/sadeem058/First-Week/blob/main/I-after.png)


________

## (ســـ) Design

•	Created a center-point circle and applied an extrude (depth = 20 mm).
	•	Added a helix, and since the bracelet has one loop, set Target Revolution = 1.
	•	Created a square at the start of the loop and defined its width and depth.
	•	Opened a new sketch and performed a sweep using the square profile and helix path.
	•	Added fillets to both the lower and upper edges.
	•	Created a plane and drew a spline to form the S-shaped teeth, then applied a suitable depth.
	•	Used a Boolean operation to merge all parts.
	•	Changed the color to gold to match my bracelet.

### Design Preview
![S-before](https://github.com/sadeem058/First-Week/blob/main/S-after.png)
![S-after](https://github.com/sadeem058/First-Week/blob/main/S-befor.jpeg)

Difficulty defining the S-shaped teeth and controlling the dimensions.
The process was complex and time-consuming.
Understanding and setting the plane correctly took a long time.


______
## (Gear) Design

•	From Add Custom Features, selected Spur Gear and set:
	•	Number of teeth = 50
	•	Tooth depth = 9.7
	•	Diameter = 77.7
	•	Center bore = 7.1
	•	Created a circle on the gear with a diameter of 77.7 to cover the extra part from the spur gear.
	•	Applied an extrude with a depth of 27.
	•	Added fillets to each gear tooth.
	•	Added a 1 mm fillet to the lower circular edge.
	•	Created a bottom circle with a diameter of 17.8.
	•	Added 6 holes around it:
•	Distance from the inner circle edge = 3.2
•	Hole diameter = 3.2
• ⁠Between each two small circles is an area of ​​13.7
• ⁠Changed the color to purple.

### Design Preview
![Gear-before](https://github.com/sadeem058/First-Week/blob/main/Gear-befor.jpeg)
![Gear-after](https://github.com/sadeem058/First-Week/blob/main/Gear-after.png)


______
## (Servo holder) Design

- On the Top Plane, a rectangle with dimensions (40.3 × 27.1) was created.
- The sketch was extruded in two directions (right and left) by 10.5.
- Front and back ledges were added using:
  - The same cover length
  - A width of 7.168
- A center connection was added for measurement reference only.
- On each ledge:
  - Two holes with a diameter of Ø 4.25 were created.
  - Each hole was positioned 4.3 mm away from the center connection.
- Bottom ledges were added with:
  - A width of 7.566
  - The same cover length
  - A fillet applied to smooth the edges.
- A new sketch was created to add two holes identical to the top holes.
- The cover color was changed to grass green.
- After completing the model, servo fitting constraints were reviewed:
  - Top screw locations
  - Bottom charger clearance
- A full rectangular section was removed to provide sufficient space for the charger.

## Design Preview
![servo-after](https://github.com/sadeem058/First-Week/blob/main/servo-befor.jpeg)
![servo-before](https://github.com/sadeem058/First-Week/blob/main/servo-after.png)


______
## (Base) Printing Specification

This base model was printed while preserving the original **length and width** with no changes applied to its outer dimensions. The only modification performed was a **bottom carving (hollowing)** using the **Shell** tool to reduce material usage.

- Original length and width maintained
- Bottom hollowing applied with a **0.7 ratio**
- Hollowing created using the **Shell** tool
- Carving applied from the underside only
- External geometry and top surface remain unchanged

### Printing Setup
- Printer: AnkerMake M5C
- Nozzle: 0.4 mm
- Filament: ABS Because it can withstand heat and weight
- Layer Height: 0.1 mm
- Wall loops: 4 mm
- Sparse infill desity: 50%
- Generate Support: Yes-12.75g

### Design Preview
![Screenshot (412)](https://github.com/sadeem058/First-Week/blob/main/Screenshot%20(412).png)
![Screenshot (411)](https://github.com/sadeem058/First-Week/blob/main/Screenshot%20(411).png)
I tried to make the dimensions of the robot as required, but I didn't change the **width** of the base, so I couldn't meet the **120mm** width requirement.

![Screenshot (413)](https://github.com/sadeem058/First-Week/blob/main/Screenshot%20(413).png)
I think if the wheels get any thinner, the car won't be able to handle it.

## **Last edit**
- 100*120 length and width
- Bottom hollowing applied with a **0.7 ratio**
- Hollowing created using the **Shell** tool
- Carving applied from the underside only
- Add Two TT-Motors , two wheels and 4 TT-motor bracket
  
## Printing Setup
- Printer: AnkerMake M5C
- Nozzle: 0.4 mm
- Filament: PLA+ we dont need strong material we want it to be more flexible.
- Layer Height: 0.1 mm
- Wall loops: 4 mm
- Sparse infill desity: 10%
- Generate Support: Yes-12.75g

## Design Preview
![100120](https://github.com/sadeem058/First-Week/blob/main/100120.png)
![120](https://github.com/sadeem058/First-Week/blob/main/120.png)
![100](https://github.com/sadeem058/First-Week/blob/main/97.png)
![35](https://github.com/sadeem058/First-Week/blob/main/35.png)


_______
## Robot ARM

- Component Import: Inserted all essential parts into the assembly, including the base, arms (brazo, antebrazo), gears, and the gripper mechanism (garra, engranajes).
- Base Grounding: Established the primary reference point by applying a Fastened Mate to the base del brazo, ensuring the entire structure remains stable during movement.
- Joint Definition (Revolute Mates): Applied Revolute Mates to the main joints (shoulder, elbow, and wrist) to allow controlled rotational movement between the arm segments.
- Gripper Mechanism: Positioned the garra components and linked them to the engranajes (gears) to facilitate the opening and closing action.
- Gear Relation: Configured a Gear Relation between the two gears to ensure that rotating one drives the other in the opposite direction for a realistic gripping motion.
- Complex Motion (Cylindrical Mates): Utilized Cylindrical Mates for parts requiring both linear sliding and rotation, such as the tubito or internal shafts.
- Ancillary Parts Assembly: Used Fastened Mates to secure static components like the circuit, tapa circuito, and indicador de perilla to their respective positions.
- Motion Validation: Tested each part individually to ensure smooth degrees of freedom and verified that there are no mechanical interferences between the moving links.

### Design Preview

![Screenshot (420)](https://github.com/sadeem058/First-Week/blob/main/Screenshot%20(420).png)
![Screenshot (421)](https://github.com/sadeem058/First-Week/blob/main/Screenshot%20(421).png)
![Screenshot (422)](https://github.com/sadeem058/First-Week/blob/main/Screenshot%20(422).png)


_______
## Kinematics task

### Design Preview

![task](https://github.com/sadeem058/First-Week/blob/main/task.jpeg)
![solve](https://github.com/sadeem058/First-Week/blob/main/solve.jpeg)
