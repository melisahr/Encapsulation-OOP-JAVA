# Encapsulation-OOP-JAVA

I learn about encapsulation while following along to a Youtube video.

Encapsulation is when the class has private data and is the only class that can access that data.
However, by using setter and getter method, we can get access to the private data. 

There are two classes: Main and Car. The Car class contains the private data. 
This can be done by adding the private keyword next to the type and the attributes.
To retrieve values from the private data, we use the getter method. Use get keyword. 
To assign new values to the private data, we use the setter method. Use set keyword. 
In the Main class, change the year from 2021 to 2022. Use: car.setYear(2022).
   
***Important in the Car class, we use public for both the set and get method. But we had different return type,
the set had void, while the get had either String or int. 
