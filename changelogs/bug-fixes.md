### 2024-02-02
 insert or update on table "invoice_item" violates foreign key constraint "invoice_item_invoice_id_fkey" (053f419)

 Quote digital to stable coin rate fix, add quote test (30eea9b)

 quoting at payment request phase not invoicing phase (3e2434c)

 let customer with canceled or expired subscription pay again (d9977d5)

 insert or update on table "invoice_item" violates foreign key constraint "invoice_item_invoice_id_fkey" (053f419)
legacyList dupe txn join and dupe settlement acct join (01f82fc)
missing transaction join on subscription plans (3a51e97)
Quote digital to stable coin rate fix, add quote test (30eea9b)
quoting at payment request phase not invoicing phase (3e2434c)

add loading spinner when balances for selected network is loading (1b6a20f)
add missing wallet address (ee9030e)
autofocus on full name field on launch (0df4c06)
balances sort for pay with wallet token select (8f6b908)
ci: add healthcheck endpoint (0579c12)
ci: add healthcheck endpoint (#8) (ed7a615)
continue polling until transactions are received (2190bd6)
disable hover color when button is loading (90ce893)
docker image failing prettier linting (#18) (ceb1f2e)
error handling around failed receipt generation (86ddf4f)
fix balance sorting when multiple non-zero balances (066ac69)
fix duplicate handling of partial payments (2a9f5fa)
fix early message when tx hash not picked up in block yet (a4725f4)
fix footer padding on small screens (3d7e4e6)
fix health-check endpoint in wrong place, bump next version (#11) (596a536)
fix invalid svg properties (d0c1515)
fix NaN balance when failed to fetch balances (0f6a6ec)
fix race condition overwriting payment_id (4161cc9)

Transaction query for when plan_id is passed (#730) (6d80086)

### 2024-02-03
use DisplayID() (077f773)

### 2024-02-06
cust portal legacy list (5ef1345)
Subscription cancellation/ new customer portal payments API FE update (#797)
Update customer portal payments to return missing fields (#733) (5339b1e)

### 2024-02-07
cust portal legacy list (5ef1345)
Transaction query for when plan_id is passed (#730) (6d80086)
Update customer portal payments to return missing fields (#733) (5339b1e)
use DisplayID() (077f773)
fix linting, import order (9bcf789)


### 2024-02-08
pfa payment txn [BOOM-1045] (#714) (4d3fc6a)
handle settlement err bug (#800) (f72b685)

handle settlement err bug (#800) (f72b685)

### 2024-02-09
handle settlement page error (#802) (19615b2)
handle settlement page error (#802) (19615b2)
Add back checkout page for redirection to v2 checkout (#803) (7740d5e)

### 2024-02-12
race between invoice and invoice payment workflow signalling (04e139f)
Fix loading currency balance for payout + omit Solana and Tron from list (#804) (96a1d90)

### 2024-02-13
customer auth cleanup (#737) (dea0f06)

### 2024-02-14
subscription active not dispatching slack event [BUG-7] (#738) (eb3e905)
non-retryable fail payment for insufficient fund [BUG-6] (#739) (01e1e3c)

### 2024-02-15
customer auth cleanup (#737) (dea0f06)
fix linting, import order (9bcf789)
non-retryable fail payment for insufficient fund [BUG-6] (#739) (01e1e3c)
pfa payment txn [BOOM-1045] (#714) (4d3fc6a)
race between invoice and invoice payment workflow signalling (04e139f)
subscription active not dispatching slack event [BUG-7] (#738) (eb3e905)

Add back checkout page for redirection to v2 checkout (#803) (7740d5e)
Fix loading currency balance for payout + omit Solana and Tron from list (#804)

MerchantContract payment dealing with Token allowance insufficient error (016e449)

MerchantContract payment dealing with Token allowance insufficient error (016e449)

invoice payment child workflow while loop refactor (5bef8ee)

billing:​ subscription in pending when initial payment required (8fb3602)

​billing:​ subscription in pending when initial payment required (8fb3602)
invoice payment child workflow while loop refactor (5bef8ee)

### 2024-02-16
transaction not included when no enabled org_settlemtn_account [BUG-10] (#743) (9feffce)
transaction not included when no enabled org_settlemtn_account [BUG-10] (#743)
native eth gas limit (#744) (b0bb3f4)
native eth gas limit (#744) (12786fb)
various card payment feedback changes (#99) (92e71d5)