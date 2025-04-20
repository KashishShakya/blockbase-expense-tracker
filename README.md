# BlockBaseProject
<hr>
<h3>Features Added:</h3>
<li>
 Check if a user is registered.
</li>
<li>
  Showing number of users registered on the same contract.
</li>
<hr>
<h3>Code Changes:</h3>
<h4>In BlockBase.sol</h4>
 Added function `isRegistered(address)` to check if a wallet is registered.
<br>
<h4>In App.js</h4>
 The number of users is fetched using the smart contract’s `getAllRegisteredPeople()` function.<br>
Updated Contract Address in line 21.
