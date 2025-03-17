# **Temperature Advice Program**

### **Description**

This Python program asks the user to enter the current temperature in Celsius and provides clothing advice based on the given temperature.

How It Works

The program prompts the user to enter the temperature.

It converts the input into a floating-point number.

Using conditional statements, it determines the appropriate advice:

If the temperature is below 10°C, it suggests wearing a jacket.

If the temperature is between 10°C and 25°C, it advises wearing short-sleeves.

If the temperature is above 25°C, it recommends staying cool.

Example Usage

Enter the temperature in Celsius: 15

It's a nice day. Wear short-sleeves!

#### Pseudo Code

    BEGIN
    PRINT "Enter the temperature in Celsius: "
    READ temperature
    CONVERT temperature to float
    IF temperature < 10 THEN
        PRINT "It's cold outside. Wear a jacket!"
    ELSE IF temperature >= 10 AND temperature <= 25 THEN
        PRINT "It's a nice day. Wear short-sleeves!"
    ELSE
        PRINT "It's hot outside. Stay cool!"
    ENDIF
    END
#### Requirements

Python 3.x

#### Running the Program

Save the Python script as temperature_advice.py.

Run the script using a Python interpreter.

Enter a numeric value when prompted and receive appropriate advice.

#### Author

Created by Muj taba
