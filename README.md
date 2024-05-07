# LaterLink
 See a cool link out there on the web but don't have time to read it right now?  
 
 LaterLink is a single-page, local-only storage service that bounces web-links you'd like to save into your own Google Sheet as the back-end.  Save interesting weblinks for later and effortlessly browse them from your very own Google Sheet.  Here's how it works.

 ## Setup


### Step 1
Start a new Google form and create three "short answer" questions. You can call the questions whatever you want. We'll call them "link," "keyword," and "notes" as shown here.

![form configuration](https://github.com/laterlink/laterlink.github.io/blob/main/Images/form01.png)

### Step 2
Next pull down the 3 verical dots and select "Get pre-filled link."

![prefilled](https://github.com/laterlink/laterlink.github.io/blob/main/Images/prefilled.png)

### Step 3
Fill in answers to your 3 questions with the words
`link`, `keyword`, and `notes` as shown here. You must fill in the 3 answers with these words exactly.

### Step 4
Next, get the link by clicking the "Get link" button.

![prefill 3 answers](https://github.com/laterlink/laterlink.github.io/blob/main/Images/prefilled3.png)

### Step 5
Go to [https://laterlink.github.io](https://laterlink.github.io) and click the 'Config' dropdown in the menubar.   Select `Set link to Google form` and paste the "Get link" link into the window.  This link is stored only in the local storage associated with your web browser.

### Step 6
Find some cool link and copy it.  Go to [https://laterlink.github.io](https://laterlink.github.io) and paste it into the link box, and optionally add any notes and keywords

### Step 7
Return to your Google form and click the `Responses` tab, then click `Link to Sheets`

![link to response sheet](https://github.com/laterlink/laterlink.github.io/blob/main/Images/linktosheet.png)

### Step 8
This will be the sheet where you can view your links.  Get a share link to this sheet and go back to  [https://laterlink.github.io](https://laterlink.github.io).  Pull down the `Config` dropdown and paste this share link into the `Set link to sheet` option.

### You're all set!

Return to [https://laterlink.github.io](https://laterlink.github.io) anytime you want to save a cool link for later, or to click the `Your links` link to see your links.

## And remember...

...nothing is stored on any server. Links are stored in your Google Sheet and the links you pasted above are only stored in the local storage associated with your browser.

The whole thing is in the one html file called `index.html` in this repo. 


