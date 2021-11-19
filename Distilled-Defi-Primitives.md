- Why Research? 
  - Doing Research right now parallel to pre-imagenet moment in computer vision [Deep Learning] 
  - Motivation: Uniswap has had very high usage somewhat counterintuitively since most people felt that people might be losing money. 

- "Problem with research papers is you always end up with more questions than you started with"

- CFMMs (Constant function market makers) - Generalized AMMs
  - Most people come at it from a very traditional finance angle 
  - CFMMs allow modeling(replicate) a variety of instruments without the need for oracles, eg: Options. (Not all things but a surprisingly large space)
  - Their research pokes at the edges of what is possible with RMMs 

- What Cant be done with CFMMs and why are oracle-less systems required
  - Regular Call Options (with Unbounded payoff and are convex) need oracles (but clipping the payoff can convert this into some
    - Oracles are the main source of financial and technical difficulty/innovation in defi), this makes them vulnerable to a variety of attacks (increased surface area of problems)
  - Exploits: Final Settlement transactions which depend on oracles give a financial incentive for a malicious actor to try and manipulate oracles. 
  - Most Oracle systems act as legal courts, (UMA Oracle) and are dependent on a variety of challenges. This post-hoc challenge regime can be difficult in financial systems because users prefer finality.

- This research has received a lot of attention because of a variety of neat formulations for practical things. 
  - Note: Why do formulations matter? Formulations provide frameworks for things, once you have a neat formulation for a problem, you can pick it apart in a variety of ways and try to solve the problem in within a bounded box.
 

" I have personally always found it true in crypto that a lot of practical stuff was first developed and then the theory for it was developed, i think their research first started with why certain things in defi actually work, 
and anyone who's done research know that it never stops at one question, so its paved way for more answers and *naturally* more improvements."


" Thanks for a hilarious podcast"

- Liveness Failure 
  - Trying to port things that work on ethereum to non-ETH chains with some incremental modifications 
  - Example: CFMMs + Orderbooks, This cant work out so analogously because there are trade offs to doing this.
    - Blockchains have liveness failure sometimes. 
    - After a liveness failure occurs, to align the price of a CFMM to that a global market needs which might require a variety of different transactions. 
-
