# Theory:

A serial adder is used to add two binary numbers in serial form. The two binary numbers to be added serially are stored in two shift registers. The circuit adds one pair at a time with the help of one full adder. The carry output from the full adder is applied to a D flip-flop, the output of which is then used as a carry input for the next pair of significant bits. However, the sum bit S from the output of the full adder can be transferred into a third shift register. 

A parallel adder is a combinational digital circuit that adds two binary numbers in parallel form. It consists of full adders connected in cascade, with the output carry from each full adder connected to the input carry of the next full adder.