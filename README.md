# Project Overview

This project demonstrates a comprehensive manual testing lifecycle for
the Swag Labs (SauceDemo) e-commerce application.

The objective was to validate core functionalities including:

-   Login
-   Product Management
-   Shopping Cart
-   Checkout Process

Testing was performed using various user personas to ensure functional
accuracy and data integrity.

------------------------------------------------------------------------

## Key Highlights

### Persona-Based Testing

Identified critical regressions specific to: - problem_user -
error_user - visual_user

### Critical Bug Discovery

Identified **3 Critical defects** in the checkout flow: - Add to Cart
failure - Last Name field issue - Finish button failure

These defects prevented successful purchases.

### Data Integrity Issues

Uncovered pricing inconsistencies between product listings and the
shopping cart.

### Agile Migration

Successfully migrated the test suite from Excel-based documentation to
Zephyr Scale for Jira, establishing a professional test management
ecosystem with: - Real-time tracking - End-to-end traceability

------------------------------------------------------------------------

## Tools Used

### Documentation

-   Microsoft Excel / CSV
-   Microsoft Word

### Test Management

-   Jira Software
-   Zephyr Scale

### Technical Analysis

-   Chrome DevTools
    -   Console logs
    -   Network logs (Root cause analysis)

------------------------------------------------------------------------

## Project Structure

    ├── Documentation
    │   ├── Test Plan (PDF/Docx)
    │   ├── Test Summary Report (PDF/Docx)
    │
    ├── Test-Assets
    │   ├── Test Cases (Excel/PDF) – 55+ detailed test cases
    │   ├── Bug Reports (Excel) – Severity/Priority rankings
    │   ├── Traceability Matrix (RTM)
    │
    ├── Screenshots
    │   ├── Bug_Evidence – Browser console errors (CORS/POST failures)
    │   ├── Project_Metrics – Zephyr pie charts & Jira Burndown charts

------------------------------------------------------------------------

## Summary of Results

| Metric                      | Value |
|-----------------------------|-------|
| Total Tests Executed        | 55    |
| Tests Passed                | 36    |
| Tests Failed                | 19    |
| Critical Defects Identified | 3     |

------------------------------------------------------------------------

## Agile Execution

### Sprint Management

-   Sprint 1: 30 Story Points
-   Sprint 2: 45 Story Points

### Metrics

-   Burndown Chart analysis
-   Defect linking to user stories in Jira

------------------------------------------------------------------------

## Project Timeline

This project followed a structured **two-month lifecycle**:

### December & January

-   Test Case Design
-   Offline Execution using Excel
-   Maintained master record of behaviors across four user personas

### February

-   Migrated project to Jira & Zephyr Scale
-   Managed Sprints
-   Generated automated QA metrics
