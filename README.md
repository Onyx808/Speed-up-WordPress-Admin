# Speed-up-WordPress-Admin
Speeds up WordPress admin pages

### Add the following code to the functions.php file of the activated theme.

```php
/*-----------------------------------------------------------------------------------*/
/* remove slow wordpress stuff
/*-----------------------------------------------------------------------------------*/

add_filter( 'postmeta_form_keys', function() { return array(); });
add_filter( 'media_library_months_with_files', function() { return array(); });
add_filter( 'media_library_show_audio_playlist', function() { return false; });
add_filter( 'media_library_show_video_playlist', function() { return false; });
```
