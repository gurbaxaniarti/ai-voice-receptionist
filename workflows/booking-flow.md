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
6. Store data in Google Sheets
7. Send SMS confirmation

## Edge Cases Handled

- Prevents booking on weekends
- Restricts appointments to defined working hours
