pragma solidity ^0.4.24;

contract BuildCustomizationInterface {
    /// @dev simply a boolean to indicate this is the contract we expect to be
    function isBuildCustomization() public pure returns (bool);

    /// @dev given build of vehicle 1 & 2, return a hybrid combination - may have a random factor
    /// @param car1 characteristics of sedan
    /// @param car2 characteristics of sport
    /// @return the customizations that are supposed to be passed down the child(hybrid)
    function mixBuilds(uint256 car1, uint256 car2, uint256 targetBlock) public returns (uint256);
}
