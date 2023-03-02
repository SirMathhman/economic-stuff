
## Basic Units

We start by defining, loosely, the basic interpretations of physical units in an economic context, specifically with regards to firms. We treat each firm as a distinct entity. In each firm with its various assets and employees, we assert that the firm is a compound organization that in of itself contains smaller particles, in the same way that an atom contains subatomic particles.

However, it is important to note that many of these physical quantities as of yet are difficult in of themselves to quantify and thus it would not be reasonable to specify one number to represent them (yet).

### Position

We start with an interpretation of position.
In an economic system, position can be interpreted as the competitive standing of a firm, whose position can be defined as a combination of its market share, its brand reputation, its pricing strategy, its distribution network, its product offerings, and other factors that contribute to its competitive advantage in the marketplace. 
A firm's position in the market can be seen as its relative location within the competitive landscape of its industry.

However, as we can see, it is somewhat difficult to quantify the position of a firm. But we introduce the idea nonetheless.

### Velocity

In physics, velocity is interpreted as the change in position with respect to time.
Given the description of position above, velocity
can be interpreted as how ideas such as the firm's
market share, brand repuation, pricing strategy, etc., change over time.

TODO: write more

### Acceleration

Likewise, acceleration can be though of as how fast that growth is.

TODO: write more

### Mass

The concept of mass in physics is a quantity that is still undergoing research, with the origin of mass not yet understood fully.

Mass, in general, is interpreted as the amount of "stuff" that is within an object or region. Likewise, the mass of a firm can be interpreted as as its organizational inertia.

Components of organizational inertia include:

- The assets owned
- The internal structure of the organization
- Human capital
- Intellectual property
- Agreements with other firms

Conceptually, organization inertia represents the inability of a firm to react to change, in the same sense that mass represents the inability or resistance of a particle to react to a force. Organizations and particles that have a higher mass, generally speaking, require more effort to change.

### Force

The concept of mass segues nicely into the economic interpretation of force.
The economic interpretation of how a firm might be subjected to a force is often understood by most laypersons, however we will note some examples of how force may be administered:

- Through government action
- Through market trends
- Through lack of consuption

Large enough forces will cause some firms to collapse, in the same sense that large enough forces cause physical structures to collapse.

However, a force does not necesarily have to be external for for a firm to change its position. A force can arise internally a firm (and it more often than not does), and it is through that force that the firm changes its position. This too happes in the physical world through ideas such as temperature (through Brownian motion).

### Work

In physics, work is defined as the product of a force and displacement.
Work can then be interpreted as having a sense of direction.

This too works out with firms, albeit one-dimensionally. A firm's position can either increase or decrease, thus corresponding in direction that work might want to carry it. Generally speaking, the work that a firm performs on itself is to increase its position, whereas other forces, such as from other firms, government action, or resource distributions, may cause the firm to decrease its position.

### Energy

It is then well-known that work is defined as the change in kinetic energy, over a given time period (in classical physics). In the context of the aforementioned ideas, work causes a firm to be more or less energetic.

However, the idea behind a firm being "energetic" is somewhat vague. Perhaps it would be more meaningful to claim that a firm **has economic value**, and
it is through that description of economic value, that the firm can be
energetic.

This does make sense in the context of economics. The work of a firm, in no particular direction, changes the value of it.

The current value of a firm, at any given point in time, is known as its market capitalization (cap). Thus, we can interpret the previous quantities as real values!

## Quantification

If we start from the idea that the total value of a firm is represented as its market cap, then we can extract information about its kinetic and potential energy.

We can actually represent the work done by a firm through a concept know as the market value added (MVA).

The [equation](https://en.wikipedia.org/wiki/Market_value_added) for the MVA is written like so:

```python
MVA = V - K
```

where:

- `V` is the current market cap/value of the item, including both equity and debt.
- `K` is the amount of initial capital invested into the firm.

A simple rewrite of the expression gives:

```python
V = MVA + K
```

Recall a formula for the total energy of a system:

```python
E = KE + PE
```

where:

- `E` is the total energy of the system.
- `KE` is the kinetic energy of the system.
- `PE` is the potential energy of the system.

It then becomes meaningful for both formulae to be equivalent,
both mathematically and conceptually!

- `V` = `E` - We have claimed before that that the market capitalization of a firm is equivalent to the total energy of that firm.

- `MVA` = `KE` - Market value added is also claimed to represent kinetic energy.

- `K` = `PE` - Thus, it does make conceptual sense that the initial capital invested into the firm can also be represented as that firm's initial potential energy!

The next chapter shows how this concept of the market capitalization being the total energy yields more insights.
