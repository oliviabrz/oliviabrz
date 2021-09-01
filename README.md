# About Me
Hello! My name is Olivia; I am 26 years old and in an interesting stage of life at the moment. For the last few years I've been working towards a career in college athletics. I spent the majority of 2020 applying and interviewing for jobs in that field. However, as time wore on, I came to the tough decision not to pursue that path and decided to go into a completely new direction. My motivation to change careers came during the pandemic when I realized the IT world would allow me to explore different industries. Prior to December 2020, I had never taken a computer course and the most analytical class I've probably taken was college algebra. So, when I say I started from scratch, I really mean that. 

# About The Process
This README documents my learning process to obtain the skills required for a career in Software Development. It began with successfully completing Coursera's [**Google IT Automation with Python**](https://www.coursera.org/professional-certificates/google-it-automation?utm_source=gg&utm_medium=sem&utm_campaign=11-GoogleITwithPython-US&utm_content=11-GoogleITwithPython-US&campaignid=8986236679&adgroupid=119480419197&device=c&keyword=&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=506915205324&hide_mobile_promo&gclid=CjwKCAjwpMOIBhBAEiwAy5M6YC58jIqHwDL-Nn4oPzbaQXaImQMMyW30OKlaNC2EtrXvSsRVKHdxehoCvroQAvD_BwE) course and receiving a certificate of completion. After completion of the course, my mentor felt it was essential to learn about Full Stack Development. We decided to build an Angular web application called [**NBA**](https://www.olib.cloud/) to display various NBA statistics. The application is built using Angular for the front end, Python Flask scripts for the Api's, and MySQL for the database. The site itself is hosted in Azure Cloud on a Ubuntu Linux VM. 

This entire process, from start to finish, took me approximately 8 months. I will be honest, this journey was quite challenging because my professional background in higher education/college athletics did not come with the hard skills necessary in IT. My mentor, who has 30 years of experience as a Software Engineer, guided me through the entire process. Looking back, what got me through was dedicating as much time as possible 7 days a week and keeping an open mind, despite the many challenges I faced. 

The content below highlights the various learning resources, technologies and concepts I learned.

## Learning Resources
- https://codewars.com

## Python
- Data Types
    -String, integer, float, list, set, tuple, dictionary, bool
- Variables
    - A user declared name that points to a memory location containing data of some data type 
- Loops
    - For loop (iterate over a range)
    - While loop (iterate while something is true)
- Expressions 
    - Expressions are made of operators and operands. An expression is like 2 + 3 
- Operators 
    - The symbols which tells the Python interpreter to do some mathematical or logical operation 
- Conditionals
    -If/elif/else statements 
- Collections
    - List (mutable, ordered, allows duplicates)
    - Tuple (immutable, ordered, allow duplicates)
    - Sets (mutable, unordered, no duplicates)
    - Dictionary(mutable, key/value)
- Functions
    - A block of code that runs only when it's called
    - Can accept parameters (variables) 
    - Can return data 
    - Makes code more modular by separating it into smaller, more specialized tasks 
- Classes
    - Bundles data and functionality together 
    - A class definition defines a new type of object, allowing new instances of that type to be made (see car example)
    - Instances of a class represent:
        - a location in **allocated memory** 
        - Properties of the class exist in memory and have an **initial state**
        - Example: An instance of class Car exists in memory and its property, current_speed == 0mph (initial state)
        - The **dunder** __init__ is a specialized function (constructor) that gets called when a new instance is being created and allows   you to specify properties and their initial values 
- Interpreter
    - A program that converts python scripts to an executable program that runs on a specific CPU/operating system (macOS, Linux, Windows)
- Resources
    - https://www.w3schools.com/python/default.asp

## Operating Systems
- An operating system is system software that manages computer hardware, software resources, and provides common services for computer programs
- Windows, MacOS, Linux, Unix

## Git 
- Version Control System
- Software that tracks changes in any set of files so you have a record of what's been done
    - Can also revert to specific versions if you ever need to 
- Used for collaborating and coordinating work among programmers 
- 3 main components of a Git project:
    - Repository
        - the .git/folder inside a project
        - if .git/folder is deleted, your project's history will be deleted 
    - Working tree
        - where files are modified 
    - Index
        - staging area where commits are prepared by comparing files in the working tree to the files in the repo
