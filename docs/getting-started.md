# ▶︎ Getting Started

!!! INFO "INFO"
    To get started you need to **download** it first. You can do so from the following links:

    - [Sublime Package Control](https://packagecontrol.io/packages/WordPress%20Customizer)
    - [Read the launch post at my blog](https://ahmadawais.com/wordpress-customizer-package-sublime-text/)
    - [GitHub](https://github.com/ahmadawais/Sublime-WP-Customizer)

## Installation and Setup
You can install this package either **manually** of through **Package Control**.

### ⚙ Package Control Installation

1. Start with [Installing Package Control](https://packagecontrol.io/installation).
2. From inside the Sublime Text, open Package Control’s Command Pallet: `Command+Shift+P` on Mac and `Ctrl+Shift+P` on Windows or Linux.
3. Type **Install Package** and hit **Return** or **Enter**. A list of available packages will be displayed.
4. Type **WordPress Customizer** and hit **Return** or **Enter**. The package will be downloaded to the appropriate directory (You can watch the progress bar in the left bottom bar of Sublime).
5. **Restart** Sublime Text to complete the installation. All the features listed should now be available.

### ⚙ Manual Installation

1. **Close** Sublime Text editor.
2. **Download** or **clone** this repository to a directory named `WordPress-Customizer` in the Sublime Text Packages directory for your platform:
    - **Sublime Text 3**
        - **OS X**: git clone `https://github.com/ahmadawais/Sublime-WP-Customizer.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/WordPress-Customizer`
        - **Windows**: git clone `https://github.com/ahmadawais/Sublime-WP-Customizer.git %APPDATA%\Sublime/ Text/ 3/Packages/WordPress-Customizer`
        - **Linux**: git clone `https://github.com/ahmadawais/Sublime-WP-Customizer.git ~/.config/sublime-text-3/Packages/WordPress-Customizer`
    - **Sublime Text 2**
        - **OS X**: git clone `https://github.com/ahmadawais/Sublime-WP-Customizer.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/WordPress-Customizer`
        - **Windows**: git clone `https://github.com/ahmadawais/Sublime-WP-Customizer.git %APPDATA%\Sublime/ Text/ 2/Packages/WordPress-Customizer`
        - **Linux**: git clone `https://github.com/ahmadawais/Sublime-WP-Customizer.git ~/.config/sublime-text-2/Packages/WordPress-Customizer`
3. **Restart** Sublime Text to complete the installation. The features listed should now be available.

!!!info "TIP"
    Sublime won't **autocomplete** PHP files when there is no closing `?>` tags , so go to **Sublime Text > Preferences > Settings-User** add this snippet:

    `"auto_complete_selector": "source, text",`

