# Sign365 Administration Portal Documentation

*6/12/2021*

## Overview

You have arrived at the documentation to search for a way to do a specific task within the Sign365 Administration Portal (SAP) or to refresh your mind on the process that the SAP utilizes. This portal is designed for managing users and data within the Sign365 application for your business. Below are some quick guides for the tech-savvy user.

### Upload Templates (Quick Guide)

1. Go to **Templates** in the left hand menu
2. Click the gray box in the middle of the page above the upload where it says "Click to Attach a PDF"
3. Select the template from a location on your computer
4. Hit the upload button
5. Verify that the document has appeared in the list below

### Upload Integration Data (Quick Guide)

Once you have installed and logged into the app you will be in the "Drafts" area. Your workflow will now consist of the following easy steps when filling out lots of PDFs

1. Go to **Integrations** in the left hand menu
2. Click the gray box in the middle of the page above the upload where it says "Click to Attach a CSV"
3. Select the CSV file from a location on your computer
4. Hit the upload button
5. Verify that the button has turned green and says "Uploaded"

### Create User (Quick Guide)

1. Go to **Users** in the left hand menu
2. Click the **+** icon in the bottom right hand corner
3. Fill all fields marked with a *****
4. Hit the blue **save** icon in the bottom right, between the **+** and the **x** 

### Change User Password (Quick Guide)

1. Go to **Users** in the left hand menu
2. Click the **Password** field of the user that you would like to change
3. Enter the password
4. Hit the blue **save** icon in the bottom right, between the **+** and the **x** 

### Change User Displayname (Quick Guide) 

1. Go to **Users** in the left hand menu
2. Click the **Displayname** field of the user that you would like to change
3. Enter the password
4. Hit the blue **save** icon in the bottom right, between the **+** and the **x** 

### Delete User (Quick Guide)

1. Go to **Users** in the left hand menu
2. Click the **trash** icon with the red background to the far right of the user that you would like to delete
3. Hit the blue **save** icon in the bottom right, between the **+** and the **x** 

## Accessing Sign365 Administration Portal (SAP)

In order to access Sign365 Administration Portal (SAP). You need to use a computer and not a mobile device as SAP is not optimized for this. You will also be required to use a modern browser like Chrome, Firefox, Safari, Edge.

## Terminology

### Sign365 Administration Portal

Is the web portal that is found online under a company specific URL such as - sign365admin.mywebsite.com.au

### Integration

An integration is a specific system that the Sign365 system interacts with. These will be listed in the iPadOS app for the users to select when they want a form to be processed by the specific system that Sign365 interacts with (see Sign365 documentation for how).

### Integration Tags

Integration Tags are labels that attach to forms to identify the information against a a specific system that the Sign365 system interacts with. They can be thought of in a similar way to sticky notes. In that you put a sticky note on a piece of paper that identifies it and categorizes it for future reference.

A form can have many tags, with many integrations. Each tag contains the following information

- Integration Name
- Identifying Field
- Value Field

### Integration Data

Integration Data is the list of **Identifying Fields** and **Value Fields** that are contained under a specific integration. 

### User

A user is defined as someone that uses the application with a given credential (username/password).

## Managing Users

In order to manage templates you will need to go to the left hand menu and select "Users". After which you will be brought to this page. Here you can:

- Add as many users as you like
- Change as many passwords as you like
- Change many user details

All within a single table which makes it more time efficient. All you need to do is make the changes you want and hit the save button to save them. Or the cancel button to revert back to the original table before you made the changes.

