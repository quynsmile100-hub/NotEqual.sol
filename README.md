# NotEqual.sol
NotEqual.sol
pragma solidity ^0.8.20;
contract NotEqual {
    function check(uint a, uint b) public pure returns(bool) {
        return a != b;
    }
}
