# Desk.com Canvas: Support Announcement
**Support Announcement** is a Desk.com Canvas application that allows you to share a company wide message with all of your support agents. You can display this message anywhere in your case layout.

## I. Deploy the Application
First, install this application by deploying the source code to your Heroku account. To deploy your application, simply click this button:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https%3A%2F%2Fgithub.com%2Fdesklabs%2Fcanvas-message)

## II. Create an Article
The message shown in the canvas application is the **Title** of an [Internal Article](https://support.desk.com/customer/portal/articles/1917925-creating-internal-articles-?b_id=6346).

1. [Create an Article](https://support.desk.com/customer/portal/articles/1594036-create-an-article) and copy the article **ID** from the URL (see, below).
2. Compose your message in the **Title** field (e.g., "This is the message I want to show.").

**Note:** After composing the message, make sure the "Show in Support Center" is turned off.

![Article Editor](https://api.monosnap.com/rpc/file/download?id=rZd667FtTCpBh3ReGBJkgaBGzIjBMA)

## III. Create the Integration URL
Having created an internal article, go ahead and create the integration URL. You'll need the article ID as well as the domain of your Heroku application.

1. In the **Name** field, add a title for the this application. In this example, we’ll you use 'Message'.

2. The **Description** field, though optional, is a way to give a general description of the integration URL.

3. Select 'Canvas iFrame' from the **Open Location** dropdown.

4. In the **URL** field, add the URL, including the article ID by specifying the `q` parameter.

5. Toggle the **Enabled** button to 'Yes' and select the [Permission level](https://support.desk.com/customer/portal/articles/1146981?b_id=7112&t=568640).

6. Click the **Update** button.

![Integration URL](https://api.monosnap.com/rpc/file/download?id=v73BvQU7iz5dANHSnLp9kt6IPct3zk)

## IV. Add it to your Case Layout
Now display the canvas application on your Case Layout.

1. **Go to Cases >> Next Gen Case Layouts**

2. Find the **Message** canvas application in the **Integrations** section on the right side of the screen.

3. **Drag** and **Drop** the application in your case layout.

4. Scroll over the left side of the 'Message' bar and click on the gear to open the **Edit** window. Adjust the pixel **Height** (e.g., 33) and **Position**, the order in which it appears in Case Details on the dashboard. Click **Save**.

![Case Layout](https://api.monosnap.com/rpc/file/download?id=iEozPLB4qaGc589tM1XOB6MSPyCbgV)

## V. Dashboard Confirmation
After you have added the canvas application to your layout and selected users, open a ticket and take a look at **Case Details** on the dashboard. You will see the message shared with the selected users in the **Message** field.

![Preview](https://api.monosnap.com/rpc/file/download?id=txdv7AWondcYhjjxuXI8OO7yiuxoai)
