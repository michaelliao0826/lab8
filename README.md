# lab8

Q1.
Executing an empty throw statement outside a catch handler calls function
terminate, which abandons exception processing and terminates the program
immediately.

Q2.
No, the program will terminate because it treat 3.0 as a double but not 
float. After I changed the catch handler to catch(double), it shows
exception caught
I love C++

Q3.
for loop: new mino_ptr[0]
for loop: new mino_ptr[1]
for loop: new mino_ptr[2]
new_hand():delete mino_ptr[0, 1]
for loop: new mino_ptr[3]
for loop: new mino_ptr[4]
new_hand():delete mino_ptr[2, 3]
for loop: new mino_ptr[5]
for loop: new mino_ptr[6]
new_hand():delete mino_ptr[4, 5]
for loop: new mino_ptr[7]
for loop: new mino_ptr[8]
new_hand():delete mino_ptr[6, 7]
for loop: new mino_ptr[9]