![Alt text](https://drive.google.com/uc?export=view&id=1ZJSfm2QI9rYzkaMSe5dleVd4ukA4RSQS "Display Users")

### Adding New User

One of the regular tasks in the life of an administrator is adding new users to the system. In Sign365 this will consist of hitting the **+** icon in the bottom right hand corner of the screen (see above image) which will add an empty row to the table of users (see below image).

![Alt text](https://drive.google.com/uc?export=view&id=19LootAVrXBeiN9aDHPtlr0A9JHEw8m6C "New User")

You must fill out all the fields that are marked with ***** and hit the save for the new user to be created. For all users the role that should be selected is "User" for all administrators (the people accessing SAP) they should have the role "Admin".

*Note: The "Service" Role can be ignored. It is used for setting up integrations and is not required for administrators*

### Updating Users

Only select items on an existing user can be edited. In the below image example we have previously created an account called "Test" we did not however specify the "Firstname" and "Lastname" when we created it. 

We can add those in by clicking the field and filling out the names we would like (in this case Test Test) and hitting the save button in the bottom right hand corner of the screen.

![Alt text](https://drive.google.com/uc?export=view&id=1pZoHEKaaQ7VFonpSFzDoUeb5_0rzbaAS "Update User")

### Deleting Old User

If we wish to delete an old User or a new user that we created but don't actually need we can hit the delete button next to the row where our user is located to remove it. We then need to hit the save button in the bottom right hand corner of the screen.

![Alt text](https://drive.google.com/uc?export=view&id=19LootAVrXBeiN9aDHPtlr0A9JHEw8m6C "New User")

### Cancelling Changes

If we no longer want to keep the changes we have made or we have lost track of the modifications we have made to a table we can revert to the previous state of our user table by hitting the red **X** button in the bottom right (see below)

![Alt text](https://drive.google.com/uc?export=view&id=19LootAVrXBeiN9aDHPtlr0A9JHEw8m6C "New User")

When this is done you will see everything back to normal (see below).

![Alt text](https://drive.google.com/uc?export=view&id=1ZJSfm2QI9rYzkaMSe5dleVd4ukA4RSQS "Display Users")

## Managing Templates

In order to manage templates you will need to go to the left hand menu and select "Templates". After which you will be brought to this page.

![Alt text](https://drive.google.com/uc?export=view&id=1icL0eljlC-pxQmqkGX9CnwooHVRo-oIp "Display Templates")

### Adding New Templates

In order to upload a PDF you need to click the grey box where it says "Click to Attach a PDF". This will bring up a file prompt box like below. Locate the file location of the file we opened earlier. Click the file ending in .csv and click open in the bottom right corner of the "File Upload" window.

![Alt text](https://drive.google.com/uc?export=view&id=1uDTxeMEgZ3S1xOL12v9vyjNLA7Hbzw_n "Find Template")

When you have done this the grey box where it says "Click to Attach a PDF" will be replaced with a green box with a tick icon and the word "Attached" as can be seen below.

![Alt text](https://drive.google.com/uc?export=view&id=19Mpw5lNvVxKs8KUsby1Ydhit8fbbf02F "Upload Template")

From here you need to click the Purple upload button and wait for it to turn green and for the text to read uploaded. Once this is done you should see a PDF appear in the below list (See below image).

![Alt text](https://drive.google.com/uc?export=view&id=1jpGFAekXBIU1pi8rQ3WHv7Km3h7WXAXd "Uploaded Template")

### Deleting Old Templates

If we now wanted to delete the above added template we can do this by simply clicking the red **trash** icon and it disappears (See below).

![Alt text](https://drive.google.com/uc?export=view&id=1icL0eljlC-pxQmqkGX9CnwooHVRo-oIp "Display Templates")

## Managing Integration Data

If you wish to modify the data that is available to the application you can do it through the Integrations Section of the SAP.

![Alt text](https://drive.google.com/uc?export=view&id=1oY7_QoQbSDKLSRKwf8kUHb3AVd6cKd4U "Integration Data")

### Adding New Integration Data

On your computer, locate the file that you want to upload in your documents.

*Note: Your documents will look different from mine. Search for wherever you store your CSV files. If you downloaded it from the internet it should be in your downloads*

![Alt text](https://drive.google.com/uc?export=view&id=1ebcHEoUP_YhLGwPjcfX5e3vXQSatGuBf "Finding CSV")

Open the file in Microsoft Excel to confirm that the file has fields and columns. 

*Note: There needs to be more than 1 column for the data to be useful in Sign365. The first column may be the identifying data like an Employee ID or an email address that is unique to a specific value. The second row will be data that is a value like a persons name or an occupation. The below data does not follow this and is not unique but it is a CSV and any valid CSV can be uploaded into Sign365*

![Alt text](https://drive.google.com/uc?export=view&id=1T7jFoTsliYrztNdCehL2bBBzVWzHNPVY "Open CSV")

Now that you have confirmed the data in the CSV by opening it in Excel you can go to Integrations by clicking the left hand menu item in SAP. You should now see a page similar to below.

![Alt text](https://drive.google.com/uc?export=view&id=1KdR1Dl2MP_FYQ0B2sIEbtpXse96IInJr "Upload CSV")

In order to upload a CSV you need to click the grey box where it says "Click to Attach a CSV". This will bring up a file prompt box like below. Locate the file location of the file we opened earlier. Click the file ending in .csv and click open in the bottom right corner.

![Alt text](https://drive.google.com/uc?export=view&id=1OtuBx9Z6VQJ8P-KNsxu99oFixJjL0Dwe "Find CSV")

When you have done this the grey box where it says "Click to Attach a CSV" will be replaced with a green box with a tick icon and the word "Attached" as can be seen below. From here you will need to:

- Choose the **Identifying field** from the drop down menu. This will be what will appear as the "ID" of the Integration Tags for the iPadOS application.
- Choose the **Value field** from the drop down menu. This will be what will appear as the "Value" of the Integration Tags for the iPadOS application.

*Note: These values will vary depending on what data you are trying to import to the system. Each integration will require specific fields. In CHIP for data to be processed the data selected needs to be the user identity and the user full name*

![Alt text](https://drive.google.com/uc?export=view&id=18Uy-Sm8spzpWSiybpHh6gCbWXuT0w3Xk "Choose Field CSV")

Finally click the purple button that says "Upload" and you will see the button turn green with the text "Uploaded". This means that the text is now located on the server.

## Appendix A.

### FAQ

#### I have a new integration that I want to be tagged. How can I add this in SAP?

You can add any required integration by contacting support and having them make the integration available to you. 

#### How do I know if what I have uploaded into SAP is available to the Sign365 App?

For templates and users you will be able to see the data appear beneath the "Upload" button. This means that the data is available on the server and will soon update on the iPads themselves.

### Support

Support can be reached from within the portal by:

1. Going to the top right hand of the screen and clicking your email address
2. Selecting "Support" from the drop down list

You can also contact Biz365 during business hours (8.30 am to 5.00 pm AWST) using the following methods:

- Phone: (08) 6394 4349
- Email: samuel.wyndham@biz365.com.au

### CHIP Specific Instructions

#### Export CSV



In order to export a CSV in CHIP you need to go to CHIP.

Go File > Import / Export From > AnyTime... 

![Alt text](https://drive.google.com/uc?export=view&id=1kkTVSheHuYPBSa7muD7bMQphsBLfxjtT "chipexport")

This will bring up the below box and you need to select the label AnyTime Data Export

![Alt text](https://drive.google.com/uc?export=view&id=1NiqaS8tAi8684q5eN6Gy9dXlP5N5x-d5 "chipexport1")

This will take you to the following page (see below) with all of the checkboxes selected by default. Leave these as they are.

The default location of the "File Directory" where these items will be saved (Beneath Export Options) is the CHIP installation location. You will want to change this to something easier to find like your desktop. You can do this by clicking the three dots on the text box where it has the text \\\ServerName\\CodeHouse\\Olympus  (if you can't see the three dots hover your mouse over the text box)

![Alt text](https://drive.google.com/uc?export=view&id=1wYrS1-OHlvVVazE-u1cgZ_kH-3mCSnzQ "chipexport2")

This will bring up a box where you can select the location you want to export the files to. When you have selected the location click the "OK" button on the "Browse for Folder" window (below) and then the "Export" button with the orange icon (above).

![Alt text](https://drive.google.com/uc?export=view&id=12a_hoW2MiWqSzXe3Zg5gdRLhFIaozHeD "chipexport3")

Finally when you hit export there are a few different files produced. Go to the location you selected and search for the files. The one you want is the one that starts with "AnyTime_Hirings" and is followed by a series of numbers.

![Alt text](https://drive.google.com/uc?export=view&id=1NCVK2LKgytH8GCmfXTM_JpeIngvpmBo2 "chipexport4")

Select this file when you do the upload of the integration data.

#### Identifying and Value Fields

The correct values on the AnyTime_Users file when you upload it as a CSV through the Integrations page are

Identifying: USR_ENTITY_KEY

Value: USR_FULLNAME