- Basic Git Workflow:
    - Modify file in the working tree
    - Stage the changes you want to include in the next commit 
        - `git add`
    - Commit changes to the repo 
        - `git commit -m` 
- https://training.github.com/downloads/github-git-cheat-sheet.pdf
- file:///Users/oliviabrzozowski/Downloads/SWTM-2088_Atlassian-Git-Cheatsheet.pdf
- GitHub is a widely used Git repository hosting service 
- Remote vs Local
    - Local repository resides on the computer of the worker
    - Remote repositories are hosted on a server, such as GitHub
## Concepts
- SOC (separation of concerns)
    - the process of separating unrelated functionality from each other 
    - achieved through functions, classes, modules, etc.
    - makes code more understandable and maintainable 
- Client/Server
    - A model where clients make requests to a server which fulfills the request
- Regular Expressions (RegEx)
    - A sequence of characters that forms a search pattern and can be used to check if a string contains the specified search pattern
    - https://help.relativity.com/9.3/Content/Relativity/Regular_expressions/Regular_expression_metacharacters.htm
    - https://regex101.com/
- ### Network Concepts
    - localhost and 127.0.0.1
        - a hostname that refers to the current computer at the network level
        - defined in `/etc/hosts` file
    - DNS/Domain Name (domain name system)
        - Domain name
            - a user friendly name for an IP Address
            - example: `olib.cloud`
        - DNS maps domain name to an IP address 
            - example: `nslookup olib.cloud`
    - IP Address
        - a unique **Internet Protocol** address that identifies a device on the internet or a local network
    - Port Number 
        - Identifies a particular application or service on a system
        - Example: think of an IP address as an apartment building's street address, and port number as a
        specific apartment number
## Compute Resources
- CPU
    - Central Processing Unit 
    - The electronic circuitry that executes instructions comprising a computer program
    - The CPU performs basic arithmetic, logic, controlling, and input/output operations specified by the instructions in the program
    - The register within a CPU is what determines the size of the CPU (32/64 bit)
        - https://techterms.com/definition/register
- Memory
    - Random Access Memory (RAM) is the high speed, non-persistent storage part of the computer that stores various parts of a running program
    - Non-persistent means when the computer shuts down, everything in memory is lost
    - This is where instructions, functions, variables, instances of classes, etc. are stored 
- Hard Drive
    - The part of a computer where persistent data is stored so that it can be retrieved after the computer restarts 
    - Persistent means when the computer shuts down, the data still exists and can be retrieved when the program runs
    - Significantly slower than RAM 
    - Examples are databasing systems (SQL servers)
## Binary
- Bits/Bytes
- Base-2
- https://www.mathsisfun.com/numbers/bases.html
## ODBC/DBMS
- DBMS (database management system)
    - A server or software system that enables users to define, create, maintain and control access to data in a database
    - MySQL, Microsoft SQL Server, MariaDB, PostgreSQL
- ODBC (Open Database Connectivity)
    - A specification that describes or defines a generic way of accessing DBMS's
    - It is meant to be independent of any specific database or operating system
    - A ODBC Driver is what implements the specific way of accessing DBMS's
        - For your program to work with a specific DBMS, you will use a driver specific to the DBMS to implement your requests
    ### Relational Database
    - A type of database that stores and provides access to data points that are related to one another
    - SQL (Structered Query Language)
        - The standard language for relational DBMS's 
    - Primary key
        - Uniquely identifies each record in a table
    - Foreign key
        - a database key that is used to link two tables together
    - Normal forms
        - First normal form
            - The relation cannot contain any repeating groups
        - Second normal form
            - Every field in the relation must be functionally dependent upon the entire primary key
        - Third normal form
            - The relation cannot contain any transitive dependencies
    - CRUD
        - Create, Read, Update, Delete
        - The 4 types of operations that can be performed on a database 
## HTTP (hypertext transmission protocol)
- HTTP is a protocol which allows the fetching of resources on the Internet 
    - https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview
- HTTP vs HTTPS
    -HTTP is insecure
    -https is secured by a certificate on a server that tells clients that they are talking to the domain they intended to talk to 
        - PKI (public key infrastructure)
            - public/private key
            - used to make https secure
            - https://www.sslshopper.com/public-key-infrastructure-pki-overview.html
