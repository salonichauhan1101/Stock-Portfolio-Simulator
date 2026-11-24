# Stock Portfolio Simulator

## Project Overview

A Java-based stock portfolio management and investment simulation application that enables users to create, manage, and analyze multiple stock portfolios using historical market data.

The application supports both graphical and command-line interfaces, allowing users to simulate stock transactions, evaluate portfolio performance, and implement systematic investment strategies.

Designed using the Model-View-Controller (MVC) architecture, the application emphasizes modularity, extensibility, separation of concerns, and object-oriented design principles.

## Technology Stack

| Technology | Purpose |
|---|---|
| Java | Core application development |
| Java Swing | Graphical user interface |
| Maven | Build and dependency management |
| Alpha Vantage API | Historical stock market data |
| Jackson (FasterXML) | JSON parsing and processing |
| MVC Architecture | Application design and separation of concerns |
| File I/O | Portfolio storage and persistence |

## Key Features

### Portfolio Management

- Create and manage multiple stock portfolios.
- Support flexible and inflexible portfolio types.
- Simulate buying and selling stocks on specific dates.
- View portfolio composition and transaction information.
- Calculate historical portfolio valuations and cost basis.
- Save and load portfolios using external files.

### Investment Strategies

- **Fixed Amount Investment:** Allocate a specified investment amount across multiple stocks using user-defined portfolio weights.
- **Dollar-Cost Averaging (DCA):** Simulate recurring investments over configurable time intervals using weighted stock allocations.

### Stock Market Analytics

- Calculate historical stock gains and losses.
- Analyze moving-average crossovers.
- Evaluate stock and portfolio performance over selected date ranges.
- Retrieve historical market data, including opening prices, closing prices, highs, lows, and trading volume.
- Visualize historical portfolio performance through text-based graphs.

### User Interface

The application provides two interaction modes:

- **Graphical User Interface (GUI):** An interactive Java Swing interface for portfolio management, investment strategies, and financial analysis.
- **Command-Line Interface (CLI):** A menu-driven interface supporting flexible and inflexible portfolio operations.

### User Management and Data Persistence

- Multi-user profile support.
- User registration and login functionality.
- File-based portfolio storage and retrieval.
- External market data integration and JSON processing.

## System Architecture

The application follows the Model-View-Controller (MVC) architectural pattern.

- **Model:** Handles portfolio management, stock transactions, financial calculations, and investment strategies.
- **View:** Provides graphical and text-based interfaces for user interaction.
- **Controller:** Processes user requests, coordinates business logic, and communicates results to the view.
- **Data Integration:** Retrieves historical stock market information through the Alpha Vantage API.
- **Persistence:** Handles file-based reading, writing, and portfolio storage.

## Software Engineering Principles

- Object-Oriented Programming (OOP)
- Abstraction and encapsulation
- Inheritance and polymorphism
- Interface-driven development
- Separation of concerns
- Modular application design
- Reusable business logic
- External REST API integration

## Current Limitations

Certain stock analytics and investment simulation features are limited to the historical market data available through the project's Alpha Vantage API configuration.

This application is designed for educational investment simulation and does not execute real-world stock trades.

## Source Code Availability

This project was developed as part of graduate coursework at Northeastern University.

To respect academic integrity and university coursework guidelines, the complete source code and executable files are not publicly available.

This repository serves as a technical showcase highlighting the application's functionality, software architecture, technology stack, and engineering design.
