---
title: "Comfort Job Application Template Override"
description: "Learn how to override and customize Comfort Job application templates. Complete guide to modifying UI layouts, creating custom interfaces, and personalizing application views without affecting core functionality."

ogType: "article"
ogTitle: "Comfort Job Application Template Override"
ogDescription: "Learn how to override and customize Comfort Job application templates. Complete guide to modifying UI layouts, creating custom interfaces, and personalizing application views without affecting core functionality."
ogSiteName: "Comfort HRM Documentation"
ogImage: "/comfort-job-application-plugin-for-wordpress.webp"
ogUrl: "https://docs.comforthrm.com/comfortjobapp/template-override"

twitterCard: "article"
twitterTitle: "Comfort Job Application Template Override"
twitterDescription: "Learn how to override and customize Comfort Job application templates. Complete guide to modifying UI layouts, creating custom interfaces, and personalizing application views without affecting core functionality."
twitterSite: "@ComfortHRM"
twitterImage: "/comfort-job-application-plugin-for-wordpress.webp"
twitterUrl: "https://docs.comforthrm.com/comfortjobapp/template-override"

fbAppId: "1249182889483061"
keywords: "Comfort Job application templates, template override, UI customization, layout modification, theme templates, custom interfaces, template files, view customization, application skinning, UI components"
---

# How to Override Template

We have implemented woocommerce like template override system which means, you can override any template/view layer of this plugin in your theme. For this plugin, mainly admin interfaces of custom screens can be overridden. The frontend tour modals cannot be overridden as they load using JavaScript.

For core plugin: `wp-content/plugins/comfortjobapp/templates`  
For pro addon: `wp-content/plugins/comfortjobapppro/templates`

To override any file from your theme you have to create a folder called `comfortjobapp` inside your theme or child theme and copy files from the plugin’s template folder and put in this newly created folder inside your theme folder `comfortjobapp`. The process is same as the woocommerce theme file override.  


