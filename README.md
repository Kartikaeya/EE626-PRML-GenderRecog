# EE626-PRML-GenderRecog
This repository contains all the source code for EE626-PRML Project titled : Gender Recognition from face images
## Project Members
- Kartikaeya Kumar (180108017)
- Swayam Bukharia (180108049)
- Adriraj Chaudhuri (180107003)
- Arpit Kumar Jain (180122009)

## Demostration  
[[Youtube video link](http://www.youtube.com/watch?v=xEdH9ddTxoE)] "EE626 : Gender Recognition from face images")  

## Dataset
[Drive link](https://drive.google.com/drive/folders/153LS7dvG_ijU1-KpSWRqydTreTNm6QcS?usp=sharing)  
Download the dataset and place in `$Root` directory.


## Results
Three different model architectures were tried : 
1. Lightweight model (~2M parameters)
![image](https://user-images.githubusercontent.com/50746590/116035941-7d6aa600-a683-11eb-90ef-cebd94ef72e9.png)
Training curve  
![image](https://user-images.githubusercontent.com/50746590/116037616-fcf97480-a685-11eb-9e16-276bb6d4bd66.png)
2. Medium weight model (~8M parameters)
![image](https://user-images.githubusercontent.com/50746590/116037707-1ac6d980-a686-11eb-9b0e-96c6e090f6ee.png)
Training curve  
![image](https://user-images.githubusercontent.com/50746590/116037763-29ad8c00-a686-11eb-983d-ba6b1b6542d0.png)
3. Heavy weight model (~10M parameters)
![image](https://user-images.githubusercontent.com/50746590/116037821-3fbb4c80-a686-11eb-8753-c673c370057e.png)
Training curve  
![image](https://user-images.githubusercontent.com/50746590/116037851-4b0e7800-a686-11eb-9b3e-8f6fae4b90c4.png)


We also tried training the medium weight model with three different optimizers
1. ADAgrad  
![image](https://user-images.githubusercontent.com/50746590/116038212-c708c000-a686-11eb-8eed-129ae0322456.png)
2. ADAM  
![image](https://user-images.githubusercontent.com/50746590/116038244-d25beb80-a686-11eb-922e-bf068c7c4e00.png)
3. RMSprop  
![image](https://user-images.githubusercontent.com/50746590/116038275-dc7dea00-a686-11eb-9337-0411911f50f7.png)
