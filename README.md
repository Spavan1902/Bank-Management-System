<h1>Bank Management System (BMS)</h1>

<h2>1.Project Introduction</h2>
<p1> A console-based Bank Management system. which covering core operations and focusing heavily on <b><br>input validation<br>transaction control<br>real date and time update<br>user Input handling.<br></b><h3>Employee login:</h3>
For system security , I implemented login security in my system with controlled access handling.
After 3 failed login attempts, the Employee ID is automatically blocked to prevent unauthorized access.
Because authentication isn’t just about logging in—it’s about stopping the wrong people from getting in.<br>
<p>
  <h3>User Input handling:</h3>
If a user enters invalid input more than three times during any operation, the system automatically cancels the transaction. This prevents misuse, reduces unnecessary system load, and ensures that repeated errors do not affect data integrity.
</p>
</p1>

<h3>2. Why does i Develop it?</h3>
<p>
The main purpose of this project is to understand how banking systems work behind the scenes. It focuses on handling user data, maintaining transaction records with real date and time update, and preventing invalid or unauthorized actions action by user.
</p>

<h2>3.Core Operations</h2>
<p1>
The system allows employees to perform the following operations according to Account status(<b> Active , Inactive, close )</b>:
<br>
&gt; <b>Employee Login </b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;(Possible only if Employee id and password are true.)<br>
&gt; <b>Create Account</b> &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(if Name, addhar No., DOB are true then Account open.) <br>
&gt; <b>Deposit Money</b>    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(possible only if A/c No. true and valid amount with correct security pin.)<br>
&gt; <b>Withdraw Money</b>   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(possible only if A/c No. true and valid amount with correct security pin.)<br>
&gt;<b> Transaction History</b>  &nbsp;&nbsp;&nbsp;&nbsp; (real date and time | Transaction Id | cradit | dabit | balance.) <br>
&gt; <B>Customer Passbook</B> &nbsp;&nbsp;&nbsp;&nbsp;  (All the possible detais that are must be in passbook.)<br>
&gt; <b>Balance Inquiry</b>   &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  (if account is true then available balace shows with possible details.) <br>   
&gt; <b>Customer Details</b>   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (if Account found then all the possible details shows of given account.)  <br>
&gt; <b>Customer List</b>   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; (it shows all the customers list which help to found customers details.) <br>
&gt; <b>Close Account</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;(if all the given data for close account is true the then account successfully closed.)<br>  
&gt; <b>System Logout</b>   &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;( After compeleting all the operations user can logout from the system.)  <br>
 deposit and withdraw contain recipt which contains real date and time, account number, and other details which need in recipt.
  
</p1>

<h3>4. How does it work?</h3>
<p>
The system starts with an employee login. If the login details are correct, access is granted to the main menu. If the user enters wrong credentials three times, the system blocks the employee ID to prevent misuse.
<br>
After login, the employee can choose different operations from the menu. The system checks all inputs carefully, such as DOB, Addhar number, Mobile number, OTP of registered Mobile No. , Security pin, account number, balance, and personal details. If something is wrong, it shows an error instead of crashing.
<br>
Each transaction is handled properly to make sure the data stays correct and consistent.<br>
After completing all the operation  user must be logout form the system which shows system stability and data prevention.
</p>

<h2>6.Limitations</h2>
<p>
- This is a console-based system (no graphical interface). <br>
- Data may be stored locally (no database support). <br>
- It does not support multiple users at the same time. <br>
- Security features are basic compared to real banking systems. <br>
</p>
