# Personalized Email Outreach system

**Description**  
Using this system, the user is able to send personalized emails to prospects on the basis of their linkedIn profile information.

**Functioning**  
This workflow starts by scraping the prospect's LinkedIn URL or username, and collecting personalized information about them. 
Then, on the basis of that information, it creates a personalized email including a personalized Subject, Intro, Offer, CTA and a P.S. 
Then, it combines the email for each prospect, and sends it to them through Email.
And finally it updates the google sheet database with a confirmation for each prospect who's been sent an email to. 

The best part is, the emails are sent with a time gap of 8 minutes between each email. This increases the email deliverability, and ensures that our emails do not come out as spam as if we burst them all out at once.

**Impact:**  
This automation can be leveraged to send personalized emails without having to worry about scraping any prospect's persoanlized information except just their LinkedIn profile, while also ensuring that the emails are sent with an appropriate time gap betweeen each one.

**Tools Used:**  
n8n, Gmail, Apify, AI agent, Google Sheets
