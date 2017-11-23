# → Adding a Customizer Control Color

!!! tip "UPDATE"
    From here, you’ll move to different **advanced** control fields which you can add in the WP Customizer. 

Let’s create a **Color Picker**. Type `wpC` in the Sublime Text and choose `wpCustomizerAddControlColor`.

![](/media/8.png)
The WordPress Customizer snippets outputs the following code:

```
<?php
// Control: Name.
$wp_customize->add_control( new WP_Customize_Color_Control(
    $wp_customize,
    'prefix_id',
    array(
        'label'      => __( 'Color Picker!', 'TEXT_DOMAIN' ),
        'section'    => 'prefix_section_id',
        'settings'   => 'prefix_id',
    )
) );
```
