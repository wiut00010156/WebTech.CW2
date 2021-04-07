# nodejs-todo

<h2> A simple To Do List application built with Node.js and Express</h2>

<p> Current nodejs application that you see on your device will let you add and remove tasks on a single page, storing both new and completed tasks in a different arrays. This appllication makes use of: </p>

<ul>
<li> EJS - A simple templating engine that lets you generate HTML markup with plain JS. Ejs is better than pug when it comes to the structure. For this reason, EJS view engine was chosen for this coursework.</li>

<li> Body-parser - This extracts the entire body portion of an incoming request stream and exposes it on req.body </li>
</ul>

You can have a look at my repository by clicking on this link(https://github.com/ 'web todo')

<br>

<p> The descripton of how to run the project locally is given below: </p>

<ol>
<li> First of all, please run 
``` bash 
npm install
```

to install all needed dependencies on the local folder.</li>

<li> Then start the server using  
```bash
node index.js
```
 </li>

<li> Navigate to your browser to the follwoing link http://localhost:7000/  to view the app </li>
</ol>

<p> You can also view the deployed website by looking at the following website:  </p>

The application is dependant on expressjs, ejs, and body-parser.

/public folder has styles.css - where the styling was completed
/views folder has index.ejs - the template of the website.
