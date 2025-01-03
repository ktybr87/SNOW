// SPDX-License-Identifier: MIT
// Generated with Spectral Syntax

pragma solidity ^0.8.25;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

contract SnowCoin is ERC20, Ownable {
    constructor() ERC20("SnowCoin", "SNOW") {
        uint256 tokenSupply = 100000000 * 10 ** decimals();
        _mint(msg.sender, tokenSupply);
    }
}
....................................
