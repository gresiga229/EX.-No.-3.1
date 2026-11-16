# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:02/11/26

## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
# PROCEDURE

### Step 1: Main body (rounded profile)

1. Open Fusion 360 and select **Design → Solid** workspace.
2. Click **Create Sketch** and select the Front (XZ) plane.
3. <img width="216" height="171" alt="Screenshot 2026-11-11 204524" src="https://github.com/user-attachments/assets/c3238025-f792-4c1e-97e5-516f5bdd081f" />

4. Choose **Sketch → Line** and draw the main rectangular portion of the side profile with a height of 32 mm.
5. <img width="542" height="767" alt="Screenshot 2026-11-11 204541" src="https://github.com/user-attachments/assets/cae4195c-055d-4c6f-a9b9-c01125c02e98" />

6. Maintain a distance of 36.28 mm from the centre of the rounded end to the rear shoulder.
7. Choose **Sketch → Arc → 3-Point Arc** and construct the semicircular front portion with a radius of 16 mm (R16).
8. Connect the arc to the straight edges to complete the closed side profile.
9. Click **Finish Sketch**.
10. Select **Extrude**, choose the closed profile and enter 40 mm as the extrusion distance.
11. 
12. Press Enter to create the main solid body.

### Step 2: Create the central gap between the fork arms

10. Select the top face of the main body and click **Create Sketch**.
11. Choose **Sketch → Rectangle → Two-Point Rectangle**.
12. Draw a rectangular profile along the centre of the body.
13. Set the width of the rectangle to 18 mm and position it equally on both sides, leaving 11 mm on each side of the 40 mm overall width.
14. Extend the rectangular profile from the front end up to a point 11 mm before the rear shoulder.
15. Click **Finish Sketch**.
16. Select **Extrude**, select the rectangular profile and choose **Cut** as the operation.
17. Set the cut distance to 32 mm so that the central material is removed through the entire height.
18. Press Enter. This creates two parallel fork arms connected by the rear portion.

### Step 3: Create the circular holes

19. Select the side face of the fork body and click **Create Sketch**.
20. Choose **Sketch → Circle → Center Diameter Circle**.
21. <img width="517" height="395" alt="Screenshot 2026-11-11 204552 - Copy" src="https://github.com/user-attachments/assets/5e7415d2-a58b-47e4-99a6-ee4fc50a0650" />

22. Place the centre of the circle at the centre of the rounded end.
23. Enter 16 mm as the diameter (Ø16).
24. Click **Finish Sketch**.
25. Select **Extrude**, choose the circular profile and set the operation to **Cut**.
26. Extend the cut through the full 40 mm width of the body.
27. Press Enter to create the circular holes through both fork arms.

### Step 4: Create the rear cylindrical shaft

27. Select the rear vertical face of the connecting portion and click **Create Sketch**.
28. Choose **Sketch → Circle → Center Diameter Circle**.
29. Place the circle at the centre of the rear face.
30. Enter 18 mm as the diameter (Ø18).
31. Click **Finish Sketch**.
32. Select **Extrude** and choose the circular profile.
33. <img width="460" height="617" alt="Screenshot 2026-11-11 212828" src="https://github.com/user-attachments/assets/c042070e-8654-4641-830b-04df93e2d9d7" />

34. Enter 32 mm as the extrusion distance, extending outward from the rear face.
35. Select **Join** as the operation to connect the cylindrical shaft to the main body.
36. <img width="230" height="311" alt="Screenshot 2026-11-16 090622" src="https://github.com/user-attachments/assets/a917b2fe-8f4c-4869-a435-aec5a0cbc68b" />

37. Press Enter to complete the shaft.

### Step 5: Final inspection and drawing

36. Use the **Orbit** tool to inspect the component from different directions.
37. Check that the two fork arms have a thickness of 11 mm each and a central gap of 18 mm.
38. Verify the circular hole diameter of 16 mm and the shaft diameter of 18 mm.
39. Confirm the overall width of 40 mm, height of 32 mm and shaft length of 32 mm.
40. Apply the required appearance and save the completed model.
41. Generate the front, top and end views along with the isometric view using the drawing workspace.
42. Add the necessary dimensions and centre lines to complete the engineering drawing.

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198551872-276f8b80-bea8-4d4a-b2e8-bfdcd1e9d3cc.png)

## OUTPUT:
<img width="982" height="707" alt="Screenshot 2026-11-15 184026" src="https://github.com/user-attachments/assets/097116e0-b103-4ba9-9379-4551538c598f" />

## RESULT:
Thus, 3D model is created from orthographic projection.
