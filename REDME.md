You should:

1. If you want to use mongoDB:
write the console:
-> sudo service mongod start
(use a separate terminal window for this process)
1a. if you open console mongo, write this:
-> mongo
2. If you want to stop the process, write the console:
-> sudo service mongod stop
3. install Mongoose:
-> npm install mongoose --saves
4. If you want to use Heroku, wtite in the console:
4a. -> heroku create
4b. -> git push heroku master
-> heroku ps:scale web=1
-> heroku open
5. use mLab:
-> click the button Create new in section MongoDB Deployments
-> use amazon and Sandbox (it's free)
-> click your bd and open users
-> click the button Add database user
-> when you see link, use it but <dbuser> write name_of_your_user and <dbpassword> write your_password_when_you_create_the_users
and do it again 4b
--------------------------------------------------------------------------------
heroku App: https://sleepy-ocean-54667.herokuapp.com/
