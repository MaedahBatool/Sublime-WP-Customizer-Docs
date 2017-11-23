## → Adding a Customizer Panel

To add a **new Panel** type `wpC` in the Sublime Text and a menu appears, choose `wpCustomizerAddPanel`.

![](/media/4.png)

Hit **Enter** and its snippet will be posted. Now just press the **tab** button to move from one editable area to another.

```
<?php
// Panel: Name.
$wp_customize->add_panel( 'prefix_panel_id', array(
    'priority'       => 160,
    'title'          => __( 'Panel Title', 'TEXT_DOMAIN' ),
    'description'    => __( 'Panle Description.', 'TEXT_DOMAIN' ),
    'capability'     => 'edit_theme_options',
    'active_callback'=> '', // is_front_page
    'theme_supports' => '',
) );
```


