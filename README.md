# 📱 Mobile Application QA Testing

## Overview

This repository contains QA test documentation for a mobile application, covering functional testing of key user flows including authentication, booking, child management, and profile settings.

The purpose of this project is to validate application functionality, user experience, and system behavior through structured test scenarios and positive/negative test cases.

---

## 🧪 Test Coverage

### 🚀 Splash Screen
**Objective:** Verify the application launches correctly.

**Covered:**
- Cold start behavior
- Splash screen UI validation
- App logo and description display
- Sign Up / Sign In options

---

### 👤 Create Account
**Objective:** Verify users can register successfully.

**Covered:**
- Account creation flow
- Required field validation
- Empty field handling
- Checkbox interaction
- Successful registration

**Expected Result:**
Users can create an account with valid information, while invalid inputs display proper validation messages.

---

### 🔐 Sign In
**Objective:** Verify user authentication functionality.

**Covered:**
- Login with credentials
- Invalid input validation
- Forgot Password flow
- Password reset request
- Google Sign In

**Expected Result:**
Users can successfully log in, reset passwords, and authenticate using supported methods.

---

### 🚪 Sign Out
**Objective:** Verify users can log out successfully.

**Covered:**
- Logout confirmation modal
- Cancel logout behavior
- Outside modal interaction
- Session termination

**Expected Result:**
Users remain logged in when logout is cancelled and are redirected to the landing page after successful logout.

---

### 📅 Booking Flow
**Objective:** Verify users can complete a booking journey.

**Covered:**
- Location selection
- Date & time slot selection
- Booking details validation
- Child selection
- Price calculation
- Promo code validation
- Checkout flow
- Payment success/failure handling

**Expected Result:**
Users can complete bookings successfully with accurate details, pricing, and payment validation.

---

### 👧 Child Profile Management
**Objective:** Verify users can manage child profiles.

**Covered:**
- View child profile
- Edit profile information
- Required field validation
- Age validation
- Delete profile
- Add new child profile

**Expected Result:**
Users can create, update, and delete child profiles with proper validation.

---

### 👤 Profile Management
**Objective:** Verify user profile settings functionality.

**Covered:**
- Profile UI validation
- Update profile information
- Upload profile picture
- Referral link sharing
- Fingerprint login settings

**Expected Result:**
Users can update profile details, copy referral links, and manage fingerprint login preferences successfully.

---

## 🛠 Testing Types

- Functional Testing
- Smoke Testing
- Regression Testing
- Negative Testing
- UI Testing
- End-to-End Testing

---

## 🧰 Tools Used

| Category | Tools |
|---|---|
| Test Documentation | Google Spreadsheet / TestRail |
| Bug Tracking | Jira |
| API Testing | Postman |
| UI Reference | Figma |
| Mobile Testing | Android & iOS Devices |

---

## 📌 Project Objective

Demonstrate QA practices in:

✅ Test scenario design  
✅ Test case documentation  
✅ Functional validation  
✅ User flow testing  
✅ Defect identification  
✅ Mobile application quality assurance
