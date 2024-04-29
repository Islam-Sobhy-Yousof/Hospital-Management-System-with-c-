# Hospital Queue Management System

This is a simple hospital queue management system implemented in C++. It allows managing patients in different specializations, adding new patients, printing the list of patients, and getting the next patient for treatment.

## Features

- Add new patients to different specializations.
- Print the list of patients in each specialization.
- Get the next patient for treatment in a specific specialization.

## Usage

1. **Compile**: Compile the `main.cpp` file using any C++ compiler. For example:

- g++ main.cpp -o hospital
  
2. **Run**: Run the compiled executable:
   1. ./hospital
3. 3. **Menu Options**: Follow the menu options to perform various operations:
- **Add new patients**: Enter the specialization, patient name, and status (0 for regular, 1 for urgent).
- **Print all patients**: Print the list of patients in each specialization.
- **Get Next patient**: Enter the specialization to get the next patient for treatment.
- **Exit**: Exit the program.

## Example

```
$ ./hospital

Enter your choice :

1. Add new patients
2. Print all patients
3. Get Next patient
4. Exit

1

Enter specialization, name, status : 1 John 0
```
