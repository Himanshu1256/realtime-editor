# realtime-editor

**Syntax Sphere** is a real-time code editor developed during a summer internship at Celebal Technologies. Built with React JS, Node JS, WebSockets, Express JS, and Socket.io.
It allows multiple users to collaborate on code simultaneously with low latency and high performance.

**Important steps** to run this web application:-                         
1. To install required node modules, run - **npm install** in terminal
2. After node modules are installed in **node_modules** folder, still one module will be left to installed i.e. **codemirror** which has to be installed manually in this project.  
3. To install **codemirror module** firstly run - **npm config set legacy-peer-deps true**, then run - **npm i codemirror@version5**. Then codemirror module should be installed in node_modules folder
5.  After all the node modules are installed successfully, type **yarn start** in terminal to *launch the web application on port no. 3000*.
6. After web application is launced, type **yarn sever:dev** in terminal to *start the server* successfully.

 

**Working of Syntax Sphere web application:-**  
1. Click on **new room** button to generate new room ID, to create a room. Enter your username in the provided field.
2. **Connected users**c will be displayed on left hand side, and code editor is provided on right hand side. 
3. Click on **Copy ROOM ID** to copy current room ID to share to other users.
4. Now **open the login page in new tab** and paste the copied ROOM ID for new user to join. 
5. The code within the room can be written and edited by both users in real-time, ensuring seamless collaboration and immediate updates.   
      

  

**Basic Features:-**
1. **Real-Time Code Editing**: Allows simultaneous editing by multiple users.
2. **Syntax Highlighting**: Supports syntax highlighting for popular languages.
3. **Version Control**: Tracks changes and revisions for easy rollbacks.
4. **Chat Functionality**: Enables real-time communication between collaborators.
5. **User Authentication**: Provides secure signup, login, and logout.
6. **Code Snippet Sharing**: Allows optional sharing of code snippets. 
