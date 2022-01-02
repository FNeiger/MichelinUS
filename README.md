# MichelinUS
The Michelin Restaurant Finder of the United States 
– Fabian Neiger, fabian.neiger@student.unisg.ch, student number: 17-852-427

The program created by the author helps the user to find Michelin Restaurants in the US, based on some input. The data for the program was taken from an article on upserve.com (Resendes, 2020) and shows a list of all Michelin Restaurants in the United States. In a further step this list could be expanded to include all restaurants in the Americas or even world-wide. Additionally, the list could include Gault-Millau restaurants as well. 
The program was written on python. 

The first idea for the project was to open a file with a function in python and reading information directly from the file, based on user-input. Unfortunately, reading information from an input on python doesn’t seem to be possible without an additional program or plug-in (e.g., Pandas). While the user can still open the source-document in python and see the available restaurant, he/she cannot choose directly at this step. 

Let us look at the steps the user takes through the program:
In a first step the user is greeted and asked for his/her name. Consequently, whenever the user is addressed, the name the user entered is shown. 
Next, the user is asked if he/she would like to see all available Michelin restaurants in the US. If the answer is affirmative (“y”), then the user will see a button that expands into the extensive list of all Restaurants. If the answer to the question is negative (“n”), then this step is skipped, and the user jumps to step three. If the user enters anything except y or n, then an error message appears, and the question is asked again. 
In a third step, the user is asked if he/she is ready to begin looking for a restaurant. Like step two, the user can enter either “y”, “n”, or something else. If the user enters “y”, then the actual program starts. If the user enters “n”, then the program quits entirely. If the user enters anything else, an error message appears, and the question is restated.

Upon having passed these quick first three steps, the user is now in the part of the program asking for his/her preferences. In a first step, the user enters what type of restaurant they are looking for. This is done by choosing the number of stars the restaurant should have, thus by entering either 1, 2 or, 3. Next, the user enters the city that he/she is in. Once again, the code is written so the user must only enter a number (1 through 6). 
The number of stars of the restaurant and the cities with said restaurants have been organised in lists in python. Based on the choices the user makes, the program will then show all restaurants with a specific star-level and location. This code looks extensive, yet is very simple, as it uses an and-function with the previously recorded choices. 
Finally, the program wishes the user well for dinner. It ends by asking the user if he/she want to jump back to the beginning of the program or if the program should end. Naturally, the user doesn’t have to re-enter his/her name but can directly choose if they want to see the list of restaurants or not. The repeat is coded with a repeat-function. 


Bibliography
Resendes, S. (2020). A Comprehensive List of Michelin Star Restaurants in the United States. Retrieved December 18, 2021, from upserve.com: https://upserve.com/restaurant-insider/michelin-star-restaurants-united-states/

