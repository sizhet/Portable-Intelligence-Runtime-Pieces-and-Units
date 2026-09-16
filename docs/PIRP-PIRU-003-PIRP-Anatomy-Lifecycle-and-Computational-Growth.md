# PIRP-PIRU-003 — PIRP Anatomy, Lifecycle, and Computational Growth

## Abstract

If Portable Intelligence Runtime Pieces and Units are to become first-class intelligence objects, they require more than a name.

They require an anatomy, a lifecycle, and a theory of growth.

This article develops a preliminary structural model of **PIRP — Portable Intelligence Runtime Piece** and its formalized counterpart, **PIRU — Portable Intelligence Runtime Unit**.

A PIRP is not defined by one fixed software class or one mandatory internal representation. Instead, it is characterized by a family of runtime properties that allow a recognizable piece of intelligence to participate in computation, preserve context, expose behavior, move across boundaries, interact with other intelligence, and potentially evolve.

A canonical PIRP may include:

- identity,
- context,
- state,
- structure,
- computation,
- trigger semantics,
- local memory,
- policy,
- evidence,
- interfaces,
- lineage,
- and growth hooks.

Six properties are proposed as especially important:

> **Identifiable, Operationally Actionable, Portable, Composable, Observable, and Evolvable.**

The article then develops a lifecycle:

> **Birth -> Localization -> Execution -> Observation -> Validation -> Specialization -> Branching -> Composition -> Unitization -> Reuse -> Growth -> Retirement**

The central claim is that Computational Growth Intelligence should not be understood only as graph growth, memory growth, or model update.

It can also be understood as:

> **the growth of a population of runtime intelligence pieces, their internal structures, their relations, their capabilities, and their ability to generate further intelligence.**

This shifts the unit of analysis from static computational structure toward an evolving ecology of executable intelligence.

---

## 1. From Ontology to Anatomy

The first two articles established two propositions.

First:

> A runtime node may produce or host something richer than a value, state transition, or structural trigger.

Second:

> Intelligence may exist before we know which computational category best describes it.

These propositions motivate PIRP.

But an abstraction becomes useful only when we can begin asking operational questions:

- What belongs inside a PIRP?
- What remains outside?
- How is a PIRP identified?
- What makes it portable?
- How does it execute?
- How does it interact with context?
- How does it change?
- When does it become a PIRU?
- When does one PIRP become several?
- When do several PIRPs become one?
- When does a PIRP cease to be useful?

These are questions of anatomy and lifecycle.

---

## 2. PIRP Is Not a Fixed Class Definition

A tempting first implementation would be:

```java
class PIRP {
    Identity identity;
    Context context;
    State state;
    Behavior behavior;
    Policy policy;
}
````

Such a class may eventually be useful.

But it should not be mistaken for the definition of PIRP itself.

The PIRP concept is deliberately broader.

A runtime intelligence piece may be implemented as:

* an object,
* a graph fragment,
* a CCC,
* a CallingPath,
* a rule set,
* a stateful function,
* a workflow,
* a structured prompt,
* an algorithm,
* a research artifact,
* a composite runtime package,
* or a structure not yet captured by an existing software category.

Therefore:

> **PIRP should first be defined by its intelligence role and runtime properties, not by one implementation technology.**

This preserves the pre-categorical principle introduced earlier.

---

## 3. A Preliminary PIRP Anatomy

A canonical PIRP can be represented conceptually as:

```text
+------------------------------------------------+
|                     PIRP                       |
|------------------------------------------------|
| Identity                                       |
| Context                                        |
| State                                          |
| Structural Knowledge                           |
| Computation / Behavior                         |
| Trigger Semantics                              |
| Local Memory                                   |
| Policy / Constraints                           |
| Evidence / Confidence                          |
| Interfaces                                     |
| Lineage / Provenance                           |
| Growth Hooks                                   |
+------------------------------------------------+
```

Not every PIRP must contain every component.

The structure is a research map, not yet a rigid schema.

Some PIRPs may be almost stateless.

Some may contain substantial memory.

Some may primarily encode structural relations.

Some may be unresolved problems with little executable code.

Some may be fully formalized runtime units.

The key is that these components help identify what makes a piece of intelligence operationally meaningful.

---

## 4. Identity

A PIRP requires enough identity to be referred to and tracked.

Possible identity information includes:

```text
PIRP-ID
Name
Version
Family
Origin
Lineage
Creation Context
Current Status
```

Identity matters because the system may need to ask:

* Is this the same PIRP seen earlier?
* Is this a new version?
* Is this a descendant?
* Is this a branch?
* Is this a composite?
* Is this merely structurally similar?
* Has this PIRP been superseded?

Traditional object identity is often insufficient.

PIRP identity may involve several dimensions:

```text
Instance Identity
Lineage Identity
Structural Identity
Behavioral Identity
Interface Identity
Semantic Identity
```

Two PIRPs may be different instances but belong to the same lineage.

Two PIRPs may share an interface but have different internal structures.

Two PIRPs may be structurally similar but serve different contexts.

Identity under growth is therefore a first-class research problem.

---

## 5. Context

Portable intelligence cannot be understood only by what it contains.

It must also represent enough of the conditions under which its intelligence is meaningful.

Context may include:

```text
environment
input assumptions
local CallingGraph position
neighboring PIRPs
available tools
historical state
domain conditions
runtime constraints
policy environment
temporal conditions
```

This creates a tension.

If too little context travels with the PIRP, portability fails.

If too much context is embedded, portability becomes expensive and overly specific.

Therefore one important PIRP design problem is:

> **What is the Minimum Sufficient Portable Context?**

This can be represented as:

```text
Original Runtime Context
          |
          v
