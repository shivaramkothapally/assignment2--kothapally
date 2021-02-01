# assignment2--kothapally
# shivaram
###### chicken
i love chicken very much because it tastes **delicious**.
and it can be easily cooked and we can try n number of **recipes**.

******

# school days
1. Get ready
2. go to the schoool
    1. listen to the classes
    2. write down the notes
3. come back to home
    1. get freshed 
    2. get some snacks
4. finish homework

*******

# getting groceries

* Go to the store
* Buy Food
  * Rice
  * Beans
  * sugar
* Come home     

link to aboutme is [AboutMe](https://github.com/shivaramkothapally/assignment2--kothapally/blob/main/AboutMe.md)

******
# places to be visited in America

| Location  |      Hours    |  Amount |
|:----------|:-------------:|--------:|
|   NY |   3hrs        |  100$   |   
|   NJ |   3hrs        |  100$   |   
|  LA |   3hrs        |  100$   |
| florida|    3hrs        | 100$    |

********
#  quotes
> it always seems impossible until its done. 
                              * NELSON MANDELA*
                              
> strive not be a success, but rather to be a value.
                                * ALBERT EINSTEIN*

*******

# Verilog

> Verilog, standardized as IEEE 1364, is a hardware description language (HDL) used to model electronic systems
>  It is most commonly used in the design and verification of digital circuits at the register-transfer level of abstraction.
 link to verilog[verilog](https://en.wikipedia.org/wiki/Verilog)

 A simple code of two `flip-flops` follows:
 ```
 module toplevel(clock,reset);
  input clock;
  input reset;

  reg flop1;
  reg flop2;

  always @ (posedge reset or posedge clock)
    if (reset)
      begin
        flop1 <= 0;
        flop2 <= 1;
      end
    else
      begin
        flop1 <= flop2;
        flop2 <= flop1;
      end
endmodule
```