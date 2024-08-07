# Bouncing Shapes Application

## Overview
The Bouncing Shapes Application is a Java project that demonstrates the principles of object-oriented programming, inheritance, polymorphism, and the Composite Design Pattern. This application allows users to manage and display a hierarchy of shapes (rectangles, squares, hexagons, heptagons, and octagons) that bounce around the screen, utilizing Java's Swing API for the user interface and event handling.

## Features
- **Shape Management:** Users can add, remove, and modify shapes, including rectangles, squares, hexagons, heptagons, and octagons.
- **Composite Design Pattern:** The application implements the Composite Design Pattern to manage nested shapes.
- **Graphics and Animation:** Shapes are drawn on the screen and follow various paths, creating a bouncing animation effect.
- **User Interface:** The application uses Java's Swing API, including a JTree for displaying the hierarchical structure of nested shapes.
- **Event Handling:** The application includes basic event handling to manage user interactions.

## Project Structure
The project consists of three main steps, each building upon the previous to create the final application.

### Step 1: Basic Text-Based Version
- Implement a simple text-based version of the program.
- Display the colors and positions of shapes on the screen.

### Step 2: Shape Drawing and Paths
- Extend the application to draw shapes on the screen.
- Implement different movement paths for the shapes.

### Step 3: Composite Design Pattern and JTree Integration
- Implement the Composite Design Pattern for nested shapes.
- Integrate a JTree to display the hierarchical structure of shapes.

## Classes and Interfaces
- `A1`: Main program class (do not modify).
- `AnimationViewer`: Displays the bouncing shapes.
- `ShapeType`: Enum defining different shape types.
- `PathType`: Enum defining different movement paths.
- `Shape`: Abstract class representing a general shape.
- `RectangleShape`: Represents a rectangle.
- `SquareShape`: Represents a square.
- `PolygonShape`: Represents polygons such as hexagons, heptagons, and octagons.
- `NestedShape`: Represents a shape that can contain other shapes.

## Usage
1. **Clone the Repository:**
    ```sh
    git clone <repository_url>
    cd bouncing-shapes-application
    ```

2. **Compile and Run:**
    Compile the Java files and run the main class.
    ```sh
    javac -d bin src/*.java
    java -cp bin A1
    ```

3. **Interact with the Application:**
    - Use the interface to add, remove, and modify shapes.
    - Observe the bouncing shapes and their hierarchical structure in the JTree.

## Development
### Prerequisites
- Java Development Kit (JDK) 8 or higher.
- An IDE or text editor for Java development.

### Setup
1. Ensure you have JDK installed.
2. Clone the repository and open it in your IDE.
3. Follow the instructions in the `Usage` section to compile and run the application.

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Acknowledgments
This project is part of an educational assignment of COMPSCI230 in University of Auckland aimed at enhancing skills in Java programming, design patterns, and GUI development.
