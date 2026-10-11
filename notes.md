
Next.js
So the things I encountered here were first and foremost the automatic git push which i had no idea about. Next apparently auto commits
your folder and all its contents without you having to do the entire commit yourself. So when you set the push -u origin main the commit gets pushed.
Then I got to know about the  that next rootLayout calls and executes automatically. It acts like a frame where all the childer
pages are placed depending on their routing and stuff.
The childer here are the various pages. For example I make a home page, login page, signup page for all of these pages I will need to 
mkdir Home and inside that I need to make a page.tsx so then next sees that there is a folder names home so that will load on /home and vice-versa.

Then I got to know about the difference between npm run dev, run build and run start. npm run dev goes into dev mode and gives access to dev tools and proper error messages to help solve errors. npm run build goes into production mode and just compiles and prepares
the app for getting started an important distinction here is that it does not start it so npm run start will go ahead and start the already built app.
