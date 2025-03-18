### **Day of the Week Activity Recommender**

### Description

This Python program suggests an activity based on the current day of the week entered by the user.

### How It Works:

The program prompts the user to enter the current day of the week (e.g., "Monday", "Tuesday").

It stores the input in a variable and converts it to lowercase for consistency.

### Using conditional statements, it suggests an activity based on the day:

Monday: Start your week with a workout.

Tuesday: It's a great day to read a book.

Wednesday: Mid-week movie night.

Thursday: Try a new recipe.

Friday: Relax and enjoy the weekend.

Saturday: Go for a hike.

Sunday: Prepare for the week ahead with some self-care.

### Example Usage:

Enter the day of the week: Friday

Relax and enjoy the weekend!

### Pseudo Code:

    BEGIN
    PRINT "Enter the day of the week: "
    READ day
    CONVERT day to lowercase
    
    IF day = "monday" THEN
        PRINT "Start your week with a workout!"
    ELSE IF day = "tuesday" THEN
        PRINT "It's a great day to read a book!"
    ELSE IF day = "wednesday" THEN
        PRINT "Mid-week movie night!"
    ELSE IF day = "thursday" THEN
        PRINT "Try a new recipe!"
    ELSE IF day = "friday" THEN
        PRINT "Relax and enjoy the weekend!"
    ELSE IF day = "saturday" THEN
        PRINT "Go for a hike!"
    ELSE IF day = "sunday" THEN
        PRINT "Prepare for the week ahead with some self-care."
    ELSE
        PRINT "Invalid input. Please enter a valid day of the week."
    ENDIF
    END
    
### Requirements

Python 3.x

Running the Program

Save the Python script as day_activity_recommender.py.

Run the script using a Python interpreter.

Enter a day of the week when prompted and receive an appropriate activity suggestion.

### Author

Created by Mujtaba
