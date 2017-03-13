# btg-email

This is the master repository for Books That Grow's email campaigns. Please be sure to read through the directions carefully and follow each step. Below the directions, you will see the documentation for which email template to use for each specific campaign.

####To use each template do the following:####

1. Open app.sendgrid.com and make sure you're logged in.

2. From the dashboard, navigate to Marketing > Campaigns.

3. Once you're on the marketing campaigns page, click on the "Create Campaign" button. It should be located in the top right part of the screen.

4. This will open a "Create a Campaign" window. You can choose any template and click Continue. **At this point it doesn't matter what template we use. In the next steps we'll copy and paste our personally customized HTML email into the code editor.**

5. After we click continue it should open our new campaign. If you look in the top left of the screen you will see a toggle switch for how to view the email with the two options, **Design** and **Code**. By default it will be set to **Design** view. Click to switch the view to **Code**.

6. The section below in this repository titled **Templates for Email Campaigns** lists out how to use the HTML templates provided. Simply look for the *Email Overview* of the campaign you'll be sending, along with what the *Subject* will read, and below it will be the file name of the HTML template. Click that link.

7. After clicking the link of whichever HTML email template you'll be using it will redirect you to the code for that template file. Highlight **ALL of the code**. Every template will start with `<!DOCTYPE html PUBLIC......>` and end with `</html>`.

8. Once you've copied the code go back to your Campaign on SendGrid, delete whatever code is already in there, and paste the copied code from our own customized templates on GitHub. *Please doublecheck to make sure all of the code was copied over correctly. Any typos could cause errors in the formatting.*

9. Use the documentation for the specific campaign chosen to now fill out the required fields in the "Settings" sidebar, left of the Code View. You'll need to fill in these sections and set them to the specified parameters:

   **_CAMPAIGN SETTINGS_**
   
  1. **Campaign Name** - *Email Overview* of the specific email you'll be sending out
  2. **From Sender** - *Alexa*
  3. **Subject** - *Subject* of the specific email you'll be sending out

   **_RECIPIENTS_**

  4. **List/Segments to Send To** - specified list to send the campaign to
  5. **Unsubscribe Group** - *Unsub*

10. After steps *1-9* are complete, you can now click the **Send Campaign** button in the top right corner of the screen. Congrats!


#Templates for Email Campaigns#

##HTML:##

###Email Overview: Intro to Books That Grow (HTML)###
####Subject: Find the same text at different reading levels####
#####Version 1#####
- [techtelltale.html](../master/html-emails/techtelltale.html)

#####Version 2#####
- techmlk.html

---

###Email Overview: Accessible Instructional Materials(HTML)###
####Subject: Redfining Accessible Reading Materials####
- sped.html

---

###Email Overview: Overview of BTG(HTML)###
####Subject: ELA Materials for Low Literate Teens and Adults####
#####Version 1#####
- techtelltale.html

#####Version 2#####
- techmlk.html

---

###Email Overview: Point out level change feature(HTML)###
####Subject: Helping SpED Students become more independent####

- techstudents.html

---

##Mail Merge (Don't forget to add links before sending):##

###Email Overview: Intro to Books That Grow(Mail Merge)###
####Subject: Introducing Books That Grow for SpED ELA####
- intro.txt

---

###Email Overview: Your Invited to Try Books That Grow###
####Subject: Special Invitation: Try Books That Grow####
- specialoffer.txt

---

###Email Overview: From Least Restrictive / Most Inclusive###
####Subject: What's qualifies as the Last Restricive Method in 2017####
- 




---
<!-- Old Templates

#Documentation On Which Templates To Use For Specific Recipient#

###For Technology Consultants###
- Tell Tale + Students w/ Free Account = techtelltale.html
- MLK + Students w/ Free Account = techmlk.html
- Just Students w/ Free Account = techstudents.html

###For Teachers###
- Tell Tale + Students = teachertelltalestudents.html
- Tell Tale + Books = teachertelltalebooks.html
- MLK + Students = teachermlkstudents.html
- MLK + Books = teachermlkbooks.html -->





