module main_tb;
reg [1:0]sel;
reg [15:0]a;
reg [15:0]b;
reg [15:0]x;
reg [15:0]y;
reg [15:0]A;
reg [15:0]B;
reg [15:0]j;
reg [15:0]k;
reg cin;
reg Op;

wire [15:0]y1;
wire [31:0]y2;
wire [15:0]y3;
wire cout;
wire carry_out;
wire m;

main_module uut(y1,y2,y3,cout,carry_out,m,sel,a,b,x,y,A,B,j,k,cin,Op);
initial begin
sel = 2'b00;
a = 10;
b = 20;
x = 25;
y = 11;
A = 12;
B = 12;
j = 16'hff12;
k = 3;
cin = 0;
Op = 1;
#10;

sel = 2'b01;
a = 10;
b = 20;
x = 25;
y = 11;
A = 12;
B = 12;
j = 16'hff12;
k = 3;
cin = 0;
Op = 1;
#10;

sel = 2'b10;
a = 10;
b = 20;
x = 25;
y = 11;
A = 12;
B = 12;
j = 16'hff12;
k = 3;
cin = 0;
Op = 1;
#10;

sel = 2'b11;
a = 10;
b = 20;
x = 25;
y = 11;
A = 12;
B = 12;
j = 16'hff12;
k = 3;
cin = 0;
Op = 1;
#10;
$finish;
end
endmodule
