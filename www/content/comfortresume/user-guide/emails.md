---
title: "Emails User Guide for Comfort Resume"
description: "Learn how to use the Emails system in Comfort Resume to automate candidate communication, customize email templates, and manage applicant notifications and interview scheduling."

ogType: "article"
ogTitle: "Emails User Guide for Comfort Resume"
ogDescription: "Learn how to use the Emails system in Comfort Resume to automate candidate communication, customize email templates, and manage applicant notifications and interview scheduling."
ogSiteName: "Comfort HRM Documentation"
ogImage: "/comfort-resume-wordpress-resume-builder-plugin.webp"
ogUrl: "https://docs.comforthrm.com/comfortresume/user-guide/emails"

twitterCard: "article"
twitterTitle: "Emails User Guide for Comfort Resume"
twitterDescription: "Learn how to use the Emails system in Comfort Resume to automate candidate communication, customize email templates, and manage applicant notifications and interview scheduling."
twitterSite: "@ComfortHRM"
twitterImage: "/comfort-resume-wordpress-resume-builder-plugin.webp"
twitterUrl: "https://docs.comforthrm.com/comfortresume/user-guide/emails"

fbAppId: "1249182889483061"
keywords: "Comfort Resume emails, candidate communication, email templates, automated emails, applicant notifications, interview scheduling, status updates, email customization, HR communications, candidate follow-up"
---

## Email System

The Comfort Resume plugin includes an email system to notify users about various events such as resume application submissions, resume approvals, and more.

#### Customizing Email Templates

1. Copy the desired email template file from `wp-content/plugins/comfortresume/templates/emails/` to your theme's directory, maintaining the folder structure.
2. Edit the copied template file as needed.

#### Available Email Templates
- **Resume creation guest user Email for Admin**: `guest_resume_create_to_admin.php`
- **Job Application Email with resume Email**: `job_applied_by_resume.php`
- **Resume Saved as Draft Email For User**: `resume_draft_to_user.php`
- **Resume Published Email For User**: `resume_published_to_user.php`
- **Resume creation guest user Email For User**: `guest_resume_create_to_user.php`
- **Resume verified  Email For Admin**: `guest_resume_verify_to_admin.php`
- **Resume verified  Email For User**: `guest_resume_verify_to_user.php`
### Single Email Settings

1. Go to `Comfort Resume > Emails`.
2. Configure the following email settings:

   - **Subject**: The subject of the email.
   - **Email heading**: The heading of the email.
   - **Additional content**: The Additional content of the emails.
   - **From Name**: The name that will appear as the sender of the emails.
   - **From Email**: The email address that will appear as the sender of the emails.
   - **Admin Email**: The email address where admin notifications will be sent.
   - **CC/BCC**: The CC & BCC of the email.

3. Save changes.

