# JavaScript Jedis - May The Object Be With You
* Team members: 
   - Bryan Nonni
   - Deandre Vasser
   - Ailany Icassatti 

## CSc 4370 - Project 2
* Topic: JavaScript Video Game 
* Video Game Name: JS Jedi
* Technologies: 
   - Node.js
   - Express.js
   - JavaScript
   - Phaser.io
   - HTML
   - CSS
   - MongoDB

How to Install
1. Clone this repo
   SSH
   ```
   git clone git@github.com:bnonni/JS_Jedis.git
   ```
   HTTPS
   ```
   git clone https://github.com/bnonni/JS_Jedis.git
   ```

2. Open the repo in your favorite editor, and navigate to app folder. If you're using VScode, do this:
   - In terminal:
      ```
      cd JS_Jedis
      code .
      ```
   - In VScode integrated terminal:
      ```
      cd app
      ```
   - Otherwise, simply open the JS_Jedis folder with your editor

3. Inside app/ folder, install dependencies:
   ```
   npm install
   ```
4. Open the mongo.env file, and add your database credentials

5. Ensure that the source.sh file has user rwx permissions (-rwx------). To check, run this command in app/ folder:
   ```
   ls -l 
   ```
   - If you see -rwx------ to the left of source.sh, you're good to move on.
   - If not, run:
   ```
   chmod 700 source.sh
   ```

6. Execute the source.sh script
   ```
   ./source.sh
   ```
6. Finally, let's run our app!
   ```
   npm start
   ```