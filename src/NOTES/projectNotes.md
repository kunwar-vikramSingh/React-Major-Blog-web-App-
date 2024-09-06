first of all we use "Appwrite" as backend as a service, in this project we use react-redux tool kit, react-redux library, react-router-dom , tinymce-react ,html-react-parser,react-hook-form and env(which is a environmental protective variable).

FORMATION_____________________________________________________
1. First of all we need to install all the packages that we need in our project, we  can do this by running the following command in our terminal: npm install @reduxjs/toolkit react-redux react-router-dom appwrite @tinymce/tinymce-react html-react-parser react-hook-form.
2.  After installing all the packages we need to create a new folder in our project folder which is known as .env , in this folder we will store all our environmental variables, which is VITE_APPWRITE_URL="test environment",etc. and then access this  variable in our project by using process.env.VITE_APPWRITE_URL in our app.jsx.
3. After that We move to appwrite, where we create account and then make a Project Section, where we creates there differnt attributes like(MyBlog,Buckets,collections,etc).after creating them we link them into a folder which is known as "conf" inside src folder.

