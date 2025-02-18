<img width="785" alt="image" src="https://github.com/user-attachments/assets/0d6aab79-1f9a-4b4a-965a-715bda668b4f" /># Pseudocode Exercise 8 Function and Procedure

---

## Exercise 1

The factorial of an integer number is the product of all the integers from that number down to 1. <br /><br/>
In general, the factorial of n is n × (n−1) × ... × 2 × 1 <br /><br/>
For example, the factorial of 5 is 5 × 4 × 3 × 2 × 1 = 120 <br /><br/>
In this question, n will be referred to as the BaseNumber.
A function FindBaseNumber() will: <br /><br/>
• be called with a positive, non-zero integer value as a parameter
• return BaseNumber if the parameter value is the factorial of the BaseNumber
• return −1 if the parameter value is not a factorial. <br /><br/>
<img width="785" alt="image" src="https://github.com/user-attachments/assets/d55dcf0f-cd79-4513-8677-53fa01aec962" />


## Exercise 2

Write pseudocode for the procedure CountVowels(). A procedure CountVowels() will: <br /><br/>
  • be called with a string containing alphanumeric characters as its parameter <br />
  • count and output the number of occurrences of each vowel (a, e, i, o, u) in the string <br />
  • count and output the number of occurrences of the other alphabetic characters (as a single total). <br /><br/>
The string may contain both upper and lower case characters.
Each count value will be stored in a unique element of a global 1D array CharCount of type
INTEGER. The array will contain six elements.


    
## Exercise 3

A program uses two 1D arrays of type integer. Array1 contains 600 elements and Array2 contains 200 elements.<br/><br/>
Array1 contains sample values read from a sensor. The sensor always takes three consecutive samples and all of these values are stored in Array1.<br/><br/>
A procedure Summarise() will calculate the average of three consecutive values from Array1 and write the result to Array2. This will be repeated for all values in Array1. <br/><br/>
The diagram below illustrates the process for the first six entries in Array1.<br/><br/>
<img width="785" alt="image" src="https://github.com/user-attachments/assets/2fd1a41b-3f99-412c-a7ec-b76ee3e03b75" /> <br/><br/>
Write pseudocode for the procedure Summarise().




 
