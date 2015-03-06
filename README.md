# drupal_cloudfront_signedurl
Simple Drupal 7.x module for Cloudfront signed urls.

This module add a Drupal field type for Amazon Cloudfront that you can render as a normal href link or just with a raw url for templating using.

If you want to use the raw url into a template, you can follow this syntax:

```
<video>
  <source src="<?php print $content['field_phone_number'][0]['#markup'];?>" type="video/mp4">
</video>
```

You can set the keypair id and the private key in the module settings.
