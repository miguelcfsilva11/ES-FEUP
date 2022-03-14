# Software Development Cyle

Each application takes a few steps during its life cycle on its way to the final product.
These can be addressed as:

- **Planning**: Allocating the time and people needed to start the project 
- **Analysis**: Understanding whats the goal, what we are targetting, what resources it'll take
- **Design**: Reaching an agreement when it comes to the architecture of our solution 
- **Implementation**: Coding and developing its features
- **Testing and Integration**: Test them and deploy our build
- **Maintenance**: Fix bugs via patches, listen to the users and build on top of that

Every step should be **revisited**, atleast during the mid-life phases such as testing and feature implementation (so that we could update a feature after we test it, allowing us to freely change our program components to a certain extent, when we should benefit from that).

## Plan-driven vs Agile

In Agile processes, planning is **incremental**, just so we can change the course of action easily whenever
our customer requirements change. In Plan-driven processes, everything is **planned ahead**, which limits our
freedom when it comes to adapting. We should combine a little bit of both to reach the much needed **efficiency** when
tackling a big project.

## Software Process Models

There are many ways we can tackle a software engineering project:

- **Waterfall**: It is a plan-driven model, as we plan everything ahead of time, excluding (briefly) the need to revisited each *SDC* phase atleast once more. Still, it is risky to assume that everything will be done perfectly at first try.
- **Spiral**: It is based on iterations. We do a bit of implementing, testing and integration each and every week. By doing so, we repeat this process by incrementing more and more complexity to each of the repeated phases, while focusing on the freedom the programmer has to change their vision on the product (as in the following weeks, he'll have the opportunity to tackle each *SDC* phase once more and possibly update / refactor it.)

## Incremental Development (& Delivery)
 
Benefits of taking this *incremental* approach:

- The cost of **accommodation** changing customer requirements is reduced
- More frequent and early customer feedback (which allows us to iterate on that)

## Integration and Configuration

Benefits of taking this *isolate and integrate* approach:

- By creating each component separately, and making use of well tested libraries and software, we reduce the cost of failure as we can fully understand and isolate the error from which each bug comes from (the code is not **entangled**)

# Rational Unified Process - RUP

It is an incremental and iterative process, developed hand-in-hand with UML. It is driven by use cases, with extreme focus on identifying the requirements. Promotes the initial definition of a robust software architecture that helps the development parallelization.

So, **what is a use-case?**: it is each and every possible scenario in that someone may use our application and benefit from it. They are the different ways one can use our product to reach their desired goal.

# eXtreme Programming Process - XP

It consists in an agile process.

Every agile process is based on the [Agile Manifesto](https://agilemanifesto.org/):

- **Individuals and interactions** over processes and tools
- **Working software** over comprehensive documentation
- **Customer collaboration** over contract negotiation
- **Responding to change** over following a plan

*That is, while there is value in the items on the right, we value the items on the left more.*

## XP motto - *Embrace Change*

Take advantage of our freedom while developers in an agile environment, making sure that if change is to be implemented, it shall be for the best. There are four core values to this mindset: **communication, simplicity, feedback, courage**.
