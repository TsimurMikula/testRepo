<!DOCTYPE html>
<script>
  "use strict"

  let calculator = {
  read () {  
    this.a = +prompt("Введите A", '2');
    this.b = +prompt("Введите B", '3');
  },

  sum () {
    return this.a + this.b;
  },

  mul () {
    return this.a * this.b;
  }
};

calculator.read();
alert( calculator.sum() );
alert( calculator.mul() );
</script>