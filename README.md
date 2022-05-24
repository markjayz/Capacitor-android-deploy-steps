# Capacitor-android-deploy-steps
Steps on how to Deploy Capacitor Android in Playstore
Dipendency : NPM, Android Studio, Git, Capacitor CLI

1. Checkout branch  :  **git checkout {branch}**
  
2. Install npm packages : **npm install**
  
3. Build Project : **sudo npm run build**
  
4. Capacitor Sync _need to install capacitor cli in local_ : **npx cap sync android** then **npx cap open android**
  
5. Change **versionCode** and **versionName**
  <img width="1776" alt="Screen Shot 2022-05-24 at 9 48 35 PM" src="https://user-images.githubusercontent.com/9428322/170051537-2a5d17de-73cd-48c1-a910-6825edf5db84.png">
  
 6. Clean Project
  <img width="1776" alt="Screen Shot 2022-05-24 at 9 50 03 PM" src="https://user-images.githubusercontent.com/9428322/170051832-a77c54bf-6b38-44b5-86ff-c3d049516375.png">
  
 7. Generate Signed APK/BUNDLE
  <img width="1776" alt="Screen Shot 2022-05-24 at 9 51 08 PM" src="https://user-images.githubusercontent.com/9428322/170052112-a39e3070-bd67-4cb0-86d4-95ca8785285c.png">
 
  8. Input KeyStore and locate the bundle
  
  <img width="1776" alt="Screen Shot 2022-05-24 at 9 51 08 PM" src="https://user-images.githubusercontent.com/9428322/170052710-5c1f15e3-d351-49d5-893c-a805486931aa.png">

  <img width="1776" alt="Screen Shot 2022-05-24 at 9 52 23 PM" src="https://user-images.githubusercontent.com/9428322/170052715-9cdef324-014c-45a3-a76f-9a607cf2aed1.png">
 
  <img width="1776" alt="Screen Shot 2022-05-24 at 9 52 30 PM" src="https://user-images.githubusercontent.com/9428322/170052772-afda4a1b-9297-473e-8941-b564bfacb8dc.png">

<img width="1776" alt="Screen Shot 2022-05-24 at 9 52 37 PM" src="https://user-images.githubusercontent.com/9428322/170052793-fcff3612-1ab4-4fa8-b3af-41e3a5038156.png">

  <img width="1776" alt="Screen Shot 2022-05-24 at 9 52 55 PM" src="https://user-images.githubusercontent.com/9428322/170052822-2afa1c26-3c25-4b65-acd8-a845e0c881a5.png">
  
 9. Get the bundle and login to Playstore Console
  
10. Create Release
  <img width="1776" alt="Screen Shot 2022-05-24 at 9 56 01 PM" src="https://user-images.githubusercontent.com/9428322/170053151-ae973b43-7885-4120-a1e5-848a92941a78.png">
  
11. Upload Bundle
  <img width="1776" alt="Screen Shot 2022-05-24 at 9 57 20 PM" src="https://user-images.githubusercontent.com/9428322/170053385-55e51b3e-2a6e-4450-a58c-5c0559a493a1.png">


