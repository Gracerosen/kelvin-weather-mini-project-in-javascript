# kelvin-Weather-mini-project-in-javascript<br>
</br>
With our knowledge of JavaScript, let’s convert Kelvin to Celsius, then to Fahrenheit.<br>
</br>
<br>
</br>
1.The forecast today is 293 Kelvin. To start, create a variable named kelvin, and set it equal to 293.
The value saved to kelvin will stay constant. Choose the variable type with this in mind.
Here’s how your code should look:
const kelvin = 293;
<br>
</br>
<br>
</br>
2. Write a comment above that explains this line of code.
Add single line comments with //.
<br>
</br>
<br>
</br>
3.Celsius is similar to Kelvin — the only difference is that Celsius is 273 degrees less than Kelvin.
Let’s convert Kelvin to Celsius by subtracting 273 from the kelvin variable. Store the result in another variable, named celsius.
Here’s how your code should look:
const celsius = kelvin - 273;
<br>
</br>
<br>
</br>
4.Write a comment above that explains this line of code.
<br>
</br>
<br>
</br>
5.
Use this equation to calculate Fahrenheit, then store the answer in a variable named fahrenheit.
Fahrenheit = Celsius * (9/5) + 32
In the next step we will round the number saved to fahrenheit. Choose the variable type that allows you to change its value.
Use the provided formula to assign the correct value to fahrenheit, like so:
let fahrenheit = celsius * (9 / 5) + 32;
<br>
</br>
<br>
</br>
6.Write a comment above that explains this line of code.
<br>
</br>
<br>
</br>
7. When you convert from Celsius to Fahrenheit, you often get a decimal number.
Use the .floor() method from the built-in Math object to round down the Fahrenheit temperature. Save the result to the fahrenheit variable.
Here’s how your code should look:
fahrenheit = Math.floor(fahrenheit);
<br>
</br>
<br>
</br>
8. Write a comment above that explains this line of code.
<br>
</br>
<br>
</br>
9. Use console.log and string interpolation to log the temperature in fahrenheit to the console as follows:
The temperature is TEMPERATURE degrees Fahrenheit.
Use string interpolation to replace TEMPERATURE with the value saved to fahrenheit.
To interpolate the string correctly, your code should look like:
console.log(`The temperature is ${fahrenheit} degrees Fahrenheit.`);
<br>
</br>
<br>
</br>
10.Run your program to see your results!
If you want to check your work, open the hint.
293 Kelvin is about 68 degrees Fahrenheit.
<br>
</br>
<br>
</br>
11. By using variables, your program should work for any Kelvin temperature — just change the value of kelvin and run the program again.
What’s 0 Kelvin in Fahrenheit?
You’ll need to go back to the top of your program and set kelvin to 0.
const kelvin = 0;
0 Kelvin is equivalent to -460 degrees Fahrenheit!
<br>
</br>
<br>
</br>
12. Great work! Kelvin can now publish his forecasts in Celsius and Fahrenheit.
If you’d like extra practice, try this:
Convert celsius to the Newton scale using the equation below
Newton = Celsius * (33/100)
Round down the Newton temperature using the .floor() method
Use console.log and string interpolation to log the temperature in newton to the console
// Convert to Newton
let newton = celsius * (33 / 100);
// Round down
newton = Math.floor(newton);
console.log(`The temperature is ${newton} degrees Newton.`);

