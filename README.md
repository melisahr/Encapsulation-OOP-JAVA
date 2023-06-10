# Encapsulation-OOP-JAVA

I learn about encapsulation while follow along a Youtube video.

Encapsulation is when the class has private data and is the only class that can access that data.
However, by using setter and getter method, we can get  access to the private data. 

There are two classes: Main and Car. The Car class contains the private data. 
This can be done by adding the private keyword next to the attributes.
Make a Car constructor with attributes inside its' parameter. 

Create a setter method:
  A setter method is able to set a new value to the private data.
  
How?
  Use public, a return type of void, and the name of the setter method with the set keyword.
  Inside the set parameter, add the type and the name of the attribute as an arguement. 
  Within the set method, use the this keyword to refer to the attribute.
  In the constructor, call the this keyword and the set method with an arguement of the attribute.
  In the Main class, change the year from 2021 to 2022. Use: car.setYear(2022).
  
Create a getter method:
  A getter method is able to retrieve the values from the private data. 
  
How?
  Use public, a return type String/int, and name the getter method with the get keyword. 
  Inside the get method, use the return keyword and the name of the attribute.
  Use in the Main: System.out.println(object.getAttribute()). 
