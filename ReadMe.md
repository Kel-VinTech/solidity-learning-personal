--getting started--

when creating a contract
you have to first declare the license and state the version of solidity you are using.
 <!-- //SPDX-License-Identifier: MIT

pragma solidity ^0.8.18; -->


when you declare a variable using "public" it creates a variable that allows you to read the value of the variable from outside of the contract.

-external: when we deploy the contract we'll be able to call it 

-pure: it is read only and does not modify the contract's data.

--data types--

solidity has 2 data types which are 1.value types and 2.reference types.

the values data types stored a value like a number or a boolean(stores true or false);

the reference data types store a reference to a value and are more complex data types like arrays and structs.

--uint and int

unit(unsign integers) ranges from 0 to 2^256-1
and it supports values from > 0.

init(integers) supports values from < 0 and > 0.

--state,local and global--

state: stores variable on the blockchain and is written to the blockchain.
they are stored inside a contract but outside a function.

-local: they are stored inside a function and are not written to the blockchain.

-global: they store account that calls a function and the blockchain transaction