# Mordor Army Manager

This Java Swing application allows you to manage an army of orcs from different tribes in Middle-earth. You can create orcs of different types (Basic, Leader, Scout) from various tribes (Mordor, Dol Guldur, Misty Mountains) and view their attributes and equipment.

## Features

- Create orcs from different tribes with unique characteristics
- Three types of orcs: Basic, Leader, and Scout
- Each tribe has unique equipment (weapons, armor, banners)
- Visual representation of the army structure using JTree
- Detailed information panel showing orc attributes with progress bars
- Automatic name generation using Lord of the Rings themed names

## Requirements

- Java 17 or higher
- Maven

## Building and Running

1. Clone the repository
2. Navigate to the project directory
3. Build the project:
   ```bash
   mvn clean package
   ```
4. Run the application:
   ```bash
   java -jar target/Lord-1.0-SNAPSHOT.jar
   ```

## Usage

1. Click the "Add Orc" button to create a new orc
2. Choose the tribe and type of orc
3. Optionally enter a name (if left empty, a random name will be generated)
4. Click "Create" to add the orc to your army
5. Select an orc in the tree view to see detailed information

## Tribes and Their Characteristics

### Mordor
- High strength (+30%)
- Low agility
- Equipment: Heavy swords, steel armor, Red Eye banner

### Dol Guldur
- Balanced attributes
- Equipment: Spears, chain mail, Spider banner

### Misty Mountains
- High agility (+30%)
- Low intelligence
- Equipment: Axes, leather armor, Moon banner 