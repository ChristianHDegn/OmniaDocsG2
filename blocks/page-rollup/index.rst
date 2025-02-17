Page Rollup
===========================================

This block can be used for many purposes, for example to rollup new news, latest news and similar - and for much more regarding pages, not just for news. The Page Rollup is, for example, an important part of a Newsletter implementation, and for an Event Management implementation.

Settings
*********
These settings are available for the block:

.. image:: page-rollup-settings-new4.png

General
--------
Here you can add a title for block:

.. image:: page-rollup-settings-general-frame.png

If any variations exist, as in the example above, titles in other languages are handled through variations. If no variations exist you can add titles in any or all languages in the tenant.

Query
------
Here you can set the following:

.. image:: page-rollup-settings-query-new4.png

+ **Pick Pages**: If the editor should be able to pick pages from a list, select this option.
+ **Pick in Write Mode**: Available when Pick Pages is selected. Select this option if editors should be able to pick pages in Write mode. If not selected, Design mode has to be used.
+ **ADD PAGE**: When you have selected Pick Pages, you can pick some pages to always be shown. Click this option and use the Page Picker. See this page for more information: :doc:`Page Picker </general-assets/page-picker/index>`
+ **Use Query Builder**: If you want to use the query builder to set which pages should be available here, select this option.
+ **Scope**: When you have chosen to use the Query Builder, select scope for the block; Publishing Apps, Page Collections or Navigation path. In Omnia 6.7 it will also be possible to select Channels as Scope. Then open the list below and select Publishing Apps/Page Collections. Regarding Navigation path, use it to select a node to get the pages from. When you have selected start node you can choose navigation depth. There's also a view available, specifically for Navigation Path - Navigation View. Select it under Display.
+ **Current User Subscription**: Available for Scope Channels. Select this if only the pages that the logged in users subscribes to should be displayed.
+ **Custom Query**: Available for Scope Channels. Use this to select one or more channels to rollup pages from. Note that a channel can be targeted to just certain colleagues or groups. See example below.
+ **Exclude current page**: Available when you have chosen scope for the Query Builder. The default setting is to exclude the current page, but if you, for some reason, would like to include the current page, uncheck this option.
+ **Trim duplicates**: Available for the Query Builder. If more than one Page Rollup block is added to a page, this option can be used to handle duplicates between the blocks. When the option is selected, you can enter a number indicating the priority for duplicates, for this block. If you set "1" for a block it means this block has priority showing a post that would have been a duplicate. 
+ **Query Item Limit**: Available for the Query Builder. Use the slider, or type the number (1-99) to set the number of pages that should be retrieved to make sure all duplicates are found. You should not set this number higher than you really need, as higher numbers may have an impact on performance. Note that when you change the number, "Max Display Limit" is also changed, see below.
+ **Page Size**: Available for Query Builder. Use the slider, or type the number (1-99) to set the number of items (pages) that should be displayed on each "page" of the list. Also see under *Display* below for additional settings for the list. 
+ **Cache on client**: This setting can be used to speed up rendering on subsequent page loads. This is is done by storing data in the browser cache. Default: selected.

When you have selected "Publishing Apps" or "Page Collections" as Scope, use the list to add one or more:

.. image:: page-rollup-query-list-new2.png

For every Publishing App or Page Collection you have selected, you can filter (meaning displaying just some of the pages) by expanding and selecting "Add filter".

.. image:: page-rollup-query-addfilter-new2.png

Here's an example of a filter that will display pages that have been updated (Modified) the last month:

.. image:: page-rollup-query-filter-example-new2.png

Here's an example of a custom query for channels (available in Omnia 6.7):

.. image:: page-rollup-channel-example.png

Filter on a specific variation
--------------------------------
If just pages with a certain variation (language or other variation) should be listed in the rollup, it can be done this way:

(Only News in Swedish will be listed in this example.)

.. image:: page-rollup-variation-example-new.png

Display
----------
Select View here. Note that a preview is shown in the block.

.. image:: page-rollup-settings-display-new.png

The following lists all available display settings, shown in different order for different displays, here listed in alphabetical order.  

