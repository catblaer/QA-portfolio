# Test Cases

## Module: Login

### TC-LOGIN-001 – Login with valid credentials
Priority: High  

Preconditions:  
User is registered  

Steps:
1. Open login page  
2. Enter valid email  
3. Enter valid password  
4. Click Login  

Expected Result:  
User is logged in and redirected to dashboard  

---

### TC-LOGIN-002 – Login with incorrect password
Priority: High  

Preconditions:  
User exists  

Steps:
1. Open login page  
2. Enter valid email  
3. Enter wrong password  
4. Click Login  

Expected Result:  
Error message displayed  

---

### TC-LOGIN-003 – Login with empty fields
Priority: Medium  

Steps:
1. Open login page  
2. Leave fields empty  
3. Click Login  

Expected Result:  
Validation errors displayed
