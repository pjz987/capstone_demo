# M A C R O _ T R A C K E R

## Project Overview

Macro Tracker is an application for calculating and tracking calories and macronutrients.  It is useful for atheletes and fitness enthusiasts as well as those who are just getting started on their fitness journeys.  Too many resources online only have half of the functionality that Macro Tracker has.  Some sites can calculate calories and macronutrients.  Some sites can track calories and macronutrients.  But this site can do both.

Macro Tracker is built in Django and Vue.  It uses the Nutritionix API and Chart.js.  It is styled with vanilla CSS.

## Features

> As a **user**, I want to **calculate my calories and macronutrients** because **I want to know how much to eat and what to eat on the days I work out or rest**.

### Tasks:
- Compute and store calorie and macronutrient data in db.
- Create form for user to submit weight, gender, activity level, etc.
  
> As a **user**, I want to **track my calories and macronutrients throught the day** because **I want to know how much more of what types of food I can eat each day**.

### Tasks:
- Learn and implement the Nutritionix API
- Create form for Custom Entry submission
- Log meals into db

## Schema (aka Data Model)

```
Macros
    grams_of_carbs: int
    grams_of_fat: int
    grams_of_protein: int
	calories: int

Meal
    grams_of_carbs: int
    grams_of_fat: int
    grams_of_protein: int
	calories: int
	time: datetime
```

## Schedule

### Week 1
1. Create django project
2. Create models
3. Get macro calculator working.
<!-- After 1 week, there is an mvp.  It's not pretty by any means but it does what it's supposed to do. -->

### Week 2
1. Make everything hotpink and greenyellow (placeholder! change eventually!)
2. Get tracker functionality working.
3. Learn Nutritionix API
<!-- After 2 weeks, the user can now calculate macros and track them for each day.  They know how their current macros compare to their goals.  But, it doesn't look particularly polished -->

### Week 3
1. Create canvas to display progress
2. Create calendar view for each month
3. Implement functionality for the app to tell the user a nearby restaurant that has food options that would fit into their macros.
4. Prepare for presentation
<!-- After 3 weeks, the project has improved upon itself over and over.  The MVP gets better each time -->

## Must/Should/Can/Won't Haves
### Must Haves
- Macro Calculation
- Macro Tracking
- Users
  
### Should Haves
- Decent CSS
- FAQ on Macronutrients
- Chart.js pie charts for Macronutrients


### Can Haves
- Custom canvas bar chart
- Nutritionix API implemenetation
  
### Won't Haves
- Nearby restaurant suggestions for macros
- A color scheme that isn't hotpink and greenyellow