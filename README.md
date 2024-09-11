# ReachInBox-Frontend

## Overview
This repository contains the code for Reachinbox frontend  App using React with Typescript for an assignment given by Reachinbox.

## Technologies Used ( Frontend )
  - Typescript
  - React
  - Tailwind css

## Deployment

The application is deployed on vercel and can be accessed [here](https://reachinbox-frontend.netlify.app/).

## Demo Video :- 
https://www.loom.com/share/b12a1f9ab67e48ae8e90efff18bccc9b?sid=6a306c49-9d1a-4b37-9dfa-21b4538e3831

## Login Page

![image](https://github.com/user-attachments/assets/405ccbdf-b80a-4dde-bd67-4ea8434e981b)


## Landing Page

![image](https://github.com/user-attachments/assets/9f0dff6c-d6d0-4d29-b405-e55c90be1c86)


## Deshboard with Dark Mode
 
![image](https://github.com/user-attachments/assets/0b5f29d8-98db-4743-8394-aeb7fb8d2104)


## Dashboard with Light Mode

![image](https://github.com/user-attachments/assets/f9c5b21f-b2da-41c1-a0f8-0ad0a5839f38)

## Delete Email 

![image](https://github.com/user-attachments/assets/2841b7e0-df70-4c53-bf51-022ed7c29943)



 # How to Run <br/>
 
   <h2>Installation</h2>
   
   Clone the repository:   ``` git clone https://github.com/shwetharavindrabaliga/reachinboxai.git  ``` <br/>
   Install the dependencies:   ``` npm install ``` <br/>
   Start the development server:   ``` npm run start ``` <br/>
   Open your browser and visit:   ``` http://localhost:3000 ``` <br/>
   

   ## Features 
   
  - Authentication
  - Get Emails
  - Post (send) Email
  - Delete Email


   <h2>Endpoints</h2>
   <h3>All Emails</h3>
   <pre><code>GET {{baseurl}}/onebox/list </code></pre>

   <h3>All Emails from Onebox</h3>
   <pre><code>GET {{baseurl}}/onebox/messages/:thread_id </code></pre>

   <h3>Add Onebox Mail</h3>
   <pre><code>POST {{baseurl}}/onebox/reply/:thread_id </code></pre>

   <h3>Delete Email</h3>
   <pre><code>DELETE {{baseurl}}/onebox/messages/:thread_id </code></pre>

   <p>Feel free to explore and integrate these endpoints into your application.</p>
  
