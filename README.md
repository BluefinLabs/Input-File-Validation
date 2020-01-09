# Input-File-Validation

## Goals

1. Create an input validation tool that can be used in batch processing and by people involved in a process to check a file before running it.
2. Catch common format and value errors early
3. Correct common issues in files

## Requirements

1. configurable for all of the following requirements. Keeping it configurable will make it useful across many projects
2. Validae headers
3. Validate required values
4. Validate common data types (states, countries etc)
5. Easily expandable data corrections/transformations. Trim whitespace, change from state code to state name and back, anything else easily defined in config
6. Return detailed and helpful errors for anything that can't be fixed

## Approach

Can start with an existing project like: https://github.com/jettcalleja/csv-validator or just use similar projects as a reference. 
Gather requirements from teams on all of the various input files and what they might need for the above requirements. 
Apply a version of it inside a process quickly to get feedbakc on how it's working.
