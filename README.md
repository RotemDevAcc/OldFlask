# iLibrary - Your Digital Library

iLibrary is a powerful digital library management system designed to make it easy to manage books, users, and interactions within your library. It offers a range of features to streamline your library's operations and enhance user experience.

## Features

## Default Admin User
- With a default username and password
  - Username: admin
  - Password: admin


## How Do i Log out?
  Click On the Message (Welcome {name})

  ![Logout](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/logout.png)

### User Authentication
- Secure user authentication with hashed passwords for maximum security.

### Logging System
- The server always tells you what the problem is so you won't be left in the dark whenever something goes wrong
- Logging don't work well with live server due to the refreshes that are caused by live server ( logging is disabled by default instead we use Red Printed Text, Change this in Back/project/helper.py)

### Book Management
- Add and remove books from your library's collection with ease.
- Track the number of copies available for each book.
- View a list of books borrowed by users.


![Book Management](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help6.png)


### User Borrowing
- Users can borrow books for different durations: a day, a week, or a month.
- Automated notifications to users and administrators when due dates expire.
- Automatic return of borrowed books when a user is deleted.

![Book Borrow](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help5.png)


### Contact Form
- Users can contact the library via a contact form.

![Contact Form](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help3.png)


- Management can view all contact forms at all times.


![View Contact Form](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help4.png)

### Book Details
- For each book, provide essential information:
  - Name
  - Author
  - Cover Image
  - Release Date

## Getting Started

### Prerequisites

- Python (version: Built With: 3.11.5)
- Flask
- SQLAlchemy
- werkzeug (for password hashing)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/RotemDevAcc/PythonFB.git
   cd PythonFB

2. Create The Virtual Enviorment:

  navigate to PythonFB/Back

  ### Install the virtual enviorment if you don't have it
  pip install virtualenv (once per computer)

  ### Create the virtual enviorment
  python -m virtualenv myenv (once per project)

  ### Activate the virtual enviorment
  myenv\Scripts\activate  (Activate)

  ### install the requirements
  pip install -r requirements.txt



3. Change The Secret Key

  Navigate To PythonFB/Back/project/init.py ( has 2 _ _ between it)

  Find __app.config['SECRET_KEY']__ and change it


  ![Secret Key](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help9.png)

4. Start The Flask Server
  
  
  Navigate To PythonFB/Back ( You can use cd Back Command)
  
  
  run python app.py or py app.py
  
  
  Flask Server Port By Default Is //:911 ( A Guide to change it below )

and Finally Enjoy!


5. Access The Interface/GUI


  open PythonFB With Visual Studio Code ( if you haven't done so already)



  ![Open With Code](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help7.png)

  then open Front/index.html with Live Server

  ![Open Live Server](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help8.png)

  



# Wanna Change The Port? 
  the port will be set to 911 by Default
  
  in order to change it you need to change it in the Backend and FrontEnd



  navigate to PythonFB/Back/app.py and change the ServerPort To whatever you want



  ![Port Back app.py](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help1.png)



  after that navigate to PythonFB/Front/script.js and change the ManualIP To true and set the ip address / port to whatever you want



  ![Port Front script.js](https://github.com/RotemDevAcc/PythonFB/raw/main/HelpImages/help2.png)