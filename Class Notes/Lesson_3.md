# Architecting

Architecting is all about constructing elements. There are classes, attributes, that all connect via the defined relations.
The architect understands what is the main goal of the project, while the designer thinks about the different tecnologies to use to make sure that the architect's vision becomes real. To do so, we must separate our application into different **components**.

And making sure that the software has:

- **Robustness**: it will not perish easily
- **Longevity**: it reacts to change
- **Scalability**: is prepared to grow

Stable systems have evolved over time. Still, all of them share something in common:

- Reached by trial and error
- Perfected by applying constant adaptation
- Affected by the ever-evolving technologies

With that in mind, the role of software architecture in each application is: improve development **predictability**, establish **tradeoffs**, ease the **collaboration** between different development teams, etc. All from a high-level point of view (with special focus on modulation and interconnections).

**Software Architecture** is the fundamental organization of a system, embodied in its components and their relationships to each other and the environment.

## Architectural Knowledge

One of the key aspects of architectural knowledge is being able to **reuse** when needed. That may be achieved by:

- Following styles that have been proven to be effective
- Updating and iterating on previous solutions that were found to be successful

Concepts like **design patterns** are a perfect example of this.

## Model-View-Controller

The most popular architectural pattern, present in many applications:

- **Model**: corresponds to all the data-related logic that the user works with
- **View**: serves as the interface for the user to connect with the system
- **Controller**: interacts with the *View* component to update it after manipulating the data with the *Model* component.

### Layered Architecture

Organizes systems into a set of layers. In a **strict** architecture, the *Layer N* can only make calls to *Layer N-1*. In a more **relaxed** approach, this ceases to happen. Generally, there are three big layers that encapsulate each running project: **presentation** layer, **application** layer, **data** layer.

