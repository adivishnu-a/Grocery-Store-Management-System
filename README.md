# Grocery Store Management System

Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data Storage](#data-storage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This is a Grocery Store Management System, a C++ application developed as part of the "Object Oriented Programming with C++" course at SRM University, AP. It provides functionality for managing a grocery store's inventory, calculating costs, profits, and salaries.

## Features

The Grocery Store Management System offers the following features:

- Add, store, and update product details
- Add, store, and update employee details
- Calculate daily profit by calculating the profit from sales and subtracting employee wages
- Use file handling to store profits and products for future reference

Show some ❤️ by starring the repository! ⭐️
## Getting Started

To run the program locally, follow these steps:

1. Clone the project:

   ```shell
   git clone https://github.com/adivishnu-a/Grocery-Store-Management-System
   ```

2. Navigate to the project directory:

   ```shell
   cd Grocery-Store-Management-System
   ```

3. Compile and run the program:

   - On Windows:

     ```shell
     g++ -o GroceryStore GroceryStore.cpp
     ./GroceryStore
     ```

   - On Linux & macOS:

     ```shell
     g++ GroceryStore.cpp
     ./a.out
     ```

## Usage

Upon running the program, you will be presented with a menu where you can choose various options, including adding entries, displaying profits, searching product details, searching employee details, and modifying product/employee details. Follow the prompts and enter the required information to perform the desired actions.

## Data Storage

The program utilizes file handling to store information. It creates separate `.txt` files for each product and employee entry. These files contain the details of the respective entities and are automatically created during program execution. You don't need to pre-load any `.txt` files as the program handles their creation and management.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
