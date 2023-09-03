# Drupal Third Party Settings Example Module

This is an example module to show how to use third party settings to augment
Drupal configuration entities.

The example here will add a text field to the "article" node content type that
will inject additional content into your  article content. This assumes that
you have installed a Drupal site using the standard install profile. Without
this content type present the module will do nothing.

The module will work with Drupal 9 and 10.

Please note that this module is only for educational purposes and provides
minimal practical application. Feel free to use this code for your own purposes.

## Usage
- Download this module from GitHub and place it in your `/modules/custom` directory.
- Install the module in the usual way.
- Go to the Article node content type edit page at `/admin/structure/types/manage/article`.
- At the bottom of the form you will see a fieldset containing a field called "Example Text Field".
- Add some text to this field and save the form.
- Go to an article content page. The text you saved to the form will be seen on the page.
- When you export the configuration of the site the text you entered will be present in the article configuration.

## Find Out More
For more information about this module please see [Drupal 10: Adding Third Party Settings To Drupal Configuration Entities](https://www.hashbangcode.com/article/drupal-10-adding-third-party-settings-drupal-configuration-entities).