Context Extraction
          |
          v
Minimum Sufficient Context
          |
          +----> PIRP
```

The correct amount may differ by PIRP family.

---

## 6. State

Some runtime intelligence depends on persistent local state.

Examples include:

* counters,
* accumulated evidence,
* current phase,
* local confidence,
* active branch,
* previous action,
* learned preference,
* cached structural search result.

State may be:

```text
immutable
mutable
ephemeral
persistent
local
shared
derived
historical
```

The important distinction is that PIRP state is not necessarily equivalent to the entire environment state.

A PIRP should carry or reference the state required for its own meaningful continuation.

---

## 7. Structural Knowledge

Many PIRPs may contain structural knowledge rather than only scalar values.

Examples include:

```text
CCC
CallingPath fragment
Metric relation
Differential structure
Trigger structure
Dependency relation
Candidate branch
Counter-evidence relation
Local topology
```

This is one of the reasons conventional function abstractions are insufficient.

A PIRP may carry knowledge about:

> **how computation is structurally related**, not merely what computation should return.

Structural knowledge may be folded, partially unfolded, dynamically constructed, or locally specialized.

---

## 8. Computation and Behavior

A PIRP should normally be operationally actionable.

This does not require that every PIRP contain executable machine code.

Operational action may include:

```text
compute
evaluate
trigger
route
search
compare
transform
validate
recommend
generate
compose
specialize
```

For example, an unresolved research PIRP may not contain a final algorithm.

But it may still be operationally actionable if another intelligence can receive it and continue the required computation.

Thus:

> **Executable intelligence is broader than executable code.**

This distinction becomes important when PIRPs move between humans, AIs, algorithms, and organizations.

---

## 9. Trigger Semantics

A PIRP may need to specify when it becomes active.

Trigger conditions may depend on:

```text
input pattern
state
event
context
metric threshold
policy condition
CallingGraph position
external signal
another PIRP
```

Conceptually:

```text
Context + State + Event
          |
          v
      Trigger Test
          |
       +--+--+
       |     |
      No    Yes
             |
             v
        PIRP Activation
```

Trigger semantics connect PIRP directly to Structural Trigger Intelligence.

A PIRP may itself be:

* triggered,
* a trigger producer,
* a trigger evaluator,
* or a structure that creates new trigger conditions.

---

## 10. Local Memory

Memory distinguishes many intelligent runtime structures from purely functional computation.

A PIRP may remember:

```text
past inputs
past outputs
evidence
failures
successful branches
local adaptations
previous relay context
historical decisions
```

Memory can support:

* specialization,
* local learning,
* consistency,
* adaptation,
* confidence estimation,
* structural growth.

However, memory also complicates portability.

A PIRP with hidden external memory may fail when transferred.

Therefore memory dependencies should become observable whenever practical.

---

## 11. Policy and Constraints

Capability does not imply permission.

A PIRP may be able to perform an action but not be authorized to do so.

Policy may govern:

```text
activation
execution
resource use
composition
modification
branching
publication
relay
retirement
```

Conceptually:

```text
Capability
    +
