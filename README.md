# Backend-Concepts
At first, working with MVC on the backend can be challenging, especially because connecting all the pieces can become challenging.

So, I start by drawing an entity relationship chart on paper. It provides a lot of clarity, helping me visualize what I want and preventing me from getting tangled up in the connections while working on a project.

For example, I did a small project involving authentication using MVC in Node.js. Here’s how I interpreted the MVC structure—though it may look different from what you typically find online. This is my personal approach to completing a project.

![image](https://github.com/user-attachments/assets/78da153a-66d7-4635-84a0-8303e02a4f89)

Here's what the folder structure and connection looks like for this authentication project. For views, i.e., U.I, I have used POSTMAN

![image](https://github.com/user-attachments/assets/22be9615-b79d-4fe9-8820-72522899ce7d)

## Programitically

a. First entry point - server.js file, we write

![image](https://github.com/user-attachments/assets/8ec8a763-413b-4072-9a29-6f0aa82999b9)

b. Next, the Router 

![image](https://github.com/user-attachments/assets/fef5bbd4-90c1-4ed7-b287-e908d8af05ae)

c. Then, Login Controller - This is where we write logic, like - Reading user's entered username and password, and then read the database through model if the value exists, if yes then validation takes place and 
a user sees respecitive message on their screen.

![image](https://github.com/user-attachments/assets/c091e3e0-9fb4-4b42-bfa6-15c4e432716c)

d. Model file content looks like this

![image](https://github.com/user-attachments/assets/537e3b7f-ceb1-49c5-888a-eec380e8e6a5)

Hope this helps, with understanding MVC pattern!















