# SauceDemo Manual Test Cases

## TC-01: Valid Login
**Scenario:** Verify that a registered user can log in using valid credentials.

**Precondition:** User is on the SauceDemo login page.

**Test Data:**
- Username: `standard_user`
- Password: `secret_sauce`

**Steps:**
1. Open the SauceDemo login page.
2. Enter a valid username.
3. Enter a valid password.
4. Click **Login**.

**Expected Result:** User is successfully logged in and redirected to the Products page.

**Actual Result:** User was successfully logged in and redirected to the Products page.

**Result:** PASS

---

## TC-02: Invalid Username
**Scenario:** Verify that login fails with an invalid username.

**Test Data:**
- Username: `invalid_user`
- Password: `secret_sauce`

**Expected Result:** User should not be logged in and an appropriate error message should be displayed.

**Actual Result:** User was not logged in and an error message was displayed.

**Result:** PASS

---

## TC-03: Invalid Password
**Scenario:** Verify that login fails with an invalid password.

**Test Data:**
- Username: `standard_user`
- Password: `invalid_password`

**Expected Result:** User should not be logged in and an appropriate error message should be displayed.

**Actual Result:** User was not logged in and an error message was displayed.

**Result:** PASS

---

## TC-04: Checkout with Empty Required Fields
**Scenario:** Verify that checkout cannot continue when required customer information is missing.

**Steps:**
1. Add a product to the cart.
2. Open the cart.
3. Click **Checkout**.
4. Leave the required fields empty.
5. Click **Continue**.

**Expected Result:** Appropriate validation error messages should be displayed.

**Actual Result:** Validation error message was displayed indicating that First Name is required.

**Result:** PASS

---

## TC-05: Complete Purchase
**Scenario:** Verify that a customer can successfully complete a purchase.

**Steps:**
1. Add a product to the cart.
2. Open the cart.
3. Click **Checkout**.
4. Enter the required customer information.
5. Click **Continue**.
6. Verify the order summary.
7. Click **Finish**.

**Expected Result:** Order should be successfully completed and an order confirmation message should be displayed.

**Actual Result:** Order was successfully completed and the confirmation message was displayed.

**Result:** PASS
