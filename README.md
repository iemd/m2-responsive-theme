# Creating a Responsive Magento 2 Theme
- The main mission of creating a new theme project called BookStore is the **practical application of concepts** we’ve previously seen.
- The BookStore theme is a Magento 2 **practical theme project** that introduces the basics of a **professional approach** to theme development.

## Managing dependencies with Composer
- Magento works with Composer to generate reliable deployments of Magento components.
- Composer is a **dependency manager** for PHP.
- Great evolution in the Magento system.
- Can provide a powerful environment for modules and theme management.
- Manages the dependencies of your project and installs packages using `composer.json` file in the Magento module or theme.

## Building the BookStore theme
Magento 2 can handle different themes inside the same vendor scope.

### Clarifications about the theme’s directory structure 
- `etc`: Usually handles the **XML configuration** of some components. 
- `Magento_Theme`: Overrides the **native Magento_Theme module** by adding new functionalities.
- `media`: Stores the **preview image** of the BookStore theme.
- `web`: Handles created CSS and images files.

### Applying new CSS to the BookStore theme
- All the files with the `.less` extension that you create in your theme are compiled by the **LESS engine** which creates the processed CSS file.
- The `styles-l.css` and `styles-m.css` files are created after the processing of modules and themes LESS files.
- The BookStore theme inherits the **luma theme**, which in turn inherits the **blank theme**.
- The BookStore theme inherits all the features of these themes.

### Developing Magento 2 templates
- Magento works with `.phtml` template files to generate the **view layer** for the users.
- The `.phtml` files contain both **embedded HTML5 as well as PHP programming logic** to render all page content using Magento processing.
- The modules and themes in Magento have their **specific group** of `.phtml` files to show data to the users.

