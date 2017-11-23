# → Adding a Customizer Control Upload

To add a **file uploader** field in your Customizer type `wpC` in the Sublime Text and choose the option for `wpCustomizerAddControlUpload`.

![](/media/10.png)

The WordPress Customizer snippets outputs the following code:

```
<?php
// Control: Name.
$wp_customize->add_control( new WP_Customize_Upload_Control(
    $wp_customize,
    'prefix_id',
    array(
        'label'      => __( 'Upload!', 'TEXT_DOMAIN' ),
        'section'    => 'prefix_section_id',
        'settings'   => 'prefix_id',
    )
) );

```
