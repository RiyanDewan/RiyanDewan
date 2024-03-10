READ ME


# Riyan Dewan | Recipe Manager

A command-line interface "Recipe Manager" created using Python.

[Video Demo](https://youtu.be/tyCLvuIGYWA)






## Installation

Use [pip](https://pip.pypa.io/en/stable/) to install the following packages:

bash
  $ pip install tabulate

  $ pip install pytest

    
## Usage

Use [python](https://www.python.org/) to run the application
javascript
$ python project.py



## Running Tests

Use [pytest](https://docs.pytest.org/en/7.2.x/) to test the application

bash
  $ pytest test_project.py


## 📝About This Project
Classes:

Ingredient:

Represents an ingredient and has a single attribute name.
Instances of this class are used in the Recipe class to represent the ingredients used in a recipe.

Recipe:

Represents a recipe with attributes name, ingredients, and category.
ingredients is a list of Ingredient instances.
category represents the category to which the recipe belongs.

MealCategory:

Represents a meal category (e.g., breakfast, lunch, dinner) with an attribute name and a list of associated recipes (recipes).

Functions:

add_recipe:

Takes input for a new recipe (name, ingredients, category).
Checks for duplicate recipe names within the same category.
If the category exists, adds the recipe to the existing category. Otherwise, creates a new category and adds the recipe.
Raises a ValueError if a duplicate recipe is found.

search_recipes:

Searches for recipes containing a specified keyword.
Returns a list of matching recipes.

show_all_recipes:

Displays a table of all recipes grouped by meal category.
Uses the display_recipes_as_table function for formatting.

delete_recipe:

Deletes a recipe based on the provided name.
Raises a message if the recipe is not found.

display_recipes_as_table:

Formats and displays a table of recipes.
Uses the tabulate library for creating a readable table.

main:

Acts as the main program loop.
Displays a menu with options to add, search, show all, delete recipes, or exit.
Handles user input and performs the corresponding operation.
Catches ValueError for duplicate recipes and displays an error message.

User Interaction:

The main function sets up a loop where the user can choose from various options. Users can add new recipes by providing a name, ingredients (separated by '|'), and a category. The program checks for duplicate recipes and adds them to the appropriate meal category. Users can search for recipes based on a keyword, display all recipes, delete a specific recipe, or exit the program.

Code Execution:

The code execution starts with the main function, creating an empty list meal_categories to store meal categories and associated recipes. The user interacts with the program through a menu-driven interface, and the corresponding functions handle the requested operations.

## 🚀 About Me
I'm a student from Pakistan, learning Python using CS50p courses online.

Gmail: riyandewan789@gmail.com
