# Banking System Test Cases

## Project Summary
- **Test Object**: Guru99 Banking SRS  
- **Scope**: 131 manual test cases (Manager + Customer flows)  
- **User Roles Covered**:
  -  **Manager Functions**:
    - Customer management (Add/Edit/Delete)
    - Account operations
    - Transaction approvals
  -  **Customer Functions**:
    - management (Add/Edit/Delete)
    - Balance enquiries  
    - Fund transfers  
    - Statement generation  


### Manager-Specific Tests
1. New customer onboarding validation
2. Account creation/modification workflows
3. Transaction authorization tests
4. Customer profile management

### Customer-Specific Tests  
1. Login and session security
2. Self-service transactions
3. Account statement access
4. Transfer limit validations

### Shared Functions
1. Authentication workflows
2. Data validation rules
3. Error handling scenarios

## Validation Rules
| Rule | Description | Applies To |
|------|-------------|------------|
| R1 | Required field | All forms |
| R2 | No special chars | IDs, PINs |
| R3 | Numeric only | Accounts, Amounts |
| R4 | Text only | Names, Addresses |
| R5 | No leading spaces | Email, User IDs |

**Test Status**: Designed - Ready for Execution  

**Tester**: Mahmoud Hamdy  
**Date**: May 2025  
