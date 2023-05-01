# BookExchnager
- A Java Web Developement Project
 
<hr>
### About
A user-friendly Online Bookstore project in which users can log in or register, view the available books, select books along with their quantity, and buy them. Users can also get payment receipts after successful payment. The project can also be used by the administrator, who can add new books, remove books, increase and decrease the quantity of books, change the price of the books as well as maintain the selling history of books.

![onlinebookstore](https://user- <span style="color:blue">**This Website is built for following purpose:-**</span>
- For Selling books online.
- Maintaining books selling history.
- Adding and managing books.
- User Friendly.
- For Implementation of Http Servlets in Java.
- This is a Mini-project developed using Java, Jdbc, And Servlets.

<span style="color:blue">**Admin Have Following Access for this online store site:-**</span>
- Add New Books.
- View Books Available.
- Remove Books.
- Increase Books Amount.

<span style="color:blue">**Users Have Following Access for this online store site:-**</span>
- Create New Account or Register.
- Login.
- View Available Books.
- Select Books to Buy.
- Select Books Quantity.
- Buy Books.
- Get Payment Receipt.

### Technologies used:-
1. Front-End Development:
- Html 5.
- CSS.
- Javascript.

2. Back-End Development:
- Java [JDK 8+]
- JDBC
- Servlet

3. Database:
- MySql

### ================ Software And Tools Required ================
- Eclipse [Enterprise Edition]
- Java [JDK 8+]
- Tomcat v8.0+
- Apache Maven
- MySQL

### ================= Dummy Database Initialization =================

STEP 1: Open MySQL Command Prompt or MySQL Workbench

STEP 2: Login to the administrator user as : ```mysql -u <username> -p``` (Enter Password if asked)

STEP 3: Copy paste the following MySql Commands-
```MySQL
create database if not exists onlinebookstore;

use onlinebookstore;

create table if not exists books(barcode varchar(100) primary key, name varchar(100), author varchar(100), price int, quantity int);

create table if not exists users(username varchar(100) primary key,password varchar(100), firstname varchar(100),
    lastname varchar(100),address text, phone varchar(100),mailid varchar(100),usertype int);

insert into books values('9780134190563','The Go Programming Language','Alan A. A. Donovan and Brian W. Kernighan',400,8);
insert into books values('9780133053036','C++ Primer','Stanley Lippman and Josée Lajoie and Barbara Moo',976,13);
insert into books values('9781718500457','The Rust Programming Language','Steve Klabnik and Carol Nichols',560,12);
insert into books values('9781491910740','Head First Java','Kathy Sierra and Bert Bates and Trisha Gee',754,23);
insert into books values('9781492056300','Fluent Python','Luciano Ramalho',1014,5);
insert into books values('9781720043997','The Road to Learn React','Robin Wieruch',239,18);
insert into books values('9780132350884','Clean Code: A Handbook of Agile Software Craftsmanship','Robert C Martin',288,3);
insert into books values('9780132181273','Domain-Driven Design','Eric Evans',560,28);
insert into books values('9781951204006','A Programmers Guide to Computer Science','William Springer',188,4);
insert into books values('9780316204552','The Soul of a New Machine','Tracy Kidder',293,30);
insert into books values('9780132778046','Effective Java','Joshua Bloch',368,21);
insert into books values('9781484255995','Practical Rust Projects','Shing Lyu',257,15);
insert into users values('demo','demo','Demo','User','Demo Home','42502216225','demo@gmail.com',2);
insert into users values('Admin','Admin','Mr.','Admin','Haldia WB','9584552224521','admin@gmail.com',1);
insert into users values('shashi','shashi','Shashi','Raj','Bihar','1236547089','shashi@gmail.com',2);

commit;


Note:- Considering this as a Sample Project, we have not much considered of web security.
#### Some Screenshots for the project:
1.FRONT PAGE
![PROJECT](https://user-images.githubusercontent.com/114331816/235481621-4773d092-cf46-4bc9-8196-cdb9d309d6f6.png)

2.LOGIN PAGE
![project 2](https://user-images.githubusercontent.com/114331816/235481899-81c78295-a30b-434b-b1da-2bde5f021b10.png)

3.USER REGISTRATION PAGE
![project 3](https://user-images.githubusercontent.com/114331816/235482042-d535f7cd-99ee-45f1-ac97-8e3dca485ca6.png)

4.AVAILABLE BOOKS
![project 4](https://user-images.githubusercontent.com/114331816/235482283-4e1f8f30-0624-4823-b3b3-cb8bbb4acc00.png)

5.CHECKOUT AND PAYMENT PAGE
![prject 5](https://user-images.githubusercontent.com/114331816/235482541-3ee9844c-d315-48c4-ab56-f4fc7c1fb2c1.png)



