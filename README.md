# Mzanzi Bank-Management-System---Java

<h3>Overview</h3>
The Mzanzi Bank Management System is a Java-based application designed to manage user accounts, perform transactions, and handle banking operations. This application utilizes a MySQL database to store user and transaction data and provides functionality for user registration, login, account management, and transactions through a command-line interface. It also relies heavily on the understanding of inheritance.

<h3>Features</h3>
1. User Registration and Login:  Allows users to register with a username, password, and additional details, and subsequently log in to manage their accounts.
2.Account Management: Users can view account details and perform transactions.
3.Transaction Types: Supports deposit, withdrawal, and transfer operations for both savings and checking accounts.
4. Database Integration: Connects to a MySQL database to store and retrieve user and transaction data.

<h3>Prerequisities</h3>
1. JDK 8 or higher
2. MySQL Database
3. MySQL Connectoe/JJDBC Driver

<h3> Set Up</h3>


<h2>Classes and Methods</h2>
<h3> Main Methods:</h3> 
<h6>public static Connection getConnection(): Establishes a connection to the MySQL database.</h6>
<h6>public static void insertUser(int userID, String lastName, String idNumber, String username, String password): Inserts a new user into the database.</h6>
<h6>public static void insertTransaction(int userID, String accountNumber, String transactionType, double amount, double balance): Inserts a transaction record into the database.</h6>
<h6>public static void viewAccount(int userId): Displays account details for a specific user.</h6>
<h6>public void start(): Starts the main menu loop.</h6>
<h6>private void registerUser(Scanner scanner): Handles user registration.</h6>
<h6>private void loginUser(Scanner scanner): Handles user login.</h6>
<h6>public void logoutUser(): Handles user logout.</h6>
<h6>public static int generateRandomUserId(): Generates a random user ID.</h6>

