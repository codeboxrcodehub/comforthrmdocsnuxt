---
title: "Comfort Job Application Email Settings"
description: "Configure email notifications and communication settings in Comfort Job Application. Complete guide to email templates, notification preferences, and SMTP configuration for application alerts."

ogType: "article"
ogTitle: "Comfort Job Application Email Settings"
ogDescription: "Configure email notifications and communication settings in Comfort Job Application. Complete guide to email templates, notification preferences, and SMTP configuration for application alerts."
ogSiteName: "Comfort HRM Documentation"
ogImage: "/comfort-job-application-plugin-for-wordpress.webp"
ogUrl: "https://docs.comforthrm.com/comfortjobapp/user-guide/emails"

twitterCard: "article"
twitterTitle: "Comfort Job Application Email Settings"
twitterDescription: "Configure email notifications and communication settings in Comfort Job Application. Complete guide to email templates, notification preferences, and SMTP configuration for application alerts."
twitterSite: "@ComfortHRM"
twitterImage: "/comfort-job-application-plugin-for-wordpress.webp"
twitterUrl: "https://docs.comforthrm.com/comfortjobapp/user-guide/emails"

fbAppId: "1249182889483061"
keywords: "Comfort Job application emails, email notifications, application alerts, email templates, notification settings, email configuration, SMTP setup, email preferences, communication settings, alert system"
---

## Email System

The Comfort Job Application plugin includes an email system to notify users about various events such as job application submissions.

#### Customizing Email Templates

1. Copy the desired email template file from `wp-content/plugins/comfortjobapp/templates/emails/` to your theme's directory, maintaining the folder structure.
2. Edit the copied template file as needed.

#### Available Email Templates
- **Notify Employer on application submission**: `job_apply_employer_notification.php`
- **Notify Candidate on application submission**: `job_apply_candidate_notification.php`
- **Notify guest user on application submission**: `guest_email_confirmation.php`

### Single Email Settings

1. Go to `Comfort Job Application > Emails`.
2. Configure the following email settings:

   - **Subject**: The subject of the email.
   - **Email heading**: The heading of the email.
   - **Additional content**: The Additional content of the emails.
   - **From Name**: The name that will appear as the sender of the emails.
   - **From Email**: The email address that will appear as the sender of the emails.
   - **Admin Email**: The email address where admin notifications will be sent(if admin notification).
   - **CC/BCC**: The CC & BCC of the email.

3. Save changes.

