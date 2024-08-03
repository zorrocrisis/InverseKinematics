## **Inverse Kinematics**
This project aimed to explore the concept of **inverse kinematics in video games**, also commonly known as **procedural animations**. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/f2110651-d5e9-4380-96bf-747d6a4201b7"/>
  <img src="https://github.com/user-attachments/assets/e6cd8969-9076-45c6-882b-62061251dc58"/>
</p>

With this goal in mind, a spider skeleton mesh was connected to a **control rig which, through a network of blueprints, determines the next position for each leg by following a procedure (logic) and a set of parameters, considering obstacles and terrain**.

<p align="center">
  <img src="https://github.com/user-attachments/assets/362b9561-122c-41c1-b2ee-9c3e1c4790a0" width=500/>
</p>

## **Source Files**
The project's source files can be downloaded from this repository. To open the program using Unreal, simply clone the repository and open the project utilising the Unreal Engine v5.3.

To reduce the skeleton mesh's file size, a few settings were altered before this project's publishment in Github. To return to the "normal" skeleton mesh settings, please follow these instructions:

- Open Content > Models > CreepySpiderSkeletalMesh
<p align="center">
  <img src="https://github.com/user-attachments/assets/33960447-982c-4319-aa98-96ab539b6ec0"/>
</p>

- In the *Asset Details* window, select *LOD 0* from *LOD Picker*

<p align="center">
  <img src="https://github.com/user-attachments/assets/576a3936-818b-4596-93d7-b614f666d256"/>
</p>

- Then, scroll down until you find *Reduction Settings* under *LOD 0*. Maximize *Percent of Triangles* and *Max Triangles Count*

<p align="center">
  <img src="https://github.com/user-attachments/assets/58839ddd-5479-4be2-8c8a-2a291df5ee9e"/>
</p>

- Scroll further down until you find *LOD Settings* and press *Regenerate*

<p align="center">
  <img src="https://github.com/user-attachments/assets/1a5cafc5-67a0-4ff4-aa9a-516090e71f3c"/>
</p>

- Additionally ensure you are using the *LOD 0* version of the model. Save the file and you should be good to go!

<p align="center">
  <img src="https://github.com/user-attachments/assets/13fb14fd-7b59-42d5-98e0-0bf66864a2b0"/>
</p>


## **Authors and Acknowledgements**
This project was developed by **[Miguel Belbute (zorrocrisis)](https://github.com/zorrocrisis)**, with inspiration from [short Youtube video](https://www.youtube.com/watch?v=vKiqs_h1WXM) by Lincoln Margison.

[Spider's model](https://lincolnmargison.gumroad.com/l/usuxn) by Lincoln Margison.
 
