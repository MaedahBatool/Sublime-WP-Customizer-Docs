# Implementing Snippets

!!! info "INFO"
    To explain how to use each of these snippets we’ve created a simple implementation of these in the form of a **WPCustomize boilerplate WordPress theme**. We recommend you to star it on **GitHub**.
    In this boilerplate, we have added all the core and advanced controls accompanied with Panels & Sections and customizer sanitization routines via `WPTRT`. 

## → Adding a Customizer Register Function

The process of creating Customizer components begin with adding a **register function**. To add a register function type `wpC` in the Sublime Text and choose `wpCustomizerRegisterFunction` from the menu shown.

![](/media/3.png)

This snippet produces the following code, which you can edit by **changing prefix** and other things — all of that by pressing the **tab** key.

```
<?php
// Customize function.
if ( ! function_exists( 'PREFIX_customize_name_panel_section' ) ) {
    // Customize Register action.
    add_action( 'customize_register', 'PREFIX_customize_name_panel_section' );
 
    /**
     * Customize: Panel.
     *
     * Customize function.
     *
     * @param  object WP_Customize  Instance of the WP_Customize_Manager class.
     * @since  1.0.0
     */
    function PREFIX_customize_name_panel_section( $wp_customize ) {
        
    }
}
```
