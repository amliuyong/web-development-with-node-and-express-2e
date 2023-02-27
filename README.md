# Examples - Web Development with Node and Express, 2nd Edition

*WORK IN PROGRESS*

Most of the code samples in this repo are complete, if difficult to navigate.  I am in the progress up updating the README files to make it easier to find your way around, and correct any missing documentation.  Please let me know if there's something that you feels needs additional clarification or explanation.

## Chapters

### Chapter 1

This is just an introductory chapter, with no example code.

### Chapter 2

The [Chapter 2 Examples](ch02/README.md) demonstrate a simple, minimal web server using Node only (no Express) to provide the reader a little background.

### Chapter 3

The [Chapter 3 Examples](ch03/README.md) demonstrate a simple, minimal web server using Express.

### Chapter 4

The [Chapter 4 Example](ch04/README.md) take the "fortune cookie" functionality developed in Chapter 3, and implement it as a Node module.

### Chapter 5

The [Chapter 5 Example](ch05/README.md) demonstrates unit testing with Jest, integration testing with Jest and Puppeteer, and linting with ESLint.

### Chapter 6

The [Chapter 6 Example](ch06/README.md) uses small examples to demonstrate various useful features of Express, such as rendering views, using cookies and sessions, processing forms, and providing an API.




#Table of Contents

Preface. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . xiii

##1. Introducing Express. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1

The JavaScript Revolution 1
Introducing Express 3
Server-Side and Client-Side Applications 4
A Brief History of Express 5
Node: A New Kind of Web Server 5
The Node Ecosystem 7
Licensing 8
Conclusion 9

##2. Getting Started with Node. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11
Getting Node 11
Using the Terminal 12
Editors 13
npm 14
A Simple Web Server with Node 15
Hello World 15
Event-Driven Programming 16
Routing 17
Serving Static Resources 18
Onward to Express 20

##3. Saving Time with Express. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
Scaffolding 21
The Meadowlark Travel Website 22
Initial Steps 22
v
Views and Layouts 26
Static Files and Views 29
Dynamic Content in Views 30
Conclusion 30

