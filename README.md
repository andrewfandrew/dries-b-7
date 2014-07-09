dries-b-7
=========

Drupal 7 sites folder and custom modules

The custom modules are contained in the /sites/all/modules/custom folder
You will find the 'safeword' module which works with the Field API
and creates a custom field with a machine name. This means it can be
added to content types by an administrator with sufficient permissions using the
admin menus ie without needing to touch the site code.

INSTALLATION

If you want to try out the modules in the repo:

- The whole site tree is included for convenience
- If you want to import the modules into your site you will need to clone
- the site folder and then extract the modules. You can then delete the rest
- of the site tree. You would then place the module(s) in your own
- sites/all/modules folder.
-
- I am using Netbeans. You can delete the
- Netbeans folder inside the sites folder since it is not needed in a
- drupal installation.