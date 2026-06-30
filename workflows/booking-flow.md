## Steps

1. User describes their issue or symptoms
2. AI maps symptoms to appropriate doctor using knowledge base
3. AI suggests the correct doctor
4. User confirms or selects doctor
5. AI extracts:
   - Date
   - Time
   - Name
6. Make checks Google Calendar
7. If slot available:
   - Book appointment
8. If conflict:
   - Suggest alternative slots
9. Blocks the calendar 
10. Store data in Google Sheets
11. Send SMS confirmation
    
## Edge Cases Handled
- Prevents booking on weekends
- Restricts appointments to defined working hours
