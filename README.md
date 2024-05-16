# SQLite Database - Book Library App

This project demonstrates the creation and management of a SQLite database within an Android app, implementing CRUD (Create, Read, Update, Delete) operations for a Book Library application. It also guides you through integrating a RecyclerView to display data from the database and incorporates animations for enhanced user experience.

## Project Structure

* **app:** Contains the main application code, including activities, fragments, adapters, and utility classes.
* **db:** Houses the database helper class that manages the database creation, schema definition, and CRUD operations.

## Learning Objectives

* Implement CRUD operations (Create, Read, Update, Delete) on a SQLite database in an Android app.
* Utilize RecyclerView to efficiently display database data in a visually appealing manner.
* Integrate animations to improve the user experience of your app.

## Project Tutorials

The project is divided into a series of steps that progressively build the Book Library app:

1. **Part 1: Setting Up the Project** 
   - Establishes the basic project structure.
   - Creates the initial activity for the app.

2. **Part 2: Inserting Data into the Database Table** (**DatabaseHelper.java**)
   - Defines the `DatabaseHelper` class responsible for database creation, schema definition, and CRUD operations.
   - Implements methods for inserting book data into the database.

3. **Part 3: Displaying Data in RecyclerView** (**CustomAdapter.java**, **item_row.xml**)
   - Creates the `CustomAdapter` class to manage data binding between the database and RecyclerView.
   - Designs the `item_row.xml` layout for individual book items in the RecyclerView.

4. **Part 4: Updating Table Data** (**DatabaseHelper.java**)
   - Expands the `DatabaseHelper` class to include methods for updating existing book data.

5. **Part 5: Deleting Table Data** (**DatabaseHelper.java**)
   - Extends the `DatabaseHelper` class with methods for deleting book data from the database.

6. **Part 6: Adding Animations to RecyclerView** (**CustomAdapter.java**, **translate_anim.xml**)
   - Enhances the `BookAdapter` class to incorporate animations when adding or removing items from the RecyclerView.
   - Defines animation styles in `translate_anim.xml` for a more engaging user experience.

## Contract Class (Optional)

This project may benefit from a dedicated `Contract` class to encapsulate database schema definitions (table names, column names) as constants. This promotes code organization, maintainability, and easy schema changes.

## Getting Started

1. Clone this repository: `git clone https://github.com/Wordyka/SimpleLibraryApp.git`.
2. Open the project in Android Studio.
3. Ensure you have the necessary Android development environment set up.
