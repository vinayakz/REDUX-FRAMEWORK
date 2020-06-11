# CREATE CUSTOM META-BOX FOR WP POSTS AND PAGES USING CMB2

## Hi guys,
## here is the code snippete to integrate/include CMB2 library and custom-meta-box fields

**to integrate/include CMB2 library and custom-meta-box fields, add the following code to your theme’s functions.php file.**

`action( 'init', 'be_initialize_cmb_meta_boxes', 9999 );
function be_initialize_cmb_meta_boxes() {
    if ( !class_exists( 'cmb_Meta_Box' ) ) {
        require_once( get_template_directory() ."/customs/CMB2/init.php" );
    }
}
require ( get_template_directory() . "/customs/CMB2/metaboxes.php");`

**in the file /customs/CMB2/metaboxes.php**
**on line 480, there is custom post’s sample meta-box**
**on line 500, there is custom page-template’s sample meta-box**

## for reference of meta-fields, you can check this file /customs/CMB2/example-functions.php

# Thank you,
