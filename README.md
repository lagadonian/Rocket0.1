# Rocket0.1
a hodler's tontine

New members can buy shares in the tontine by depositing ether during the enrollment period. They are free to withdraw their funds in full until the end of the enrollment period. No deposits are allowed after the end of the enrollment period. After enrollment and prior to expiration, withdrawing members are paid out 80% of their share, leaving the remaining 20% to the surviving members. Individual members' shares grow as other members leave and pay penalties -- in some cases, early withdrawal is profitable, even minus the 20% penalty. After expiration, withdrawals can be made at any time and are paid out in full.   

May the strongest hands win. 


Notes on the contract: 

enrollment_end: seconds after launch to end the enrollment period. Measured from the UNIX timestamp of the Ethereum block in which the contact is deployed. 
expiration: seconds after launch to end the withdrawal penalty period.
