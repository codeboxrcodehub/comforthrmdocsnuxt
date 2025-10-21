---
title: "Comfort Job Application User Guide"
description: "Complete user guide for Comfort Job application. Learn general features, navigation, and basic setup to get started with the job board application effectively."

ogType: "article"
ogTitle: "Comfort Job Application User Guide"
ogDescription: "Complete user guide for Comfort Job application. Learn general features, navigation, and basic setup to get started with the job board application effectively."
ogSiteName: "Comfort HRM Documentation"
ogImage: "/comfort-job-application-plugin-for-wordpress.webp"
ogUrl: "https://docs.comforthrm.com/comfortjobapp/user-guide/general"

twitterCard: "article"
twitterTitle: "Comfort Job Application User Guide"
twitterDescription: "Complete user guide for Comfort Job application. Learn general features, navigation, and basic setup to get started with the job board application effectively."
twitterSite: "@ComfortHRM"
twitterImage: "/comfort-job-application-plugin-for-wordpress.webp"
twitterUrl: "https://docs.comforthrm.com/comfortjobapp/user-guide/general"

fbAppId: "1249182889483061"
keywords: "Comfort Job application guide, application overview, getting started, user manual, application features, general settings, application navigation, user interface, dashboard overview, application basics"
---

# Comfort Job Application User Guide

ComfortJobApp simplifies the job application process for candidates and recruiters. Manage applications efficiently with this plugin.

## File Structure

```
resume/
├── assets/
│   ├── css/
│   ├── js/
│   ├── vendors/
├── includes/
│   ├── Api/
│   ├── Controllers/
│   ├── Helpers/
│   ├── Models/
│   ├── ComfortJobApp.php
│   ├── ComfortJobAppAdmin.php
│   ├── ComfortJobAppHooks.php
│   ├── ComfortJobAppPublic.php
│   └── ComfortJobAppUninstall.php
├── templates/
│   ├── admin/
│   ├── emails/
│   ├── form-fields/
├── comfortjobapp.php
└── readme.txt
```
## Key Files and Directories

- **assets/**: Contains CSS, JavaScript, and vendor files.
- **includes/**: Contains core PHP files for the plugin, including API routes, controllers, helpers, models, and main plugin classes.
- **templates/**: Contains template files for the plugin's frontend and admin views.
- **comfortjobapp.php**: The main plugin file that initializes the plugin.

### ComfortJobApp

The main class for the plugin, located in `wp-content/plugins/comfortjobapp/includes/ComfortJobApp.php`.

```php
class ComfortJobApp {
    public static function instance() {
        // Returns the main instance of ComfortJobApp.
    }

    public function __construct() {
        // Constructor method.
    }

    private function include_files() {
        // Includes necessary files.
    }
}
```
### ComfortJobAppAdmin
Handles the admin functionalities of the plugin, located in `ComfortJobAppAdmin.php`.

```
<?php
class ComfortJobAppAdmin {
    public function create_menus() {
        // Creates admin menus.
    }

    public function display_resume_listing_page() {
        // Displays the resume listing page.
    }
}
```
### ComfortJobAppPublic
Handles the public-facing functionalities of the plugin, located in `ComfortJobAppPublic.php`.

```
<?php
class ComfortJobAppPublic {
    public function enqueue_scripts() {
        // Enqueues public scripts and styles.
    }
}
```

## Uninstallation

The uninstallation script is located in ComfortJobAppUninstall.php.

```
<?php
ComfortJobAppUninstall::uninstall();
```