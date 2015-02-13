# [Contact Form 7 - InfusionSoft Add-on](https://wordpress.org/plugins/contact-form-7-infusionsoft-add-on/)

Welcome to the Contact Form 7 - InfusionSoft Add-on repository on GitHub. Here you can browse the source, look at open issues, and even contribute to development.

If you are not a developer, please install this plugin on the official [Contact Form 7 - InfusionSoft Add-on plugin page](https://wordpress.org/plugins/contact-form-7-infusionsoft-add-on/) on WordPress.org.

*This plugin is not offered, sponsored, associated with or endorsed by Infusion Software, Inc.*

## Support

This repository is not suitable for support. Please don't use the issue tracker for support requests, but for core plugin development-related issues only. Support will take place in the [official plugin support forum](https://wordpress.org/support/plugin/contact-form-7-infusionsoft-add-on) on WordPress.org.

Support requests in issues on this repository will be closed immediately.

## Contributing

Community-made patches, localisations, bug reports and contributions are always welcome. When contributing please ensure you follow the guidelines below so that I can keep on top of things.

**Note:**

GitHub is for *bug reports and contributions only* - if you have a support question or a request for a customization don't post here. Use the [official plugin support forum](https://wordpress.org/support/plugin/contact-form-7-infusionsoft-add-on) for customer and community support.

### Getting Started

* Make sure you have a [GitHub account](https://github.com/signup/free)
* Submit a ticket for your issue, assuming one does not already exist.
  * Clearly describe the issue including steps to reproduce when it is a bug.
  * Make sure you fill in the earliest version that you know has the issue.

### Making Changes

* Fork the repository on GitHub.
* Make the changes to your forked repository.
  * **Try to stick to the [WordPress Coding Standards](http://make.wordpress.org/core/handbook/coding-standards/php/).**
* When committing, [reference your issue number](https://help.github.com/articles/closing-issues-via-commit-messages/) and include a note about the fix.
* Push the changes to your fork and submit a pull request on the master branch of this repository.
* Please don't modify the changelog.

At this point I'll review all pull requests, and make suggestions and changes if necessary.

## To-Do

The following items are on the development to-do list. If you feel like trying to tackle one or more of them, feel free to submit a pull request.

1. "Prettify" the contact tag input to use a similar style to the default WordPress Tags input meta box that appears on post edit screens. 
2. Add support for all [InfusionSoft contact fields](https://developer.infusionsoft.com/docs/read/Table_Documentation#Contact). 
3. Modify the JS tag generator so that input `type`s are modified, according to which contact field is selected. For example, an "infusionsoft-email" field should use `<input type="email">` rather than `<input type="text">`.
4. Limit required fields to "infusionsoft-email" and the name fields. These fields are all that are required by the InfusionSoft API to validate a contact.

## Additional Resources

* [General GitHub documentation](http://help.github.com/)
* [GitHub pull request documentation](http://help.github.com/send-pull-requests/)

*This plugin is not offered, sponsored, associated with or endorsed by Infusion Software, Inc.*
