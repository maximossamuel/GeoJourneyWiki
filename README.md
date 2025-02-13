# GeoJourney Wiki
Due to API keys being present in the code, the GeoJourney source code will remain private. This repo serves as a way to show off GeoJourney's UI and functionality.

## What is GeoJourney?
GeoJourney is a mobile app that uses React Native and SQL made by myself and [@rblotsky](https://github.com/rblotsky). GeoJourney is best described as a "Map-based Notetaking App". The idea behind it being that users can make markers on parts of the map where they have been. The user can then add text or images to that marker. Making them accessible when you click on said marker on the map. This can be used for a variety of reasons:
- Maybe you found a cool restaurant you want to try out later.
- Maybe you're shooting a movie and you pass by a place you feel would be good for a certain scene. Placing a marker on that location and adding a note to that marker will help you remember that place, so you can easily find it later.
- Perhaps you had a really fun day with your friends in the city and took a bunch of pictures. You can use the markers as a way to attach those memories to the places you had them.
We made GeoJourney to be flexible with whatever people would want to use it for. The user has the power in this case.

## Using GeoJourney
### Start Screen
Upon starting GeoJourney you will see a map showing your current location and two buttons at the bottom. The green button is to start a new journey whereas the blue button is to add a new marker. 

<img src="https://github.com/user-attachments/assets/fac2054c-eb5c-4366-b7d2-e0e5fe9f1b35" alt="GeoJourney Start Screen" width="200"/>


### Standalone Markers

#### Adding a New Marker
Upon pressing the blue button, a drawer will appear. In this drawer, you can give your marker a title, description, and images. Looking at the icons, you can see that you get the choice of either choosing an image from your gallery or taking a picture with your device's camera. A note should be made that we have made it so that pictures taken using GeoJourney will be stored on your device. When you add a picture to your marker, it will appear on the drawer, you can press the minus icons on those pictures to remove them from this marker. Pressing the checkmark on the top-right corner of the drawer will save your marker, adding it, along with all the data you inserted, onto the map.

<img src="https://github.com/user-attachments/assets/61402050-2bd9-47a2-a324-453c158627cf" alt="Empty Marker" width="200"/>
<img src="https://github.com/user-attachments/assets/f741d59e-c0f6-4a4a-b59c-9e2c8f94e1c7" alt="Filled Marker" width="200"/>




#### Viewing a Marker
Markers can be viewed simply by clicking them on the map. A drawer will appear showing the title of your marker, your images, title and description (if applicable) and the time/date the marker was created. You will also find icons to either edit or delete the marker.

<img src="https://github.com/user-attachments/assets/9237a40b-0125-4ffa-b3a0-9d442271c475" alt="Viewing a marker" width="200"/>

#### Editing a Marker
Markers can be edited if you wish to change anything. The UI will show an identical interface to what you see when adding a marker.

<img src="https://github.com/user-attachments/assets/4c7d0e63-ebb5-4053-9a8d-5a0381fce1d5" alt="Editing a marker" width="200"/>


### Journeys/Journey Markers
In GeoJourney, a journey represents a series of connected markers. Where a user starts a journey and add markers that serve as part of said journey until they tell the app to end it.


#### Starting a new journey
Similar to adding a standalone marker, a drawer will appear upon pressing the green button. This drawer will look very similar to the one shown when adding a marker, only the title field box is where you will put the title for the whole journey and not a marker. Pressing the checkmark icon will start the journey. While you are on a journey, you can still add standalone markers if you find something you want to write about which is irrelevant to your journey.

<img src="https://github.com/user-attachments/assets/c1cb03e0-7fd4-4296-bf9c-ac6e6733b86b" alt="Starting a new journey drawer" width="200"/>
<img src="https://github.com/user-attachments/assets/993aba22-4b59-466b-a7e2-9f58998f0587" alt="New journey started" width="200"/>



#### Adding/Editing Journey Markers
Whilst on a journey, you can press the green button again and it will add a journey marker. You can add the same info you do on regular markers, only this marker will be connected to others of that same journey. 

<img src="https://github.com/user-attachments/assets/b438976a-4702-4feb-b004-ae9cc776c5e5" alt="Adding a new journey marker" width="200"/>
<img src="https://github.com/user-attachments/assets/05424086-c726-46c2-ad91-ac34bcd3db06" alt="Connected journey markers" width="200"/>

#### Ending a Journey
Once you wish to stop placing journey markers, you can press the green stop button. Doing this will complete the journey.

#### Viewing a Journey
If you wish to view a journey, you can do so by pressing any of its markers. You will see all the same info you would on a regular marker's drawer, only now the journey's title will appear under the date. You will also see buttons above the drawer that you can press to look at the next or previous marker in the journey. 

<img src="https://github.com/user-attachments/assets/bed73e4a-a422-4b66-a781-8f660d4e3728" alt="Viewing a Journey Marker" width="200"/>

