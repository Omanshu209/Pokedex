# Pokedex
This is a Python-based application that allows users to search for information about different Pokemons. The app has two main screens:

**Pokemon Loader**: This screen allows users to search for a Pokemon by name or ID. When the user enters a valid query and clicks the search button, the app loads the corresponding Pokemon's information, including its image, name, ID, type(s), height, weight, abilities, and stats (HP, Attack, Defense, Special Attack, Special Defense, and Speed).
![Screenshot_2023-03-09-18-32-37-629](https://user-images.githubusercontent.com/114089324/224038705-e593a756-8590-4d21-9332-becde0536f90.jpeg)

**Pokemon Details**: This screen displays the information about the Pokemon selected by the user in the Pokemon Loader screen. The app shows the same information as in the previous screen but in a more detailed and organized way.
![Screenshot_2023-03-09-18-34-19-916](https://user-images.githubusercontent.com/114089324/224039139-a0b39841-afb6-4c03-aa82-689ab9b369dd.jpeg)

## Technologies Used
The app is built using the following technologies:

**Python 3.8**: The core programming language used to develop the app.

**Kivy**: A free and open-source Python framework for creating multi-touch applications with a natural user interface (NUI).

**KivyMD**: A collection of Material Design compliant widgets for Kivy, a Python framework for building multi-touch applications.

**PokeAPI**: A RESTful API that provides access to data about Pokemon creatures from the Pokemon video game franchise.

## Requirements
To run the app, you need to have the following software installed on your computer:

> Python 3.8 or later
> 
You also need to install the following Python packages:

>kivy
>
>kivymd
>
>pokebase

You can install them by running the following command in your terminal:
```
pip install kivy kivymd pokebase
```
## Usage
To run the app, you need to execute the main.py script located in the root directory of the project. You can do it by running the following command in your terminal:
```
python3 Pokedex_code.py
```
When you run the app, you will see the Pokemon Loader screen. Enter the name or ID of a Pokemon and click the search button to load its information. If the Pokemon exists, you will see its name, image, and other details. Click the Pokemon button to see more details about the selected Pokemon in the Pokemon Details screen.

In the Pokemon Details screen, you can see the same information as in the previous screen but in a more detailed and organized way. Click the back button to return to the Pokemon Loader screen and search for another Pokemon.

## Credits
This app was developed by **Omanshu**.
