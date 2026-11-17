# Restaurant Booking Automation 🍽️

An n8n automation project that helps restaurants manage customer table-booking requests more efficiently.

## Business Problem

Restaurants often receive booking requests manually. This can take staff time and make it easier to miss customer information or forget to notify the owner.

This workflow automates the initial booking process.

##  How It Works

1. **Customer Form:** Customer submits their name, phone number, booking date, and number of guests.
2. **Guest Validation:** Checks whether the guest count is between 1 and 20.
3. **Phone Validation:** Checks whether the phone number contains 7–15 digits.
4. **Format Data:** Organizes the booking information.
5. **Google Sheets:** Saves valid booking details.
6. **Email Notification:** Sends an email to the restaurant owner.

## Features

- Customer booking form
- Guest-count validation
- Phone-number validation
- Automatic Google Sheets entry
- Email notification
- Human review before confirming reservations

## 🧪 Testing

The workflow was tested with a real form submission.

- Valid booking information was saved to Google Sheets.
- An email notification was successfully delivered.
- Invalid phone-number input was tested.
- Guest-count validation was configured.

## 🛠️ Tools Used

- n8n
- Google Sheets
- Gmail SMTP
- Docker
- JSON

## 📸 Workflow Screenshot

![Restaurant Booking Automation Workflow](workflow-overview.png)

## Project Files

- `restaurant-booking-workflow-public.json` — Sanitized workflow template.
- `workflow-overview.png` — Workflow screenshot.

## Notes

This is a personal learning project, not a production-ready restaurant booking system.

The public JSON is a template. It requires configuration of Google Sheets, email credentials, and other settings before it can be executed.

Customer reservations are not automatically confirmed. The restaurant owner must check availability and confirm them.

## What I Learned

- Building workflows in n8n
- Working with triggers, conditions, and actions
- Validating customer input
- Connecting Google Sheets
- Configuring email notifications
- Testing an end-to-end automation
- Solving a practical business problem

---

*Built as part of my AI Automation Learning Journey.*