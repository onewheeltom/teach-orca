# Orca - a two dimensional esoteric programming language
Original archive is here [https://github.com/hundredrabbits/Orca](https://github.com/hundredrabbits/Orca). 

I have replaced some of the command definitions with simpler ones and defined each command separately.
My changes/updates are marked with an :asterisk:. Original definitions are linked at the end of that line.

- [About Orca](https://git.sr.ht/~rabbits/orca#orc)

## commands
* [A](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/a.orca) add(*a* b):Outputs sum of inputs
* [B](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/b.orca) **subtract**(*a* b):Outputs difference of inputs
* [C](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/c.orca) **clock**(*rate* mod):Outputs modulo of frame
* [D](./d.orca) **delay** (*rate* mod):asterisk: Bangs on modulo of frame :asterisk: [Original definition](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/d.orca)
* [E](./e.orca) **east**:Moves eastward or bangs:asterisk: - also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [F](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/f.orca) **if**(*a* b):Bangs if inputs are equal
* [G](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/g.orca) **generator**(*x* *y* *len*):Writes operands with offset
* [H](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/h.orca) **halt** Halts southward operand
* [I](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/i.orca) **increment**(*step* mod): Increments southward operand by step
* [J](./j.orca) **jumper**(*val*): Outputs northward operand to the south :asterisk: [Original definition](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/j.orca)
* [K](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/k.orca) **koncat**(*len*): Reads multiple variables
* [L](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/l.orca) **less**(*a* b):Outputs smallest of inputs
* [M](./m.orca) **multiply**(*a* b):Outputs product of inputs :asterisk:
* [N](./n.orca) **north**:Moves Northward or bangs :asterisk: -  also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [O](./o.orca) **read**(*xy* read):Reads operand with offset :asterisk:
* [P](./p.orca) **push**(*len *key* val):Writes eastward operator :asterisk:
* [Q](./q.orca) **query**(*x* *y* *len*):Reads operands with offset :asterisk:
* [R](./r.orca) **random**(*min* max):Outputs random value :asterisk:
* [S](./s.orca) **south**:Moves southward or bangs :asterisk: - also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [T](./t.orca) **track**(*key* *len* val):Reads eastward operand :asterisk:
* [U](./u.orca) **uclid**(*step* max): Bangs on Euclidean rhythm :asterisk: [Original definition](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/u.orca)
* [V](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/v.orca) **variable**(*write* read):Reads and writes variables
* [W](./w.orca) **west**:Moves westward or bangs :asterisk: - also see [cardinals.orca](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks/cardinals.orca)
* [X](./x.orca) **write**(*x* *y* val):Writes operand with offset :asterisk:
* [Y](./y.orca) **jymper**(*val*):Outputs westward operand to the east :asterisk:
* [Z](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/z.orca) **lerp**(*rate* target):Fades input to output at rate
* \* **bang**: Bangs neighboring operands
* \# **comment**: Halts a line

## sending notes
* [midi](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/_midi.orca): Sending notes to a software or hardware MIDI device
* [osc](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/_osc.orca): Sending notes using Open Sound Control (OSC)
* [udp](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics/_udp.orca): Sending notes over a network with UDP

## orca-examples
* [basics](https://git.sr.ht/~rabbits/orca-examples/tree/master/basics): Command definitions on the main Orca site
* [benchmarks](https://git.sr.ht/~rabbits/orca-examples/tree/master/benchmarks): Examples of categorized commands in context
* [misc](https://git.sr.ht/~rabbits/orca-examples/tree/master/misc): Various examples of Orca coding technique
* [setups](https://git.sr.ht/~rabbits/orca-examples/tree/master/setups): Examples of techniques for sending data 
* [tutorial](https://git.sr.ht/~rabbits/orca-examples/tree/master/tutorial): Interactive Orca tutorial using Orca code [Instructions](https://git.sr.ht/~rabbits/orca-examples/tree/master/tutorial/README.md)
