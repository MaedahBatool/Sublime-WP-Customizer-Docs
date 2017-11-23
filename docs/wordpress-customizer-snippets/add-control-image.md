# → Adding a Customizer Control Image

Let’s create an **image field** with this package. Type `wpC` in the Sublime Text and choose `wpCustomizerAddControlImage`.

![](/media/9.png)

The code snippet goes like this:

```
<?php
// Control: Name.
$wp_customize->add_control( new WP_Customize_Image_Control(
    $wp_customize,
    'prefix_id',
    array(
        'label'      => __( 'Upload an image', 'TEXT_DOMAIN' ),
        'section'    => 'prefix_section_id',
        'settings'   => 'prefix_id',
        'context'    => 'your_setting_context'
    )
) );
```
