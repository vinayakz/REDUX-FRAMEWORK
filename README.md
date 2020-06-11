# CREATE CUSTOM THEME OPTIONS PANEL FOR WP CUSTOM THEME USING REDUX FRAMEWORK

## Hi guys,
## here is the code snippete custom Theme Options Panel for wp custom theme using Redux Framework

**to integrate/include Redux Framework, add the following code to your theme’s functions.php file.**

`require_once (dirname(__FILE__) . '/redux/redux-framework.php');
if ( class_exists( 'Redux' ) ) {
    require_once (dirname(__FILE__) . '/redux/sample/barebones-config.php');
}`

### for reference of all in-built fields, you can check this file /redux/sample/sample-config.php