Context
    +
Policy
    |
    v
Permitted Runtime Behavior
```

This distinction becomes increasingly important as PIRPs gain growth capabilities.

A system that permits PIRPs to modify or generate other PIRPs without governance may become difficult to reason about.

Therefore PIRP growth and policy should be designed together.

---

## 12. Evidence and Confidence

A PIRP should ideally expose evidence about why its behavior is considered useful or valid.

Evidence may include:

```text
test results
historical success
counter-evidence
supporting observations
benchmark results
runtime traces
source artifacts
validation status
```

A PIRP should not necessarily collapse uncertainty into one scalar confidence score.

It may instead preserve structured evidence.

For example:

```text
PIRP-X
 |
 +---- Supporting Evidence
 |
 +---- Counter-Evidence
 |
 +---- Unknown Conditions
 |
 +---- Validation Status
```

This supports future re-evaluation.

---

## 13. Interfaces

Portability requires interfaces.

A PIRP may expose:

```text
input interface
output interface
trigger interface
state interface
evidence interface
composition interface
growth interface
relay interface
```

A PIRP may begin with partially implicit interfaces.

A PIRU should normally make them more explicit.

Thus interface extraction is one of the major transitions from PIRP to PIRU.

---

## 14. Lineage and Provenance

Runtime intelligence may evolve.

Therefore it is useful to know where a PIRP came from.

Possible lineage information includes:

```text
Parent PIRP
Source PIRU
Source CCC
Source Artifact
Derived From
Merged From
Branched From
Localized From
Relayed From
```

A simple lineage may look like:

```text
PIRP-A
  |
  +----> PIRP-B
  |
  +----> PIRP-C
            |
            +----> PIRP-D
```

Lineage provides more than auditability.

It can become intelligence.

The system can learn:

* which structures tend to produce useful descendants,
* which branches repeatedly fail,
* which combinations create novel capabilities,
* which contexts produce productive specialization.

This will become important in the broader PIRP ecology.

---

## 15. Growth Hooks

Growth is one of the most distinctive PIRP properties.

A PIRP may expose opportunities for:

```text
update
specialization
branching
composition
merging
replacement
extension
new interface
new trigger
new policy
```

A growth hook does not mean unrestricted self-modification.

It means the structure explicitly represents where and how future structural change may occur.

For example:

```text
PIRP
 |
 +---- Stable Core
 |
 +---- Replaceable Policy
 |
 +---- Extensible Evidence
 |
 +---- Open Branch
 |
 +---- Candidate Composition Interface
```

This makes growth observable and governable.

---

# Part II — Minimum PIRP Properties

## 16. Property 1 — Identifiable

A PIRP must be sufficiently recognizable to participate in a lifecycle.

Without identity, we cannot reliably:

```text
store
retrieve
compare
relay
version
validate
retire
```

Identity may initially be weak or provisional.

But some continuity must exist.

---

## 17. Property 2 — Operationally Actionable

A PIRP must enable meaningful continuation of computation or intelligence.

This may mean direct execution.

But it can also mean:

* providing a structural decision,
* exposing an unresolved problem,
* specifying a validation task,
* carrying a reusable reasoning structure,
* enabling another intelligence to continue work.

Therefore:

> **Operationally actionable is more general than machine executable.**

---

## 18. Property 3 — Portable

A PIRP should survive at least one meaningful boundary transition.

Examples:

```text
Node -> Node
Runtime -> Runtime
Context -> Context
Application -> Application
Human -> Human
Human -> AI
AI -> Human
AI -> AI
Generation -> Generation
```

Perfect portability is not required.

Portability may be conditional.

The important question is whether enough intelligence can survive transfer to remain useful.

---

## 19. Property 4 — Composable

A PIRP should be capable of participating in a larger structure.

Composition may take several forms.

### Sequential

```text
PIRP-A -> PIRP-B -> PIRP-C
```

### Hierarchical

```text
        PIRP-X
       /      \
   PIRP-A    PIRP-B
