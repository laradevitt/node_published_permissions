# Node published permissions

This Drupal module provides a few new node access checks for each content type:

* Edit any published content
* Edit own published content
* Delete any published content
* Delete own published content

This module is designed to block users from editing or deleting published content where they otherwise could (as provided by other node access modules), not to allow them to edit or delete published content where they otherwise couldn't.

After enabling this module, activate these permissions for all roles where you wish to maintain status quo (no effect). Deactivate these permissions to prevent roles from editing or deleting published content.

IMPORTANT

This module has not been vetted by the community so use at your own risk!

EXAMPLES

1. User can edit own content, regardless of published status:

  Node  
  [ x ] Article: Edit own content

  Node published permissions  
  [ x ] Article: Edit own published content

2. User can only edit own unpublished content:

  Node  
  [ x ] Article: Edit own content

  Node published permissions  
  [ _ ] Article: Edit own published content
