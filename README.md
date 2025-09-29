Slot Booking Project

This project is a ServiceNow customization for slot booking.
It includes client scripts that handle slot visibility and date validation.

Features

Show or hide slots (u_1 to u_10) based on the selected booking day.

Slots are visible on weekdays (Monday–Friday).

Slots are hidden on weekends.

Validate the booking date.

Only today’s date or future dates are allowed.

Shows an error if a past date is selected.

How to Use

Add the scripts as Client Scripts in ServiceNow.

Attach them to the fields:

u_booking_day → slot visibility script

#screenshots
<img width="1909" height="515" alt="Screenshot 2025-09-29 230003" src="https://github.com/user-attachments/assets/e3603f6b-9033-4c78-b05a-8cda0110cbf8" />

<img width="1919" height="299" alt="Screenshot 2025-09-29 230015" src="https://github.com/user-attachments/assets/801008a0-c539-4c8f-920b-65b69f87541b" />


u_today_date → date validation script

Test by selecting different days and dates.