```

### Collaborative

```text
PIRP-A
   \
    +----> PIRP-C
   /
PIRP-B
```

### Competitive

```text
PIRP-A ----+
           |
           +----> Selection
           |
PIRP-B ----+
```

### Conditional

```text
Context
   |
   +----> PIRP-A
   |
   +----> PIRP-B
```

Composition is central to scaling intelligence beyond isolated units.

---

## 20. Property 5 — Observable

A PIRP should expose enough runtime behavior for examination.

A useful observation record may contain:

```text
PIRP-ID
Timestamp
Input
Context
State-Before
Trigger
Selected Behavior
Evidence Used
Output
State-After
Structural Delta
Growth Event
```

Observability supports:

* debugging,
* validation,
* learning,
* governance,
* comparison,
* structural folding.

Without observability, intelligence growth becomes difficult to understand.

---

## 21. Property 6 — Evolvable

A PIRP should permit meaningful structural change where appropriate.

Possible evolution operations include:

```text
Update
Specialize
Branch
Compose
Merge
Replace
Promote
Demote
Retire
```

This does not mean every PIRP must perform autonomous self-modification.

Evolution may be driven by:

* humans,
* AI,
* runtime evidence,
* policy,
* structural search,
* collective learning.

The essential property is that PIRP identity and lifecycle can accommodate change.

---

# Part III — The PIRP Lifecycle

## 22. Stage 1 — Birth

A PIRP can originate from many sources:

```text
Human insight
AI generation
Runtime anomaly
Structural gap
Counter-evidence
Existing PIRU
CCC unfolding
CallingGraph growth
Composition
Research problem
Failed attempt
```

Birth occurs when a sufficiently meaningful intelligence structure becomes recognizable.

It does not require complete formalization.

---

## 23. Stage 2 — Capture

Emergent intelligence can disappear if it is not preserved.

Capture may record:

```text
what appeared
where
under what context
why it seemed meaningful
what evidence exists
what remains unknown
```

This is especially important for unusual runtime structures.

A PIRP-first system should prefer:

> **capture before forced interpretation.**

---

## 24. Stage 3 — Localization

A PIRP may need to be placed into an appropriate runtime context.

Localization can determine:

```text
where it belongs
when it applies
which node should host it
which context activates it
which structural neighborhood is relevant
```

Later work will extend localization beyond structural position toward **Relay Localization**:

> finding the human, AI, tool, or intelligence unit most qualified to continue a PIRP.

---

## 25. Stage 4 — Execution or Continuation

Once localized, the PIRP participates in runtime intelligence.

It may:

```text
execute
trigger
route
search
evaluate
transform
recommend
generate
request further work
```

An Open PIRP may be "executed" by being investigated.

A code PIRU may be executed directly by a machine.

The execution semantics depend on the PIRP type.

---

## 26. Stage 5 — Observation

Execution produces evidence.

Observation captures:

```text
behavior
result
failure
unexpected output
context sensitivity
resource use
structural delta
```

This evidence feeds validation and growth.

---

## 27. Stage 6 — Validation

Validation asks whether the PIRP behaves as expected.

Possible outcomes:

```text
Validated
Partially Validated
Context-Limited
Contradicted
Failed
Unknown
```

Counter-evidence should be preserved.

Failure does not necessarily eliminate a PIRP.

It may instead narrow its valid context or generate a new Open PIRP.

---

## 28. Stage 7 — Specialization

A general PIRP may become more effective in a particular context.

```text
General PIRP
     |
     +----> Context A -> Specialized PIRP-A
     |
     +----> Context B -> Specialized PIRP-B
```

Specialization may improve:

* performance,
* accuracy,
* interpretability,
* portability within a domain,
* policy compliance.

But excessive specialization may reduce general portability.

This creates a design tradeoff.

---

## 29. Stage 8 — Branching

When evidence supports multiple structural directions, a PIRP may branch.

```text
          PIRP-X
          /    \
         /      \
   PIRP-XA    PIRP-XB
