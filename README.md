# The Alvenhime Assassin

## Overview

**The Alvenhime Assassin** is an interactive visual novel mystery game inspired by tabletop **Dungeons & Dragons–style whodunit investigations**. The game was developed using the **Ren’Py visual novel engine (Python)** and features branching dialogue, interactive investigation mechanics, and a **MySQL backend used to store clues, items, and investigation data**.

This project combines **interactive storytelling, database-driven gameplay, and visual character design** to create a detective experience where players must analyze clues and interrogate suspects to solve a murder.

The game was developed as part of the **Information Structures and Implications** course in the **MSc Digital Humanities program at KU Leuven (Belgium)**.

---

# Game Description

The story takes place in the fantastical land of **Alvenhime**, a magical world inhabited by mystical creatures inspired by the **Dungeons & Dragons universe**.

At the Royal Spirits Court, a noble has been assassinated by poison. The identity of the **Alvenhime Assassin** remains unknown.

The player takes on the role of a **detective** tasked with solving the crime. At the beginning of the investigation, the **Royal Secret Services** provide three crucial clues related to the poisoning. These clues point to several suspicious ingredients believed to have been sold at a faerie-owned shop known as **Anahaita’s Apothecary**.

To uncover the truth, the detective must:

- investigate the shop’s transaction records  
- analyze clues connected to suspicious items  
- question potential suspects  
- piece together evidence  

Through careful investigation and deduction, the player must determine **who committed the murder**.

---

# Game Development and Features

The project demonstrates the integration of **interactive storytelling, database systems, and game logic**.

## Database Design

- Adaptation of a **mock CSV dataset inspired by the Dungeons & Dragons world**
- Dataset source: A [mock database](https://github.com/PatrickLeal/projeto_baldursgate_vendor_sales) set in the DnD universe was modified as per our game storyworld
- Data imported, modified, structured in **MySQL** for use within the game

## Gameplay Systems

- **D&D-inspired dice mechanics** implemented for chance-based interactions
- **Branching dialogue system** implemented using Ren’Py scripting and Python logic
- **Dynamic game screens and dialogue** generated through MySQL queries using a Python **QueryBuilder**
- Database-driven investigation mechanics allowing players to interact with shop records and clues

## Narrative Design

- Multiple **story branches and endings** depending on player decisions
- Detective-style clue analysis system
- Original fantasy characters and world-building elements

## Visual Design

- Custom **character illustrations** created specifically for the game

---

# Technologies Used

- **Ren’Py** – Visual novel game engine  
- **Python** – Game logic and database interaction  
- **MySQL** – Backend database for clues, suspects, and investigation data  
- **CSV datasets** – Source data for in-game shop records
- **Open source visual assets**- For the background open source assets from itch.io were used

---

# Repository Structure
- **data** folder contains the mysql backend data.
- **scripts** folder contains Python querybuilder and queries to create the JSON for the file. The file paths are hardcoded as this is just for documentation purposes.
- **gameplay** folder contains a flowchart of the gameplay.
- Download the game from releases.

---

# Academic Context

This project was developed as part of the **Information Structures and Implications** course within the **Master of Science in Digital Humanities at KU Leuven**.

The assignment explored how **data structures and relational databases can support interactive narrative systems and investigative gameplay mechanics** within digital storytelling environments.

### Development Team

- **Game Design & Development:** Chahna Ahuja, Liangyu Gan  
- **Character Illustrations:** Darlee Urbzitondo  


---

# License

Copyright (c) 2026 Chahna Ahuja and Liangyu Gan.

All rights reserved.

This project, including its code, story, artwork, and assets, may not be copied, modified, or redistributed without explicit permission from the authors.
