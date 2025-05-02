# Pos Malaysia Rate Calculator Test Automation

## Question 1: API Testing
- Postman Collection: `pos-rate-api.postman_collection.json`
- APIs tested:
  - Get countries list
  - Get state from postcode
  - Calculate shipping rate

## Question 2: UI Test with Playwright
- `rateCalculator.spec.ts` verifies that user can calculate a shipment quote from Malaysia to India.

### Setup
```bash
npm install
npx playwright install
npx playwright test
