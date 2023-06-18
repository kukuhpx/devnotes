## **UPLOADING REPO TO HEROKU SERVER**
*Follow these steps to upload your repo to Heroku server:*
1. Open your terminal and go to ypur inside project folder.
2. If you haven't create the repo in your project, create the repo with using git command:
> git init
3. Crete 3 files:
	1. index.html
        // just create html file ussualy
	2. index.php
        <?php include_once('index.html'); ?>
	3. composer.json
        {}
4. Add all file to stage:
    > git add --all
5. Commit all staged files:
    > git commit -m ['your message"]
6. Login to your Heroku account with command:
    > heroku login
    (If there appear "ip mismatch" message in browser, use command [heroku login -i])
7. Click press any key to open your browser.
8. Click login button, before you click the button, you must log in to the Heroku website.
9. Close your browser and back to terminal.
10. Crete heroku app with command below, choose one cmmmand:
    > heroku create
11. There will be 2 outputs:
	1. [unique app name].herokuapp.com
	2. [remote url]
12. Upload your repo to heroku:
    > git push heroku [your repo name]
13. Wait until finish.
14. Done.