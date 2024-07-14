# forward-and-inverse-kinematics-of-3-DOF

## Forward kinematics 

![Image (8)](https://github.com/user-attachments/assets/2fe20242-a073-4b51-a6e0-6abef35220f5)

the main purpose of the forward kinematics is to find the final position of the end effector 

first i will find the end effector for link1, link2, link3 in the x-axis separitly then sum them up 


![Screenshot 2024-07-14 100822](https://github.com/user-attachments/assets/2ef51b8e-3986-432a-bb61-9c3b489b455e)


then i will do the same steps in the y-axis 


![Screenshot 2024-07-14 101251](https://github.com/user-attachments/assets/9b742e53-786f-4234-86d4-e5804ca2be8a)

that's how we can calculate the forward kinematics 


## Inverse kinematics 

![Image (9)](https://github.com/user-attachments/assets/14115f21-a277-4df4-b0e2-9413508e78a5)


the main purpose of the inverse kinematics is to find the angles for link1, link2, and link3 

for link1 and link2, they are the same as the 2 DOF using X and Y we can get them easily using trigonometry, and for link3 we can subtract angle1 + angle2 from the total angle


![Screenshot 2024-07-14 101829](https://github.com/user-attachments/assets/567911a8-d3f4-4bbe-af42-068dc023cb95)
