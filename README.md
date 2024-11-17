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
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.19;

contract PersonalizedGreeting {
    string public welcomeMessage = "Hello, Blockchain Enthusiasts!";

    function updateGreeting(string memory _newMessage) public {
        welcomeMessage = _newMessage;
    }

    function getGreeting() public view returns (string memory) {
        return welcomeMessage;
    }

    function resetGreeting() public {
        welcomeMessage = "Hello, Blockchain Enthusiasts!";
    }
}
