1) Synthesis

  Invoke openlane using docker, add the required package and use prep command for initial preparation

  ![image](https://github.com/user-attachments/assets/b9353f6b-a46d-4f4e-8c31-f687f367d7e5)

  Excecuting run_synthesis command

  ![image](https://github.com/user-attachments/assets/28fe3b3b-3ca6-44e7-8dd9-0102db7b10cf)

  Checking flop ratio

  ![image](https://github.com/user-attachments/assets/573786da-ec46-49b1-9181-419e0a002097)

  ![image](https://github.com/user-attachments/assets/af87f1a7-d9e5-4870-ae91-90aed7ea7483)

  Calculation of Flop Ratio and DFF % from synthesis statistics report file

  Flop Ratio=1613/14876=0.108429685

  Percentage of DFF′s=0.108429685∗100=10.84296854%

2) Floorplan

  Excecuting run_floorplan command

  ![image](https://github.com/user-attachments/assets/78d20365-dbb6-42f7-a3fb-dd7404f4dcd6)

  ![image](https://github.com/user-attachments/assets/b7cce9b9-6d75-492e-be22-9dfd10ee21c5)

  Calculating die area in microns from floorplan def
  
  ![image](https://github.com/user-attachments/assets/59e42fa2-368b-4c39-982c-e397ca460ad6)

  1000 Unit Distance = 1 Micron 
  
  Die width in unit distance = 660685 − 0 = 660685 
  
  Die height in unit distance = 671405 − 0 = 671405

  Distance in microns = Value in unit distance/1000

  Die width in microns = 660685/1000 = 660.685 microns

  Die width in microns = 671405/1000 = 671.405 microns

 Area of Die in microns = 660.685 * 671.405 = 443587.212425 square microns

 3) Placement

    Excecuting run_placement command

  ![image](https://github.com/user-attachments/assets/a8a93818-f494-4386-aa0f-c20635a0f261)

  ![image](https://github.com/user-attachments/assets/e8a22cf6-2188-46fb-a0e5-586a98734fc3)

