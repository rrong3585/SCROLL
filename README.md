# SCROLL
SCROLL简单的合约部署
// SPDX-License-Identifier: MIT
pragma solidity >=0.7.0 <0.9.0;

contract mrblockzj {
uint public storedData;
function pull(uint x) public {

storedData = x;
}
function push() public view returns (uint retVal) {

return storedData;
}
}
