When I first learn to code, I find it crucial to have a firend review my code and **give me feedback** the first time I write something inefficient. I can not find a website whicn enalbes users to practise coding online and can **collaboratively editing** their code: Leetcode do not support collaborative editing, collabedit does not support running your program directly, coderpad does not provide problems and test cases. 

Since I am learning MEAN stack, I decided to develop a site myself. This project is what I have built:) This is a **online judge website**(kind of like Leetcode), but I add some features like collabrative editing (like google doc) to my website.

There are 2 role on this website, one is normal user. **Users** can browse questions and coding in the editer and submit their answer. My website will run their code and give the complie infomation as well as the result of their program.(TODO: this feature is under development). User can also code with their friends like editing on google doc. You can see anther user's cursor and want they are typing in real time.

The other role is **Administraters**. Besides from coding and browsing the website, they can add new questions for the website. They need to provide the name, description as well as the level of the new question.

This project using **MEAN stack**: Angularjs as the client side framework, Nodejs and Exxpress as the server side, MongoDB as the database. I also use Socket.io to implement the collabrative editing part, use docker to run users' program and use Auth0 to handle the user signin and signup.

TODOs:
1. Develop the run program feature which enables users to run their program on Docker in the backend.
2. Deploy this project online! It is so excited to release my very first product:)
3. Add a pad for user to draw. A picture is the most efficient way to express your idea:)
