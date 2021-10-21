# Project_PokerCards
## Prerequisites
.Net Framework 4.5 or above

Redirect to project folder and find "Data/poker-hands.txt"file and past file inside the "C:\TestData\poker-hands.txt" or change path in Data/FileReader.cs file(variable name FilePath) to define any other relative path. 


## Build and Run using Visual Studio 
Download the code files and open the solution *.sln file in Visual Studio 2019. 

C# .NETCore console application has been used for this project.

Fails and displays error message if file doesn't exists. Change filepath and build again and run the code.

Build the solution and run project. 

## Build and run using VS code
Download and clone the project.

Build the project using CMD- $dotnet build

traverse into Project_PokerCards folder. (as folder contains 2 projects).

To run the project CMD: $dotnet run

Fails and displays error message if file doesn't exists.

Build the solution and run project again.

## Displays output showing 
filepath  

File exist or not??

Player 1: 263 hands

Player 2: 237 hands

## Unit Test Cases
Have used Nunit test cases

TestCases

1.Checking if file exist.

2.Comparing Output of the application.

