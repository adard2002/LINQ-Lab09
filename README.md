# LINQ-Lab09

## The Problem Domain
Create a program that brings in data from an external file, reads the data, and can filter the data based on specified values.

## Program Specifications
Your solution should include the following:

- The data.json file to your solution root folder
- Read in the file and answer the questions below
- Each question and answer should be outputted to the console.

## Questions
Each query builds off of the prior query. You should be chaining.

1. Output all of the neighborhoods in this data list (Final Total: 147 neighborhoods)
2. Filter out all the neighborhoods that do not have any names (Final Total: 143)
3. Remove the duplicates (Final Total: 39 neighborhoods)
4. Rewrite the queries from above and consolidate all into one single query.
5. Rewrite at least one of these questions only using the opposing method (example: Use LINQ Query statements instead of LINQ method calls and vice versa.)
6. You should have a total of 5 outputs.

## Guidance
Provided is a JSON file that contains a data set of location information for properties in Manhattan.

- Use LINQ queries and Lambda statements (when appropriate) to find the answers.
- Use a combination of both to answer the questions.
- Explore the NuGet packages and install NewtonSoftJson
- Do some self research and find out how to read in JSON file (hint: JsonConvert.DeserializedOject is part of it)
- You will need to break up each section of the JSON file up into different classes, use your resources - ask the TA’s if your stuck. (Maybe find a converter of some sort??)