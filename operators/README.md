## operators
* [A](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/a.orca) add(*a* b):Outputs sum of inputs
* [B](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/b.orca) **subtract**(*a* b):Outputs difference of inputs
* [C](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/c.orca) **clock**(*rate* mod):Outputs modulo of frame
* [D](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=1544391754) **delay** (*rate* mod) Bangs on modulo of frame -  [Original definition of D](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/d.orca)
* [E](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=1022297745) **east**:Moves eastward or bangs - also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [F](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/f.orca) **if**(*a* b):Bangs if inputs are equal
* [G](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/g.orca) **generator**(*x* *y* *len*):Writes operands with offset
* [H](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/h.orca) **halt** Halts southward operand
* [I](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=376926259) **increment**(*step* mod): Increments southward operand by step [Original Definition for I](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/i.orca)
* [J](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=848624817) **jumper**(*val*): Outputs northward operand to the south  [Original definition of J](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/j.orca)
* [K](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/k.orca) **koncat**(*len*): Reads multiple variables
* [L](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/l.orca) **less**(*a* b):Outputs smallest of inputs
* [M](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=792065870) **multiply**(*a* b):Outputs product of inputs
* [N](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=782076382) **north**:Moves Northward or bangs -  also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [O](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=516599666) **read**(*xy* read):Reads operand with offset
* [P](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=861724472) **push**(*len *key* val):Writes eastward operator
* [Q](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=1080828800) **query**(*x* *y* *len*):Reads operands with offset
* [R](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=366918395) **random**(*min* max):Outputs random value
* [S](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=1145454981) **south**:Moves southward or bangs - also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [T](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=2047801949) **track**(*key* *len* val):Reads eastward operand
* [U](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=1215575674) **uclid**(*step* max): Bangs on Euclidean rhythm [Original definition of U](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/u.orca)
* [V](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/v.orca) **variable**(*write* read):Reads and writes variables
* [W](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=1121314402) **west**:Moves westward or bangs - also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [X](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=1931801148) **write**(*x* *y* val):Writes operand with offset
* [Y](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=950288332) **jymper**(*val*):Outputs westward operand to the east
* [Z](https://docs.google.com/spreadsheets/d/1uTc0G1ZM6YOZMSro9523Htooc0q2ke16_3YjUeXDtRk#gid=933294220) **lerp**(*rate* target):Fades input to output at rate [Original definition of Z](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/z.orca)
* \* **bang**: Bangs neighboring operands
* \# **comment**: Halts a line
