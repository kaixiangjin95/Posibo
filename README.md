# Posibo
<strong style="font-size:30px">Introduction:</strong><br/>
This project is a user feedback website and it is used to provide production information and feedback online. All feedbacks are transparent and real time, which allows all users can acquire objective feedback about corresponding product. Also, user can manage their personal reviews in comment interface. For business owner, it can collect Customer Satisfaction Score with star widgets. It guides shopkeepers to identify issues and take actions.<br/>

<strong style="font-size:30px">component:</strong><br/>
Each users can register and login in this website by the responsive form module that created by angular material. The users can add different product information according to corresponding store and leave their reviews on displaying page and it was creating with fade in and fade out animations. All reviews are transparent and real-time, which allows all users can acquire fully objective feedback on their selected product. Also, the user can manage their personal reviews on comment interface, which greatly increase the flexibility of this comment system.<br/>
And I used Nodejs and expressjs to build a backend server for this application and implement the get, put, post and delete API for this app. For example, the put API allows user to add new product on the displaying page or add new comments under corresponding product. And routers which the express created can help users to interact with the database. I also use some nodejs middleware to further complete the back end server, such as, I use body-parser to parse the incoming request bodies and Morgan to display the detail of all client-side requests, so the app can pinpoint the error when the server does not work. <br/>
And also to increase the security for this app, I use Json web token to implement user authentication. Once the user log in, each subsequent request will include the JWT, allowing users to access their own management interface that are permitted with that token. For data management, I used MongoDB to design and develop database and store product information and comments to the database.<br/>

<strong style="font-size:30px">Instruction to start the application.</strong><br/>
1.run npm install to install the dependencies.<br/>
2.run ng serve to check this application.<br/>
3.This project will be run on localhost:4200.<br/>

<strong style="font-size:30px">Environment:</strong><br/>
HTML5, CSS3, TypeScript, JavaScript, Angular CLI8, Node.js v12.18.2, Boostrap4, Jest v26.0.0, VS code v1.39, Git v2.28.0, NgRx v6.5.1, MongoDB v4.2.8.
