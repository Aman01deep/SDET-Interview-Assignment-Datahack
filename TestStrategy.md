# Test Strategy Document

## Overview
The Datahack - Loan Prediction III page allows users to participate in a data science competition. It provides details about the problem, dataset, evaluation metric, and leaderboard.

## Scope of Testing
**In-Scope:**
- UI functionality
- Links and navigation
- Responsiveness
- Form submissions
- Accessibility

**Out-of-Scope:**
- Server-side validation
- Internal APIs or DB validation

## Assumptions
- No access to backend or APIs
- Only black-box UI and external behavior is testable

## Types of Testing
- Functional Testing
- UI/UX Testing
- Compatibility & Responsive Testing
- Negative Testing
- Accessibility Testing (basic WCAG checks)
- Performance (basic load check via Lighthouse)
- Security (surface-level checks like HTTPS)

## Test Environments
- Chrome, Firefox, Edge (Windows)
- Safari (macOS)
- Mobile browsers (Android, iOS)

## Tools
- Manual: Chrome DevTools, Lighthouse
- Automation: Selenium + Java (UI), pytest + requests (API)

