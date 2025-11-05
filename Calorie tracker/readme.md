# Daily Calorie Tracker
A simple, command-line Python script designed to help you track your daily calorie intake. This tool allows you to log individual meals and their respective calorie counts, then provides a comprehensive analysis against your personal daily limit.

---

##  Features
* **Dynamic Meal Entry**: Log any number of meals you have throughout the day.
* **Automatic Calculations**: Instantly calculates the **total** and **average** calories consumed.
* **Daily Limit Analysis**: Compares your total calorie intake against a daily limit set by you.
* **Contextual Feedback**: Provides a warning if you exceed your limit or shows how many calories you have left if you're under.
* **Formatted Summary**: Displays a clean, easy-to-read table summarizing all your meals, the total calories, and the average calorie count per meal.
* **Basic Error Handling**: Prevents crashes from non-integer input when specifying the number of meals.

---


##  How to Run
1.  Download or save the `tracker.py` file to your local machine.
2.  Open your terminal or command prompt.
3.  Navigate to the directory where you saved the `tracker.py` file.
4.  Execute the script using the following command:
    
    python first.py

5.  Follow the on-screen prompts to enter the number of meals, their names, calorie counts, and your daily limit. The script will then display the full analysis.

---

##  Example Usage

Here is a sample run of the program:

Welcome to the Daily Calorie Tracker!
No. Of meals : 3

 Meals
Meal #1 Name: Oatmeal 
Calorie Count in 'Oatmeal' 450
Meal #2 Name: Sandwich
Calorie Count in 'Sandwich' 650
Meal #3 Name: Veggies
Calorie Count in 'Veggies' 700

Thank you ! All meals are added

Whats your daily calorie limit:  2200

--Your Calorie Analysis--
Great job! (2200 calories) not exceeded.
you can take 400 calories more.

--- Meal Summary ---
Meal Name            Calories
-----------------------------
Oatmeal               450
Sandwich              650
Veggies               700
-----------------------------
Total:               1800
Average:             600.00
-----------------------------

---

##  Author
* **Name**: Aditya Saini (2501350001)
* **Date**: October 6, 2025