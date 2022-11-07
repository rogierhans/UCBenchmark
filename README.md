# UCBenchmark

Collection of Unit Commitment (UC) instances.

Two folders of the UC instances used in two differnt papers.

The folders contain similar instances, but the data from “New efficient ADMM algorithm for the Unit Commitment Problem” is more cleaned up, e.g. I removed some generators that had weird parameters.

Explanation for the generator data:

Count: number of generators of the type

pMin: minimum generation

pMax: maximum generation

a,b,c: coëfficiënt in the generation cost function f(p) = a + bp + cp^2 

RU: ramp up limit

RD: ramp down limit

SU: start up limit

SD: shutdown limit

MinUp: minimum up time

MinDown: minimum down time

FSC,VSC,Lamba: coefficients of the start cost formula FSC + VSC(1-e^(-Lambda))

SCI: Startup Cost Interval (example: 0:10:24)

SCV: Startup Cost Value   (example: X:Y:Z) (startup cost between 0 and 10 timesteps is X, startup cost between 10 and 24 timesteps is Y, after 24 its Z)
