# Counter.sol
Counter.sol4
pragma solidity ^0.8.20;

contract Counter {
    uint public count;

    function increment() public {
        count += 1;
    }

    function decrement() public {
        count -= 1;
    }
}
Optimize gas usage
Adjust constructor logic