```

Branching is especially important when uncertainty should be preserved.

Instead of forcing one winner too early, the system can retain multiple candidates.

Future evidence may later:

* select one,
* merge them,
* preserve both,
* or generate additional branches.

---

## 30. Stage 9 — Composition

Multiple PIRPs may form a larger intelligence structure.

```text
PIRP-A
   \
    \
     +----> Composite PIRP-C
    /
   /
PIRP-B
```

Composition may produce capabilities that do not exist in either component alone.

This creates an important growth mechanism:

> **new intelligence can emerge from relations among existing intelligence pieces.**

The composite itself may become a new PIRP.

---

## 31. Stage 10 — Unitization

When a PIRP becomes sufficiently understood, it may be formalized into a PIRU.

The process may include:

```text
boundary discovery
identity stabilization
interface extraction
typing
validation
policy definition
versioning
runtime contract
```

Conceptually:

```text
PIRP
 |
 | understand
 | validate
 | bound
 | type
 v
PIRU
```

Unitization increases reuse and governance.

But unexplained leftovers should remain explicit whenever possible.

---

## 32. Stage 11 — Reuse

A PIRU can be reused across:

```text
nodes
CallingGraphs
applications
domains
agents
organizations
runtime environments
```

Reuse is one of the primary benefits of formalization.

But reuse also generates new contexts.

Those contexts may expose previously unknown behavior.

Thus reuse can reopen the growth cycle.

---

## 33. Stage 12 — Reopening

A stable PIRU may encounter evidence that exceeds its formal definition.

For example:

```text
PIRU-X
  |
  | new context
  v
Unexpected Behavior
  |
  v
New Structural Delta
  |
  v
PIRP-X'
```

This is a crucial mechanism.

Formalization must not permanently close the intelligence structure.

A growth-capable system should permit stable units to generate new exploratory pieces.

---

## 34. Stage 13 — Retirement

Not every PIRP should live forever.

Retirement may occur when a PIRP is:

```text
superseded
invalidated
unsafe
obsolete
redundant
fully absorbed into another structure
no longer useful
```

Retirement should ideally preserve:

* lineage,
* evidence,
* reason for retirement,
* successor relationships.

A retired PIRP may still provide historical intelligence.

---

# Part IV — Computational Growth

## 35. What Is Growing?

Computational Growth Intelligence raises a fundamental question:

> **What exactly grows?**

Several answers are possible.

### Graph Growth

```text
Nodes + Edges
```

### Knowledge Growth

```text
More structural relations
```

### Memory Growth

```text
More retained experience
```

### Policy Growth

```text
More differentiated control
```

### Capability Growth

```text
More things the system can do
```

### PIRP Growth

```text
More intelligence pieces
+
richer pieces
+
better relations
+
better composition
+
better localization
```

These are not mutually exclusive.

PIRP provides a common runtime perspective across them.

---

## 36. Growth Is Not Merely Accumulation

A system with one million PIRPs is not necessarily more intelligent than a system with one thousand.

Growth must be distinguished from accumulation.

Simple accumulation:

```text
PIRP
PIRP
PIRP
PIRP
PIRP
```

Structural growth:

```text
        PIRP-A
        /    \
       /      \
 PIRP-B      PIRP-C
    |           |
    +-----+-----+
          |
          v
       PIRP-D
```

The second contains:

* differentiation,
* relation,
* composition,
* lineage,
* reusable structure.

Therefore:

> **Computational Growth is structural, not merely numerical.**

---

## 37. Growth Dimensions

PIRP growth can occur along several dimensions.

### 37.1 Population Growth

More useful PIRPs exist.

### 37.2 Internal Growth

A PIRP becomes structurally richer.

### 37.3 Specialization Growth

New context-specific descendants emerge.

### 37.4 Composition Growth

Existing PIRPs form higher-order structures.

### 37.5 Relation Growth

New dependencies, contrasts, and relay relations appear.

### 37.6 Interface Growth

New ways of interacting with PIRPs become available.

### 37.7 Evidence Growth

Confidence and counter-evidence become richer.

### 37.8 Capability Growth

The system can perform computations previously unavailable.

These dimensions should be distinguished when evaluating computational growth.

---

## 38. Structural Delta as the Basic Growth Event

A useful primitive is:

> **Structural Delta**

A structural delta records meaningful change between intelligence states.

For example:

```text
Before:
PIRP-X

