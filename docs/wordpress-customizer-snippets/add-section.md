# → Adding a Customizer Section

To add a **new Section** type `wpC` in the Sublime Text and choose `wpCustomizerAddSection`.

![](/media/5.png)

The snippet appears like this:

```
<?php
// Section: Name.
$wp_customize->add_section( 'prefix_section_id', array(
    'priority'       => 160,
    'panel'          => 'prefix_panel_id',
    'title'          => __( 'Section Title', 'TEXT_DOMAIN' ),
    'description'    => __( 'Section Description.', 'TEXT_DOMAIN' ),
    'capability'     => 'edit_theme_options',
    'active_callback'=> '', // is_front_page
    'theme_supports' => '',
) );
```

Again you can edit its contents by pressing the **tab** button.
