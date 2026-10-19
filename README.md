# CS2-Guadalquiver-JacobEzekiel
Computer Science 2 2nd Quarter FA 2

# Travel Fare Calculator

## Description
This program calculates the total travel fare for a trip based on a flat fare rate per kilometer, the distance traveled, and the number of passengers.

## Version 1 - Original code without input validation
- Input: Accepts a passenger's name, distance in kilometers, and number of passengers.
- Process: Multiplies the distance by a standard fare rate of 14, then multiplies by the number of passengers.
- Output: Passenger's name and the calculated total travel fare, rounded to exactly two decimal places.
- Does not include input validation.

## Version 2 - New code with input validation
- Input: Accepts a passenger's name, distance in kilometers, and number of passengers.
- Process: Checks inputs using selection structures (`if` statements). It validates that the name is not blank, the distance is a positive number, and the passenger count is a positive whole number. It then calculates the total fare using a standard rate of 14.
- Output: Passenger's name and the calculated total travel fare if inputs pass validation, or an error message requesting re-entry.
