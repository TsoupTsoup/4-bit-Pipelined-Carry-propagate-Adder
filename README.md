# 4-bit-Pipelined-Carry-propagate-Adder
As the name suggests, it's a 4-bit adder built using carry propagate architecture. It's also pipelined, so after an initial setup delay of 4 clock cycles, it can output a new result every single cycle.

The design is using a synchronous FA as a cell. In this specific VHDL code I've manually written all the different connections between the FA stages, and also all of the connections needed to delay the input bits and the output bits so that the pipeline works properly. Although this is the "dumb" approach, it's not too labor intensive in the case of a 4 bit adder. I might make a more elegant implementation (that's also scalable, so you can have an N-bit adder) some time in the future.
