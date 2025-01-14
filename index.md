# Paul Kim ePortfolio

## Professional Self-Assessment

Hello! My name is Paul Kim, and welcome to my ePortfolio!

I've had a challenging yet fulfilling journey in studying computer programming, where I’ve had to overcome many obstacles. My coding and problem-solving skills were tested time and time again, pushing me to think and adapt to many scenarios. Driven by my passion for technology and a commitment to overcoming obstacles, I’ve evolved into a programmer who sees challenges as opportunities for innovation and growth. 
This ePortfolio is a testament to that journey, showcasing the projects and experiences that have shaped my understanding of software design, algorithms, data structures, and database management. Each artifact represents a significant milestone in my development, reflecting the skills I’ve acquired and the lessons I’ve learned along the way. 

In this ePortfolio, I’m excited to share with you the artifacts that not only highlight my technical abilities but also tell the story of my personal and professional development. I hope that through this ePortfolio, you'll gain insight into my journey, the lessons I've learned, and the passion that drives me to continue growing in this ever-evolving field of computer science.

Let's begin with the first artifact I want to showcase in this ePortfolio: my Inventory App, which I have named **InvenTrack** to reflect its purpose of efficient inventory tracking and management.  

**App Functionalities**

Upon launching the app, the user is prompted to grant SMS permissions. Depending on their response, the app will either send SMS notifications or refrain from doing so. 

![SMS Permissions](/assets/img/sms-permissions.PNG)

After this, the user will be directed to the Login screen, where they can either log in or sign up. Note that the 'Login' button is disabled until the user fills in the username and password fields.

![Login Screen](/assets/img/loginScreen.PNG)

If the user opts to sign up, a dialog fragment will appear, allowing them to enter their username, password and email. 

![SignUp Screen](/assets/img/signup-dialog.PNG)

These credentials are then stored in a SQLite database, where the app will validate and authenticate the user's information accurately. 

![Login Authentication](/assets/img/login-database.PNG) ![Authentication Example](/assets/img/credentials-authentication.PNG)

Once logged in, users can create or delete categories and assign items to a specific category, ensuring that items are organized according to their designated categories. 

The user can press the '+' button at the bottom right corner to prompt the user to add a category and it will appear in the grid.  

![Categories Screen1](/assets/img/categories-screen.PNG) ![Categories Screen2](/assets/img/categories-dialog.PNG) ![Categories Screen3](/assets/img/add-category-example.PNG)

If the user clicks on a category, they will be directed to the Inventory screen where a recycler view displays the items of that category and where the user can add or modify these items's name, description, quantity, and price which are stored in a SQLite database.

![Inventory Screen](/assets/img/inventory-screen.PNG) ![Add Item](/assets/img/add-item.PNG) ![Add Item Example](/assets/img/add-item-example.PNG)
![InventoryEdit Screen](/assets/img/edit-item-screen.PNG) 

## Code Review
[Code Review](https://youtu.be/rIfXHOgMl9w)

I've created a code review video that discusses my original artifact and details the enhancements I plan to make across the three key categories, aiming to further improve the artifact and highlight my technical skills. 
As discussed in my code review, this artifact is an Android application developed in Java using Android Studio, designed to manage warehouse inventory through SQLite databases, which handle both item tracking and user authentication. It applies both front-end and back-end development principles to ensure a comprehensive solution.
On the front-end, the app features an intuitive and simple user interface to streamline inventory management. On the back-end, it implements robust class structures, CRUD operations, and essential algorithms for efficient data handling. 

The video review outlines the specific improvements I intend to make in the three key categories and are designed to showcase my ability to integrate software design and engineering principles effectively, while aligning with the course objectives and demonstrating my evolving technical expertise.

# Narratives
[Software Design and Engineering](/software-design-enhancement.md)

[Datastructure Algorithms](/datastructure-algorithms.md)

[Database](/database.md)
