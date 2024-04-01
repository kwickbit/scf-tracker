# scf tracker: Kwickbit SCF#20 Submission
Public repository to track the progress and deliverables of KwickBit through SCF grants, providing transparency and community engagement.

Check the submission [here](https://communityfund.stellar.org/projects/soroswap-protocol-scf-14)

- Total expected: 400
- Total completed (%): 100%


# Deliverables:

# Deliverable 1: Indexer on Stellar/Soroban (open-source)

Repository: [mercury-sdk](https://github.com/paltalabs/mercury-sdk)

___
### ✅ Deliverable 1.1
**Description:** review, test case indexers subquery and mercury to choose the most fit for us.

**Reviewer Instructions:** Reviewer will visit our docs on how to setup and interact with both indexers.

**Result:** [docs](https://docs.soroswap.finance/04-partners/01-mercury-subquery)
___

### ✅ Deliverable 1.2
**Description:** Set-up indexer node.

**Reviewer Instructions:** Reviewer can make http requests to the indexer.
Reviewer should visit docs section with quick examples of http requests.

**Result:** [mercury-sdk](https://github.com/paltalabs/mercury-sdk#instantiate)
___
### ✅ Deliverable  1.3

**Description:** Implement transactions identification algorithms.

**Reviewer Instructions:** Reviewer can make requests to the indexer and check labels on transactions.
Reviewer should visit docs section with quick examples of requests with returned data and labels. 

**Result:** [mercury-sdk](https://github.com/paltalabs/mercury-sdk#parse-data-results)
___


# Deliverable 2: Transaction identification algorithm (open-source)


### ✅Deliverable 2.1

**Description:** Choose the 7 most common DeFi transactions.

**Reviewer Instructions:** Reviewer should visit docs section.

**Result:**  [mercury-client](https://github.com/paltalabs/mercury-client#run-scripts)

___
### ✅ Deliverable 2.2
**Description:** Define and implement how these transactions should be identified (events?, which protocol standards?, Stellar Classic DEX, path payments, etc…)

**Reviewer Instructions:** Reviewer should visit the repository and the docs page with examples on how the implemented algorithms are invoked.

**Result:** [mercury-sdk](https://github.com/paltalabs/mercury-sdk#retrieve-information)

___
### ✅ Deliverable 2.3
**Description:** Implement how these transactions should be identified (events?, which protocol standards?, Stellar Classic DEX, path payments, etc…)

**Reviewer Instructions:** Reviewer should visit the repository and the docs page with examples on how the implemented algorithms are invoked.

**Result:** [mercury-sdk](https://github.com/paltalabs/mercury-sdk#parse-data-results)

___
### ✅ Deliverable  2.4

**Description:** Write an article about the chosen 7 DeFi transactions.

**Reviewer Instructions:** Reviewer should visit the docs page for the article.

**Result:** [article](https://dev.to/soroswap/7-common-transactions-on-stellar-and-soroban-to-explore-using-mercury-and-how-to-retrieve-them-51ab)

___

# Deliverable 3: Frontend (open-source)
Repository: [kwickbit_frontend_v0](https://github.com/kwickbit/kwickbit_frontend_v0)

___
### ✅ Deliverable 3.1

**Description:** Users can signup and login on the page.

**Reviewer Instructions:** Reviewer can visit the frontend page and signup/login on the page.

**Result:**
1. ✅ User signup/login can be tested at [KwickBit App](https://app.dev.host.kwickbit.com/)
2. ✅ Check tickets [ticket 3](https://github.com/kwickbit/kwickbit_frontend_v0/issues/3) and [ticket 4](https://github.com/kwickbit/kwickbit_frontend_v0/issues/4).


___
### ✅ Deliverable 3.2

**Description:** Users can copy paste or connect their freighter wallet.

**Reviewer Instructions:** Reviewer can add his wallet address from.

**Result:**
1. ✅ Reviewer can add his wallet address at [KwickBit App Source page](https://app.dev.host.kwickbit.com/sources)
2. ✅ Check tickets [ticket 6](https://github.com/kwickbit/kwickbit_frontend_v0/issues/6), [ticket 7](https://github.com/kwickbit/kwickbit_frontend_v0/issues/7), [ticket 8](https://github.com/kwickbit/kwickbit_frontend_v0/issues/8), [ticket 9](https://github.com/kwickbit/kwickbit_frontend_v0/issues/9).


___
### ✅ Deliverable 3.3

**Description:** Users can see their on-chain transactions.

**Reviewer Instructions:** Reviewer can see on-chain transactions from the app.

**Result:** In Progress

UI to display transactions implemented with mock data for now.

1. ✅ Reviewer can see transactions at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions)
2. ✅ Check tickets [ticket 16](https://github.com/kwickbit/kwickbit_frontend_v0/issues/19) and [ticket 19](https://github.com/kwickbit/kwickbit_frontend_v0/issues/16)

___
### ✅ Deliverable 3.4

**Description:** Users can connect their QuickBooks account using oauth2.

**Reviewer Instructions:** Reviewer can connect his/her QuickBooks account within the app.

**Result:**
1. ✅ Reviewer can connect his/her QuickBooks account at [KwickBit App Integration page](https://app.dev.host.kwickbit.com/integrations)
2. ✅ Check tickets [ticket 12](https://github.com/kwickbit/kwickbit_frontend_v0/issues/12) and [ticket 13](https://github.com/kwickbit/kwickbit_frontend_v0/issues/13)


___
### ✅ Deliverable 3.5

**Description:** Users can fetch their chart of accounts from QuickBooks.

**Reviewer Instructions:** Reviewer can visualize his/her chart of accounts from QuickBooks when trying to publish
a transaction to QuickBooks.

**Result:** In Progress

UI to display chart of accounts implemented with mock data for now.

1. ✅ Reviewer can see chart of accounts when checking single transaction view to push QuickBooks at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions)
2. ✅ Check tickets [ticket 19](https://github.com/kwickbit/kwickbit_frontend_v0/issues/19)


___
### ✅ Deliverable 3.6

**Description:** Users can fetch their invoices/bills from QuickBooks.

**Reviewer Instructions:** Reviewer can visualize his/her invoices/bills from QuickBooks when trying to publish
a transaction to QuickBooks.

**Result:** In Progress

UI to display chart of invoices/bills implemented with mock data for now.

1. ✅ Reviewer can see invoices/bills when checking single transaction view to push QuickBooks at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions)
2. ✅ Check tickets [ticket 19](https://github.com/kwickbit/kwickbit_frontend_v0/issues/19)



___
### ✅ Deliverable 3.7

**Description:** Users can set mapping of non-native tokens and lumens their to QuickBooks currencies.

**Reviewer Instructions:** Reviewer can set mappings from the app.

**Result:** In Progress

1. ✅ Reviewer can set mapping token/crypto-currency by clicking 'Settings' button in QuickBooks card
at [KwickBit App Integrations page](https://app.dev.host.kwickbit.com/integrations) (reviewer must have connected
his/her QuickBooks account)


___
### ✅ Deliverable 3.8

**Description:** Users can publish their transactions to Quickbooks from the app.

**Reviewer Instructions:** Reviewer can push his/her transaction to QuickBooks accounts/ledgers.

**Result:**
1. ✅ Reviewer can publish transaction to QuickBooks by clicking 'View' button in
at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions)
and then choose type of transaction:
- Income or Invoice with corresponding Account or Invoice reference for incoming transactions
- Expense of Bill with corresponding Item or Bill reference for outgoing transaction.
- Swap for swap transactions.
(reviewer must have connected his/her QuickBooks account)



## Deliverable 4: Backend
___
### ✅ Deliverable 4.1

**Description:** API to signup/login/refresh-token with authentication required.

**Reviewer Instructions:** Reviewer can visit the frontend page and signup/login on the page.
Reviewer can be given access to backend repo.

**Result:**
1. ✅ User signup/login can be tested at [KwickBit App](https://app.dev.host.kwickbit.com/) 
2. ✅ Reviewer can inspect backend repository after requesting access.

___
### ✅ Deliverable 4.2

**Description:** Implement queue system to publish jobs to fetch transactions on the blockchain.

**Reviewer Instructions:** Reviewer can trigger job by clicking job on the frontend app and check on backend queue system that
the job is in the queue.
Reviewer can be given access to backend repo.

**Result:**
1. ✅ User can trigger job at [KwickBit App Sources Page](https://app.dev.host.kwickbit.com/sources) and be given access to queue backend to verify the job is there.
2. ✅ Reviewer can inspect backend repository after requesting access.

___

___
### ✅ Deliverable 4.3

**Description:** Implement API to request and save wallet sources with address on database..

**Reviewer Instructions:** Reviewer can add wallet from frontend app. Reviewer can see current wallets
from frontend UI.
Reviewer can be given access to backend repo.

**Result:**
1. ✅ Reviewer can add his wallet address at [KwickBit App Source page](https://app.dev.host.kwickbit.com/sources)
2. ✅ Reviewer can see his added wallets address at [KwickBit App Source page](https://app.dev.host.kwickbit.com/sources)
3. ✅ Reviewer can inspect backend repository after requesting access.


___
### ✅ Deliverable 4.4

**Description:** Implement callable job to fetch transactions on the blockchain and save them on database.


**Reviewer Instructions:** Reviewer can click fetch his/her on-chain transactions and be given access to backend database to check that transactions are there.
Reviewer can be given access to backend repo.


**Result:**
1. ✅ Started implementing library [mercury-sdk](https://github.com/paltalabs/mercury-sdk) with [Palta Labs 🥑](https://github.com/paltalabs)
2. ✅ Reviewer can trigger "fetch transactions" at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions) which will fetch on-chain transactions and save them to backend database.
Reviewer can be given backend access to check transactions are in database.
3. ✅ Started using Now Nodes for first time of a specific wallet address because indexer can only fetch transactions
with createdAt after subscription time. Previous transactions must be fetched using node.


___
### ✅ Deliverable 4.5

**Description:** Implement API to request transactions saved on database.

**Reviewer Instructions:** Reviewer can see on-chain transactions from frontend UI.
Reviewer can also be given access to backend repo.

**Result:**
1. ✅ Reviewer can request us to write simple code with API call on frontend side.

___
### ✅ Deliverable 4.6

**Description:** Implement Websocket to enable notifications regarding fetching transactions, invoices, bills, ledgers.

**Reviewer Instructions:** Reviewer can click fetch on-chain transactions.
Once the backend fetching job is done, user should see new transactions appear on the UI section.
Reviewer can be given access to backend repo.


**Result:**
1. ✅ Notification system working with console.log.


___
### ✅ Deliverable 4.7

**Description:** Implement callable job to fetch invoices/bills from QuickBooks and save them to database.


**Reviewer Instructions:** Reviewer can click fetch invoices and bills and be given access to backend database to check that invoices/bills are there.
Reviewer can be given access to backend repo.

1. ✅ Reviewer can trigger "fetch invoices/bills" at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions) which will fetch on-chain transactions and save them to backend database.
Reviewer can be given backend access to check invoices/bills are in database.

___
### ✅ Deliverable 4.8

**Description:** Implement API to request invoices/bills saved on database.

**Reviewer Instructions:** Reviewer can see invoices/bills from frontend UI.
Reviewer can also be given access to backend repo.

**Result:**
1. ✅ Reviewer can request us to write simple code with API call on frontend side.


___
### ✅ Deliverable 4.9

**Description:** Implement callable job to fetch ledger references from QuickBooks and save them to database.


**Reviewer Instructions:** Reviewer can click fetch ledger references and be given access to backend database to check that ledger references are there.
Reviewer can be given access to backend repo.

**Result:**
1. ✅ Reviewer can trigger "fetch ledgers" at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions) which will fetch on-chain transactions and save them to backend database.
Reviewer can be given backend access to check invoices/bills are in database.


___
### ✅ Deliverable 4.10

**Description:** Implement API to request ledger references saved on database.

**Reviewer Instructions:** Reviewer can see ledger references from frontend UI.
Reviewer can also be given access to backend repo.

**Result:**
1. ✅ Reviewer can request us to write simple code with API call on frontend side.

___
### ✅ Deliverable 4.11

**Description:** Implement callable job to publish transaction (whether using invoice, bill or ledger reference) from QuickBooks and save status to database.


**Reviewer Instructions:** Reviewer can click publish and check on his QuickBooks account that transactions are there.
Reviewer can be given access to backend repo.

**Result:**
1. ✅ Reviewer can publish transaction to QuickBooks by clicking 'View' button in
   at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions)
   and then choose type of transaction:
- Income or Invoice with corresponding Account or Invoice reference for incoming transactions
- Expense of Bill with corresponding Item or Bill reference for outgoing transaction.
- Swap for swap transactions.
  (reviewer must have connected his/her QuickBooks account)

___
### ✅ Deliverable 4.12

**Description:** Implement job to analyze non-native tokens that are not mapped to a QuickBooks currency, save them and notify them.


**Reviewer Instructions:** Reviewer can use a wallet address that contains a non-native token that is not mapped to a QuickBooks currency and be given access to backend database.
Reviewer can be given access to backend repo.

**Result:**
1. ✅ Reviewer can request us to write simple code with API call on frontend side.

___
### ✅ Deliverable 4.13

**Description:** API to request non mapped tokens yet saved on database.


**Reviewer Instructions:** Reviewer can use a wallet address that contains a non-native token that is not mapped to a QuickBooks currency and see warning banner from frontend UI.
Reviewer can be given access to backend repo.

**Result:**
1. ✅ Reviewer can request us to write simple code with API call on frontend side.

___
### ✅ Deliverable 4.14

**Description:** Add QuickBooks transactions integrations information on transactions.

**Reviewer Instructions:** Reviewer can see which (and where) transactions have been published to QuickBooks from UI.
Reviewer can also be given access to backend repo.

**Result:**
1. ✅ Reviewer can see transaction's status for a specific transaction by clicking 'View' button in
   at [KwickBit App Transactions page](https://app.dev.host.kwickbit.com/transactions).