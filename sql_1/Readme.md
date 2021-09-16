# DBM - Database management Systems - Task 1

## The Task
- Using SQL create a database that maintains the following:

### Users Table
<table>
  <tr>
    <td>ID PK</td>
    <td>Name U</td>
    <td>Credit Score</td>
    <td>Date of updation</td>
  </tr>
    <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

### Accounts Table
<table>
  <tr>
    <td>Account Number PK</td>
    <td>UserId FK->(Users)ID U</td>
    <td>Balance</td>
    <td>Date of updation</td>
  </tr>
    </tr>
    <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

### Balance sheet
<table>
  <tr>
    <td>ID PK</td>
    <td>Action U</td>
    <td>Account Number FK->(Accounts)AccountNumber</td>
    <td>Date of updation</td>
  </tr>
    </tr>
    <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

### Secondary Task
- Populate the Database and create Queries which gets the total balance using balance sheet.
- Get Name of top 10 customers by networth and credit limit:
  - Priority of customer given by:
    - Credit limit > 600 && Balance
    - If Credit limit < 600: Balance does not matter.
- _Time Limit: 60 Mins_
    
