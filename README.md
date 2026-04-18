# Simplfai-QA-Test-Project
# 🧪 Simplfai — QA Documentation

> Manual QA testing documentation for the [Simplfai](https://smplifai-frontend.vercel.app/) web application.  
> Includes test plan, test cases, bug reports, and test execution results.

---

## 📁 Project Structure

```
📦 simplfai-qa
 ┣ 📄 README.md               # Project overview (this file)
 ┣ 📄 Test_Plan.md            # Test strategy, scope, environment
 ┣ 📄 Test_Cases.md           # All 17 test cases with steps and results
 ┗ 📄 Bug_Report.md           # Identified bugs and fix status
```

---

## 📊 Test Summary

| Metric | Value |
|--------|-------|
| Total Test Cases | 17 |
| ✅ Passed | 11 |
| ❌ Failed | 6 |
| Pass Rate | 64.7% |
| Fail Rate | 35.3% |
| Application Version | 1.0 |
| Environment | QA |
| Browser | Google Chrome |
| OS | Windows 10 |

---

## ✅ Test Scope

### In Scope
- User Login / Logout
- Profile Management
- Reset Password
- Search feature
- Notifications
- Settings section
- Help page
- Tooltip behavior
- Application creation, deletion, export to PDF
- Billing & History sections

### ❌ Out of Scope
- Performance Testing
- Security Testing (basic level only)

---

## 🐛 Bug Overview

| Bug ID | Title | Priority | Status |
|--------|-------|----------|--------|
| BUG-1 | Search does not return results for existing data | Medium | 🔧 Fixed |
| BUG-2 | Password reset functionality is not working | High | 🔧 Fixed |
| BUG-3 | Notifications are not displayed correctly | Medium | 🔧 Fixed |
| BUG-4 | Settings button does not open when clicked | High | 🔧 Fixed |
| BUG-5 | Help page does not open when clicked | Medium | 🔧 Fixed |
| BUG-6 | Tooltip is not displayed when hovering over button | Low | 🔧 Fixed |

---

## 🧰 Tools Used

| Tool | Purpose |
|------|---------|
| Postman | API testing |
| Jira | Bug tracking |
| TestRail | Test case management |
| Google Drive | Screenshot & attachment storage |

---

## 👥 Team

| Role | Responsibility |
|------|---------------|
| QA Engineer | Test execution and bug reporting |
| Developer | Bug fixing |
| Project Manager | Monitoring and coordination |

---

## 📋 Test Strategy

Testing types performed:
- **Manual Testing**
- **Functional Testing**
- **UI Testing**

---

## 📌 Conclusion

The application is mostly stable after bug fixes. All 6 identified bugs have been resolved.  
Further **regression testing** is recommended before production release.

---

## 🔗 Links

- 🌐 **App URL:** [https://smplifai-frontend.vercel.app](https://smplifai-frontend.vercel.app)
