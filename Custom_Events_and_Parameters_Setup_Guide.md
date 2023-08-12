# Custom Events and Parameters Setup Guide

This Markdown guide will help you create a new custom event with form ID and form location parameters. If you're not tech-savvy, consider getting help from a developer.

## Step 1: Identifying Data for GTM

1. Open the webpage with the form, right-click and select Inspect Element.
2. Search and identify the form's code. In our example, the form ID is `wpforms‑form‑65`.
3. Confirm this ID in your WordPress plugin page.

## Step 2: Enabling Variables in GTM

1. Go to GTM -> Variables -> Configure.
2. Enable the `Form ID` form section.
    - For events like clicks, ensure those built-in variables are also enabled.

## Step 3: Creating Custom Event

1. Go to Tags -> New.
2. Name the tag (e.g. `form_signup tag`).
3. Click Tag Configuration -> GA4 event -> GA4 setup tag.
4. Add event name (e.g. `form_signup`) and parameters (`wp_form_id`, `wp_form_location`).
5. Set parameter values:
    - For `wp_form_id`, select `Form ID`.
    - For `wp_form_location`, select `Page URL`.
6. Define trigger via Triggering -> plus icon -> form_signup trigger -> Form Submission.
7. Add condition: Form ID contains `wpforms‑form‑65`.
8. Save the trigger and the tag.

After setting up the custom event, use Preview to verify the setup. Upon successful form_submit, the Tag Assistant should report the firing of the `form_signup` tag. Finally, submit and publish the changes in GTM.

## Step 4: Adding Custom Event to GA4 Property

1. Go to Admin -> Events -> Create event -> form_signup.
2. Check `Copy parameters from the source event`.
3. Add new conversion event with the same name as your custom event.

## Step 5: Adding Custom Parameters to GA4

For each custom parameter created, go to Custom definitions -> Create custom dimension:

-   For `wp_form_id`:

    -   Name: `WP Form ID`.
    -   Scope: Event.
    -   Description: `Form ID for WP forms`.
    -   Event parameter: `wp_form_id`.

-   For `wp_form_location`:
    -   Name: `WP Form Location`.
    -   Scope: Event.
    -   Description: `Form Location for WP forms`.
    -   Event parameter: `wp_form_location`.

Upon completion, the custom dimensions will be available in your reports after 24 to 48 hours.

## Final Step: Testing

Confirm your setup by checking the DebugView in your GA4 property for the new custom event along with the custom parameters.

[Previous Topic](Creating_Recommended_Events_in_GA4.md) [Next Topic](Note.md)
