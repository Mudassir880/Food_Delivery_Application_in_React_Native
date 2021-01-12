# Food_Delivery_Application_in_React_Native

<b><i>Installation:</i></b><br>
Installed react native navigatioin, stack navigatioin, drawer navigation & top tab navigation in this project by running following commands.<br>
  <i>i-</i> npm install @react-navigation/native @react-navigation/stack<br>
  <i>ii-</i> npm install react-native-reanimated react-native-screens react-native-gesture-handler react-native-safe-area-context @react-native-community/masked-view<br>
  <i>iii-</i> npm install @react-navigation/drawer<br>
  <i>iv-</i> npm install @react-navigation/material-top-tabs react-native-tab-view<br>
  
And then installed Vector Icons by running this command<br>
  <i>i-</i> npm install react-native-vector-icons

<b><i>Project Structure:</i></b><br>
Currently, this application contains total 12 screen components with the following folder structure.
<img src="https://user-images.githubusercontent.com/63854449/102757151-b40d7880-4392-11eb-8eb5-58c62299b77a.jpg" align="left" width="1000" height="380" >


<b><i>Logo & Title:</i></b><br>
To set a particular Logo for your React Native application, follow the following steps.<br>
<i>i-</i> Go to YourProject\android\app\src\main\res\mipmap-hdpi and paste your logo image here.<br>
<i>ii-</i> Then go to android\app\src\main and open AndroidManifest.xml file & change the value of "android:icon" variable to your logo image name.

And to change the name of application, go to YourProject\android\app\src\main\res\values, open strings.xml file and set your desired name against "name" variable.<br>
Styling of all screens has been done in a seperate file names as Stylo.js.<br>
<img src="https://user-images.githubusercontent.com/63854449/102753096-6f7ede80-438c-11eb-9d0b-8f206b569932.JPG" align="right" width="350" height="580" >


<b><i>Screens:</i></b><br>

When application opens, a Loading screen appears for few seconds without any statsbar and then automatically navigates towards the home screen of the application.<br>
<img src="https://user-images.githubusercontent.com/63854449/102749264-8a9a2000-4385-11eb-9221-13f44fae6f5d.JPG" align="left" width="390" height="580" >

After loading of few seconds, a Login screen appears for the user.<br>
<img src="https://user-images.githubusercontent.com/63854449/104359348-5d2e3580-5531-11eb-9ff9-04221b2fc402.JPG" align="right" width="360" height="580" >

And if user is not already registered, then he/she can move towards the Registration Screen.<br>
<img src="https://user-images.githubusercontent.com/63854449/104359657-c150f980-5531-11eb-9ab0-bf58cdfed4ce.JPG" align="left" width="360" height="580" >

Home Screen is designed like this. A hamburger icon is placed in this screen's header to open a side menu. User can also directly move towards the Main Menu by clicking 'Main Menu' button to choose and order food items.<br>
<img src="https://user-images.githubusercontent.com/63854449/102764029-554cfc80-439c-11eb-9fb4-5145b75bc83d.JPG" align="right" width="370" height="580" >

By clicking the hamburder icon in Home screen, a side drawer open like this from where you can choose various options to move.<br>
<img src="https://user-images.githubusercontent.com/63854449/102754635-119fc600-438f-11eb-8fef-f532c320b7bf.JPG" align="left" width="350" height="580" >

And by clicking 'Main Menu' button in home screen, the main menu opens. Here Top Tabs navigation nested by stack navigation is used. Main Menu contains three categories scrollable food lists. It also contains a basket vector icon in its header to see your orders. Here order can be placed by clicking red colored 'Order Now' button.<br>
<img src="https://user-images.githubusercontent.com/63854449/104377559-80181400-5548-11eb-8b9b-6555a9800604.JPG" align="right" width="350" height="580" >

When user clicks on 'Order Now' button of a food item, a Modal pops up and the background of modal fades or darkens.  Modal screen shows the name and price of that particular item and shows an option to choose the quantity of that item. After choosing quantity, user can click on 'Add to Cart' button to confirm his/her order.<br>
<img src="https://user-images.githubusercontent.com/63854449/104377716-b6559380-5548-11eb-8c6a-93a333dee532.JPG" align="left" width="350" height="580" >

After clicking 'Add to Cart' button, it passes three values to the basket screen using the Stack navigation.
As you can see, now the basket screen contains the Dish/Food item name, its price & the quantity selected by the user.<br>
<img src="https://user-images.githubusercontent.com/63854449/104378011-22d09280-5549-11eb-8e8d-5c9fb513651e.JPG" align="right" width="350" height="580" >

STILL WORKING ON THIS APP.
SOON THE LOGIN AND REGISTRATION PAGES WILL ALSO BE INCLUDED AND BASKET SCREEN WILL BE DESIGNED AS WELL.
