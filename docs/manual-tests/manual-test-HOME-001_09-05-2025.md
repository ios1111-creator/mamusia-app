# Manual Test: Home Component  
🗓️ Date: 09-05-2025  
👤 Tested by: Adam P.  
📎 Related Ticket: [`MAMA-101` – Create home component with login and registration buttons](https://pawlikaddam.atlassian.net/jira/software/projects/MAMY/boards/1?selectedIssue=MAMY-1)

## 🎯 Purpose  
Ensure that the Home component renders correctly and routes work as expected.

## 🧪 Test Steps
1. Navigate to `http://localhost:4200/`
2. Check for header: "Śledź rozwój swojego dziecka w jednym miejscu!
Lista korzyści:
📌 Zapisywanie dat szczepień
📝 Notatki o rozwoju"
3. Click "Zaloguj się" button
4. Verify redirection to `/login`
5. Click browser back
6. Click "Zarejestruj się" button
7. Verify redirection to `/register`

## ✅ Expected Result  
- Header is visible  
- Buttons styled with Angular Material  
- Buttons navigate to correct routes

## 🧾 Actual Result  
🟢 All tests passed – UI is correct, navigation works as expected

## 📊 Status  
**PASSED ✅**

## 🌐 Environment  
- URL: `http://localhost:4200`  
- Browser: Chrome 136.0.7103.93 
- Angular: v15 