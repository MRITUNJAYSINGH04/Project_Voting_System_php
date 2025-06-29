📊 Advanced Online Voting Management System in PHP & MySQL
A web-based voting system built using PHP and MySQL that allows users to cast votes online in a secure, scalable, and user-friendly environment. Suitable for use in elections, contests, educational polls, and corporate voting systems.

🚀 Key Features
🧑‍💼 Admin login & role management

🗳️ Voter registration and authentication

📥 Vote preview before submission

📊 Result visualization with bar charts

🖨️ Export results as PDF

🔄 Dynamic ordering of positions

✏️ CRUD for voters, candidates, and positions

🔐 Secure login system with session control

🛠️ Tech Stack
Language: PHP

Database: MySQL

Frontend: HTML, Bootstrap, jQuery, AJAX

Server: XAMPP / WAMP / LAMP

📂 Modules Included
Login & Authentication

Election/Contest Creation

Voting Mechanism

Vote Counting Logic

Results Display with Charts

Admin Dashboard

📥 How to Run
🧪 For educational use only

Download or clone this repository.

Install XAMPP and start Apache & MySQL.

Copy the project folder to xampp/htdocs.

Open browser → visit http://localhost/phpmyadmin

Create a DB named votingsystem

Import votingsystem.sql from the db folder

Now go to: http://localhost/votingsystem

🔑 Admin Credentials

""""""""""""""""""""""
Username: nurhodelta
Password: password
""""""""""""""""""""""

🧠 Project Structure
index.php – User login

admin/ – Admin dashboard & management

submit_ballot.php – Vote submission logic

preview.php – Preview ballot page

tcpdf/ – PDF generation

db/ – SQL dump

📈 ER Diagram & Flowchart
Entity relationships between users, votes, candidates, and elections

Vote lifecycle from login → cast vote → tally → result display

✅ Objectives
Enable remote & secure online voting

Ensure transparency, reliability, and re-countable audit logs

Reduce physical infrastructure and manual effort in elections

📌 Note
This project is designed for learning purposes. Customize it for production use with enhanced security and scalability as needed.
