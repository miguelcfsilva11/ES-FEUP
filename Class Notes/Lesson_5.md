# Verification and Validation

They may seem synonymous, but in fact, their actual meaning in the context of software development is:
- **Verification** – are we building the product right?
- **Validation** – are we building the right product? 

These properties may be tested in both a **static** and **dynamic** fashion, which complement each other.
- Static techniques involve analyzing the static system
representations to find problems and evaluate quality
- Dynamic techniques involve executing the system (or an
executable representation) and observing its behavior


## Testing Software

*"Testing can show the presence of bugs, not their absence"* - Some guy named Dijkstra, probably.

What are the main goals while testing a piece of software? We should focus on the various examples of testing domains:

- **Defect** testing – using test cases with high defect finding capability
- **Statistical** testing – using representative test data and test cases to
estimate a software quality metric (e.g., performance) 

The process of implementing a test starts with defining the objectives of testing and the approach for
meeting *test objectives* within *constraints* imposed by the context (also known as **test planning**).

After that, you need to **monitor** its progress, analyse the results, **derive** new test cases, and **collect data from** the completed scenarios.

### Test Properties
- **Level / Phase** - Regression, Acceptance, System, Integration, Unit
- **Quality** - Functional, Security, Performance, Usability, Reliability
- **Design Strategy** - White-box and Black-box

These characteristics may be found in *unit* tests, *integration* and *acceptance* tests, and even in *regression* tests.