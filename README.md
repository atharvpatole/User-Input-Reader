# User-Input-Data

This program reads user input containing individual information (first name, last name, zip code) and stores it in objects. It validates input format and data types, and then displays the collected data upon program completion.

Functionality:

-Prompts the user to enter data in the format: first_name <tab> last_name <tab> zip_code (separated by tabs).

-Validates input format, ensuring each line contains three tab-delimited values.

-Validates zip code data type, ensuring it's a valid integer.

-Stores each person's information in a Data object, consisting of firstName, lastName, and postalCode.

-Maintains an ArrayList to store the collected Data objects.

-Upon receiving "quit", the program terminates and displays the stored data to the console.
