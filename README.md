# ngrok
ngrok is a cross-platform application that enables developers to expose a local development server to the Internet with minimal effort.

to install ngrok on your linux machien , follow these steps : 

first of all , create an ngrok account by going to the link below : 

          https://ngrok.com/

after you signed up ,  download the ngrok tar file 

extract it by executing the command below : 

        tar -xf  "the package's name " 

after that  , go to your ngrok account , find your authtoken and copy it 

go back to the directory where you extracted the package  , and execute the command below : 

       ./ngrok config  add-authtoken  " paste your authtoken"


Well Done !!!! you made it !!!! 

  now you can run an ngrok server by running this command  below (just an example): 

         ./ngrok http [port number]  

