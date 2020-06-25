## Back-end API to store repositories of your portfolio.
Built using JavaScript/Node.js and the web framework [Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs).
  
Allow the creation, listing, updating and removal of the repositories, and allow the repositories to receive "likes".

**How to run:**

First clone the repository or download it;

Open the project folder and run in the terminal:
	$ yarn
	$ yarn dev
	
In [Insomnia](https://insomnia.rest/download/), create a (get, post, put, delete) request and copy the following routes: 

GET (list repositories): http://localhost:3333/repositories

POST (create repository): http://localhost:3333/repositories

PUT (update repository): http://localhost:3333/repositories/:id

DELETE (delete repository): http://localhost:3333/repositories/:id

POST (add like): http://localhost:3333/repositories/:id/like