+ **Autoplay**: If the roller should roll automatically, select this option. Available for "Dynamic Roller" only.
+ **Cards per Row**: Available for Card only. As it says, set the number of cards to show per row.
+ **Contact**: Select the property to be displayed as Contact. Available for Newsletter only.
+ **Content**: Select the property that contains the page content for the item to display. Available for Newsletter only.
+ **Content Image**: Select image to display, if any. Available for dialog display only.
+ **Create button for page collection**: When you have selected "Show create button", this optipon is shown. Use it to select in which page collection the new page will be created.
+ **Date**: Select the property that contains the date for the item(s) to display.
+ **Delay between slides**: Set the time between slides in milli seconds.
+ **Hide block when no data**: Select this option if the block should be hidden when there's nothing to display.
+ **Hide if read**: Select this option to hide all pages the logged in user has visited. This affects all pages, including news.
+ **Highlight non-read**: This option makes sure non-read pages are highlighted. Default=selected. Deselect if you don't want that.
+ **Image**: Select the property that contains the image for the item(s) to display.
+ **Image Ratio**: Select ratio for the image; Landscape, Square or Wide. 
+ **Image x and y**: Select the image format here. Available for "Single Item" only.
+ **Max Display Limit**: To limit the number of items being displayed, add a fixed number here. Note that if combined with "No paging", the number of items you enter here are the only items users can access from the list. Also note that if you change this value, the "Query Item Limit" is also changed, see above.
+ **Link label**: Add the text to be shown for the link here. Available only if "Show link" is selected.
+ **Link url**: Add the url to open when a user clicks the link. Available only if "Show link" is selected.
+ **Loop**: Available for Dynamic Roller. Normally a roller stops when the last post is reached (and can restart after a short while). When this option is selected, there is no "end" and the roller just keeps rolling. Important note: When Loop is selected the arrows users can use to roll "manually" are not shown.
+ **No result text**: Enter the text that will be shown if no page can be displayed.
+ **Number of slides to display**: Select number of slides, 1-12. Available for "Dynamic Roller" only.
+ **Open link in new tab**: If the link should be opened in a new tab (as opposed to in current window or dialog), select this option. Available only if "Show link" is selected.
+ **Open page as a dialog**: If the page should be opened in a dialog instead for in a page (new or current), select this option. 
+ **Overlay**: If an overlay text should be shown on the image(s), add the text here. Available for "Roller" only.
+ **Padding**: Add some padding between the list and the block border, if needed.
+ **Page Content Character Limit**: If the number of characters displayed for Page Content should be limited, add the number here. The Content is simply jus cut after that. Available for Newsletter only.
+ **Page Summary Character Limit**: If the number of characters displayed for Page Summary should be limited, add the number here. The Summary is simply jus cut after that. Available for Newsletter only.
+ **Paging**: Select paging here; "No paging", "Classic" or "Scroll".
+ **Person**: This option can be used to show properties in Card view.
+ **Show create button**: To make it possible for editors to create a new page from here, select this option to add a button to the block heading, and type the name for the button. 
+ **Show Default image**: If there is no image available for a page, a placeholder image can be used. If that image should be used, select this option.
+ **Show Likes/Comments**: If the number of likes and comments should be displayed for the item, select this option. 
+ **Show link**: You can add a link button at the bottom of the list. The first page collection is default, but you can link to any target.
+ **Show Navigation**: If navigation icons for the users to use for rolling should be shown, select this option. Available for "Dynamic Roller" only.
+ **Show Paging**: Available for "Dynamic Roller" only. Small icons shown that users can use to page back and fort. See image below for an example.
+ **Show Rating**: If the rating for the page(s) displayed should be shown, select this option. Available for "Listing With Image" only.
+ **Slider Type**: Select Horisontal slider or Vertical slider. Available for "Dynamic Roller" only.
+ **Slider Size**: Select the size of the slider here: Small, Medium, Large or Extra large. Available for "Dynamic Roller" only.
+ **Sort by**: Choose what the list should be sorted by, and then select ascending or descending.
+ **Summary**: Select the property that contains the page summary for the item to display.
+ **Term properties**: Can be used to show properties in Card view. Click "Add" and select a property. Continue the same way for additional properties.
+ **Title**: If a title should be shown for the block, add it in this field. If no variation exists for the page, you can set the title in the languages active in the tenant. If variations exists, only one title can be set. In that case, titles in other languages are set in the variations.

**Note!** For "List View" and "Event List", you also have to add at least one column, for the display to work. Here's an example with three columns added for List View:

.. image:: list-view-columns-new3.png

This could show the following:

.. image:: list-view-example-new.png

"a month ago" etc is the "Social" setting for date. If you would like to show exact dates instead, select "Normal".

"Show paging" in settings for "Dynamic Roller" makes these icons available for navigation:

.. image:: show-paging-dynamic-new.png

Here's a simple example of a Card view used for navigation purposes:

.. image:: card-view-example-pages.png

Card view can now display sub pages if the scope "Navigation path" is used. Here's an example:

.. image:: card-view-example-sub-pages.png

The card view also supports a dynamic number of properties that can be displayed in the card. Here's an example:

.. image:: pagerollup-cardview-terms.png

The Navigation View can be used to display a mega menu style navigation. Here's an example of Page Rollup used for this purpose:

.. image:: navigation-view-mega-example.png

Style settings
----------------
For Roller, Dynamic Roller and Card, extra Style settings are available, for example (Card):

.. image:: page-roller-style.png

Just try out these settings. A preview is shown in the block.

Filter
-------
If users should be able to filter the list and/or search here, use these options to add filters. 

The following options are specific for the Page Rollup block:

.. image:: page-rollup-filter-65.png

