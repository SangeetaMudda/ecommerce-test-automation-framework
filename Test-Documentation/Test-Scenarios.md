# Test Scenarios - E-Commerce Application

## Application Under Test

nopCommerce Demo E-Commerce Application

---

# 1. User Registration Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| REG_TS_001 | Verify user can register with valid information |
| REG_TS_002 | Verify registration fails when mandatory fields are empty |
| REG_TS_003 | Verify registration fails when email format is invalid |
| REG_TS_004 | Verify user cannot register with an already registered email |
| REG_TS_005 | Verify password and confirm password validation |

---

# 2. Login Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| LOGIN_TS_001 | Verify registered user can login successfully |
| LOGIN_TS_002 | Verify login fails with invalid password |
| LOGIN_TS_003 | Verify login fails with invalid username |
| LOGIN_TS_004 | Verify login validation when username is empty |
| LOGIN_TS_005 | Verify login validation when password is empty |
| LOGIN_TS_006 | Verify user can logout successfully |
| LOGIN_TS_007 | Verify forgot password functionality |

---

# 3. Product Search Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| SEARCH_TS_001 | Verify user can search products using valid keywords |
| SEARCH_TS_002 | Verify search results display matching products |
| SEARCH_TS_003 | Verify search with invalid product name |
| SEARCH_TS_004 | Verify product filtering functionality |
| SEARCH_TS_005 | Verify product sorting functionality |

---

# 4. Product Details Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| PRODUCT_TS_001 | Verify product details page displays correctly |
| PRODUCT_TS_002 | Verify product price is displayed |
| PRODUCT_TS_003 | Verify product availability status |
| PRODUCT_TS_004 | Verify product images are displayed |
| PRODUCT_TS_005 | Verify product reviews and ratings |

---

# 5. Shopping Cart Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| CART_TS_001 | Verify user can add product to cart |
| CART_TS_002 | Verify product quantity can be updated |
| CART_TS_003 | Verify user can remove product from cart |
| CART_TS_004 | Verify cart total calculation |
| CART_TS_005 | Verify cart persists after user login |

---

# 6. Wishlist Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| WISH_TS_001 | Verify user can add product to wishlist |
| WISH_TS_002 | Verify user can remove product from wishlist |

---

# 7. Checkout Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| CHECKOUT_TS_001 | Verify user can proceed to checkout |
| CHECKOUT_TS_002 | Verify shipping address entry |
| CHECKOUT_TS_003 | Verify order summary details |
| CHECKOUT_TS_004 | Verify order confirmation after checkout |
| CHECKOUT_TS_005 | Verify order number generation |

---

# 8. Order Management Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| ORDER_TS_001 | Verify user can view order history |
| ORDER_TS_002 | Verify order details are displayed |
| ORDER_TS_003 | Verify order status updates correctly |

---

# 9. Admin Module

| Scenario ID | Test Scenario |
|-------------|---------------|
| ADMIN_TS_001 | Verify admin login functionality |
| ADMIN_TS_002 | Verify admin can add products |
| ADMIN_TS_003 | Verify admin can update products |
| ADMIN_TS_004 | Verify admin can delete products |
| ADMIN_TS_005 | Verify admin can view customer orders |

---

# Automation Candidates

The following scenarios will be automated:

- User Login
- User Registration
- Product Search
- Add Product to Cart
- Checkout Flow
- Order Verification

Automation tools:

- Selenium WebDriver
- Playwright
- REST Assured
