# NOTE TAKER

I created a note taker that organizes and displays a well structured not taking system that diplays the notes took.

File explanation: .gitignore keeps the all the node module files out. package.json links the express script downloaded in node, then package-lock.json has all everything that makes express work. The public folder is the HTML's, called public becasue thats what users will see. Then theres the db folder with the db.json file, which is our data base. All the new notes will be stored inside of it. Then the routes folder with index.js inside, that tells the notes to go into the database folder. Lastly is the server.js file, this adds what users write on the page into a js file.

How everything goes full circle: We have our HTML for users to interact with, that has the index.js script linked

Then index.js grabs those notes, creates a file, stringify's it and pushes it to the database, which is linked. 

Lastly the server.js links the database to it and puts the newly made information from the database to the page, in a nice format beacause of the HTML.


1. [My repo Link](https://github.com/bmallar/Note-Taker)
2. [My Live URL link](https://note-taker-8xer.onrender.com/)