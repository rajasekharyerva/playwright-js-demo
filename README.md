# Playwright
### Installing Playwright
    npm init playwright@latest

### What's Installed
    playwright.config.ts
    package.json
    package-lock.json
    tests/
    example.spec.ts
    tests-examples/
    demo-todo-app.spec.ts

### Check playwright
    npx playwright --version

### Running the Example Test
    npx playwright test

### HTML Test Reports
    npx playwright show-report

### Running the Example Test in UI Mode
    npx playwright test --ui

### Updating Playwright
    npm install -D @playwright/test@latest
    # Also download new browser binaries and their dependencies:
    npx playwright install --with-deps