+ **Save filter state**: If you select this option the filter keeps it's state in the page url as long as the page is active, and will be activated when the user goes back to the page, by using the browser's Back button. The url can also be copied and for example be used to prepopulate the page rollup.

The rest of the options are the same as other blocks. See this page for information on how to use these options: :doc:`Filter UI </blocks/general-block-settings/filters/index>`

Social Period
--------------
Use these settings to decide for how long likes, comments, ratings and page feedback should be displayed here. The default setting is "No limit" but you can select one week, two weeks or one month instead.

.. image:: page-rollup-settings-social-new2.png

Layout and Write
**********************
The WRITE tab is not used here. The Layout tab contains general settings, see: :doc:`General Block Settings </blocks/general-block-settings/index>`

Page Rollup implementations
****************************
In this a number of examples of how the Page Rollup could be implemented are described.

News Archive/News Center
--------------------------
The purpose of a News Center is to display ALL published news for the users to read. Normally a News Editor can create and edit news artcicles from there.

Here's an example of how the user interface can look:

.. image:: page-rollup-example-news-center-new.png

(The "Create News Article" button is shown only for those that has the permission to create News.)

The Page Rollup can be set up the following way:

+ Query: Scope - Page Collections, News (the Page Collection with the name "News").
+ The option "Exclude current page" can be a good idea to have selected. 
+ The option "Enable partial word search" is also useful in this case.
+ Social Period: All default.

.. image:: news-archive-example-1new.png

+ Display: Depends on how you want it to look. In the above example, these settings are used:

.. image:: news-archive-example-1new-display.png

and these:

.. image:: news-archive-example-2new.png

and finally, these:

.. image:: news-archive-example-3new.png

Note the "Show create button" option, the label for that button and the option to set in which Page Collection these pages are created (in this case "News", the Page Collection selected under "Query").

+ Filters: A search box is always a good idea in a News Center. The users should most likely also be able to filter the list on one or more properties, for example:

.. image:: news-archive-filters-new.png

+ Page Variations: None. (If Page variations will be used, for example for different languages, it will be used on the pages. Or a separate News Center could be set up for News in other languages, or for any other purpose, for that matter.)

Latest News
-------------
The purpose of this Page Rollup is as it says - to display a number of the latest News.

It can look like this for users:

.. image:: page-rollup-latest-news-example-new.png

For this purpose the Page Rollup block can be set up like this:

+ Query: Scope - Page Collections, News.
+ The option "Exclude current page" can be a good idea to have selected. 
+ The option "Enable partial word search" is also useful in this case.
+ Social Period: All default.
+ Display: Depends on how you want it to look, of course. In the above example, these settings are used:

.. image:: latest-news-example-1new.png

and these:

.. image:: latest-news-example-2new.png

+ Filters: none.
+ Page Variations: Default Variations.

Most Commented News
----------------------
The purpose of this Page Rollup is as it says - to display a number of the most commented News.

It can look like this for users:

.. image:: page-rollup-example-most-commented-news.png

For this purpose the Page Rollup block can be set up like this:

+ Query: Scope - Page Collections, News.
+ If this block is placed in the Page Type for News, "Exclude current page" can be a good idea to have selected. 
+ Social Period - Comment: If you don't want old comments to affect the list, select a social period.
+ Display: Depends on how you want it to look. In the above example, these settings are used:

.. image:: most-commented-example-1new.png

and these:

.. image:: most-commented-example-2-new.png

+ Filters: none.
+ Page Variations: User variation.

Most Liked News
-----------------
The purpose of this Page Rollup is as it says - to display a number of the most liked News.

It can look like this for users:

.. image:: page-rollup-most-liked-news-example.png

For this purpose the Page Rollup block can be set up like this:

+ Query: Scope - Page Collections, News.
+ If this block is placed in the Page Type for News, "Exclude current page" can be a good idea to have selected. 
+ Social Period - Like: If you don't want old likes to affect the list, select a social period.
+ Display: Depends on how you want it to look. In the above example, these settings are used:

.. image:: most-liked-example-1new.png

and these:

.. image:: most-liked-example-2new.png

+ Filters: none.
+ Page Variations: User variation.

News - Dynamic Roller
------------------------
When a Dynamic Roller display is used for news, it can look like this:

.. image:: dynamic-roller-example-new.png

In this example the Page Rollup block is set up this way:

+ Query: Scope - Page Collections, News.
+ If this block is placed in the Page Type for News, "Exclude current page" can be a good idea to have selected. 
+ Social Period - Like: If you don't want old likes to affect the list, select a social period.
+ Display: Depends on how you want it to look. In the above example, these settings are used:

.. image:: dynamic-roller-example-1new.png

and these:

.. image:: dynamic-roller-example-2new.png

and, finally, these:

.. image:: dynamic-roller-example-3new.png

(Padding is set to 0, not shown in the image above.)

+ Filters: none.
+ Page Variations: User variation.
