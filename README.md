# Simple financial management application_SQLite_Tkinter
<p class="has-line-data" data-line-start="1" data-line-end="3">This code implements a simple financial management application using the Tkinter library in Python. The application allows users to track their expenses and incomes by adding, editing, and viewing financial records.<br>
The main components of the code are as follows:</p>
<ol>
<li class="has-line-data" data-line-start="3" data-line-end="4">The Main class represents the main application window. It displays a toolbar with buttons for adding and editing records, and a treeview widget to display the financial records. It interacts with the DB class to store and retrieve data from an SQLite database.</li>
<li class="has-line-data" data-line-start="4" data-line-end="5">The Child class is a popup window that appears when the user wants to add a new financial record. It contains entry fields for entering the description, type (expense or income), and amount of the record. Clicking the “Dodać” button adds the record to the database.</li>
<li class="has-line-data" data-line-start="5" data-line-end="6">The Update class is a subclass of Child and is used for editing existing financial records. It prepopulates the entry fields with the selected record’s data and allows the user to modify it. Clicking the “Zmienić” button updates the record in the database.</li>
<li class="has-line-data" data-line-start="6" data-line-end="10">The DB class handles the database operations. It creates a table for storing financial records and provides methods for inserting data into the table.<br>
The <strong>main</strong> block initializes the application by creating a Tkinter root window, instantiating the DB class, and creating an instance of the Main class. It sets the window title, size, and starts the Tkinter event loop.<br>
Overall, this code provides a basic framework for a financial management application with features for adding, editing, and viewing financial records.</li>
</ol>
