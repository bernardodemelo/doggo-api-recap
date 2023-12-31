### 🐶 Doggo API Recap 🐶

Today, on our Recap Session we're going to use Doggo API to display cute photos of dogs 🥺

<img width="700" height="500" src="https://bestlifeonline.com/wp-content/uploads/sites/3/2019/10/Screen-Shot-2019-10-09-at-5.37.37-PM.jpg?quality=82&strip=all"/>

## Instructions

### Clone the Repo and Install NPM Packages

Hint: you have already the package-lock.json. So, after cloning the lab, you should only need to do 'npm install' to download the npm packages that are needed 😉

<br>

### 1st Interation: Display 5 Random Images on your Homepage

After having your project configured, check your app.js file. There you will find some basic Express / HBS configurations with already two 'GET' Request Routes created. 

Let's start with the first one. Inside GET '/' you should call your Doggo API to retrieve you 5 random Dog Photos 🐕🐕🐕🐕🐕

How can you do that? Just follow the documentation that is here: https://www.npmjs.com/package/doggo-api-wrapper 

After having the data with you, display it on the Browser, using your <b>all-breeds.hbs</b> file. 

<br>

### 2nd Interation: Display a Schnauzer Image on your Schnauzer Page

5 random Dog Photos is a cool ideia, but what about my doggo? He's a Schnauzer Miniature and he needs a single page for him. 

To do that, check your GET '/schnauzer' Route and the API Documentation that you have already. 

After having the data with you, display it on the Browser, using your <b>schnauzer.hbs</b> file. 

<b>Hint: do not forget that 'Schnauzer' is a breed and 'Miniature' a sub-breed 🧐 </b>

<br>

### Bonus: CSS, CSS, CSS 🎉

<br>

### Material 
<a href="https://zellwk.com/blog/async-await-express/#:~:text=To%20use%20async%2Fawait%2C%20you,handlers%E2%80%9D%20is%20more%20explicit).&text=Once%20you%20have%20the%20async,something%20immediately%20in%20your%20code."> How to use async/await Express Requests </a>
