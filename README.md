BEP20 TOKEN 

edit value

#constructor
constructor() {
        _name = "NAME";
        _symbol = "SYMBOL";
        uint256 supply  =  "AMOUNT" ether;
        _mint(msg.sender,supply);
        emit Transfer(address(0), msg.sender, _totalSupply);
   }