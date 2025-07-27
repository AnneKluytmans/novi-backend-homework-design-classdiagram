# TechItEasy UML Design – NOVI Backend Assignment

## About the Project

This repository contains the **UML class diagram** and **requirements documentation** for the *TechItEasy* application – a fictional backend system for managing electronic products, such as TVs, remotes, CI modules, and wall brackets.

The assignment is part of the the Backend Java module at [Novi University](https://www.novi.nl).
The goal of this project is analyze a case study and identifying classes, relationships, and both functional and non-functional requirements.

---

## Table of Contents

- [Tech Stack](#tech-stack)
- [Preview Class Diagram](#class-diagram)
- [Credits](#credits)
- [License](#license)

---

## Tech Stack

- UML class diagram created using [draw.io](https://draw.io)
- Markdown for documentation

---

## Class Diagram

![TechItEasy class diagram](/assets/techItEasyKlassendiagram.png)

Key design aspects:

- `Product` is an **abstract superclass** with shared attributes.
- `Tv`, `Remote`, `WallBracket`, and `CiModule` inherit from `Product`.
- `Tv` has **many-to-many relationships** with both `CiModule` and `WallBracket`.
- `Tv` and `Remote` have an **optional one-to-one** association.
- `User` exists separately with login and authorization attributes.

## Credits
> "This assignment was developed as part of the Backend Java module in the NOVI Software Development program. All instructions, logic, and structure are part of the official coursework."

## License
> "This repository is intended for educational purposes only. You are welcome to use the code for learning, but not for commercial use."