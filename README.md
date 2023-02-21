# minmax

This code defines several functions to perform various calculations:

- The saluer function takes a prenom (first name) argument of type String and simply prints it to the console.
- The calculerAge function takes an anneeNaissance (year of birth) argument of type UInt and returns the person's age as of 2019, which is calculated as 2019 - anneeNaissance.
- The calculerAgeDe function takes a nom (last name) argument of type String and an anneeNaissance argument of type UInt. It calculates the person's age as before, and returns a tuple containing the person's name and age.
- The code then calls calculerAgeDe twice, once for "John" and once for "Mary". It prints "John" and "Mary"'s ages using the tuple's fields.
- The function calculerMinMax takes a variable number of integer arguments using the values parameter which is of type Int.... It calculates and returns a tuple containing the minimum value, the sum of all the values, and the average of the values passed. If no value is passed it returns a tuple with all fields equal to 0.
- The variable data is assigned to the result of calling the calculerMinMax function with three integer arguments. The fields of the resulting tuple are printed to the console.
- The variable maFonction2 is assigned to the calculerMinMax function, but with the argument list wrapped in an array. It is then called with a list of integer values, and the result is assigned to the variable data2. The fields of the resulting tuple are printed to the console.
