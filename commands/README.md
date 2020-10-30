Links to the original Orca command definitions plus some simplified ones

## commands
* [A](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/a.orca) **add**(*a* b):Outputs sum of inputs
* [B](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/b.orca) **subtract**(*a* b):Outputs difference of inputs
* [C](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/c.orca) **clock**(*rate* mod):Outputs modulo of frame
* d.orca delay(*rate* mod)
* [E](./e.orca) **east**:Moves eastward or bangs - also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [F](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/f.orca) **if**(*a* b):Bangs if inputs are equal
* [G](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/g.orca) **generator**(*x* *y* *len*):Writes operands with offset
* [H](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/h.orca) **halt** Halts southward operand
* [I](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/i.orca) **increment**(*step* mod)
* [J](./j.orca) **jumper**(*val*)
* [K](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/k.orca) **koncat**(*len*)
* [L](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/l.orca) **less**(*a* b):Outputs smallest of inputs
* [M](./m.orca) **multiply**(*a* b):Outputs product of inputs
* [N](./n.orca) **north**:Moves Northward or bangs -  also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [O](./o.orca) **read**(*xy* read):Reads operand with offset
* [P](./p.orca) **push**(*len *key* val):Writes eastward operator
* [Q](./q.orca) **query**(*x* *y* *len*):Reads operands with offset
* [R](./r.orca) **random**(*min* max):Outputs random value
* [S](./s.orca) **south**:Moves southward or bangs- also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [T](./t.orca) **track**(*key* *len* val):Reads eastward operand
* [U](./u.orca) **uclid**(*step* max)
* [V](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/v.orca) **variable**(*write* read):Reads and writes variables
* [W](./w.orca) **west**:Moves westward or bangs - also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [X](./x.orca) **write**(*x* *y* val):Writes operand with offset
* [Y](./y.orca) **jymper**(*val*):Outputs westward operand
* [Z](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/z.orca) **lerp**(*rate* target):Fades input to output at rate

## sending notes
* [midi.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/_midi.orca)
* [osc.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/_osc.orca)
* [udp.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/_udp.orca)
