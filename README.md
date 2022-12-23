
# Grocery Store Management System

An inventory management application developed using C++.
Done as part of the Semester 3 "Object Oriented Programming with C++" Course at SRM University, AP


## Features

We have designed the project in a way that it can manage a Grocery Store’s Revenue, and calculate their costs, profits, salaries.

This application allows the user to:
- Add, Store and Update Product Details
- Add, Store and Update Employee Details
- Calculate the daily profit by finding the profit from sales, and subtracting the employee’s daily wage
- Use file handling to store the profits and products for next days



## Run Locally


Clone the project

```bash
  git clone https://github.com/adivishnu-a/Grocery-Store-Management-System
```

Go to the project directory

```bash
  cd Grocery-Store-Management-System
```

Run the program

```bash
  g++ -o GroceryStoreMgmt GroceryStoreMgmt.cpp&GroceryStoreMgmt.exe
```


## FAQ

#### Are changes required in any part of the code?

No, the code is system and platform independent, so changes in the .cpp script are not required. Just make sure you have the GCC/G++ compiler, and run the program

#### How is the data stored for multiple executions?
The program creates .txt files to store the information of various products, and the detils of employees, each record entity having it's own seperate file.

#### So, do I need to have the .txt files pre-loaded for the program to run smoothly?
Though the program can also use any existing .txt files during it's execution, it can run without any existing .txt files. The program automatically creates .txt files for each entry added during execution, so that they can be used for the successive runs. So you don't have to presave any .txt files.
