# Santa Gold Token #

   Overview
   
   The Santa Gold Token contract santagold.sol is an ERC20-compliant token with the following characteristics:
   
     1. Pre-minted tokens with a fixed total supply
     2. Specification for "burning" tokens (irreversible reduction of token supply)
     
   # implementation #
   OpenZeppelin code was used for SafeMath StandardToken Ownable Burnable logic
   
  SafeMath provides arithmetic functions that throw exceptions when integer overflow occurs
   
   Ownable keeps track of a contract owner and permits the transfer of ownership by the current owner
   
   Burnable provides a burn function that reduces the balance of the burner and the total supply
   
   StandardToken specifies functions in compliance with the ERC20 standard
   
  The token contract includes the following constants:

    name             = "SantaGold";
    symbol           = "SGD";
    decimals         = 8;
    INITIAL_SUPPLY   = 12 million SGD
    

    

