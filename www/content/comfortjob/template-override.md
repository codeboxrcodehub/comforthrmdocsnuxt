---
title: "Comfort Job Template Override Guide"
description: "Learn how to override Comfort Job plugin templates to customize your job board design. Step-by-step guide for template modification and theme integration without losing changes on updates."

ogType: "article"
ogTitle: "Comfort Job Template Override Guide"
ogDescription: "Learn how to override Comfort Job plugin templates to customize your job board design. Step-by-step guide for template modification and theme integration without losing changes on updates."
ogSiteName: "Comfort HRM Documentation"
ogImage: "/comfort-job-wordpress-job-board-plugin.webp"
ogUrl: "https://docs.comforthrm.com/comfortjob/template-override"

twitterCard: "article"
twitterTitle: "Comfort Job Template Override Guide"
twitterDescription: "Learn how to override Comfort Job plugin templates to customize your job board design. Step-by-step guide for template modification and theme integration without losing changes on updates."
twitterSite: "@ComfortHRM"
twitterImage: "/comfort-job-wordpress-job-board-plugin.webp"
twitterUrl: "https://docs.comforthrm.com/comfortjob/template-override"

fbAppId: "1249182889483061"
keywords: "Comfort Job template override, customize job board, WordPress template customization, job listing design, theme override, template files, PHP templates, CSS customization, job board styling, plugin templates"
---

# How to Override Template

We have implemented woocommerce like template override system which means, you can override any template/view layer of this plugin in your theme. For this plugin, mainly admin interfaces of custom screens can be overridden. The frontend tour modals cannot be overridden as they load using JavaScript.

For core plugin: `wp-content/plugins/comfortjob/templates`  
For pro addon: `wp-content/plugins/comfortjobpro/templates`

To override any file from your theme you have to create a folder called `comfortjob` inside your theme or child theme and copy files from the plugin’s template folder and put in this newly created folder inside your theme folder `comfortjob`. The process is same as the woocommerce theme file override.  


