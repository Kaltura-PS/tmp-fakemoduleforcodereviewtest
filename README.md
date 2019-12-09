# Fake module for a code review test

The task is to create a new MediaSpace module called "AwesomeMediaReport".

The module should render a standalone page with entries report and add the link to this page to the user menu.

The page name and the user menu item name should be "My Media Report".

The page should contain a table with the latest media of the user that currently logged in to the System.

The table should have the following columns:
1. "ID" - media ID.
1. "Name" - media name.
1. "Creator" - the name of the user that created the media.
   If the creator is the user that is currently viewing the page, add "(you)" label after the user name.
1. "Published In" - the list of the channels and galleries that the entry is published to.
   Each channel and gallery name should be a link to the channel/gallery view page.
   Gallery full name should be displayed when highlighting the gallery label.
1. "Likes":
   - The number of media likes.
   - An indicator of whether the media was liked by the current user. Clicking the indicator will toggle the like for the user.

The table should have pagination.

The user should be able to peek media type to display in the report - the filter should be above the table.
The options should be "Video" (pre-selected), "Audio", "Live", "Image".
