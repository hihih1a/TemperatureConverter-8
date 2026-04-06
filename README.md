# TemperatureConverter-8
TemperatureConverter.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract TemperatureConverter {
    function celsiusToFahrenheit(uint256 c) public pure returns (uint256) {
        return (c * 9 / 5) + 32;
    }

    function fahrenheitToCelsius(uint256 f) public pure returns (uint256) {
        return (f - 32) * 5 / 9;
    }
}