##4. Tidying Up. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31
File and Directory Structure 31
Best Practices 32
Version Control 32
How to Use Git with This Book 33
If You’re Following Along by Doing It Yourself 33
If You’re Following Along by Using the Official Repository 34
npm Packages 36
Project Metadata 37
Node Modules 37
Conclusion 39
##5. Quality Assurance. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 41
The QA Plan 42
QA: Is It Worth It? 43
Logic Versus Presentation 44
The Types of Tests 45
Overview of QA Techniques 45
Installing and Configuring Jest 45
Unit Testing 46
Mocking 47
Refactoring the Application for Testability 47
Writing Our First Test 48
Test Maintenance 50
Code Coverage 50
Integration Testing 51
Linting 54
Continuous Integration 58
Conclusion 58
## 6. The Request and Response Objects. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 59
The Parts of a URL 59
HTTP Request Methods 61
Request Headers 61
Response Headers 62
Internet Media Types 62
Request Body 63
vi | Table of Contents
The Request Object 63
The Response Object 65
Getting More Information 67
Boiling It Down 68
Rendering Content 68
Processing Forms 69
Providing an API 70
Conclusion 72
##7. Templating with Handlebars. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 73
There Are No Absolute Rules Except This One 75
Choosing a Template Engine 75
Pug: A Different Approach 76
Handlebars Basics 77
Comments 78
Blocks 78
Server-Side Templates 80
Views and Layouts 81
Using Layouts (or Not) in Express 82
Sections 83
Partials 85
Perfecting Your Templates 87
Conclusion 88
##8. Form Handling. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 89
Sending Client Data to the Server 89
HTML Forms 90
Encoding 91
Different Approaches to Form Handling 91
Form Handling with Express 93
Using Fetch to Send Form Data 95
File Uploads 97
File Uploads with Fetch 99
Improving File Upload UI 100
Conclusion 100
##9. Cookies and Sessions. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 103
Externalizing Credentials 105
Cookies in Express 106
Examining Cookies 107
Sessions 107
Memory Stores 108
Table of Contents | vii
Using Sessions 109
Using Sessions to Implement Flash Messages 110
What to Use Sessions For 112
Conclusion 112
##10. Middleware. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 113
Middleware Principles 114
Middleware Examples 115
Common Middleware 118
Third-Party Middleware 120
Conclusion 120
##11. Sending Email. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 121
SMTP, MSAs, and MTAs 121
Receiving Email 122
Email Headers 122
Email Formats 123
HTML Email 123
Nodemailer 124
Sending Mail 125
Sending Mail to Multiple Recipients 126
Better Options for Bulk Email 127
Sending HTML Email 127
Images in HTML Email 127
Using Views to Send HTML Email 128
Encapsulating Email Functionality 130
Conclusion 131
##12. Production Concerns. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 133
Execution Environments 133
Environment-Specific Configuration 134
Running Your Node Process 136
Scaling Your Website 137
Scaling Out with App Clusters 138
Handling Uncaught Exceptions 140
Scaling Out with Multiple Servers 142
Monitoring Your Website 143
Third-Party Uptime Monitors 143
Stress Testing 143
Conclusion 145
viii | Table of Contents
##13. Persistence. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 147
Filesystem Persistence 147
Cloud Persistence 149
Database Persistence 150
A Note on Performance 151
Abstracting the Database Layer 151
Setting Up MongoDB 153
Mongoose 154
Database Connections with Mongoose 154
Creating Schemas and Models 155
Seeding Initial Data 156
Retrieving Data 158
Adding Data 160
PostgreSQL 162
Adding Data 168
Using a Database for Session Storage 169
Conclusion 172
##14. Routing. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 173
Routes and SEO 175
Subdomains 175
Route Handlers Are Middleware 177
Route Paths and Regular Expressions 178
Route Parameters 179
Organizing Routes 180
Declaring Routes in a Module 181
Grouping Handlers Logically 182
Automatically Rendering Views 183
Conclusion 184
##15. REST APIs and JSON. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 185
JSON and XML 186
Our API 186
API Error Reporting 187
Cross-Origin Resource Sharing 188
Our Tests 189
Using Express to Provide an API 191
Conclusion 192
##16. Single-Page Applications. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 193
A Short History of Web Application Development 193
SPA Technologies 196
Creating a React App 197
React Basics 198
The Home Page 200
Routing 201
Vacations Page—Visual Design 204
Vacations Page—Server Integration 205
Sending Information to the Server 208
State Management 210
Deployment Options 212
Conclusion 212
##17. Static Content. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 215
Performance Considerations 216
Content Delivery Networks 217
Designing for CDNs 218
Server-Rendered Website 218
Single-Page Applications 219
Caching Static Assets 219
Changing Your Static Content 220
Conclusion 221
##18. Security. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 223
HTTPS 223
Generating Your Own Certificate 224
Using a Free Certificate Authority 225
Purchasing a Certificate 226
Enabling HTTPS for Your Express App 228
A Note on Ports 229
HTTPS and Proxies 230
Cross-Site Request Forgery 231
Authentication 232
Authentication Versus Authorization 232
The Problem with Passwords 233
Third-Party Authentication 234
Storing Users in Your Database 234
Authentication Versus Registration and the User Experience 236
Passport 236
Role-Based Authorization 246
Adding Authentication Providers 247
Conclusion 248

##19. Integrating with Third-Party APIs. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 249
Social Media 249
Social Media Plugins and Site Performance 249
Searching for Tweets 250
Rendering Tweets 253
Geocoding 256
Geocoding with Google 256
Geocoding Your Data 258
Displaying a Map 260
Weather Data 261
Conclusion 263
##20. Debugging. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 265
The First Principle of Debugging 265
Take Advantage of REPL and the Console 266
Using Node’s Built-in Debugger 267
Node Inspector Clients 268
Debugging Asynchronous Functions 272
Debugging Express 272
Conclusion 275
##21. Going Live. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 277
Domain Registration and Hosting 277
Domain Name System 278
Security 279
Top-Level Domains 279
Subdomains 280
Nameservers 281
Hosting 283
Deployment 285
Conclusion 288
##22. Maintenance. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 291
The Principles of Maintenance 291
Have a Longevity Plan 291
Use Source Control 293
Use an Issue Tracker 293
Exercise Good Hygiene 294
Don’t Procrastinate 294
Do Routine QA Checks 294
Monitor Analytics 295
Optimize Performance 295
Table of Contents | xi
Prioritize Lead Tracking 296
Prevent “Invisible” Failures 297
Code Reuse and Refactoring 298
Private npm Registry 298
Middleware 298
Conclusion 300
##23. Additional Resources. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 301
Online Documentation 301
Periodicals 302
Stack Overflow 302
Contributing to Express 304
Conclusion 306
Index. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 307
