# Desk.com Canvas: Related Articles
**Related Articles** search is a Desk.com Canvas application that allows users to search for case-relevant articles by using search terms. Administrators and agents can employ precise terms in the query, ensuring efficient response time.

## I. Deploy the Application
First, install this application by deploying the source code to your Heroku account. To deploy your application, simply click this button:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https%3A%2F%2Fgithub.com%2Fdesklabs%2Fcanvas-articles)

## II. Create the Integration URL
Now that you have the application on Heroku, go ahead and create the integration URL.

1.  In the **Name** field, add a title for this application. In this example, we'll you use 'Related Articles'.

2. The **Description** field, though optional, is a way to give a general description of the integration URL.

3. Select 'Canvas iFrame' from the **Open Location** dropdown.

4. In the **URL** field, specify the `q` parameter. In this instance it is `{{case.subject}}`. Use the `count` parameter to specify the number of articles to be displayed.
**Note:** Refer to the [List of Liquid Variables](https://support.desk.com/customer/portal/articles/2916-list-of-liquid-variables) knowledge article for a complete list of Desk Liquid Objects.

5. Toggle the **Enabled** button to 'Yes' and select the [Permission level](https://support.desk.com/customer/portal/articles/1146981?b_id=7112&t=568640).

6. Click the **Update** button.

![Integration URL](https://api.monosnap.com/rpc/file/download?id=mktVLhMLxeB97DlaiTT0LE3t3inFNk)

## III. Add it to your Case Layout
Now display the canvas application on your Case Layout.

1. **Go to Cases >> Next Gen Case Layouts**

2. Find the **Related Articles** canvas application in the **Integrations** section on the right side of the screen.

3. **Drag** and **Drop** the application in your case layout.

4. Scroll over the left side of the 'Related Articles' bar and click on the gear to open the **Edit** window. Adjust the pixel **Height** (e.g., 33) and **Position**, the order in which it appears in Case Details on the dashboard. Click **Save**.

![Case Layout](https://api.monosnap.com/rpc/file/download?id=Sk6HYfJ8M5EAIVJnI1r0Yr3n9BJVhN)

## IV. Dashboard Confirmation
After you have added the canvas application to your layout and selected users, open a ticket and take a look at **Case Details** on the dashboard. Notice that three Related Articles are displayed.

![Preview](https://api.monosnap.com/rpc/file/download?id=kZSx7QhKE3Qwhkui8Aq2xhTfIoVHhb)
