install Dependency:
npm install
npx playwright install
npm install --save-dev @types/node (Install for import fs , import path )

Allure report show command:
allure serve allure-results

Test run command:
npx playwright test
npx playwright test tests/searchProduct.test.ts --headed
npx playwright test tests/addToCart.test.ts --headed
