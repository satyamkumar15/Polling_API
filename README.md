
# 🗳️Polling System API

🔴This Polling API is made with NODEJS.🔴You can create question on this API and add Options to it.🔴You can vote for specific option. 🔴 You can Delete question. 🔴 You can only Delete Question or Option only if it has not votes;
## 🪧Demo

https://polling-api-t2ug.onrender.com/

## 📐Installation
1)Download Zip and Extract it and then run following commands in directory

2)Install my-project by running below command in console
```bash
  npm install
```
3)Provide `.env` file with `DB_URL` link inside it.

4)execute below command to run the server on localhost
```bash
  npm start
```
## 🪛Built With
🟠NODEJS 🟠ExpressJS 🟠MongoDB 🟠Mongoose 
## 🖼️Screenshots

🔴Landing Page

![WhatsApp Image 2023-06-29 at 9 13 54 PM](https://github.com/satyamkumar15/Polling_API/assets/104920110/d6ba9e05-613e-4b9c-9260-3c60ffe9512f)


## ✨Features

● User Can:
 
  * Create a question (you can add as many questions as you want)
  * Add options to a question.
  * Log out. 
  * Add a vote to an option of question.
  * Delete a question → ( A question can’t be deleted if one of it’s options has votes).
  * Delete an option → (An option can’t be deleted if it has even one vote given to it).
  * View a question with it’s options and all the votes given to it.
    
● Available Routes:
  * https://polling-api-t2ug.onrender.com/questions/create  (To create a question)
  * https://polling-api-t2ug.onrender.com/questions/:id/options/create  (To add options to a specific question)
  * https://polling-api-t2ug.onrender.com/questions/:id/delete (To delete a question)
  *	https://polling-api-t2ug.onrender.com/options/:id/delete (To delete an option)
  *	https://polling-api-t2ug.onrender.com/options/:id/add_vote (To increment the count of votes)
  * https://polling-api-t2ug.onrender.com/questions/:id (To view a question and it’s options)
    
## 🚦Version
1.0 - Running Succesfully with above feature.
