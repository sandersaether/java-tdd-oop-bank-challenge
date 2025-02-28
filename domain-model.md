```
As a customer,
So I can safely store and use my money,
I want to create a current account.

As a customer,
So I can save for a rainy day,
I want to create a savings account.

As a customer,
So I can keep a record of my finances,
I want to generate bank statements with transaction dates, amounts, and balance at the time of transaction.

As a customer,
So I can use my account,
I want to deposit and withdraw funds.


```


| Classes        | Methods                             | Scenario                     | Returns                              |
|----------------|-------------------------------------|------------------------------|--------------------------------------|
| Account        | String deposit(int amount)          | want to deposit money.       | amount deposited and current balance |
| CurrentAccount | String withdraw(int amount)         | want to withdraw             | amount withdrawn and current balance |
| SavingsAccount | void createAccount(Account account) | want to create a new account | creates new account                  |
| Customer       | String bankStatement()              | want to see bank statement   | list out bank history and balance    |
| Transactions   |                                     |                              |                                      |

```
As a bank manager,
So I can expand,
I want accounts to be associated with specific branches.

As a customer,
So I have an emergency fund,
I want to be able to request an overdraft on my account.

As a bank manager,
So I can safeguard our funds,
I want to approve or reject overdraft requests.


```

| Classes          | Methods   | Scenario             | Output                         |
|------------------|-----------|----------------------|--------------------------------|
| RequestOverDraft | approve() | bankmanager approves | edit limit to requested amount |
|                  | reject()  | bankmanage rejects   | limit stays the same           |
|                  |           |                      |                                |
|                  |           |                      |                                |
