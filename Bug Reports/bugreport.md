# Bug Report for Login Issue

## [BUG-1] Login for a user is not working with valid username and password with 500 error in login API  
**Created**: 10/Jan/22  
**Updated**: 12/Jan/22  

---

### **Status**
- **To Do**

### **Project**
- **BUG**

### **Components**
- **None**

### **Affects Versions**
- **None**

### **Fix Versions**
- **None**

---

### **Type**
- **Task**

### **Priority**
- **Medium**

### **Reporter**
- **Pro Mode**

### **Assignee**
- **Unassigned**

### **Resolution**
- **Unresolved**

### **Votes**
- **0**

### **Labels**
- **login**

### **Remaining Estimate**
- **Not Specified**

### **Time Spent**
- **Not Specified**

### **Original Estimate**
- **Not Specified**

---

### **Attachments**
- [API Testing Interview Questions & Answers - Part 1 (HINDI).xmind](#)  
- [API Testing Interview Questions & Answers Part 1 Hindi.jpeg](#)  

---

### **Description**
The login functionality is not working as expected for users with valid credentials. When attempting to login with correct username and password, a **500 error** occurs in the login API.

---

### **Steps to Reproduce**
1. Navigate to `stage.demoapp.xyz/login`
2. Enter user credentials:
   - **Username**: X
   - **Password**: Y
3. Click on the **Login** button
4. Observe that after clicking the login button, the login process does not proceed and a **500 error** is returned.

---

### **Actual Result**
- The login process fails and a **500 Internal Server Error** is returned when the user submits valid login credentials.

### **Expected Result**
- The user should be successfully logged in, and the application should redirect to the user dashboard page.

---

### **URL**
- `stage.demoapp.xyz/login`

### **Environment**
- **URL**: `stage.demoapp.xyz`
- **Logs**: Error with 500 /login with JSON  
- **[Video Replay](https://www.loom.com/share/174c8830bcb24de3ac38d488e8b57643)**  

---

### **Notes**
- **Error logs** and **screenshots** have been provided above.
- **Reproducibility**: Happens consistently for valid users.
- **Network**: Confirmed to occur in both Wi-Fi and Ethernet connections.

---

### **End of Report**

