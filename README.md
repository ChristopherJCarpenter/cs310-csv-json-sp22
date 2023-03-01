# CSV To JSON Converter 
## Introduction 
This program takes CSV input and translates it into JSON, or vice versa. 
## Methodology 
### Inputs 
This program uses CSV strings or JSON strings as inputs.
### Outputs 
This program outputs a CVS string converted to a JSON string or a JSON string converted to a CSV string, depending on the input.
### Methods 
The two main functions in this program are CSVtoJSON and JSONtoCSV. 
#### CVStoJSON
This function creates a JSONobject to store the converted CSV data. This data is stored and organized using arrays into rows and
columns. A CSV reader is created to iterate through the list of CSV data in the array. The data is then stored into the JSON object
and the results converted to a JSON string as the output. 
#### JSONtoCSV 
This function creates a new CSV string writer object and a JSON parser to convert the JSON data to CSV data. A JSON array is used to 
organize the data and is then iterated through using a for loop. The iterated data written to the CSV writer. Two for loops are then used 
to iterate through the written data to parse to the CSV writer for the end converted output. 
## Results 
The results of the program are converted outputs from CSV to JSON or vice versa. 
## Conclusion 
Java has built in compatibilities that make converting CSV to JSON, or vice versa, extremely simple. Program could be 
improved by combining certain elements. 