After:
PIRP-X
  |
  +---- New Trigger
  |
  +---- New Evidence
  |
  +---- New Branch
```

The delta may be:

```text
new node
new edge
new rule
new context
new capability
new policy
new interface
new branch
new composition
new counter-evidence
```

Computational Growth Intelligence can therefore be viewed as the controlled accumulation and organization of meaningful structural deltas.

---

## 39. Growth Can Produce New Categories

The Pre-Categorical Intelligence Hypothesis implies a particularly important form of growth.

A PIRP may emerge that cannot be represented well by any existing PIRU type.

Instead of discarding it, the system may eventually define a new category.

```text
Known PIRU Types
      |
      v
Runtime
      |
      v
Novel PIRP
      |
      v
Repeated Observation
      |
      v
New Structural Pattern
      |
      v
New PIRU Type
```

Thus computational growth can modify not only instances.

It can modify the **type system of intelligence itself**.

This is a deeper form of structural growth.

---

## 40. Growth Through Failure

Failure is often treated as discarded computation.

PIRP changes this interpretation.

A failed PIRP may contain:

```text
Problem
Attempt
Context
Evidence
Failure Condition
Boundary
Lesson
```

That structure may prevent repeated failure.

It may also reveal:

* missing context,
* incorrect assumptions,
* new branches,
* better metrics,
* new research questions.

Therefore:

> **Failure can be a productive PIRP transformation.**

A failed attempt may generate a more valuable Open PIRP than the original attempt.

---

## 41. Growth Through Counter-Evidence

Counter-evidence is another growth mechanism.

Suppose:

```text
PIRP-A
 |
 | predicts
 v
Outcome X
```

but evidence repeatedly produces Y.

Instead of simply lowering a score, the system can create:

```text
PIRP-A
 |
 +---- Supporting Context
 |
 +---- Counter-Evidence Context
 |
 +---- New Branch
          |
          v
       PIRP-B
```

Counter-evidence therefore creates structural differentiation.

This is more informative than merely adjusting confidence.

---

## 42. Growth Through Composition

Composition can produce genuinely new runtime behavior.

Suppose:

```text
PIRP-A = Structural Search

PIRP-B = Counter-Evidence Validation
```

Their composition may produce:

```text
PIRP-C =
Structural Search
+
Counter-Evidence Validation
+
Iterative Refinement
```

PIRP-C may exhibit behavior not explicitly present in either parent.

This creates a route from reusable intelligence pieces toward higher-order intelligence.

---

## 43. Growth Through Localization

The same PIRU may produce different PIRPs when localized into different contexts.

```text
             PIRU-X
           /    |    \
          /     |     \
Context-A  Context-B  Context-C
    |          |          |
    v          v          v
 PIRP-A     PIRP-B     PIRP-C
```

Localization therefore is not merely deployment.

It can be a growth operation.

Context reveals different aspects of reusable intelligence.

Those differences can later be folded back into structural memory.

---

## 44. Growth Through Relay

A PIRP may also grow by being transferred to another intelligence.

```text
Agent-A
   |
   v
PIRP-X
   |
   | relay
   v
Agent-B
   |
   | new perspective
   v
PIRP-X'
```

The receiving intelligence may contribute:

* different knowledge,
* different tools,
* different context,
* different metrics,
* different counter-evidence.

Relay therefore becomes a growth mechanism.

Later articles will treat relay and relay localization as first-class components of the PIRP/PIRU ecology.

---

# Part V — Population and Ecology

## 45. From One PIRP to a Population

Once PIRPs can be created, branched, composed, reused, and retired, the runtime no longer contains isolated intelligence objects.

It contains a population.

```text
PIRP-A      PIRP-B
   |           |
   +-----+-----+
         |
       PIRP-C
       /    \
      /      \
 PIRP-D     PIRP-E
