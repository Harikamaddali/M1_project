
# Test Plan



## Tableno:High level Test Plan
| Teat ID | Description                                        | Expected output | Actual output | Pass/fail(Result) |
|---------|----------------------------------------------------|-----------------|---------------|-------------------|
| H_01    | Check if the new contact is created or not         | SUCCESS         | SUCCESS       | PASS              |
| H_02    | Check if the contact information is updated or not | SUCCESS         | SUCCESS       | PASS              |
| H_03    | Check if the contact is modified                   | SUCCESS         | SUCCESS       | PASS              |
| H_04    | Check if the contact is saved                      | SUCCESS         | SUCCESS       | PASS              |
| H_05    | Check  if the contact is saved                     | SUCCESS         | SUCCESS       | PASS              |

## Table no:Low level Test Plan
| ID   | Description                                                              | Exp IN                     | Exp OUT             | Actual Out          |
|------|--------------------------------------------------------------------------|----------------------------|---------------------|---------------------|
| L-01 | During the contact saving check if contact is unique in that application | Name                       | SUCCESS             | SUCESS              |
| L_02 | During saving if name alrady exists, do not allow for saving             | Name and other             | NAME_ALREADY EXISTS | NAME_ALREADY EXISTS |
| L-03 | Check if contact is properly saved                                       | Name and other information | SUCCESS             | SUCCESS             |
| L_04 | If data is collected from file during when the user needed               | contact file               | SUCCESS             | SUCCESS             |
| L_05 | If the contact is removed then delete                                    | contact                    | SUCCESS             | SUCCESS             |
