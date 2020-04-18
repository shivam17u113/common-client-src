# common-client-src
this folder basically contains the src folder that you have to paste in your client project by beleting the previous one.

follow the following steps to create client side.
#1.npm init                        // cmd
#2.npm i -g @vue/cli               // cmd
#3.vue create client               // cmd

#4.// copy the src folder from git and pasete in that folder
#5.// in package.josn add following lines in by removing old blank ruels object

  "rules": {
      "no-console": "off",
      "no-unused-vars": "off",
      "no-multiple-empty-lines": "off"
    },
    "parserOptions": {
      "parser": "babel-eslint"
    }
  },
  
 #6. copy the .vue.config.js and paste it in the client folder
 #6.1   run this command
  npm install --save vue-resource vue-router  // cmd
 #7. cd client                             // cmd
 #8. npm run serve                        // cmd to run file
