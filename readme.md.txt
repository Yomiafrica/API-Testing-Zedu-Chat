# Zedu Chat API Testing - Postman Collection

**Project:** REST API Testing for Zedu Chat Platform  
**Tester:** Adesanya Oriyomi  
**Date:** May 2025  
**Framework:** Postman  
**Status:** Complete

---

## 📋 Project Overview

Comprehensive API testing of the Zedu Chat platform REST API endpoints. 
This project demonstrates:

- ✅ REST API testing methodology
- ✅ Bearer token authentication handling
- ✅ Request/response validation
- ✅ Status code assertions
- ✅ Negative test scenarios
- ✅ Edge case coverage
- ✅ Error handling validation

---

## 🎯 API Endpoints Tested

| Method | Endpoint | Purpose | Status |
|--------|----------|---------|--------|
| POST | /auth/register | User registration | ✓ Tested |
| POST | /auth/login | User login | ✓ Tested |
| POST | /auth/password-reset | Password reset | ✓ Tested |
| POST | /auth/verify-email | Email verification | ✓ Tested |
| GET | /users/profile | Get user profile | ✓ Tested |
| POST | /messages/send | Send message | ✓ Tested |
| GET | /messages/list | List messages | ✓ Tested |

---

## 📊 Test Coverage

- **Total Requests:** 25+
- **Positive Test Cases:** 15
- **Negative Test Cases:** 8
- **Edge Cases:** 2
- **Pass Rate:** 95%

### Authentication Testing
- ✓ Valid credentials login
- ✓ Invalid email/password
- ✓ Missing required fields
- ✓ Bearer token validation
- ✓ Token expiry handling
- ✓ Refresh token logic

### Response Validation
- ✓ HTTP status codes (200, 201, 400, 401, 403, 404, 500)
- ✓ JSON response structure
- ✓ Required fields presence
- ✓ Data type validation
- ✓ Error message clarity

### Security Testing
- ✓ HTTPS/TLS verification
- ✓ Token security
- ✓ Input sanitization
- ✓ Authorization checks

---

## 🚀 How to Use

### Import into Postman

1. Download the Postman collection: `zedu-chat-api-testing.json`
2. Open Postman
3. Click **"Import"** (top left)
4. Select the JSON file
5. Collection imported and ready to use!

### Run Tests

1. Open the collection in Postman
2. Click **"Run"** (or use Collection Runner)
3. Select environment (if using variables)
4. Click **"Start Run"**
5. View test results and assertion status

### API Documentation

Access Swagger/OpenAPI docs: https://api.zedu.chat/swagger/

---

## 🔑 Key Features

### Variables & Environment
- Base URL configured as variable
- Auth tokens stored and reused
- Dynamic data generation
- Environment-specific settings

### Assertions
Each request includes assertions for:
- Status code validation
- Response time checks
- JSON schema validation
- Field value verification
- Error message validation

### Token Management
- Login endpoint extracts token
- Token stored in Postman variable
- Reused across authenticated requests
- Token expiry handled gracefully

---

## 📈 Test Results Summary

| Category | Result |
|----------|--------|
| **Functional Tests** | 15/15 Pass |
| **Negative Tests** | 7/8 Pass |
| **Edge Cases** | 2/2 Pass |
| **Overall Pass Rate** | 95% |

---

## 🐛 Issues Found

### Critical
- None

### High
- Password reset endpoint slow (>3 sec response time)
- Email verification sometimes delayed

### Medium
- Error messages could be more descriptive
- Missing rate limiting headers

---

## 💡 Testing Insights

### What Worked Well
- Clear API endpoint structure
- Good error handling
- Proper status code usage
- Authentication flow intuitive

### Areas for Improvement
- Response time optimization needed
- API documentation could be more detailed
- Rate limiting should be implemented
- Webhook support would improve testing

---

## 🔧 Technologies Used

- **Postman:** API testing platform
- **REST API:** Testing approach
- **JSON:** Data format
- **Bearer Token:** Authentication method

---

## 📝 Test Methodology

1. **Analyze API Documentation** (Swagger)
2. **Identify Test Scenarios** (positive, negative, edge cases)
3. **Create API Requests** (with proper headers, parameters, body)
4. **Add Assertions** (validate responses)
5. **Execute Tests** (run collection)
6. **Document Findings** (bugs, insights)

---

## ✅ Quality Assurance Practices

- ✓ Structured test design
- ✓ Comprehensive coverage (positive + negative + edge cases)
- ✓ Assertion-based validation
- ✓ Error scenario testing
- ✓ Token/session management testing
- ✓ Security-focused testing

---

## 📞 Contact & Links

**Tester:** Adesanya Oriyomi  
**Email:** Adesanyayomi26@gmail.com  
**LinkedIn:** linkedin.com/in/adesanya-oriyomi-2701b1164  
**GitHub:** github.com/yomiafrica  
**Postman Collection:** https://www.postman.com/yomi-7318514/yomi-s-workspace/folder/gwvtuea/zedu-chat-api-testing

---

## 📋 Files in This Repository

- `zedu-chat-api-testing.json` - Postman collection export
- `README.md` - This file
- `TEST_RESULTS.md` - Detailed test execution results
- `API_TESTING_REPORT.txt` - Comprehensive testing report

---

**Last Updated:** May 23, 2025  
**Status:** Complete & Ready for Production  
**Maintainer:** Adesanya Oriyomi