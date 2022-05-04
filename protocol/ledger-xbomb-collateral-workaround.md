# Ledger, xBOMB Collateral workaround

A few of our users have experienced problems when trying to deposit xBOMB as collateral into our [busm.money](https://busm.money) protocol when using a Ledger device.

Please follow the steps below to manually fix this problem! (Until a long term fix has been applied).

* Head to [this link](https://bscscan.com/address/0x66a5224a941bc56dccdaf6c37f29f3e4bcb8f9eb).
* Select "**Contract**".

![](<../.gitbook/assets/Annotation 2022-05-04 181705.png>)

* Select "**Write Contract**".

![](<../.gitbook/assets/Annotation 2022-05-04 181814.png>)

* Click "**Connect to Web3**". (_Connect with your Ledger)._

![](<../.gitbook/assets/Annotation 2022-05-04 181908.png>)

* Once connected, scroll down to section "**10. SetMasterContractApproval**".
* Enter the following information;
* user - **enter your Ledger address here**
* masterContract - **0x070430D1C765623C46C66c06A8164bB29705fF7F**
* approved - **true**
* v - **0**
* r - **0x**
* s - **0x**

![](<../.gitbook/assets/Annotation 2022-05-04 182906.png>)

* After you have filled in the information correctly, click "**Write**" and confirm the MetaMask transaction.

Once these steps have been completed, you can head back over to [busm.money](https://busm.money) and deposit your xBOMB as collateral, problem solved!

