# Appointment Booking Workflow

## Steps

1. User requests appointment
2. AI extracts:
   - Date
   - Time
   - Name
3. Make checks Google Calendar
4. If slot available:
   - Book appointment
5. If conflict:
   - Suggest alternative slots
6. Blocks the calendar
7. Store data in Google Sheets
8. Send SMS confirmation

## Edge Cases Handled

- Prevents booking on weekends
- Restricts appointments to defined working hours
