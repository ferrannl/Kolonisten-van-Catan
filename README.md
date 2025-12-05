# Kolonisten van Catan

A Java implementation of (parts of) **The Settlers of Catan**, created as a project for **Informatics 1 – Group I**.  
This is an Eclipse-based project focused on practicing object-oriented programming, teamwork, and Git workflows.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Running the Project in Eclipse](#running-the-project-in-eclipse)
- [Working With Branches](#working-with-branches)
- [Known Limitations](#known-limitations)
- [Authors](#authors)
- [License](#license)

---

## About the Project

This repository contains the source code for an educational Java assignment based on **The Settlers of Catan**.  
The project focuses on:

- Practicing **Java** and object-oriented design.
- Using **Eclipse** as the development environment.
- Collaborating through **Git**, including branching and merging.

The repository can serve as reference material for students or anyone learning Java.

---

## Project Structure

Key components:

- `.metadata`, `.settings`, `.classpath`, `.project`  
  Eclipse configuration files.
- `src/`  
  Contains all Java source code for the project.

Inside `src/`, look for classes containing a `public static void main(String[] args)` method — these are entry points for running the program.

---

## Requirements

Make sure you have:

- **Java Development Kit (JDK)** — originally designed for **Java 9**.  
  More recent versions (e.g., Java 11 or 17) often work but may require adjusting Eclipse settings.
- **Eclipse IDE for Java Developers**, or another IDE that supports Java.
- **Git** (optional if you download ZIP only).

---

## Installation

Below is a cleaned-up version of the original setup instructions.

### 1. Install Java (JDK/JRE)

- Install a JDK of your choice (Java 9 recommended for full compatibility).
- Set Eclipse to use the same Java version for this project.

### 2. Import the Project into Eclipse

#### Option A — Import Existing Project (recommended)

1. Open Eclipse.
2. Go to: `File` → `Import...` → `Existing Projects into Workspace`.
3. Select the folder containing the cloned/unzipped repository.
4. Click **Finish**.

#### Option B — Create a New Project and Add Source

1. Create a new Java project.
2. Set the *Execution Environment* to **JavaSE-9** or another compatible version.
3. Copy the contents of this repo’s `src` folder into your new project's `src` folder.

### 3. Clone the Repository (if using Git)

```bash
git clone git@github.com:ferrannl/Kolonisten-van-Catan.git
# or
git clone https://github.com/ferrannl/Kolonisten-van-Catan.git

4. Done

Open the project in Eclipse.

Ensure there are no compile errors.

Run the main class.



---

Running the Project in Eclipse

1. Open/import the project.


2. Expand the src/ folder.


3. Locate a file with a main method.


4. Right-click → Run As → Java Application.




---

Working With Branches

Notes based on the original README:

Some branches may not be fully up to date with develop or master.

To update a branch (e.g., chat) with the latest changes from develop:


git checkout chat
git merge develop

master is intended as the production/stable branch.
Development should happen on develop or feature branches.



---

Known Limitations

This is an educational project, not a complete game implementation.

Branches may be incomplete or contain outdated work.

There is no build system (like Maven or Gradle); it is structured as a classic Eclipse project.



---

Authors

Group I – Informatics 1: Catan Project


If you are one of the original contributors and want your name added, feel free to update this section.


---

License

No explicit license file is included.
Assume that all rights belong to the original authors, and redistribution should follow your institution’s guidelines or require permission.
