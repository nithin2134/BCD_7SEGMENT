# BCD_7SEGMENT

![image](https://github.com/RESMIRNAIR/BCD_7SEGMENT/assets/154305926/804ab8db-8637-45ac-b10f-80e77d818d61)

# PROGRAM:
~~~
module segment7(

     bcd,

     seg
    
    );
    
     input [3:0] bcd;
    
     output [6:0] seg;
     
     reg [6:0] seg;

    always @(bcd)
    
    begin
    
        case (bcd)
        
            0 : seg = 7'b0000001;
            
            1 : seg = 7'b1001111;
            
            2 : seg = 7'b0010010;
            
            3 : seg = 7'b0000110;
            
            4 : seg = 7'b1001100;
            
            5 : seg = 7'b0100100;
            
            6 : seg = 7'b0100000;
            
            7 : seg = 7'b0001111;
            
            8 : seg = 7'b0000000;
            
            9 : seg = 7'b0000100;
            
            default : seg = 7'b1111111; 
        
        endcase
    
    end

    endmodule
 ~~~
# OUTPUT:

![image](https://github.com/nithin2134/BCD_7SEGMENT/assets/160302970/c3e61f90-b852-4389-aba5-0f6836261f02)

    
