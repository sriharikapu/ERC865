 #ethdoc-viewer{ font-size: 0.8em; padding: 1em; } #ethdoc-viewer .lead{ font-size: 1em; } #ethdoc-viewer table { width: 50%; } #ethdoc-viewer hr { margin: 0; margin-bottom: 0.5rem; } #ethdoc-viewer p{ margin-bottom: 0.5rem; } 

### SampleERC865Token

**Functions**

* * *

###### name - view

**\*\*Add Documentation for the method here\*\***

No parameters

Returns:

Name

Type

Description

string

* * *

###### approve - read

Approve the passed address to spend the specified amount of tokens on behalf of msg.sender. \* Beware that changing an allowance with this method brings the risk that someone may use both the old and the new allowance by unfortunate transaction ordering. One possible solution to mitigate this race condition is to first reduce the spender's allowance to 0 and set the desired value afterwards: https://github.com/ethereum/EIPs/issues/20#issuecomment-263524729

Name

Type

Description

\_spender

address

The address which will spend the funds.

\_value

uint256

The amount of tokens to be spent.

Returns:

Name

Type

Description

bool

* * *

###### transferPreSigned - read

Name

Type

Description

\_signature

bytes

bytes The signature, issued by the owner.

\_to

address

address The address which you want to transfer to.

\_value

uint256

uint256 The amount of tokens to be transferred.

\_fee

uint256

uint256 The amount of tokens paid to msg.sender, by the owner.

\_nonce

uint256

uint256 Presigned transaction number.

Returns:

Name

Type

Description

bool

* * *

###### transferFromContract - read

**\*\*Add Documentation for the method here\*\***

No parameters

Returns:

Name

Type

Description

bool

* * *

###### totalSupply - view

total number of tokens in existence

No parameters

Returns:

Name

Type

Description

uint256

* * *

###### recover - view

Name

Type

Description

hash

bytes32

bytes32 message, the hash is the signed message. What is recovered is the signer address.

sig

bytes

bytes signature, the signature is generated using web3.eth.sign()

Returns:

Name

Type

Description

address

* * *

###### transferFrom - read

Transfer tokens from one address to another

Name

Type

Description

\_from

address

address The address which you want to send tokens from

\_to

address

address The address which you want to transfer to

\_value

uint256

uint256 the amount of tokens to be transferred

Returns:

Name

Type

Description

bool

* * *

###### getNonce - view

**\*\*Add Documentation for the method here\*\***

Name

Type

Description

\_owner

address

Returns:

Name

Type

Description

nonce

uint256

* * *

###### decimals - view

**\*\*Add Documentation for the method here\*\***

No parameters

Returns:

Name

Type

Description

uint8

* * *

###### approvePreSigned - read

Name

Type

Description

\_signature

bytes

bytes The signature, issued by the owner.

\_spender

address

address The address which will spend the funds.

\_value

uint256

uint256 The amount of tokens to allow.

\_fee

uint256

uint256 The amount of tokens paid to msg.sender, by the owner.

\_nonce

uint256

uint256 Presigned transaction number.

Returns:

Name

Type

Description

bool

* * *

###### decreaseApproval - read

Decrease the amount of tokens that an owner allowed to a spender. \* approve should be called when allowed\[\_spender\] == 0. To decrement allowed value is better to use this function to avoid 2 calls (and wait until the first transaction is mined) From MonolithDAO Token.sol

Name

Type

Description

\_spender

address

The address which will spend the funds.

\_subtractedValue

uint256

The amount of tokens to decrease the allowance by.

Returns:

Name

Type

Description

bool

* * *

###### balanceOf - view

Gets the balance of the specified address.

Return : An uint256 representing the amount owned by the passed address.

Name

Type

Description

\_owner

address

The address to query the the balance of.

Returns:

Name

Type

Description

uint256

* * *

###### decreaseApprovalPreSigned - read

Name

Type

Description

\_signature

bytes

bytes The signature, issued by the owner

\_spender

address

address The address which will spend the funds.

\_subtractedValue

uint256

uint256 The amount of tokens to decrease the allowance by.

\_fee

uint256

uint256 The amount of tokens paid to msg.sender, by the owner.

\_nonce

uint256

uint256 Presigned transaction number.

Returns:

Name

Type

Description

bool

* * *

###### owner - view

**\*\*Add Documentation for the method here\*\***

No parameters

Returns:

Name

Type

Description

address

* * *

###### symbol - view

**\*\*Add Documentation for the method here\*\***

No parameters

Returns:

Name

Type

Description

string

* * *

###### transfer - read

transfer token for a specified address

Name

Type

Description

\_to

address

The address to transfer to.

\_value

uint256

The amount to be transferred.

Returns:

Name

Type

Description

bool

* * *

###### increaseApprovalPreSigned - read

Name

Type

Description

\_signature

bytes

bytes The signature, issued by the owner.

\_spender

address

address The address which will spend the funds.

\_addedValue

uint256

uint256 The amount of tokens to increase the allowance by.

\_fee

uint256

uint256 The amount of tokens paid to msg.sender, by the owner.

\_nonce

uint256

uint256 Presigned transaction number.

Returns:

Name

Type

Description

bool

* * *

###### decimalValue - view

**\*\*Add Documentation for the method here\*\***

No parameters

Returns:

Name

Type

Description

uint256

* * *

###### \_value - view

**\*\*Add Documentation for the method here\*\***

No parameters

Returns:

Name

Type

Description

uint256

* * *

###### increaseApproval - read

Increase the amount of tokens that an owner allowed to a spender. \* approve should be called when allowed\[\_spender\] == 0. To increment allowed value is better to use this function to avoid 2 calls (and wait until the first transaction is mined) From MonolithDAO Token.sol

Name

Type

Description

\_spender

address

The address which will spend the funds.

\_addedValue

uint256

The amount of tokens to increase the allowance by.

Returns:

Name

Type

Description

bool

* * *

###### allowance - view

Function to check the amount of tokens that an owner allowed to a spender.

Return : A uint256 specifying the amount of tokens still available for the spender.

Name

Type

Description

\_owner

address

address The address which owns the funds.

\_spender

address

address The address which will spend the funds.

Returns:

Name

Type

Description

uint256

* * *

###### recoverPreSignedHash - view

Name

Type

Description

\_token

address

address The address of the token

\_functionSig

bytes4

\_spender

address

address The address which will spend the funds.

\_value

uint256

uint256 The amount of tokens.

\_fee

uint256

uint256 The amount of tokens paid to msg.sender, by the owner.

\_nonce

uint256

uint256 Presigned transaction number.

Returns:

Name

Type

Description

bytes32

* * *

###### transferOwnership - read

**\*\*Add Documentation for the method here\*\***

Name

Type

Description

newOwner

address

Returns:

No parameters

* * *

###### constructor - read

Name

Type

Description

\_tokenSupply

uint256

Returns:

No parameters
