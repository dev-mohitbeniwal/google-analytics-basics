# Google Tag Manager and Google Analytics 4 Integration Guide

This guide will help you understand the steps to integrate Google Tag Manager (GTM) with Google Analytics 4 (GA4), and check if our GA4 configuration is working perfectly.

## Step 1: Creating Google Tag Manager Account and Adding Tag

1. Visit [Google Tag Manager](https://tagmanager.google.com).
2. Create an account and a container for placing your tags.
3. Instead of pasting your GA4 snippet in your website header, paste the Google Tag Manager code.

## Step 2: Adding GA4 Configuration to GTM

1. Go to your GTM account and click **Add tag**.
2. Select 'GA4 Configuration' from the available options.
3. Find your measurement ID in your GA4 account (Admin > Data Streams > select relevant data stream) and copy the ID.
4. Paste it into the GTM tag configuration.

## Step 3: Choosing Tag Triggers

1. Choose 'All Pages' as a trigger for this tag as we want the code to work for all pages.
2. Test using the 'Preview' option before making changes public.
3. Once you confirm the tag is working correctly through the 'Tag Assistant', click 'Submit' to make changes public in GTM.

[Previous Topic](Setting_Up_GA4_Tracking.md) [Next Topic](Understanding_Reports.md)
