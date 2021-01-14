# Required Installations:
Installed react native navigatioin, stack navigatioin, drawer navigation & top tab navigation in this project by running following commands.<br>
  #### i-   npm install @react-navigation/native @react-navigation/stack<br>
  #### ii-  npm install react-native-reanimated react-native-screens react-native-gesture-handler react-native-safe-area-context @react-native-community/masked-view<br>
  #### iii- npm install @react-navigation/drawer
  #### iv-  npm install @react-navigation/bottom-tabs
  #### v-   npm install @react-navigation/material-top-tabs react-native-tab-view<br><br>
  
And then installed Firebase, Vector Icons & async-storage by following commands<br>
  #### v-   npm install @react-native-firebase/app
  #### v-   npm install @react-native-firebase/auth
  #### vi-  npm install react-native-vector-icons
  #### vii- npm install @react-native-community/async-storage
  <br>

# Project Structure:
Currently, this application contains total 12 screen components with the following folder structure.
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

# Logo & Title:
<img src="https://user-images.githubusercontent.com/63854449/102753096-6f7ede80-438c-11eb-9d0b-8f206b569932.JPG" align="right" width="300" height="480" >
<br>To set a particular Logo for your React Native application, go to<br><br>
 i- YourProject\android\app\src\main\res\mipmap-hdpi<br><br>
and paste your logo image here. Then go to<br><br>
 ii- android\app\src\main and open AndroidManifest.xml<br><br>
and change the value of "android:icon" variable to your logo image name.<br><br><br>
And to change the name of application, go to <br><br>
 i- YourProject\android\app\src\main\res\values<br><br>
open strings.xml file and set your desired name against "name" variable.<br><br>
Styling of all screens has been done in a seperate file names as Stylo.js.<br>
<br><br>

# Screens:
## Loading Screen:
<img src="https://user-images.githubusercontent.com/63854449/102749264-8a9a2000-4385-11eb-9221-13f44fae6f5d.JPG" align="left" width="320" height="480" ><br><br>
When application opens, a Loading screen appears for few seconds without any<br><br>statsbar and then automatically navigates towards the login section of the application.<br><br><br>
Here, settimeout function is used to set a time period of few seconds for which screen<br><br>appears.
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Login Screen:
<img src="https://user-images.githubusercontent.com/63854449/104359348-5d2e3580-5531-11eb-9ff9-04221b2fc402.JPG" align="left" width="300" height="480" ><br><br>
After loading of few seconds, a Login screen appears for the user.<br><br><br>
Here users can input their credentials like Email address & a password<br><br>associated with it to verify their identity.
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Registration Screen:
<img src="https://user-images.githubusercontent.com/63854449/104359657-c150f980-5531-11eb-9ab0-bf58cdfed4ce.JPG" align="left" width="300" height="480" ><br><br>
And if user is not already registered, then he/she can move towards<br><br>the Registration Screen.<br><br><br>
Users will have to fill Name, Email address & password fields.
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Home Screen:
<img src="https://user-images.githubusercontent.com/63854449/102764029-554cfc80-439c-11eb-9fb4-5145b75bc83d.JPG" align="left" width="300" height="480" ><br><br>
Home Screen is designed like this. A hamburger icon is placed in this<br><br>screen's header to open a side menu.<br><br><br>User can also directly move towards the Main Menu by clicking 'Main Menu' <br><br>button to choose and order food items.<br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Side Menu:
<img src="https://user-images.githubusercontent.com/63854449/102754635-119fc600-438f-11eb-8fef-f532c320b7bf.JPG" align="left" width="300" height="480" ><br><br>
By clicking the hamburder icon in Home screen, a side drawer open<br><br>like this from where you can choose various options to move.<br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Main Menu:
<img src="https://user-images.githubusercontent.com/63854449/104377559-80181400-5548-11eb-8b9b-6555a9800604.JPG" align="left" width="300" height="480" ><br><br>
And by clicking 'Main Menu' button in home screen, the main menu opens. Here Top Tabs navigation nested by stack navigation is used. Main Menu contains three categories scrollable food lists. It also contains a basket vector icon in its header to see your orders. Here order can be placed by clicking red colored 'Order Now' button.<br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Confirm Order:
<img src="https://user-images.githubusercontent.com/63854449/104377716-b6559380-5548-11eb-8c6a-93a333dee532.JPG" align="left" width="300" height="480" ><br>
When user clicks on 'Order Now' button of a food item, a Modal pops up and the background of modal fades or darkens.  Modal screen shows the name and price of that particular item and shows an option to choose the quantity of that item. After choosing quantity, user can click on 'Add to Cart' button to confirm his/her order.<br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## Cart:
<img src="https://user-images.githubusercontent.com/63854449/104382919-cf624280-5550-11eb-829d-df9abfd66b83.JPG" align="left" width="300" height="480" ><br>
After clicking 'Add to Cart' button, it passes three values to the basket screen using the Stack navigation.-
As you can see, now the basket screen contains the Dish/Food item name, its price & the quantity selected by the user.<br>
