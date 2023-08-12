# Audience Creation and Management in GA4

Creating and managing your audience in GA4 (Google Analytics 4) is a crucial step toward a more tailored approach to your users. This documentation will guide you through the process.

## Pre-requisites

1. Remember, audiences are not retroactive, thus they only accumulate users once you create them.
2. To create audiences for a GA4 property, you must have the Editor role.
3. The maximum limit is 100 audiences per property.
4. Google Signals must be activated if a Google Ads campaign targets a specific audience.
5. You can create up to 20 audience triggers per property.
6. You can edit audience's name and description, but not the conditions to join an audience. In case you wish to add new conditions, you'll need to archive the existing audience and create a new one.

## Steps to Create Your First Audience

1. Go to `Admin` -> `Audiences`, select `New Audience`.
2. There are two options - you can build an audience from scratch or use suggested audiences.
3. Let's say you want to track repeat customers. Add conditions to track if the purchase event has occurred three times.
4. To further refine your audience, add another condition based on the traffic source dimension.
5. Name your audience appropriately, and click `Save`.

Remember, audiences are flexible. You can include or exclude users based on conditions, and you can set different types of condition (occurring simultaneously or not, within the same event or session, etc.).

[Previous Topic](Configuring_Events,_Conversions_and_Audiences.md) [Next Topic](Creating_Recommended_Events_in_GA4.md)
