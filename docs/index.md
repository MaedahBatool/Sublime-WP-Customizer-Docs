# 🍒 Sublime WordPress Customizer Package

Since WordPress 3.4, the [Theme Customization API](https://codex.wordpress.org/Theme_Modification_API) has emerged as an important `PHP` and `JavaScript` based API in core. It introduced developers to a standardized way of adding theme options in the **Customizer Panel** of the WordPress Dashboard.

!!! danger "PROBLEM STATEMENT"
    Last year, while working on a project, I found out that adding panels, sections, and control and setting options with the Customizer API is somewhat time-consuming — since they have so many similar options and it’s a tiring process of going back and forth with the documentation.

    It brings a lot of hassle, and I think the basic concepts of WordPress customizer should be incredibly clear.

[![Customizer object relationships and high-level API structure](/media/1.png)](https://developer.wordpress.org/themes/customize-api/customizer-objects/)

!!! success "SOLUTION"
    What if I tell you that you can **build Customizer options** for your next WordPress product (theme/plugin) under **5 minutes**? Yes, it is possible!

To save time, I’ve built a `Sublime-WP-Customizer` which is a **Sublime Package of snippets** for WordPress Customizer. It helps you add the following:

- Customizer Panels
- Customizer Sections
- Controls, and
- Settings 

All of that with standard compliant code with tab triggered snippets. Let’s take a look at the details.