- URL (Uniform Resource Locater)
    - The path to a unique resource on the Web
    - https://blog.hubspot.com/marketing/parts-url
    - https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL 
- HTTP server
    - Computer software that accepts requests via HTTP
    - All web applications/api's require a http server
    - Examples: Apache Tomcat, IIS, node.js, python flask/waitress
- Most common HTTP methods
    - GET, POST, PUT, DELETE
- Headers
    - Area in an http request/response where key/value pairs of information about the request/response reside
        - Example: **User-Agent:** Mozilla/5.0 (Macintosh; Intel Mac OS X 10.9; rv:50.0) Gecko/20100101 Firefox/50.0
## Web API
- API (Application Programming Interface)
    - An interface which has a set of functions that allow programmers to access specific features or data of an application, operating     system or other services 
- Web API
    - A set of functions that are called or requested using HTTP 
    - Requests are received by an HTTP server and passed to a programmer defined service running on a computer that executes the functions
    - example: https://www.balldontlie.io/#getting-started
- JSON (JavaScript Object Notation)
    - A text based data format used to send/receive lightweight messages between computers
    - Uses key/value pairs to structure data
- Media Type
    - Formally known as MIME type (Multipurpose Internet Mail Extensions)
    - A standard way of classifying file types on the Internet according to their nature and format
## HTML
- HTML (Hypertext Markup Language)
- The set of markup symbols or codes inserted into a file intended for display on the Internet
- The markup tells web browsers how to display a web page's words and images
- JavaScript
    - A programming language that can add interactivity to a website 
    - https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics
    - https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript
- DOM (Document Object Model)
    - When a web page is loaded, the browser creates a **D**ocument **O**bject **M**odel of the page
        - The HTML DOM model is constructed as a tree of objects and exposes an api of functions and properties that can be easily accessed programatically
            -  https://www.w3schools.com/js/js_htmldom.asp
        - JavaScript can modify the DOM in realtime using the DOM api to give a much more interactive user experience 
            - https://www.digitalocean.com/community/tutorial_series/understanding-the-dom-document-object-model
    - You can visualize this using `F12` to bring up the browser debugger
        - Go to `Console`, then type in `document.` and you should see the DOM api functions pop up
