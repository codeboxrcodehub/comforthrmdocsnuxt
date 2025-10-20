---
title: "Template Override Guide for Comfort Resume"
description: "Learn how to override Comfort Resume templates to create custom resume designs and layouts. Complete guide for customizing PDF resumes, email templates, and resume styling for your HR system."

ogType: "article"
ogTitle: "Template Override Guide for Comfort Resume"
ogDescription: "Learn how to override Comfort Resume templates to create custom resume designs and layouts. Complete guide for customizing PDF resumes, email templates, and resume styling for your HR system."
ogSiteName: "Comfort HRM Documentation"
ogImage: "/comfort-resume-wordpress-resume-builder-plugin.webp"
ogUrl: "https://docs.comforthrm.com/comfortresume/template-override"

twitterCard: "article"
twitterTitle: "Template Override Guide for Comfort Resume"
twitterDescription: "Learn how to override Comfort Resume templates to create custom resume designs and layouts. Complete guide for customizing PDF resumes, email templates, and resume styling for your HR system."
twitterSite: "@ComfortHRM"
twitterImage: "/comfort-resume-wordpress-resume-builder-plugin.webp"
twitterUrl: "https://docs.comforthrm.com/comfortresume/template-override"

fbAppId: "1249182889483061"
keywords: "Comfort Resume template override, custom resume templates, resume design customization, override resume layout, custom PDF resumes, resume styling, child theme templates, custom resume fields, template hierarchy"
---
# How to Override Template


We have implemented woocommerce like template override system which means, you can override any template/view layer of this plugin in your theme. For this plugin, mainly admin interfaces of custom screens can be overridden. The frontend tour modals cannot be overridden as they load using JavaScript.

For core plugin: `wp-content/plugins/comfortresume/templates`  
For pro addon: `wp-content/plugins/comfortresumepro/templates`

To override any file from your theme you have to create a folder called `comfortresume` inside your theme or child theme and copy files from the plugin’s template folder and put in this newly created folder inside your theme folder `comfortresume`. The process is same as the woocommerce theme file override.  


