# Blockchain-based-Crowdfunding-Platform

**This program is a SMART CONTRACT wriiten in Solidity language using Remix IDE**

Initially using constructor the owner addres, deadline, target, and minimum contribution to be done by contributor is saved in state variable.

The contributor contributes using contribute() function in crowd funding. If the deadline is not over and the funds are meeting the minimum requirements then the address and value is stored in state variable mapping.

If the target is not met and contributor wants the refund then he can refund the money by using refund() function.

The owner can request the all contributors to withdraw the funds by uing createRequest() function and tell the description, address to which the funds will be sent, and the total funds which to be sent.

All the contributors vote using voteRequest() function and if the votes are more than the 50% of contributors then using the makePayment() function the money is sent to the perticular address which owner has provided.

