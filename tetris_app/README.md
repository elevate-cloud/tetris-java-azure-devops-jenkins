# Tetris
Tetris game built on HTML5 Canvas and Javascript. Built mostly as a learning exercise for array matrixes and how to manipulate them.
[Live app](https://squaredrop.io)

# Deploying a tetris application to Azure App Service by using Azure DevOps pipeline and release functions.

1- An azure container registry has been created using terraspace. Please check /terraspace codes/app/stacks/acr

2-The docker image of the app has been created and deployed to the azure container registry by using azure pipelines. 

  <img width="1432" alt="Screen Shot 2023-02-05 at 5 23 47 PM" src="https://user-images.githubusercontent.com/113396504/216851395-06ccbe56-9ab0-423c-8fd3-3ce9c42b8bd8.png">

  <img width="1432" alt="Screen Shot 2023-02-05 at 5 24 09 PM" src="https://user-images.githubusercontent.com/113396504/216851291-0d1ac777-57a0-4ef6-a29d-a0e35dabafb8.png">
  
  Image has been deployed to the acr
  
   <img width="1432" alt="Screen Shot 2023-02-05 at 6 11 32 PM" src="https://user-images.githubusercontent.com/113396504/216851449-c8e818c8-f588-490c-a3ad-803e327a96f1.png">

3- After deploying the image to the acr, an azure web app service has been created using terraspace. Please check /terraspace codes/app/stacks/tetris_linux_webapp/ 

<img width="1432" alt="Screen Shot 2023-02-05 at 5 24 24 PM" src="https://user-images.githubusercontent.com/113396504/216852209-6f678b48-48d1-4719-b052-36e704d4199f.png">

<img width="1432" alt="Screen Shot 2023-02-05 at 5 25 18 PM" src="https://user-images.githubusercontent.com/113396504/216852215-0e9e96e9-8ff1-41fe-bc15-ee0c0024befb.png">

<img width="1432" alt="Screen Shot 2023-02-05 at 5 25 34 PM" src="https://user-images.githubusercontent.com/113396504/216852223-b9d84b49-f67d-4185-9705-dc77053b58d1.png">

4- Finally, the tetris app has been deployed to the app service successfully and then published at https://tetriswebapp001.azurewebsites.net 

<img width="1432" alt="Screen Shot 2023-02-05 at 5 32 02 PM" src="https://user-images.githubusercontent.com/113396504/216852239-9e51f94f-0f5b-49c5-ac72-598399e148b6.png">
<img width="1432" alt="Screen Shot 2023-02-05 at 5 31 17 PM" src="https://user-images.githubusercontent.com/113396504/216852244-07b75286-8598-4e1d-a709-9cabcb601270.png">
