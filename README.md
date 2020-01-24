# Samsung Calculator Replica #

This repository stores the code used to create an Android replica of the Samsung Calculator using Kotlin. It will discuss the process of creating the layouts, activities and logic as well as potential improvements if I were to start the project from the start. It will go over every class and layout and how they function. We’ll go through the by their modules in this order:

*   [Main Module](https://github.com/Sgrygorczuk/Android_Calculator/tree/master/app/src/main/java/com/example/calculator/main/ "Main Module")

	* [Main Activity](https://github.com/Sgrygorczuk/Android_Calculator/blob/master/docs/MainActivity.md/ "Main Activity") takes in all of the user inputs passes them to Main Logic for computation or send us to other activities. 
	* [Main Logic](https://github.com/Sgrygorczuk/Android_Calculator/blob/master/docs/MainActivityLayoutPort.md/ "Main Logic") deals with the parsing function and arithmetic computation that gets sent back to Main Activity to be displayed
	* [Main Layout Portrait](https://github.com/Sgrygorczuk/Android_Calculator/blob/master/docs/MainLogic.md/ "Main Layout Portrait") builds the basic layout of a calculator with core being input screen, result screen and keypad for input
	* [Main Layout Landscape](https://github.com/Sgrygorczuk/Android_Calculator/blob/master/docs/MainLogic.md/ "Main Layout Landscape") is an upgraded version of the portrait screen that allows for scientific calculator operations
*   History
	* History Gradle Project and Gradle Module 
	* History Entry
	* History Dao
	* History Database 
	* History Repository
	* History Adapter
	*History Layout
*   Conversion 
	* Conversion Activity 
	* Conversion Logic
	* Conversion Layout
	* Spinner Entry and Adapter
	* Spinner Layout
*   Tip
	* Tip Activity 
	* Tip Logic
	* Tip Layout

## Main Module ##

