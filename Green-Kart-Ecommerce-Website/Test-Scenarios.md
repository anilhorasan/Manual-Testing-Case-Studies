# Test Scenarios for Green Kart Ecommerce Website

## 1. Cart Functionality

### 1.1 Add Single Item to Cart
- **Scenario**: Add one unit of an item (e.g., Broccoli) to the cart.
- **Test Steps**:
  1. Navigate to the homepage.
  2. Add 1 unit of "Broccoli" to the cart.
  3. Click the "cart" icon in the navigation bar.
- **Expected Result**: The cart should display "Broccoli" with a quantity of 1.
- **Test Case**: [TC-1001](./Test-Cases.xlsx#TC-1001)

### 1.2 Persist Cart After Refresh
- **Scenario**: Verify that the cart persists after a page refresh.
- **Test Steps**:
  1. Add an item (e.g., "Broccoli") to the cart.
  2. Refresh the page.
  3. Click the "cart" icon in the navigation bar.
- **Expected Result**: Items in the cart should remain unchanged after refresh.
- **Test Case**: [TC-1002](./Test-Cases.xlsx#TC-1002)

### 1.3 Increase and Verify Quantity
- **Scenario**: Increase the quantity of an item (e.g., Cucumber) and verify the updated quantity in the cart.
- **Test Steps**:
  1. Add "Cucumber" to the cart.
  2. Increase the quantity of "Cucumber" to 2.
  3. Click the "cart" icon in the navigation bar.
- **Expected Result**: "Cucumber" should be displayed with a quantity of 2 in the cart.
- **Test Case**: [TC-1003](./Test-Cases.xlsx#TC-1003)

### 1.4 Empty Cart and Verify
- **Scenario**: Verify that the cart is empty after removing all items.
- **Test Steps**:
  1. Remove all items from the cart.
  2. Verify the "Proceed to Checkout" button is disabled and inactive.
  3. Verify the "Your cart is empty!" message is displayed.
- **Expected Result**: The cart should be empty with the correct message displayed.
- **Test Case**: [TC-1006](./Test-Cases.xlsx#TC-1006)

## 2. Price Calculation

### 2.1 Verify Item Prices in Cart
- **Scenario**: Verify the price of an item (e.g., Broccoli) in the cart.
- **Test Steps**:
  1. Add 1 unit of "Broccoli" to the cart.
  2. Navigate to the cart.
- **Expected Result**: The price displayed for "Broccoli" should be correct (120).
- **Test Case**: [TC-1007](./Test-Cases.xlsx#TC-1007)

### 2.2 Verify Cart Totals
- **Scenario**: Verify that the total price of items in the cart is calculated correctly.
- **Test Steps**:
  1. Add 3 units of "Broccoli" (120 * 3 = 360) and 1 unit of "Cauliflower" (180).
  2. Navigate to the cart and proceed to checkout.
- **Expected Result**: The total price should be correctly calculated as 540.
- **Test Case**: [TC-1008](./Test-Cases.xlsx#TC-1008)

### 2.3 Verify Price Updates After Quantity Change
- **Scenario**: Verify that the price updates correctly after the quantity of items is changed.
- **Test Steps**:
  1. Add 3 units of "Broccoli" (120 * 3 = 360) and 1 unit of "Cauliflower" (180).
  2. Update the quantity of each item to 4 units.
  3. Verify the updated prices in the cart.
- **Expected Result**: The updated prices and totals should be correctly displayed.
- **Test Case**: [TC-1009](./Test-Cases.xlsx#TC-1009)

## 3. Search Functionality

### 3.1 Search Partial Keyword
- **Scenario**: Search for an item by entering a partial keyword (e.g., "cu").
- **Test Steps**:
  1. Enter "cu" in the search bar.
  2. Verify the search results include items like "Cucumber" and "Capsicum".
- **Expected Result**: The search results should match the partial query.
- **Test Case**: [TC-1010](./Test-Cases.xlsx#TC-1010)

### 3.2 Search with No Matches
- **Scenario**: Search for a non-existent item (e.g., "?") and verify the result.
- **Test Steps**:
  1. Enter "?" in the search bar.
  2. Verify the message "Sorry, no products matched your search!" is displayed.
- **Expected Result**: No items should be shown, and the correct message should be displayed.
- **Test Case**: [TC-1011](./Test-Cases.xlsx#TC-1011)

## 4. Navigation Bar

### 4.1 Verify Navigation Links 1 - Limited Offer
- **Scenario**: Verify that clicking on the "Limited Offer" link redirects to the correct page.
- **Test Steps**:
  1. Click on the "Limited Offer" link in the navigation bar.
  2. Verify it redirects to the QA Summit page.
- **Expected Result**: The navigation should redirect to the correct page.
- **Test Case**: [TC-1012](./Test-Cases.xlsx#TC-1012)

### 4.2 Verify Navigation Links 2 - Top Deals
- **Scenario**: Verify that clicking on the "Top Deals" link redirects to the correct page.
- **Test Steps**:
  1. Click on the "Top Deals" link in the navigation bar.
  2. Verify it redirects to the Deals page.
- **Expected Result**: The navigation should redirect to the correct page.
- **Test Case**: [TC-1013](./Test-Cases.xlsx#TC-1013)

## 5. User Interface

### 5.1 Verify Orange "ADDED" Pop-up
- **Scenario**: Verify that the orange "ADDED" pop-up appears and disappears after adding an item to the cart.
- **Test Steps**:
  1. Add 1 unit of "Broccoli" to the cart.
  2. Verify the orange "ADDED" pop-up appears and disappears within 5 seconds.
- **Expected Result**: The pop-up should appear and disappear as expected.
- **Test Case**: [TC-1015](./Test-Cases.xlsx#TC-1015)

### 5.2 Verify Logo Visibility and Functionality
- **Scenario**: Verify that the website logo is visible and clickable.
- **Test Steps**:
  1. Check that the logo is visible on the homepage.
  2. Click the logo.
  3. Verify that it redirects to the homepage.
- **Expected Result**: The logo should be visible and redirect to the homepage.
- **Test Case**: [TC-1016](./Test-Cases.xlsx#TC-1016)

