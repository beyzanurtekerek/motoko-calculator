actor calculator {

  var cell: Int = 0;
  
  // addition
  public func add(x : Int) : async Int {
    cell += x;
    cell
    // (Debug.print(debug_show (cell));)
  };

  // subtraction
  public func sub(x : Int) : async Int {
    cell -= x;
    cell
  };

  // multiplication
  public func mul(x : Int) : async Int {
    cell *= x;
    cell
  };

  // division
  public func div(x : Int) : async ?Int {
    if (x == 0) {
      null
    } else {
      cell /= x;
      ?cell
    };
  };

  // clear
  public func clear() : async () {
    cell := 0;
  };

};



