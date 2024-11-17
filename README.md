// SPDX-License-Identifier: MIT
pragma solidity ^0.8.19;

contract CustomGreeting {
    string public greeting = "Welcome to the Blockchain!";

    function setGreeting(string memory _newGreeting) public {
        greeting = _newGreeting;
    }

    function resetGreeting() public {
        greeting = "Welcome to the Blockchain!";
    }
}
