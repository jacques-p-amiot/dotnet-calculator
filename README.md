[![Build Status](https://dev.azure.com/{jacquesphilippeamiot0056}/{helpers}/_apis/build/status/{
jacques-p-amiot.dotnet-calculator}?branchName=master)](https://dev.azure.com/{jacquesphilippeamiot0056}/{helpers}/_build/latest?definitionId={2})

# What I'm hoping to achieve with this repo
A dotnet application hooked up to a full CICD pipeline.

## The dotnet application
I'll make a simple calculator class library which will be consumed by a console application which gathers and manages user input. Project structure:
-- calculator app soln      
    |       
    |--- class library      
    |--- unit testing class library     
    |--- console application (consumes class library)       
