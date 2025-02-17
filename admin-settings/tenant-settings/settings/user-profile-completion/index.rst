User Profile Completion
==================================

This is the settings for the user option "Strengthen Profile", that can found inte the Action Menu:

.. image:: strengthen-profile-new2.png

and for the Profile Completion block, that can look like this:

.. image:: profile-completion-example.png

Another option is to set that a dialog should appear with certain intervals, see below.

The settings
**************

The following settings are available:

General
--------
Here you can set these settings:

.. image:: user-profile-general-new.png

(All options are not shown in the image.)

+ **Show Dialog**: Decide how often the Dialog should be shown for a user. First set "Daily", "Weekly" or "Monthly" and then set details if needed. The dialog appears on all Omnia pages when a user starts the intranet and remains open until the users closes the dialog.
+ **Start date**: Click in the field and use the calendar to select start date for the Dialog's first appearance.
+ **No end date/End by**: Select when the Dialog should no more be shown; never ("No end date") or click in the "End by" field and use the calendar to set a date.
+ **Title**: Use this field to enter a Title for the Dialog. Click the list icon to add Titles for all available languages. See example below.
+ **Description**: Enter a description, or rather information about what the user should do, in this field. Click the list icon to add Descriptions for all available languages. See example below.
+ **Feeback email**: Add the email address that feedback from User profile Completion should be sent to.
+ **Levels**: Use these color settings to set what color to display for different levels pf completion. 

.. image:: user-profile-general-example-new.png

Property mappings
------------------
Use these settings to map user input to certain Properties.

.. image:: user-profile-property-new2.png

To edit a property mapping, click the heading. The same settings as for a new profile property can be used, see below. To delete a profile property, click the dust bin.

Heres an example of a property mapping:

.. image:: property-mapping-1-new.png

Create a new property mapping
------------------------------
Here's how to create a new property mapping:

1. Click Add Section.

.. image:: click-add-section-new.png

2. Add names and descriptions in one or more of the available languages (default language is mandatory).
3. Click Add Mapping.

.. image:: click-add-mapping-new.png

Use the following settings:

.. image:: mapping-settings-new.png

(Different options are shown depending on Type selected.)

+ **Type**: Open the list and select type of property.
+ **Label**: Add a lable for the property.
+ **Property**: Select Property in the list. Available for alla types except Profile Picture.
+ **Completeness Impact**: Select the impact of completeness status: None, High, Medium or Low. Think how important it is that this property is filled in by the user.
+ **Multiple**: Available for the type Term Set only. Check the box to make it possible for the user to select more than one term for the property.
+ **Read-Only**: Select this option for properties that should be shown to the user, but can't be edited by the user. 
+ **Allow feedback**: To make it possible for users to send feedback for this property, check the box.

**Tip!** If you allow feedback for a Read-Only property, the user can still send feedback about the information shown in the field.

Mapping Profile Images
-------------------------------------------------
If profile images are managed in another system (or in the SharePoint My Site, which is likely the case in an on-prem installation), you can use these options to map to that system, this way:

1. Create a Profile Image mapping, and then select "Add Mapping".
2. Select "Sharepoint User Profile".
3. Select "Profile Picture" for "Type".
4. Select "Custom target".

.. image:: profile-image-mapping.png

5. Add the Custom Target Url.

.. image:: profile-image-mapping-target.png

6. Add additional settings as needed.
7. Click OK.