```

The population has:

* ancestry,
* diversity,
* specialization,
* composition,
* competition,
* cooperation,
* retirement.

This begins to resemble an intelligence ecology.

---

## 46. Population Quality Matters More Than Population Size

A useful PIRP population should not maximize raw count.

It should improve properties such as:

```text
coverage
diversity
validation
composability
localizability
portability
growth potential
low redundancy
clear lineage
```

A mature runtime may therefore need mechanisms for:

* consolidation,
* deduplication,
* pruning,
* promotion,
* retirement,
* structural folding.

Growth and cleanup are complementary.

---

## 47. PIRP Families

Related PIRPs may form families.

```text
PIRP-Family-X
 |
 +---- PIRP-X1
 |
 +---- PIRP-X2
 |
 +---- PIRP-X3
```

A family may represent:

* different contexts,
* different versions,
* different strategies,
* different policies,
* different implementations.

Families can preserve diversity without losing structural organization.

A PIRU may sometimes represent the stable common structure of a PIRP family.

---

## 48. PIRP and PIRU Coexistence

A mature runtime should not consist exclusively of PIRPs or exclusively of PIRUs.

Instead:

```text
Exploratory Layer
      |
     PIRPs
      |
      v
Formalization Layer
      |
     PIRUs
      |
      v
Operational Layer
      |
Execution / Composition
      |
      v
Growth Layer
      |
New PIRPs
```

This coexistence creates a dynamic balance.

PIRPs provide openness.

PIRUs provide stability.

Computational Growth requires movement between them.

---

# Part VI — Governance and Safety of Growth

## 49. Growth Must Be Governed

Evolvability does not imply unrestricted mutation.

A PIRP may be allowed to:

```text
observe
suggest
branch
```

but not:

```text
replace production logic
publish globally
modify protected policy
```

without additional authorization.

A useful separation is:

```text
Growth Proposal
      |
      v
Validation
      |
      v
Policy Check
      |
      v
Promotion
```

This keeps discovery open while execution remains controlled.

---

## 50. Growth Roles

Different participants may have different permissions.

```text
Observer
Creator
Validator
Composer
Publisher
Promoter
Governor
Retirer
```

These roles may be filled by:

* humans,
* AIs,
* algorithms,
* organizations,
* policy systems.

The important principle is:

> **Capability, authority, and validation should remain distinguishable.**

---

## 51. PIRP Growth Audit

Every meaningful growth event should ideally leave an audit trace.

```text
Growth Event
 |
 +---- Parent PIRP
 |
 +---- Trigger
 |
 +---- Context
 |
 +---- Structural Delta
 |
 +---- Actor
 |
 +---- Evidence
 |
 +---- Policy Decision
 |
 +---- Resulting PIRP(s)
```

This trace later becomes useful for:

* validation,
* debugging,
* governance,
* structural learning,
* relay analysis.

The history of growth is itself intelligence.

---

# Part VII — A Canonical Lifecycle

## 52. Full PIRP Lifecycle

The lifecycle developed in this article can be summarized as:

```text
                     BIRTH
                       |
                       v
                    CAPTURE
                       |
                       v
                 LOCALIZATION
                       |
                       v
              EXECUTE / CONTINUE
                       |
                       v
                  OBSERVATION
                       |
                       v
                  VALIDATION
                       |
          +------------+------------+
          |                         |
          v                         v
    SPECIALIZATION              FAILURE
          |                         |
          v                         v
      BRANCHING                OPEN PIRP
          |                         |
          +------------+------------+
                       |
                       v
                  COMPOSITION
                       |
                       v
                  UNITIZATION
                       |
                       v
                     PIRU
                       |
                       v
                     REUSE
                       |
                       v
                NEW CONTEXT
                       |
          +------------+------------+
          |                         |
          v                         v
      STABLE USE             STRUCTURAL DELTA
                                    |
                                    v
                                NEW PIRP
                                    |
                                    +-------> ...

                     RETIREMENT
                         ^
                         |
            may occur where appropriate
```

This lifecycle is intentionally non-linear.

Real intelligence growth may loop among stages many times.

---

## 53. Canonical Growth Loop

The deepest recurring loop is simpler:

```text
PIRP
 |
 | formalize
 v
PIRU
 |
 | execute / localize / compose
 v
Runtime
 |
 | observe structural delta
 v
New PIRP
 |
 +---------------------------->
