# Documentation

## Funnel Configuration

When setting parameters, we select the desired one, for instance, 'page title'. We can request a specific category by looking for 'kid' and selecting it, then clicking 'Apply'.

On the side, we see the audience has shrunk as we picked a specific category. To discard any parameter, simply click the 'X' adjacent to it.

## Steps in the Funnel

1. After a user sees a category page, we want them to view a specific item. Therefore, our next step in the funnel should be 'View Product'. We change the event condition to 'view_item'.
2. For the third step, we want the user to add the desired item to their shopping cart. We change the third step name to 'Add to Cart' and put the event 'add_to_cart'.
3. In the final step, we want the user to make the purchase.

We can add time restrictions, more steps or even adjust their order. After setting the funnel, we click 'Apply'.

**Note:** Neural funnels allow us to track where we are losing customers, analyze the data and make the necessary changes. The funnel works as an instant review tool, showing us the effects of changes we make.

## Path Explorations

Path explorations have diverse applications; they enable us to observe how users are interacting with our website and trace any potential loops.

To access it, go to the 'Template gallery' from the 'Explore menu', choose 'Path exploration'.

**Note:** Unlike steps in funnel, we cannot change node types in path exploration.

With the 'unique node feature', we can remove the non-unique nodes in the flow of events, making our explorations neater.

We can segment data into focused subsets by adding dimensions pertinent to our investigation using 'country' dimensions as an example.

This feature allows us to begin from a starting or ending point with our analysis, allowing us to work backward from any event and identify sources.

**Example Analysis:** For diagnosing errors, say you've set an error event to recognize the occurrence of various errors like broken links. Open your path exploration, select the 'ending point', 'event name', and search for 'errors'. You can then trace back the source of these errors by navigating through the nodes and sharing the information with the development team for resolution.

Another common use of path exploration is understanding the user journey when they visit our site. We select the 'starting point' as 'Home' to understand how users navigate after landing on the home page. Further exploration can bring insights into user behaviors and interactions with your site.

[Previous Topic](<Google_Analytics_4_(GA4)_Documentation.md>) [Next Topic](Path_Explorations.md)
