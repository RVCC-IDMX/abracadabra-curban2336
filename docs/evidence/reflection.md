1. What happens when you open index.html directly in the browser (file://) vs using the development server?
Opening in the browser provides no magical transformation. Instead the ACME site stays bland and had a message saying that the site cannot reach its true potential being opened as is. Using the development server allows the website to undergo the transformation and become colorful with multiple ASCII art pictures. There are also console logs providing more details about needing to use npm run serve.

2. Why does the magic only work on port 3000 specifically?
The magic.js script filters it so only being opened on port 3000 allows for magic transformations. This means that any port beyond what is specified in the serve script will provide no magic transformations. 

3. What did you learn about npm scripts and how they can chain together?
I learned that, through npm scripts, you can run multiple scripts at the same time/in the specified sequence. the dev script runs generate AND serve in order to run the complete workflow of the assignment and open the magically transforming ACME site. In the case of dev, it used the && to run both at the same time. 

4. How does this project demonstrate the value of development tools and automation?
This shows how you can use the package.json to incorporate automated procedures to make testing and running builds so much faster. This can help cut down time spent on a project if the proper preparations can be made before hand. It took very little work to set up the scripts for this project, but now that it's done, I can run the entire workflow of the project with one simple command.

5. What other npm scripts could be useful for web development workflows?
Multiple npm scripts could be useful for web development. You could make a script to run an npm list check to verify the dependencies are installed. Combine this with an npm install run before hand to install dependencies and verify in one fell swoop. This allows to preset tests and verifications of specific aspects of the project with relative ease. 