```

This can be expressed conceptually as:

> **Emergence -> Unitization -> Runtime -> Growth -> Emergence**

The loop provides a possible primitive for Computational Growth Intelligence.

---

## 54. Core Principles

The article can be condensed into ten working principles.

### Principle 1 — PIRP Is Defined by Intelligence Role, Not Implementation Type

A PIRP may cross conventional software categories.

### Principle 2 — Identity Must Survive Enough Change to Support a Lifecycle

Without identity or lineage, growth cannot be tracked.

### Principle 3 — Context Is Part of Portable Intelligence

Portability requires enough context for meaningful continuation.

### Principle 4 — Executability Is Broader Than Machine Code

A problem, validation structure, or research task can be operationally actionable.

### Principle 5 — Observability Is Required for Intelligent Growth

Growth without evidence becomes difficult to validate or govern.

### Principle 6 — Evolvability Does Not Mean Unrestricted Mutation

Growth should be explicit, observable, and policy-governed.

### Principle 7 — Failure and Counter-Evidence Are Growth Inputs

They should produce structural information rather than disappear.

### Principle 8 — Composition Can Produce New Intelligence

Relations among PIRPs may create capabilities absent from individual pieces.

### Principle 9 — Computational Growth Is Structural, Not Merely Numerical

More PIRPs do not automatically mean more intelligence.

### Principle 10 — Growth Can Change the Intelligence Type System

Novel PIRPs may eventually require entirely new PIRU categories.

---

## 55. Research Questions

Several questions remain open.

### 55.1 Minimum Anatomy

Which PIRP fields are truly mandatory?

### 55.2 Minimum Portable Context

How much context must travel with a PIRP?

### 55.3 Identity

What invariants define continuity across growth?

### 55.4 Granularity

How large or small can a PIRP be?

### 55.5 Composition

How can composition preserve provenance and policy?

### 55.6 Growth Metrics

How should useful computational growth be measured?

### 55.7 Population Management

How should redundant, obsolete, or contradictory PIRPs be handled?

### 55.8 Unitization

When is a PIRP mature enough to become a PIRU?

### 55.9 Reopening

When should a stable PIRU return to exploratory PIRP status?

### 55.10 Relay

How should a PIRP identify the next intelligence most qualified to continue its growth?

These questions lead naturally toward publication, open PIRPs, relay context, and collective intelligence.

---

## 56. Conclusion

PIRP/PIRU becomes useful only when intelligence is treated as something with a lifecycle.

A runtime intelligence piece may:

> **appear, be captured, localized, executed, observed, validated, specialized, branched, composed, formalized, reused, reopened, relayed, grown, and retired.**

Its anatomy may include:

```text
Identity
Context
State
Structure
Computation
Trigger
Memory
Policy
Evidence
Interfaces
Lineage
Growth Hooks
```

Its most important operational properties are:

> **Identifiable**
> **Operationally Actionable**
> **Portable**
> **Composable**
> **Observable**
> **Evolvable**

These properties allow intelligence to become more than an ephemeral output of computation.

They allow it to become a persistent participant in future computation.

The resulting view of Computational Growth Intelligence is broader than graph expansion or memory accumulation.

It becomes:

> **the structural growth of runtime intelligence pieces, their internal capabilities, their relations, their compositions, their lineages, and their capacity to generate further intelligence.**

This suggests a transition:

```text
Static Computation
       |
       v
Runtime Intelligence
       |
       v
Portable Intelligence
       |
       v
Composable Intelligence
       |
       v
Growing Intelligence Population
       |
       v
Intelligence Ecology
```

The next major question is therefore no longer only how PIRPs exist internally.

It is:

> **How does intelligence leave the runtime or individual that produced it and become usable by another intelligence?**

That question leads directly to publication as a first-class portability mechanism.

---

## Next Article

**PIRP-PIRU-004 — Publishing as Portable Intelligence Transfer**

The next article examines a broader interpretation of portability:

> **A PIRP is not merely portable across machines or runtimes. It may be portable across intelligences.**

From this perspective, publishing becomes more than information dissemination.

It becomes a mechanism through which intelligence can be externalized, transferred, localized into another human or AI, incorporated into new Known-Knowledge, and continued through collective learning.

