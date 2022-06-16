# Survival-Game-Sample
## Completed Features
1. Fine-tuned the camera location, offset the character to the bottom left.   
2. The Use of Controller Desired Rotation:    
   Only distinguish when the character is idle.  
   Do not apply when the angle between the character and the camera is less than 80 degrees.      
3. Skeleton and animations resources imported. Retargeted to the old skeleton.  
4. Remake the animation blueprint so as to a smooth character moving animation.  
 ![image](https://user-images.githubusercontent.com/42362114/173990514-8721d0b8-cd88-4c65-9275-d8edc9346e56.png)
5. Character sprint. Adjust anim speed to adapt to walk speed and run speed respectively.  
6. Toggle view. Switch between first and third person view. Set visibility of skeletal mesh and mesh in different view.  
7. Created running UI. Includes character attributes and game world time. Link data to UI.  
   Initialiaze character attributes and decreasing rate.   
   GlobalTimer created. Convert game running time to virtual world time.  
   ![image](https://user-images.githubusercontent.com/42362114/173993235-c3cc2aaa-af69-4e70-b482-c474f671fd18.png)
   ![image](https://user-images.githubusercontent.com/42362114/173993320-3bd4657c-e8cc-4b1b-b408-eb80eb1026a0.png)
8. Set dynamic sun light rotation to simulate real sun light.  
9. Item and inventory system. 
   Created item base class and pickable interface. Items refinement.  
   Refine character and items collider. Created items detector which works when overlapping happens.  
   Pickable panel function and UI. Inventory panel function and UI.  
   ![image](https://user-images.githubusercontent.com/42362114/173997825-77a15d81-7ac9-4f85-86f3-5504f8901d60.png)
   ![image](https://user-images.githubusercontent.com/42362114/173997893-e47c8a6f-99ae-49b0-8a02-3bd4dc7fef6d.png)

