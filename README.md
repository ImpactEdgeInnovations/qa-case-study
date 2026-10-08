# QA Case Study: Mobile and Channel Testing

A small portfolio project showing how I test digital banking channels.

**Live site:** https://YOUR-USERNAME.github.io/qa-case-study/

## What is in it
- `index.html`: QA dashboard with test cases, defect log, device matrix, regression scope, release sign-off and improvement ideas
- `app.html`: demo mobile banking app (the application under test). `?v=1.0` has 4 planted defects, `?v=1.1` has them fixed
- `plan.html`: test plan with scope, approach, environment, entry/exit criteria and risks
- `integration.html`: integration tests between the app and a backend service, outcome matrix, failure investigation report
- `api.html`: 5 API checks against the free JSONPlaceholder practice API
- `style.css`: shared styling

## My process
1. Wrote test cases covering normal use, errors and navigation
2. Executed them on v1.0 and logged defects with severity, priority and steps to reproduce
3. Re-tested fixes and ran the full regression suite on v1.1
4. Validated API status codes and response data
5. Wrote a release sign-off and listed quality improvements

## Scope and limits
Static demo: no real backend, no real money. I kept the build simple so the focus stays on testing. Not covered: performance, security, automation.

## Tools
Manual testing, browser developer tools, Postman (optional), GitHub Pages for hosting.
