DevByteRepository - Solution Code
==================================

DevByteRepository app displays a list of DevByte videos by Google Android developers. This app implements the Repository pattern for code separation and architecture. Using repository pattern the data layer is abstracted from the rest of the app. The repository acts as mediator between different data sources, such as persistent models, web services, and caches and the rest of the app. 
<br>
<br>
When the user first launches the application, they will be presented with a screen that contains a recyclerview with a list of videos that can be clicked on. When the user decides which video they would like to watch, the application will redirect the user to the corresponding YouTube video in the YouTube application. If the user does not have the YouTube application, then it will simply redirect to the web URL. 
<br>
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/57158277/170174119-af0eb491-e995-4eb2-ae29-6be7a74e91b6.png" width="250">
  <img src="https://user-images.githubusercontent.com/57158277/170174173-2a7807d2-4803-4b20-accc-78872a66cc42.png" width="250">
</p>
<br>
<br>

