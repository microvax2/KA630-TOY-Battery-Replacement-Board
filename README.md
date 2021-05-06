# KA630-TOY-Battery-Replacement-Board

A modern Lithium ion battery replacement board for the KA630 CPU.

The original KA630 CPU has a Ni-Cad battery on its FUNCT SEL/SLU module.
It allows the KA630 clock (a MC146818 chip) to keep the time for up to 240 hours unpowered.

This board allows you to get rid of the old 3.6V NiCad battery in favor of a modern 14500-type Lithium ion battery.

The board plugs directly into an existing FUNCT SEL/SLU board, using its 20-pin connector.
Connect the KA630's 20-pin flat cable to this board, and you're done.

The circuit takes care of the battery charge and protects it from over-discharge.

Not fully tested for performance, but a typical 900mAh battery should keep the time for up to two years.
Testing to be completed.

# DO NOT use a standard 1.5V alkaline battery in this board. The size is similar to a 14500, but it will end in tears.
