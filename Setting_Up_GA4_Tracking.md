# Setting Up GA4 Tracking

To begin with GA4 tracking setup, follow these steps:

## Step 1: Account and Property Setup

1. Visit [google.com/analytics](https://www.google.com/analytics)
2. Click on Admin
3. Click on Create Account
4. Fill in the account information
5. Read and accept Terms of Service
6. Click Next, and create a property name
7. Hit Next and fill in the relevant business information
8. Select the platform (Web or App) you're setting up tracking on

Our tip is to keep the Account and Property names same for small projects, while for bigger projects, consider including geographical information or the target audience.

## Step 2: Data Streams and Code Snippet

1. Add your site and data stream name
2. Ensure your stream name is more specific (adding “web” or “site” next to it is recommended)
3. Enabled Enhanced Measurement
4. Click Create Stream
5. Copy the snippet of code provided

This code snippet must be added to every page of your website.

## Step 3: Inserting the Code Snippet

This step varies based on the type of website:

1. On basic HTML sites, paste the code on all pages after the `<head>` element and upload them via FTP.
2. For WordPress sites, use a plugin (like Header Footer Code Manager). Install the plugin, activate it, select JavaScript, paste your code, and save.
3. For other templates or themes, look for a predefined field in the theme options or consult the theme documentation.

## Step 4: Use Google Tag Manager

Google Tag Manager (GTM) provides a more professional and centralized way for setting up GA4. You can create a GTM account, just like GA4, and utilize it to manage all your tags in one place. This method significantly reduces the complexities involved with traditional tracking setup methods.

The upcoming sections will guide you more on the Google Tag Manager and GA4 account structure.

Remember, all these steps help you gather valuable user journey data while respecting user's privacy by not tracking PII. This data can inform your marketing decisions and lead to more effective ad budget allocation.

[Previous Topic](User_Interaction,_Event_Tracking,_and_Session_Data_in_GA4.md) [Next Topic](Google_Tag_Manager_and_Google_Analytics_4_Integration_Guide.md)
