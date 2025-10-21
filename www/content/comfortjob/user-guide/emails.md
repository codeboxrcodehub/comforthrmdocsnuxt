---
title: "Comfort Job Email Settings"
description: "Configure email notifications and templates for job applications and employer communications. Complete guide to email settings, template customization, and notification workflow management."

ogType: "article"
ogTitle: "Comfort Job Email Settings"
ogDescription: "Configure email notifications and templates for job applications and employer communications. Complete guide to email settings, template customization, and notification workflow management."
ogSiteName: "Comfort HRM Documentation"
ogImage: "/comfort-job-wordpress-job-board-plugin.webp"
ogUrl: "https://docs.comforthrm.com/comfortjob/user-guide/emails"

twitterCard: "article"
twitterTitle: "Comfort Job Email Settings"
twitterDescription: "Configure email notifications and templates for job applications and employer communications. Complete guide to email settings, template customization, and notification workflow management."
twitterSite: "@ComfortHRM"
twitterImage: "/comfort-job-wordpress-job-board-plugin.webp"
twitterUrl: "https://docs.comforthrm.com/comfortjob/user-guide/emails"

fbAppId: "1249182889483061"
keywords: "Comfort Job emails, email notifications, job application emails, email templates, notification settings, applicant emails, employer notifications, email customization, SMTP settings, email workflow"
---

## Email System

The Comfort Job plugin includes an email system to notify users about various events such as job application submissions, job approvals, and more.

#### Customizing Email Templates

1. Copy the desired email template file from `wp-content/plugins/comfortjobpro/templates/emails/` to your theme's directory, maintaining the folder structure.
2. Edit the copied template file as needed.

#### Available Email Templates

- **Job Published Email For User**: `job_published_to_user.php`
- **New job create admin alert**: `guest_job_create_to_admin.php`
- **New Job create User alert**: `guest_job_create_to_user.php`(Pro)
- **Job Approved Admin alert**: `guest_job_verify_to_admin.php`(Pro)
- **Job Approved User alert**: `guest_job_email_verified.php`(Pro)

### Single Email Settings

1. Go to `Comfort Job > Emails`.
2. Configure the following email settings:

   - **Subject**: The subject of the email.
   - **Email heading**: The heading of the email.
   - **Additional content**: The Additional content of the emails.
   - **From Name**: The name that will appear as the sender of the emails.
   - **From Email**: The email address that will appear as the sender of the emails.
   - **Admin Email**: The email address where admin notifications will be sent.
   - **CC/BCC**: The CC & BCC of the email.

3. Save changes.

