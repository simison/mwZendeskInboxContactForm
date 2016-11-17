# Zendesk Inbox Contact Form
### Mediawiki Extension

Extension adds a contact form for [Zendesk Inbox](https://www.zendesk.com/inbox/) to every page.

## Installation
Download and place the files in a directory called `ZendeskInboxContactForm` in your `extensions` folder.
Add the following code at the bottom of your `LocalSettings.php`:

```php
$wgZendeskAccount = 'YOUR_USERNAME.zendesk.com';
wfLoadExtension( 'ZendeskInboxContactForm' );
```

## License
GPL-2.0+
