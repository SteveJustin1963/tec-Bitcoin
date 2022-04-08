# tec-Bitcoin
tec-1 bitcoin mining


http://www.righto.com/2014/09/mining-bitcoin-with-pencil-and-paper.html

if it can be done by hand then the z80 can too.

actually stupid, better make a tec-1-coin and use it among tec-1 members
use tec-1 to handle the blocks

https://lifehacker.com/how-to-create-your-own-cryptocurrency-1825337462

## sudo code
- take previous financial operation (new purchase history etc.)
- Concatanate hash of previous block in the chain
- add a integer (Lets call it :A), First time round, :A = 0, 
- Concatante :A at the end, Hash through an alorigthm (MD5, SHA1 etc)
- check if output meets a certain condition (Like having 3 0's at the end)
- If does not meet condition, Imcrement :A (:A += 1) and goto 18
- When the condition is met, organise the block, this is done by:
- Combine the financial record with the integer and this with the hash
- Add this block onto the chain
- Update this copy of the block chain to all users of the network
- Your done! be sure to repeat this operation as fast as possible to prevent counterfeit of your currency

- every now and then, verify the blockchain, by hashing the part containing the financal record and number (:A) to make sure it has not been tampered with and review the financial history to make sure everyones balances is correct
