# Space Invaders - JavaFX

A recreation of the classic arcade game "Space Invaders", developed as a university project focused on software architecture, clean code practices, and Object-Oriented Programming (OOP).

## Technologies & Architecture
*   Language: Java 8+
*   GUI Framework: JavaFX (Native FXML files used to keep the visual logic strictly isolated from the business rules).
*   Architecture: MVC (Model-View-Controller).

## Design Patterns Applied
The core of the game (Model) is built upon advanced OOP principles to ensure scalability and maintainability:
*   State: Manages the different game phases (Active, Victory, Defeat).
*   Strategy: Implements interchangeable logic for different firing types (Single, Arrow, Diamond).
*   Factory: Handles the scalable instantiation of Ships and Enemies.
*   Singleton: Provides a centralized manager for the overarching game state.

## Technical Highlights
*   Strict separation of concerns between the business logic and the user interface.
*   Utilization of Java 8 functional features (Streams API and Lambdas) for efficient collection processing, entity filtering, and a more declarative, clean codebase.
*   Dynamic navigation system through controllers and visual state management for entity selection and ranking.

## Development Team
This project was collaboratively developed by Erik, Julen, and Alex. 

**My specific contributions to the project include:**
*   Developing the Controller layer and managing the navigation flow between different screens.
*   Designing the graphical user interfaces using FXML (specifically the Start and Ranking views).
*   Implementing bi-directional property binding between the Views and the Model using JavaFX Properties.
