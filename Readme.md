# Demo Evershop - Search Functionality Testing

## Overview
This project tests the **search functionality** of the e-commerce platform [Demo Evershop](https://demo.evershop.io/). The test cases focus on various search features such as keyword matching, real-time suggestions, filtering, and multilingual support.

---

## Summary
| **Project ID**           | Ostad101                         |
|--------------------------|-----------------------------------|
| **Tester**               | Md. Tahsin Islam Molla           |
| **Test Case Preparation Date** | 30 January 2025             |
| **Version**              | 0.01                             |
| **Website**              | [https://demo.evershop.io/](https://demo.evershop.io/) |
| **Test Scenario**        | Search functionality             |
| **Total Test Cases**     | 28                               |
| **Passed**               | 12                               |
| **Failed**               | 11                               |
| **Not Implemented**      | 5                                |

---

## Key Observations
- **Passed**: Core functionalities like keyword search, partial matches, and special characters worked as expected.
- **Failed**: Issues identified in fuzzy search, synonym recognition, category-based searches, and specialized queries (e.g., SKU, barcode).
- **Not Implemented**: Features like voice search, image search, and multilingual support remain untested.

---

## Defects Identified
1. **Search**: Typos like "Nike Aor" fail to return results.
2. **Synonym Recognition**: Synonyms like "trainers" do not match "sneakers."
3. **SKU/Barcode Search**: Queries by SKU or barcode return no results.
4. **Multilingual Support**: Non-English terms like "Zapatillas" fail.
5. **Category-Based Search**: Searching for "Running Shoes" returns no results.

---

## Test Environment
- **Scenario**: Search functionality
- **Devices**: Mobile and Desktop
- **Browsers**: Major browsers assumed (Chrome, Firefox, Edge)

---

## Contributors
- **Tester**: Md. Tahsin Islam Molla  

---

## Version
- **Version**: 0.01  
- **Test Case Preparation Date**: 30 January 2025  

For further details, contact Md. Tahsin Islam Molla.
