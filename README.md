# Desk.com Canvas Articles
This is a Desk.com canvas application that allows you to search for related articles by providing it with a search term. Just to make sure we provide a valuable response we also strip meaningless words from the query.

![Preview](https://api.monosnap.com/rpc/file/download?id=kZSx7QhKE3Qwhkui8Aq2xhTfIoVHhb)

## Installation Steps
### Deploy the Application
The first step to install this application is to deploy the source code to your Heroku account. Simply click this button and the application will be deployed.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https%3A%2F%2Fgithub.com%2Fdesklabs%2Fcanvas-articles)

### Create the Integration URL
Now that you have the application on Heroku, go ahead and create the integration URL. You'll need specify the `q` param which in this instance is `{{case.subject}}` and how many articles you want to display, using the `count` param.

![Integration URL](https://api.monosnap.com/rpc/file/download?id=mktVLhMLxeB97DlaiTT0LE3t3inFNk)

### Add it to your Case Layout
The last step is to display your canvas application on your case layout. Don't forget to select some users you'd like to show the application to as well as change the height of the canvas based on the amount of articles you want it to display.

![Case Layout](https://api.monosnap.com/rpc/file/download?id=Sk6HYfJ8M5EAIVJnI1r0Yr3n9BJVhN)
