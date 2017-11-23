# → Adding a Customizer Basic Control

To add a **new Basic Control** field type `wpC` in the Sublime Text and choose `wpCustomizerAddControlBasic`.

![](/media/7.png)

The snippet has the following lines of code.

```
<?php
// Control: Name.
$wp_customize->add_control( 'prefix_id', array(
    'label'       => __( 'Label', 'TEXT_DOMAIN' ),
    'description' => __( 'Description', 'TEXT_DOMAIN' ),
    'section'     => 'prefix_section_id',
    'type'        => 'text', // text (default | variations email/url/number/hidden/date), textarea, checkbox, radio/select (requires choices array below), dropdown-pages
    'choices'  => array(
        'enable'  => 'Enable',
        'disable' => 'Disable',
    ),
    'settings'    => 'prefix_id',
    'active_callback' => 'is_front_page',
) );
```
