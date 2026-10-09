# EcoPoints Recycling Tracker ♻️

A console-based Java application designed to track household recycling activities, calculate eco points, and generate recycling reports.

## - Overview

The **EcoPoints Recycling Tracker** is a Java practice project completed as part of a guided project on Coursera. The application helps manage household registrations and recycling events while encouraging environmentally friendly behavior through a simple points-based system.

Households earn **10 EcoPoints for every kilogram of recycled material**. The application records recycling activities, tracks total recycled weight, and calculates points earned by each household.

## - Features

- **Household Management:** Register households with unique IDs, names, addresses, and joining dates.
- **Recycling Event Tracking:** Record material types, recycled weight, dates, and earned points.
- **EcoPoints Calculation:** Award 10 points per kilogram of recycled material.
- **Data Management:** Organize household and recycling records using Java collections.
- **Data Persistence:** Save and reload application data using file I/O and serialization.
- **Recycling Reports:** Display household recycling statistics and identify the household with the highest points.
- **Input Validation:** Handle invalid inputs, duplicate household IDs, and file-related errors.
- **Console Interface:** Interact with the application through a menu-driven interface.

## - Technologies and Concepts

- Java
- Object-Oriented Programming (OOP)
- Encapsulation
- ArrayList and HashMap
- Java Date and Time API
- Loops and Conditional Statements
- Exception Handling
- File I/O and Serialization

## - Project Structure

```text
ecopoints-recycling-tracker/
├── src/
│   ├── EcoPointsRecyclingTracker.java
│   ├── Household.java
│   └── RecyclingEvent.java
├── README.md
└── .gitignore
```

## - Getting Started

### Prerequisites

- Java Development Kit (JDK) installed
- A terminal or Java IDE

### Installation and Execution

1. Clone the repository:

   ```bash
   git clone https://github.com/mahsawye/ecopoints-recycling-tracker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ecopoints-recycling-tracker
   ```

3. Compile the Java source files:

   ```bash
   javac -d out src/*.java
   ```

4. Run the application:

   ```bash
   java -cp out EcoPointsRecyclingTracker
   ```

## - Learning Objectives

This project demonstrates practical experience with:

- Designing classes and objects using OOP principles.
- Managing related data with Java collections.
- Working with dates and user input.
- Implementing file-based data persistence.
- Applying exception handling and input validation.
- Generating reports from stored records.

## - Project Background

This project was completed as part of a guided project on Coursera to practice Java programming and object-oriented software development.

It demonstrates the practical application of Java concepts, including OOP, collections, exception handling, and file I/O.

## - Author

**Mahsa**

GitHub: [@mahsawye](https://github.com/mahsawye)
