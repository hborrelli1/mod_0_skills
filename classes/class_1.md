## Class that may exist in a Restaurant

### Class: Menu

**Attributes**  
menuItems (array)  
menuColor (string)  
numOfMenuItems (integer)  
mostPopularItem (string)  
isHappyHour (boolean)  
happyHourTimes (array max of 2)  
happyHourDiscount (integer)  

**Methods**  
addMenuItem ( adds a value (menu item) to the menuItems array and updates numOfMenuItems )  
changeMenuColor ( changes the value of menuColor from one string to another )  
menuItemCount ( returns the .length value of the menuItems array )  
changePopularItem ( changes the mostPopularItem from one string to another )  
applyHappyHourPricing ( if currentTime is between happyHourTimes[0] and happyHourTimes[1] apply happyHourDiscount )  
