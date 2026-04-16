# Test Cases - Login Page

## Task 1: Login Test Cases

| Test Case ID | Description | Steps | Expected Result |
|--------------|------------|-------|----------------|
| TC_01 | Valid Login | Open page → enter valid username & password → login | Redirect to dashboard |
| TC_02 | Invalid Login | Enter wrong credentials | Error: Invalid credentials |
| TC_03 | Empty Fields | Leave fields empty | Fields cannot be empty |
| TC_04 | SQL Injection | Enter ' OR 1=1 -- | Login blocked |

---

## Task 2: Boundary Value Testing

| Test Case ID | Input | Expected Result |
|--------------|-------|----------------|
| TC_BV_01 | 7 chars | Rejected |
| TC_BV_02 | 8 chars | Accepted |
| TC_BV_03 | 12 chars | Accepted |
| TC_BV_04 | 13 chars | Rejected |
