---
title: "Comfort Job Application Hooks & Filters"
description: "Learn how to use hooks and filters to extend Comfort Job application functionality. Complete guide to customizing application behavior, adding features, and modifying core processes through hooks system."

ogType: "article"
ogTitle: "Comfort Job Application Hooks & Filters"
ogDescription: "Learn how to use hooks and filters to extend Comfort Job application functionality. Complete guide to customizing application behavior, adding features, and modifying core processes through hooks system."
ogSiteName: "Comfort HRM Documentation"
ogImage: "/comfort-job-application-plugin-for-wordpress.webp"
ogUrl: "https://docs.comforthrm.com/comfortjobapp/hooks-and-filters"

twitterCard: "article"
twitterTitle: "Comfort Job Application Hooks & Filters"
twitterDescription: "Learn how to use hooks and filters to extend Comfort Job application functionality. Complete guide to customizing application behavior, adding features, and modifying core processes through hooks system."
twitterSite: "@ComfortHRM"
twitterImage: "/comfort-job-application-plugin-for-wordpress.webp"
twitterUrl: "https://docs.comforthrm.com/comfortjobapp/hooks-and-filters"

fbAppId: "1249182889483061"
keywords: "Comfort Job application hooks, application filters, functionality extension, custom hooks, event filters, application customization, plugin extensions, action hooks, filter hooks, application development"
---
# Hooks and Filters Documentation for ComfortJobApp & ComfortJobAppPro

## ComfortJobApp Plugin

### Action Hooks


1. **`comfortjobapp_wpheading_wrap_right_before`**
   - Triggered before the settings import/export button is added.
   - **Example**:
     ```php
     add_action( 'comfortjobapp_wpheading_wrap_right_before', function() {
         // Add custom content before the button
     } );
     ```

2. **`comfortjobapp_admin_enqueue_scripts`**
   - Triggered to enqueue admin scripts and styles.
   - **Example**:
     ```php
     add_action( 'admin_enqueue_scripts', function() {
         // Enqueue custom admin scripts
     } );
     ```

---

### Filter Hooks

1. **`comfortjobapp_settings_fields`**
   - Filters the settings fields for the plugin.
   - **Parameters**:
     - `$fields` (array): The settings fields.
   - **Example**:
     ```php
     add_filter( 'comfortjobapp_settings_fields', function( $fields ) {
         $fields['new_field'] = [
             'name' => 'new_field',
             'label' => 'New Field',
             'type' => 'text',
         ];
         return $fields;
     } );
     ```

2. **`comfortjobapp_form_type`**
   - Filters the form types available in the application form builder.
   - **Parameters**:
     - `$types` (array): The form types.
   - **Example**:
     ```php
     add_filter( 'comfortjobapp_form_type', function( $types ) {
         $types['custom_type'] = 'Custom Type';
         return $types;
     } );
     ```

3. **`comfortjobapp_global_<section_id>_fields`**
   - Filters the fields for a specific settings section.
   - **Parameters**:
     - `$fields` (array): The fields for the section.
   - **Example**:
     ```php
     add_filter( 'comfortjobapp_global_comfortjobapp_general_fields', function( $fields ) {
         $fields['custom_field'] = [
             'name' => 'custom_field',
             'label' => 'Custom Field',
             'type' => 'text',
         ];
         return $fields;
     } );
     ```

4. **`comfortjobapp_steps`**
   - Filters the application steps.
   - **Parameters**:
     - `$steps` (array): The application steps.
   - **Example**:
     ```php
     add_filter( 'comfortjobapp_steps', function( $steps ) {
         $steps['custom_step'] = 'Custom Step';
         return $steps;
     } );
     ```

---

## ComfortJobAppPro Plugin

### Action Hooks

1. **`comfortjobapppro_admin_enqueue_scripts`**
   - Triggered to enqueue admin scripts and styles for the Pro plugin.
   - **Example**:
     ```php
     add_action( 'admin_enqueue_scripts', function() {
         // Enqueue custom admin scripts for Pro
     } );
     ```

2. **`comfortjobapppro_wpheading_wrap_right_before`**
   - Triggered before the settings import/export button for the Pro plugin.
   - **Example**:
     ```php
     add_action( 'comfortjobapppro_wpheading_wrap_right_before', function() {
         // Add custom content before the button for Pro
     } );
     ```

---

### Filter Hooks

1. **`comfortjobapppro_settings_fields`**
   - Filters the settings fields for the Pro plugin.
   - **Parameters**:
     - `$fields` (array): The settings fields.
   - **Example**:
     ```php
     add_filter( 'comfortjobapppro_settings_fields', function( $fields ) {
         $fields['pro_field'] = [
             'name' => 'pro_field',
             'label' => 'Pro Field',
             'type' => 'text',
         ];
         return $fields;
     } );
     ```

2. **`comfortjobapppro_form_type`**
   - Filters the form types available in the Pro application form builder.
   - **Parameters**:
     - `$types` (array): The form types.
   - **Example**:
     ```php
     add_filter( 'comfortjobapppro_form_type', function( $types ) {
         $types['pro_custom_type'] = 'Pro Custom Type';
         return $types;
     } );
     ```

3. **`comfortjobapppro_steps`**
   - Filters the application steps for the Pro plugin.
   - **Parameters**:
     - `$steps` (array): The application steps.
   - **Example**:
     ```php
     add_filter( 'comfortjobapppro_steps', function( $steps ) {
         $steps['pro_custom_step'] = 'Pro Custom Step';
         return $steps;
     } );
     ```

---

This documentation provides an overview of the available hooks and filters in the `ComfortJobApp` and `ComfortJobAppPro` plugins. Use these to extend or customize the functionality as needed.