## Angular
- https://angular.io/docs
- A development platform, built on [TypeScript](https://www.typescriptlang.org/), used for building single page web applications 
- SPA (Single-Page Application)
    - A web application that loads most resources (HTML+CSS+Scripts) only once when the site is first loaded by the browser
    - Only data is transmitted back and forth
    - This is all made possible by the DOM
- Components
    - The main building block for Angular applications
    - Each component consists of:
        - A HTML template that declares what renders on the page
        - A Typescript class that defines behavior
        - A CSS selector that defines how the component is used in a template
        - Optionally, CSS styles applied to the template
- TypeScript(ts)
    - Open-source language which builds on JavaScript
    - Strongly typed language
        - Each type of data is predefined 
            - Native data types, such as a string, integer, datetime, boolean, are built into the language
            - User defined data types, such as class or interface, allow users to define their own data types
    - https://www.typescriptlang.org/
- Interfaces
    - User defined data type that describes the shape of data to create a data contract
    - Data contract
        - A formal agreement that describes data to be exchanged 
    - Differ from classes because they only provide shape of data (what it looks like), whereas classes provide both shape and storage (class properties) of the data
- Databinding
    - The synchronization of data between the model and view components
        - https://docs.angularjs.org/guide/databinding#:~:text=Data%2Dbinding%20in%20AngularJS%20apps,the%20model%20at%20all%20times.
- HttpClient service class
    - https://angular.io/guide/http
    - This is what we used to call our Restful api's
- Angular Client (ng)
    - https://angular.io/cli
    - scaffold new application
        - `ng new`
    - build application
        - `ng build`
    - run application
        - `ng serve`
## SSL Certificates 
- Used to make https secure
- An SSL (Secure Sockets Layer) certificate is a digital certificate that provides the following two functions:
    1. Establishes trust by authenticating the identity of a website
        - CA (Certificate Authority)
            - A trusted organization that verifies a domain that websites run under, so that you trust who you’re communicating with online            
        - CSR (Certificate Signing Request)
            - A block of encoded text that is given to a Certificate Authority when applying for a signed SSL Certificate
            - Contains information that will be included in the certificate such as the public key, organization name, common name (domain name), locality, and country
            - A private key is usually created at the same time that you create the CSR, making a key pair
        - Signed Certificate
            - The process a CA uses to digitally sign your certificate using their signing certificate. When your browser trusts the CA, it's automatically trusting your certificate because it was signed by the CA.
    2. Encrypts information sent between the client/server using SSL technology and PKI
- An SSL certificate contains the following information:
    - The certificate holder's name
    - The certificate's serial number and expiration date
    - A copy of the certificate holder's public key
    - The digital signature of the certificate-issuing authority
- PKI (**P**ublic **K**ey **I**nfrastructure)
    - This is what the encryption function of SSL cerfiticates are based on
    - Implemented by Asymmetric algorithms, like RSA, that use the **public key** for encrypting data and **private key** for decrypting data 
    - https://www.sslshopper.com/public-key-infrastructure-pki-overview.html
- Exciting CA for obtaining your SSL certification 
    - https://letsencrypt.org/


## SSL Certification Process
In order to run our Angular NBA app on our azure VM, we had to secure it with an SSL certificate. The following is the process we used to get our certificate:
1. Purchased `olib.cloud` domain from GoDaddy.com, a **Domain Registrar**
2. Purchased SSL certificate from RapidSSLOnline.com, a **Certificate Authority (CA)**
3. Create Certificate Signing Request (CSR) as follows:
    ### Creating CSR
    - Generate CSR here: https://www.digicert.com/easy-csr/openssl.htm
        - This generates the openSSL command to generate the CSR and public/private key pair
        > openssl req -new -newkey rsa:2048 -nodes -out junk.csr -keyout junk.key -subj "/C=US/ST=KS/
        > L=your city/O=junk/CN=junk"
    - Copy generated CSR and paste into RapidSSL CSR screen
    ### Domain Control Verification (DCV)
    - Before a certificate can be issued to a domain, you must prove to the CA that you control the domain.
    - See: https://docs.digicert.com/manage-certificates/demonstrate-control-over-domains-pending-certificate-order/use-http-practical-demonstration-validation-method-verify-domain-control/
    - There are numerous methods for DCV such as email and HTTP Practical Demonstration.
    - We chose **HTTP Practical Demonstration**. This process is as follows for our domain `olib.cloud`:
        - In GoDaddy, add an `A` record that points to the IP Address of our VM
            - To verify a domain's IP, run `nslookup olib.cloud` and verify the IP address is correct for the domain
        - In RapidSSL, choose HTTP file verification method
            - You will be given a **.txt** file to download 
            - You will be given the verification URL to pull the file from your VM
        - Setup your VM to serve the .txt file. On your VM, do the following:
            - Copy .txt file to a local directory given in the verification URL 
            - Run a http server like `sudo python3 -m  http.server 80` from the root of the path in the verification URL
            - Verify you can pull the .txt file using the verification URL
            - Because the file can be retrieved from my VM, proves I own the domain and VM

## Useful Tools
- Chrome debugger
    - `F12` key
- VisualStudio Code
    - Free editor we used for all of our work
    - Supports Git, Python debugging,
- DBeaver
    - Client for connecting to and using various SQL servers 
- Postman
    - Client for making http requests, especially for testing web Api's 

## Azure
- Microsoft's cloud platform that offers many services 
- We chose to use Azure VM to host our NBA web application 
- Other cloud platforms include Amazon Web Service (AWS), Google Cloud 

## NBA Application 
The [**NBA**](https://www.olib.cloud/) web application is my final project and first attempt at **Full Stack Development**.
The application is designed to display various NBA statistics that we pulled from publically available web Api's. The application is built using Angular for the front end, Python Flask scripts for the Api's, MySQL for the database, and NGINX for the web server. The site itself is hosted in Azure Cloud on a Ubuntu Linux VM. 

### Full Stack Development
- The development process that encompasses both Frontend (Client) and Backend (Server) technologies 
- Frontend (Client)
    - This is typically the User Interface (UI) 
    - This can be web or mobile based applications
    - We used [Angular](#angular) to build our web front end 
        - The technologies we used are HTML, CSS, Typescript
    - We hosted the Frontend on a Ubuntu Linux VM in Azure Cloud
- Backend (Server)
    - These are the parts of the application that include the following:
        - Databasing to persist (store) our data
        - Api's used by the Frontend to update and retrieve data from our databases 
        - Web server to provide https to the internet for the NBA app and the Api's
    - We used `MySQL` as our database server 
        - We used `DBeaver` as a client tool to manage our database 
    - We used Python, Flask, and Waitress to build a set of Api's for easier integration between the frontend and MySQL database
        - `Python` is used to build the functions used to interface with MySQL 
        - `Pyodbc` is the Python module we used for the MySQL ODBC Driver 
        - `Flask` is used to take Python functions and make them callable through http
        - `Waitress` is used to make our Flask functions production ready since Flask only provides a development server
    - We used `NGINX` to take https requests from the internet and route the request either to the NBA app or to our Api's running under Waitress web server
        - NGINX routes `https://olib.cloud` requests to the NBA Angular app
        - NGINX routes `https://olib.cloud/api*` requests to the Waitress http server to fulfill Api requests 
            - These Api requests happens when the Angular application needs data (ex. when you click the `Players` menu link)
            - To see this in action, click `F12` to bring up the debgugger and click on Network tab 

### Setup Python Flask Api as a service 
- https://medium.com/codex/setup-a-python-script-as-a-service-through-systemctl-systemd-f0cc55a42267
- sudo nano /etc/systemd/system/api.service
- copy/paste contents of systemd.txt
- sudo systemctl daemon-reload
- sudo systemctl enable api.service
- sudo systemctl start api.service
- sudo systemctl status api.service

- ~/NBA/run/python
- /var/www/olib.cloud/html/
- /etc/nginx/sites-available
- www_olib_cloud.key
- www_olib_cloud.pem

### Setup NGINX on our Linux VM
Steps to setup:
- sudo mkdir -p /var/www/olib.cloud/html
- sudo chown -R $USER:$USER /var/www/olib.cloud/html
- sudo chmod -R 755 /var/www/olib.cloud
- nano /var/www/olib.cloud/html/index.html
- sudo nano /etc/nginx/sites-available/olib.cloud
- sudo ln -s /etc/nginx/sites-available/olib.cloud /etc/nginx/sites-enabled/
- sudo nano /etc/nginx/nginx.conf
- sudo systemctl restart nginx

- NBA website files are here:
    - /var/www/olib.cloud/html 

Resources:
- https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-20-04
- https://dev.to/thetrebelcc/how-to-run-a-flask-app-over-https-using-waitress-and-nginx-2020-235c
- https://medium.com/@anasecn/how-to-serve-an-angular-app-with-node-js-api-on-a-nginx-server-ca59de51850
### Setup ODBC Driver for module pyodbc (unixODBC)
- pyodbc is the python implentation of the ODBC specification
1. Download the driver for your specific database
2. Open terminal
3. Run `odbcinst -j`
You should see something like:
`
unixODBC 2.3.9
DRIVERS............: /etc/odbcinst.ini
SYSTEM DATA SOURCES: /etc/odbc.ini
FILE DATA SOURCES..: /etc/ODBCDataSources
USER DATA SOURCES..: /Users/oliviabrzozowski/.odbc.ini
SQLULEN Size.......: 8
SQLLEN Size........: 8
SQLSETPOSIROW Size.: 8
`
4. Open file to the right of `DRIVERS:`
5. Enter your driver information something similiar to
`
[MySQL ODBC 8.0 ANSI Driver]
Driver=/usr/local/lib/libmyodbc8a.so
UsageCount=1
`
6. In your python code, use the string within the brackets for the 'Driver='

## Issues and their fixes
### Pyodbc
In our Python script where we created our Apis, we had an issue with the returning dictionary, generated using __dict__ , where strings were returned with the unicode replacement character. The line below fixed the issue:
> self.cnxn.setdecoding(pyodbc.SQL_CHAR, encoding='utf-8')

### Fixing Flask error
When we tried running the Flask script, we would get an error stating 'address already in use'. The lines below fixed the issue:
    (Killing the Flask process does not stop the port it's using.)

The Fix:
> ps -fA | grep python
>
> kill -9 `<pid>`





