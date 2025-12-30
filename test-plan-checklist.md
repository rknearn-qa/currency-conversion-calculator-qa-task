# Test Plan & Checklist
Currency Conversion Calculator

## 1. Smoke / Basic Checks
- Page loads successfully
- Calculator is visible and interactive
- Default currencies are selected
- Conversion result is displayed after input

## 2. Functional Testing

### Input Field
- Accepts valid numeric values
- Accepts decimal values
- Rejects non-numeric characters
- Handles zero value
- Handles negative values
- Handles empty input
- Copy-paste input support

### Currency Selection
- Change source currency
- Change target currency
- Same currency conversion (e.g. EUR → EUR)
- Rapid switching between currencies

### Calculation Logic
- Correct conversion rate is applied
- Result updates after input change
- Result updates after currency change
- Correct rounding behavior
- No calculation for invalid input

## 3. Boundary & Edge Cases
- Very small amounts (e.g. 0.0001)
- Very large amounts
- Maximum allowed decimal precision
- Input cleared after calculation

## 4. UX / Usability
- Clear error or validation messages
- Input field state clarity
- Result readability
- Disabled states (if applicable)

## 5. Exploratory / Risk-Based Testing
- Rapid input changes
- Multiple currency changes in sequence
- Browser refresh during usage
- Network throttling during calculation

## 6. Non-Functional (High-Level)
- Performance (calculation speed)
- Cross-browser (Chrome, Firefox)
- Mobile responsiveness (basic check)
