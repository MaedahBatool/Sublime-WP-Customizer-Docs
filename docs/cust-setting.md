# → Adding a Customizer Setting

To add a **new Setting** type `wpC` in the Sublime Text and choose `wpCustomizerAddSetting`. Note that you’ll add **Setting** before **Control** options.

![](/media/6.png)

Hit **Enter** and the code snippet appears like:

```
<?php
// Setting: Name.
$wp_customize->add_setting( 'prefix_id', array(
    'type'                 => 'theme_modoption',
    'default'              => 'default',
    'transport'            => 'refreshpostMessage', // Options: refresh or postMessage.
    'capability'           => 'edit_theme_options',
    'sanitize_callback'    => '', // esc_attr, esc_textarea, absint, esc_url_raw, sanitize_hex_color, wp_strip_all_tags, wp_filter_nohtml_kses 
    'sanitize_js_callback' => '', // Basically to_json.
    'theme_supports'        => '', // Optional. This can be used to hide a setting if the theme lacks support for a specific feature (using add_theme_support).
) );
```

!!! warning "REMEMBER" 
    Remember to add the setting before you add a control. Since a control needs to be attached to a setting which should be defined before the control definition.
