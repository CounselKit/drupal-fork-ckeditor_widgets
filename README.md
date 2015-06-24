Angular Media
=============

Rethinking the media dialog interface with the help of Angular.

###Highlights
* A better user interface for selecting and editing files in Drupal
* Easy multi-upload built-in to every selection method
* Search for and easily add creative commons photos with proper attribution

###Installation
* Install the module dependencies (file_entity, media, views, features, views_data_export_json).
* Install the module in Drupal
* Add a new File field and select the Angular Media Browser widget

###CKEditor configuration steps
In order to get the CKEditor integration to work, follow these steps:
1. In CKEditor profile, under Editor Apperance, check Plugin for Angular Media Browser and add the insert image button.
2. In CKEditor profile, under File Browser Settings, change File browser type to "CKFinder".
3. In global CKEditor settings(`/admin/config/content/ckeditor/editg`), in Local path to CKFinder, enter any valid url (we use "modules" in Helm).
4. On permissions (`admin/people/permissions`), give the appropriate role access to CKFinder access.

###Status
This module is currently in a MVP state and should not be used on production websites.  It is under active development and many features and improvements will be added in the coming weeks. If you are interested in helping, please post a note in the issue queue.

###Roadmap
* Make the Angular Media field work when there are multiple instances on one edit page
* Remove the media dependency
* Make the Angular Media field work when the form is loaded via the Drupal AJAX api (ctools modals)


###Who?
Conception and development to this point has been done by <a href="http://albatrossdigital.com">Albatross Digital</a>. We believe that every website should look beautiful, and having a user-friendly media experience is paramount to that vision.