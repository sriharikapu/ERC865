
### SampleERC865Token

**Functions**

* * *

###### name - view

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>string</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### approve - read

Approve the passed address to spend the specified amount of tokens on behalf of msg.sender. * Beware that changing an allowance with this method brings the risk that someone may use both the old and the new allowance by unfortunate transaction ordering. One possible solution to mitigate this race condition is to first reduce the spender's allowance to 0 and set the desired value afterwards: https://github.com/ethereum/EIPs/issues/20#issuecomment-263524729

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_spender</td>

<td>address</td>

<td>The address which will spend the funds.</td>

</tr>

<tr>

<td>_value</td>

<td>uint256</td>

<td>The amount of tokens to be spent.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### transferPreSigned - read

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_signature</td>

<td>bytes</td>

<td>bytes The signature, issued by the owner.</td>

</tr>

<tr>

<td>_to</td>

<td>address</td>

<td>address The address which you want to transfer to.</td>

</tr>

<tr>

<td>_value</td>

<td>uint256</td>

<td>uint256 The amount of tokens to be transferred.</td>

</tr>

<tr>

<td>_fee</td>

<td>uint256</td>

<td>uint256 The amount of tokens paid to msg.sender, by the owner.</td>

</tr>

<tr>

<td>_nonce</td>

<td>uint256</td>

<td>uint256 Presigned transaction number.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### transferFromContract - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### totalSupply - view

total number of tokens in existence

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### recover - view

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>hash</td>

<td>bytes32</td>

<td>bytes32 message, the hash is the signed message. What is recovered is the signer address.</td>

</tr>

<tr>

<td>sig</td>

<td>bytes</td>

<td>bytes signature, the signature is generated using web3.eth.sign()</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### transferFrom - read

Transfer tokens from one address to another

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_from</td>

<td>address</td>

<td>address The address which you want to send tokens from</td>

</tr>

<tr>

<td>_to</td>

<td>address</td>

<td>address The address which you want to transfer to</td>

</tr>

<tr>

<td>_value</td>

<td>uint256</td>

<td>uint256 the amount of tokens to be transferred</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### getNonce - view

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_owner</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>nonce</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### decimals - view

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint8</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### approvePreSigned - read

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_signature</td>

<td>bytes</td>

<td>bytes The signature, issued by the owner.</td>

</tr>

<tr>

<td>_spender</td>

<td>address</td>

<td>address The address which will spend the funds.</td>

</tr>

<tr>

<td>_value</td>

<td>uint256</td>

<td>uint256 The amount of tokens to allow.</td>

</tr>

<tr>

<td>_fee</td>

<td>uint256</td>

<td>uint256 The amount of tokens paid to msg.sender, by the owner.</td>

</tr>

<tr>

<td>_nonce</td>

<td>uint256</td>

<td>uint256 Presigned transaction number.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### decreaseApproval - read

Decrease the amount of tokens that an owner allowed to a spender. * approve should be called when allowed[_spender] == 0\. To decrement allowed value is better to use this function to avoid 2 calls (and wait until the first transaction is mined) From MonolithDAO Token.sol

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_spender</td>

<td>address</td>

<td>The address which will spend the funds.</td>

</tr>

<tr>

<td>_subtractedValue</td>

<td>uint256</td>

<td>The amount of tokens to decrease the allowance by.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### balanceOf - view

Gets the balance of the specified address.

Return : An uint256 representing the amount owned by the passed address.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_owner</td>

<td>address</td>

<td>The address to query the the balance of.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### decreaseApprovalPreSigned - read

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_signature</td>

<td>bytes</td>

<td>bytes The signature, issued by the owner</td>

</tr>

<tr>

<td>_spender</td>

<td>address</td>

<td>address The address which will spend the funds.</td>

</tr>

<tr>

<td>_subtractedValue</td>

<td>uint256</td>

<td>uint256 The amount of tokens to decrease the allowance by.</td>

</tr>

<tr>

<td>_fee</td>

<td>uint256</td>

<td>uint256 The amount of tokens paid to msg.sender, by the owner.</td>

</tr>

<tr>

<td>_nonce</td>

<td>uint256</td>

<td>uint256 Presigned transaction number.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### owner - view

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### symbol - view

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>string</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### transfer - read

transfer token for a specified address

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_to</td>

<td>address</td>

<td>The address to transfer to.</td>

</tr>

<tr>

<td>_value</td>

<td>uint256</td>

<td>The amount to be transferred.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### increaseApprovalPreSigned - read

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_signature</td>

<td>bytes</td>

<td>bytes The signature, issued by the owner.</td>

</tr>

<tr>

<td>_spender</td>

<td>address</td>

<td>address The address which will spend the funds.</td>

</tr>

<tr>

<td>_addedValue</td>

<td>uint256</td>

<td>uint256 The amount of tokens to increase the allowance by.</td>

</tr>

<tr>

<td>_fee</td>

<td>uint256</td>

<td>uint256 The amount of tokens paid to msg.sender, by the owner.</td>

</tr>

<tr>

<td>_nonce</td>

<td>uint256</td>

<td>uint256 Presigned transaction number.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### decimalValue - view

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _value - view

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### increaseApproval - read

Increase the amount of tokens that an owner allowed to a spender. * approve should be called when allowed[_spender] == 0\. To increment allowed value is better to use this function to avoid 2 calls (and wait until the first transaction is mined) From MonolithDAO Token.sol

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_spender</td>

<td>address</td>

<td>The address which will spend the funds.</td>

</tr>

<tr>

<td>_addedValue</td>

<td>uint256</td>

<td>The amount of tokens to increase the allowance by.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### allowance - view

Function to check the amount of tokens that an owner allowed to a spender.

Return : A uint256 specifying the amount of tokens still available for the spender.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_owner</td>

<td>address</td>

<td>address The address which owns the funds.</td>

</tr>

<tr>

<td>_spender</td>

<td>address</td>

<td>address The address which will spend the funds.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### recoverPreSignedHash - view

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_token</td>

<td>address</td>

<td>address The address of the token</td>

</tr>

<tr>

<td>_functionSig</td>

<td>bytes4</td>

<td></td>

</tr>

<tr>

<td>_spender</td>

<td>address</td>

<td>address The address which will spend the funds.</td>

</tr>

<tr>

<td>_value</td>

<td>uint256</td>

<td>uint256 The amount of tokens.</td>

</tr>

<tr>

<td>_fee</td>

<td>uint256</td>

<td>uint256 The amount of tokens paid to msg.sender, by the owner.</td>

</tr>

<tr>

<td>_nonce</td>

<td>uint256</td>

<td>uint256 Presigned transaction number.</td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bytes32</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### transferOwnership - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>newOwner</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

No parameters

* * *

###### constructor - read

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_tokenSupply</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

No parameters

</div>
