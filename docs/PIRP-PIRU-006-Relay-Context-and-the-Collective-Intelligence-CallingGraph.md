# PIRP-PIRU-006 — Relay Context and the Collective Intelligence CallingGraph

## Abstract

Portable Intelligence becomes significantly more powerful when intelligence can move from one human, AI, tool, team, or runtime to another.

But the transfer event itself contains information.

When one intelligence receives a PIRP, the important questions are not limited to:

- Where did the PIRP come from?
- Who created it?

We may also ask:

- Why was this PIRP picked up?
- Why by this intelligence?
- Under what context?
- Through which perspective?
- What knowledge or capability did the receiver contribute?
- What transformation occurred?
- What evidence was added?
- What Structural Delta resulted?
- What new PIRPs were generated?

This article introduces **Relay Context** as a first-class intelligence structure.

A Relay Context records the meaningful conditions and consequences of an intelligence transfer.

This leads to a distinction between two related graphs:

> **Knowledge CallingGraph — what intelligence depends on, extends, contradicts, validates, or composes with what intelligence.**

and:

> **Relay CallingGraph — how intelligence actually moved between intelligences, under which contexts and perspectives, and what growth resulted.**

Together, these graphs form the basis of a broader **Collective Intelligence CallingGraph**.

The central proposition is:

> **The history of how intelligence was received, interpreted, transformed, and continued is itself reusable intelligence.**

Once Relay Context is preserved, a system can begin learning not only from solutions, but from the trajectories through which distributed intelligence produces those solutions.

---

## 1. Intelligence Does Not Grow Only Inside One Intelligence

The previous articles established a basic lifecycle:

```text
PIRP
 |
 v
Publish
 |
 v
Discover
 |
 v
Localize
 |
 v
Receiving Intelligence
 |
 v
Continue Computation
 |
 v
Structural Growth
````

This lifecycle contains a transition that deserves independent attention:

```text id="d9zly5"
PIRP
 |
 | transfer
 v
Another Intelligence
```

We call this transition:

> **Relay**

Relay means that computation does not end when the original intelligence stops.

Another intelligence continues from the current frontier.

---

## 2. Relay Is More Than Transfer

A simple transfer can be represented as:

```text id="x7ih63"
Agent-A
   |
   v
PIRP-X
   |
   v
Agent-B
```

But this representation loses most of the useful information.

Why did Agent-B receive PIRP-X?

What did Agent-B know that Agent-A did not?

What perspective did Agent-B apply?

What changed?

A richer representation is:

```text id="zvt8fe"
PIRP-X
   |
   | Relay
   v
Agent-B
   |
   +---- Context C
   |
   +---- Perspective P
   |
   +---- Capability K
   |
   v
Structural Delta D
   |
   v
PIRP-X'
```

The relay event has structure.

That structure can be remembered and reused.

---

## 3. Relay Context

We define:

> **Relay Context — the structured record of why, where, how, and with what result a PIRP was transferred to and continued by another intelligence.**

A preliminary Relay Context may include:

```text id="f27cqe"
Source PIRP
Source Intelligence
Receiving Intelligence
Context
Reason for Pickup
Perspective
Capabilities Used
Tools Used
Transformation
Evidence Added
Counter-Evidence Added
Structural Delta
Outcome
Derived PIRPs
Timestamp
Policy / Permission
```

This is much richer than ordinary provenance.

---

## 4. Provenance vs Relay Context

Provenance typically answers:

> Where did this artifact come from?

For example:

```text id="3r21dq"
PIRP-C
 |
 +---- derived from PIRP-B
       |
       +---- derived from PIRP-A
```

This is valuable.

But Relay Context asks additional questions:

> Why did this intelligence receive the PIRP?

> What perspective did it apply?

> What capability made the relay productive?

> What changed because of the relay?

Thus:

```text id="szbgzq"
Provenance:
Where did it come from?

Relay Context:
Why did it become productive here,
and what happened next?
```

The two structures are complementary.

---

## 5. A Canonical Relay Event

A canonical relay can be represented as:

```text id="xqkq6p"
Source Intelligence
        |
        v
     PIRP-X
        |
        | Publish / Transfer
        v
Receiving Intelligence
        |
        +---- Context
        +---- Perspective
        +---- Capability
        +---- Tool
        |
        v
Continuation
        |
        v
Structural Delta
        |
        +---- New Evidence
        +---- New Relation
        +---- New Branch
        +---- New Failure
        +---- New Interface
        |
        v
     PIRP-X'
```

The relay is therefore not simply an edge between two people.

It is a structured computational event.

---

## 6. The Receiver Can Be Many Things

The receiving intelligence does not need to be human.

It may be:

```text id="ok4lh3"
Human
LLM
Specialized Model
Algorithm
Search Engine
Database
Simulator
Formal Prover
Runtime PIRU
Team
Organization
Hybrid Human-AI System
```

This matters because Collective Intelligence should not assume one type of participant.

The relevant question is:

> **Which intelligence configuration can produce useful continuation?**

---

## 7. The Source Can Also Be Many Things

Likewise, a PIRP may originate from:

```text id="u1sgzx"
Human insight
AI inference
Runtime anomaly
Experiment
Paper
Repository
Failed attempt
Counter-evidence
Structural search
Existing PIRU
Another relay
```

Therefore the Collective Intelligence system is inherently heterogeneous.

---

## 8. Why the PIRP Was Picked Up

One important Relay Context field is:

> **Reason for Pickup**

Possible reasons include:

```text id="blgzm2"
structural similarity
domain relevance
known contradiction
available capability
personal interest
runtime need
search result
recommendation
dispatch
open challenge
unexpected analogy
```

This field is valuable because successful pickup patterns can later be learned.

---

## 9. Perspective

Two equally capable intelligences may approach the same PIRP differently.

For example:

```text id="t5c86s"
PIRP-X
 |
 +----> Agent-A -> Graph Perspective
 |
 +----> Agent-B -> Metric Perspective
 |
 +----> Agent-C -> Biological Perspective
 |
 +----> Agent-D -> Runtime Perspective
```

Each perspective may reveal a different Structural Delta.

Thus Relay Context should preserve not only **who**, but **how they looked at the problem**.

---

## 10. Perspective Transfer

Sometimes the most important contribution is not an answer.

It is a perspective imported from elsewhere.

Suppose:

```text id="rx9l6u"
Domain-A Problem
      |
      v
Agent-B
      |
      | imports Perspective from Domain-C
      v
New Structural Interpretation
```

The transferred perspective may unlock a previously stalled PIRP.

This is a form of **Transfer Inspiration**.

If recorded, the system can later learn:

> Which perspectives transfer productively across which structural problem classes?

---

## 11. Capability

Relay Context should also preserve the capability that made the continuation possible.

For example:

```text id="8qjx7m"
Agent-B
 |
 +---- formal proof
 +---- domain expertise
 +---- simulation
 +---- structural search
```

The useful relationship is not:

```text id="6s8u38"
Agent-B is good.
```

It is:

```text id="r8jz3u"
Under Context C,
for PIRP Type X,
Capability K of Agent-B
produced Structural Delta D.
```

This is much more actionable.

---

## 12. Structural Comparative Advantage

This leads to the concept of:

> **Structural Comparative Advantage**

Comparative advantage should not be treated as a permanent label attached to an intelligence.

Instead it is relational and contextual.

Conceptually:

```text id="81d64r"
PIRP Structure
      +
Context
      +
Agent Capability
      |
      v
Expected Structural Growth
```

An agent may be highly effective for one PIRP family and ineffective for another.

Therefore:

> **Qualification is contextual, not absolute.**

---

## 13. Transformation

A relay may transform the PIRP.

Possible transformations include:

```text id="5r5u2x"
specialization
generalization
translation
implementation
validation
contradiction
decomposition
composition
formalization
reframing
```

The transformation should be preserved because it describes how intelligence changed.

---

## 14. Structural Delta

The most important output of a relay is often the **Structural Delta**.

Examples include:

```text id="eow4yd"
new relation
new branch
new evidence
new counter-evidence
new algorithm
new implementation
new failure
new interface
new problem
new PIRU
```

A relay can therefore be evaluated not merely by whether the receiver participated, but by what structural change occurred.

---

## 15. Relay Outcome

A relay may have several outcomes.

```text id="5c3lfz"
Successful Extension
Partial Extension
Useful Failure
Counter-Evidence
No Progress
Mislocalization
New Open PIRP
New PIRU
Composite PIRP
```

Even unsuccessful relays may be informative.

Repeated mislocalization teaches the system where not to dispatch similar PIRPs.

---

# Part II — Knowledge CallingGraph

## 16. From Documents to Intelligence Relations

Traditional knowledge systems often represent relations among documents.

For example:

```text id="u8nshh"
Paper-A -> cites -> Paper-B
```

PIRP/PIRU allows a richer graph.

```text id="jbm1qy"
PIRP-A
 |
 +---- extends ----> PIRP-B
 |
 +---- contradicts -> PIRP-C
 |
 +---- validates ---> PIRP-D
 |
 +---- composes ----> PIRP-E
```

This graph captures semantic intelligence relations.

We call this:

> **Knowledge CallingGraph**

---

## 17. Knowledge CallingGraph Definition

A Knowledge CallingGraph answers:

> **What intelligence structurally depends on, extends, contradicts, validates, specializes, generalizes, or composes with what other intelligence?**

Possible edge types include:

```text id="y4ag51"
derived-from
depends-on
extends
specializes
generalizes
implements
validates
contradicts
supports
composes-with
opens-question
resolves
```

The graph describes structural relationships among intelligence objects.

---

## 18. Example Knowledge CallingGraph

```text id="6f9jn8"
             PIRP-A
             /    \
            /      \
      extends      contradicts
          /          \
         v            v
      PIRP-B        PIRP-C
         |
      validates
         |
         v
      PIRU-D
```

This is already richer than a citation graph.

But it still does not explain how the intelligence moved between participants.

For that, we need another graph.

---

# Part III — Relay CallingGraph

## 19. Relay CallingGraph Definition

We define:

> **Relay CallingGraph — a graph representing how PIRPs move between intelligences, under what contexts and perspectives, and what Structural Deltas result from those transfers.**

Its nodes may include:

```text id="5plj51"
PIRPs
PIRUs
Humans
AIs
Tools
Teams
Contexts
```

Its edges represent structured relay events.

---

## 20. Example Relay CallingGraph

```text id="92rybh"
PIRP-X
  |
  | Relay-1
  v
Agent-A
  |
  | Structural Delta D1
  v
PIRP-X1
  |
  | Relay-2
  v
Agent-B
  |
  | Structural Delta D2
  v
PIRP-X2
```

The relay history becomes a computational trajectory.

---

## 21. Parallel Relay

One PIRP may be relayed to multiple intelligences.

```text id="dqs6j3"
                PIRP-X
              /    |    \
             /     |     \
            v      v      v
        Agent-A Agent-B Agent-C
            |      |      |
            v      v      v
        PIRP-A  PIRP-B  PIRP-C
```

This supports parallel exploration.

Different agents may contribute:

* different perspectives,
* different evidence,
* different failures,
* different solutions.

The graph preserves diversity rather than forcing premature convergence.

---

## 22. Relay Branching

A relay can create branches.

```text id="kqf5ph"
PIRP-X
  |
  v
Agent-A
 /     \
v       v
PIRP-Y PIRP-Z
```

One receiving intelligence may discover that the original PIRP actually contains two distinct problems.

Thus relay can cause structural decomposition.

---

## 23. Relay Composition

The reverse can also occur.

```text id="w3l37x"
PIRP-A ----\
            \
             > Agent-X -> PIRP-C
            /
PIRP-B ----/
```

Agent-X recognizes that two apparently separate PIRPs share a common structure.

Relay therefore can create composition.

---

## 24. Relay Chains

Long-running research may form relay chains:

```text id="1k3f4q"
Human-A
   |
 PIRP-1
   |
 AI-B
   |
 PIRP-2
   |
 Team-C
   |
 PIRP-3
   |
 Human-D
```

The final result contains intelligence accumulated across multiple participants.

No single participant necessarily possessed the entire path.

This is a form of distributed computation.

---

## 25. Relay Context as Edge Intelligence

A major consequence follows.

If a relay edge contains:

```text id="3h27tu"
Source
Receiver
Context
Perspective
Capability
Transformation
Evidence
Outcome
```

then the edge itself contains meaningful intelligence.

Therefore:

> **An edge can itself be treated as a PIRP.**

This creates recursive structure.

---

## 26. Node = PIRP, Edge = PIRP

The graph can be interpreted recursively:

```text id="ymssas"
Node      = PIRP
Edge      = PIRP
Subgraph  = PIRP
Graph     = PIRP
```

This does not mean every graph object must be implemented identically.

It means each can potentially be treated as a bounded portable intelligence structure.

For example:

```text id="7rfj4e"
Relay Edge PIRP
 |
 +---- Source PIRP
 +---- Receiver
 +---- Context
 +---- Transformation
 +---- Outcome
```

The edge describes how another PIRP became productive.

---

## 27. PIRPs Can Describe Relations Among PIRPs

This recursive property is important.

A PIRP may represent:

```text id="0q6vli"
an algorithm
```

Another PIRP may represent:

```text id="w8d4j8"
the relation between that algorithm
and a particular problem class
```

Another may represent:

```text id="6p5wcx"
how a human discovered that relation
through transfer from another domain
```

Thus:

> **PIRPs can describe relations among PIRPs.**

This allows higher-order structural intelligence.

---

# Part IV — Collective Intelligence CallingGraph

## 28. Combining the Two Graphs

The Knowledge CallingGraph answers:

> What intelligence is structurally related to what intelligence?

The Relay CallingGraph answers:

> How did intelligence actually move and grow?

Together:

```text id="5hj5qs"
Knowledge CallingGraph
          +
Relay CallingGraph
          +
Context
          +
Agent Capability
          +
Outcome
          |
          v
Collective Intelligence CallingGraph
```

This graph contains both knowledge structure and growth history.

---

## 29. Canonical Collective Intelligence Event

A canonical event can be represented as:

```text id="kk0e19"
Intelligence A
      |
      v
   PIRP-X
      |
      | Relay
      v
   Agent-B
      |
      +---- Context C
      |
      +---- Perspective P
      |
      +---- Capability K
      |
      v
Structural Delta D
      |
      +---- Evidence E
      |
      v
Intelligence F
```

This sequence contains much more information than:

```text id="bzb8f0"
A cites F
```

It captures an actual intelligence-growth event.

---

## 30. Collective Intelligence History

Repeated events produce:

> **Collective Intelligence History**

This history records:

```text id="e30j1e"
what existed
who received it
why they received it
what they knew
which perspective they used
what they changed
what succeeded
what failed
what emerged next
```

This history can itself be folded into reusable intelligence.

---

## 31. Known-Knowledge Becomes a Trajectory

Known-Knowledge is often modeled as a current state:

```text id="esj4mx"
Known-Knowledge(t)
```

Relay history suggests a richer model:

```text id="s2v79v"
Known-Knowledge
+
Origin
+
Derivation
+
Relay History
+
Failed Alternatives
+
Successful Transfers
+
Remaining Open Branches
```

Knowledge becomes not merely a state.

It becomes a trajectory.

---

## 32. Knowledge Trajectory

A Knowledge Trajectory may look like:

```text id="9uxs9r"
PIRP-A
  |
  | Agent-B / Perspective-X
  v
PIRP-B
  |
  | Agent-C / Counter-Evidence
  v
PIRP-C
  |
  | AI-D / Structural Search
  v
PIRP-D
```

The trajectory explains how current knowledge came to exist.

This can improve:

* interpretation,
* trust,
* transfer,
* debugging,
* future localization.

---

# Part V — Learning from Relay

## 33. Every Relay Is a Training Example

Suppose the system observes:

```text id="m1uew9"
PIRP Signature
      +
Agent Capability Signature
      +
Relay Context
      |
      v
Structural Delta
      +
Outcome
```

This event becomes a training example for future relay decisions.

Therefore:

> **Every relay teaches the system how to relay better next time.**

---

## 34. Successful Relay Pattern

Suppose repeated history shows:

```text id="h8yrqw"
PIRP Type X
+
Context C
+
Perspective P
+
Capability K
      |
      v
High-Value Structural Growth
```

The system can learn a reusable pattern.

This pattern may later influence localization.

---

## 35. Failed Relay Pattern

Failures are equally useful.

Suppose:

```text id="id47g5"
PIRP Type X
+
Agent Type Y
+
Context C
      |
      v
Repeated No Progress
```

This does not prove Agent Type Y is globally unsuitable.

But it provides evidence against that particular relay pattern.

Thus relay failure becomes Counter-Evidence for future dispatch.

---

## 36. Comparative Advantage Emerges from History

Instead of manually declaring:

```text id="l0o6us"
Agent-A is expert in X.
```

the system can observe:

```text id="kngdfd"
Across PIRPs structurally similar to X,
under contexts C1, C2, C3,
Agent-A repeatedly produced useful Structural Deltas.
```

This is a stronger basis for capability estimation.

Structural Comparative Advantage can emerge from actual relay history.

---

## 37. Hidden Capability Discovery

An agent may repeatedly succeed on PIRPs outside its nominal category.

For example:

```text id="4rr61k"
Official Domain: A

Observed Relay Success:
PIRP-B
PIRP-C
PIRP-D
```

Structural analysis may reveal a shared capability:

```text id="jdt9zk"
All require Pattern K.
```

The system discovers a hidden capability not captured by conventional labels.

This is another form of intelligence produced by the Relay Graph.

---

## 38. Cross-Domain Transfer Discovery

Suppose:

```text id="v98bdl"
Domain-A PIRP
   |
   v
Agent-X
   |
   | imports method from Domain-B
   v
Successful Growth
```

Repeated events may reveal:

```text id="n3w81q"
Domain-B Perspective
       |
       v
Useful for PIRP Family A
```

This relationship may not be visible in traditional disciplinary organization.

Relay history exposes it empirically.

---

## 39. Transfer Inspiration as a Learnable Structure

Transfer inspiration is often treated as mysterious creativity.

Relay Context can make part of it explicit.

For example:

```text id="yknc75"
Source Structure S
      |
      v
Agent Perspective P
      |
      v
Analogy
      |
      v
Target PIRP T
      |
      v
Structural Delta D
```

If enough such events are preserved, the system may learn which kinds of structural analogy repeatedly generate useful growth.

---

# Part VI — Relay Graph as Structural Memory

## 40. The Graph Remembers More Than Results

A conventional knowledge base may preserve:

```text id="7v8ylk"
Final Result
```

A Relay Graph preserves:

```text id="l1w3mg"
Final Result
+
Path
+
Participants
+
Context
+
Perspectives
+
Failures
+
Transformations
```

This is richer structural memory.

---

## 41. Why Path Matters

Two identical conclusions may have different histories.

Path A:

```text id="trpqku"
Hypothesis
  |
  v
Direct Validation
```

Path B:

```text id="lbf1fp"
Hypothesis
  |
  v
Failure
  |
  v
Counter-Evidence
  |
  v
Reframing
  |
  v
Validation
```

The final conclusion may look similar.

But Path B contains more information about:

* failure conditions,
* alternative interpretations,
* robustness,
* future search.

Therefore the path itself should not be discarded.

---

## 42. Relay Graph as Foldable Experience

Relay histories can be accumulated:

```text id="53ml24"
Relay Event 1
Relay Event 2
Relay Event 3
...
Relay Event N
```

Then structurally folded into patterns such as:

```text id="p8mr2m"
For PIRP Family X,
Perspective P
under Context C
often produces useful Growth D.
```

Thus Relay Context becomes raw material for Structural Folding.

---

## 43. Folded Relay Intelligence

The resulting folded structure may support future dispatch.

```text id="knj60d"
Historical Relay Graph
        |
        v
Structural Folding
        |
        v
Relay Pattern
        |
        v
Future Localization
```

This creates a closed learning loop:

```text id="9p1rhv"
Relay
  |
  v
Observe
  |
  v
Record
  |
  v
Fold
  |
  v
Improve Relay
```

---

## 44. Relay Intelligence as Per-Node Intelligence

The Relay Graph itself may eventually develop Per-Node Intelligence.

For a given PIRP node, the system may know:

```text id="yq63fy"
who previously handled similar PIRPs
which perspectives worked
which tools were useful
which contexts caused failure
which branches remain open
```

Thus the graph can participate in deciding its own next growth path.

This closes an important conceptual loop:

> **Per-Node Intelligence can help produce PIRPs, and PIRP relay history can in turn enrich Per-Node Intelligence.**

---

# Part VII — A Preliminary Relay Context Schema

## 45. Relay Context Record

A conceptual record may look like:

```text id="a1btxs"
RelayContext

relayId
sourcePIRP
sourceAgent
receivingAgent

context
reasonForPickup
perspective

capabilitiesUsed
toolsUsed

transformation
evidenceAdded
counterEvidenceAdded

structuralDelta
outcome

derivedPIRPs

timestamp
policy
```

This is intentionally conceptual.

It is not yet proposed as a final implementation standard.

---

## 46. Minimal Relay Context

A practical MVP may require much less:

```text id="1i40kl"
sourcePIRP
receivingAgent
context
perspective
structuralDelta
outcome
```

Even this small structure is far richer than an ordinary transfer log.

The implementation threshold is therefore relatively low.

---

## 47. Relay Edge Types

Possible Relay CallingGraph edge types may include:

```text id="mx2w6r"
picked-up-by
continued-by
validated-by
implemented-by
challenged-by
specialized-by
generalized-by
composed-by
transferred-by
reframed-by
```

These may eventually become typed PIRUs themselves.

---

# Part VIII — Relay and Collective Learning

## 48. Collective Learning Is Not Only Knowledge Accumulation

A naive Collective Learning model is:

```text id="myh6xb"
More Participants
      |
      v
More Knowledge
```

A stronger model is:

```text id="y5a3of"
More Participants
      |
      v
More PIRPs
      |
      v
More Relay Events
      |
      v
Better Relay History
      |
      v
Better Localization
      |
      v
More Productive Structural Growth
```

Thus Collective Learning improves not only what the system knows.

It improves how intelligence moves.

---

## 49. The System Learns to Relay

This leads to a key proposition:

> **Collective Learning does not only make the Knowledge Graph larger; it makes the system increasingly good at relaying.**

The system learns:

```text id="wh7i80"
what should move
where it should move
who should receive it
under what context
through which perspective
with which tools
```

This is a distinct intelligence capability.

---

## 50. Three Core Objects

The framework can be summarized using three objects.

### PIRP

> **Relayable intelligence.**

### Relay

> **Transfer and continuation of computation.**

### Relay Graph

> **Structural memory of how Collective Intelligence actually grows.**

Together:

```text id="l2owgk"
PIRP
 |
 v
Relay
 |
 v
Structural Delta
 |
 v
Relay Graph
 |
 v
Collective Learning
```

---

## 51. Relay Is Distributed Computation

Suppose no single intelligence can solve a problem.

But:

```text id="56lgxn"
Agent-A
  |
  v
PIRP-1
  |
  v
Agent-B
  |
  v
PIRP-2
  |
  v
Agent-C
  |
  v
PIRP-3
```

The chain as a whole performs computation.

This suggests:

> **Relay is a mechanism for computation across intelligence boundaries.**

The computation is distributed not merely across machines, but across heterogeneous intelligences.

---

## 52. The Collective Intelligence CallingGraph

A canonical high-level model is:

```text id="dmlwp2"
             PIRP-A
            /      \
           /        \
      Relay-1      Relay-2
         |            |
         v            v
      Agent-B      Agent-C
         |            |
    Context-X      Context-Y
         |            |
 Perspective-P   Perspective-Q
         |            |
         v            v
      Delta-B       Delta-C
         |            |
         v            v
      PIRP-B        PIRP-C
           \          /
            \        /
             v      v
             PIRP-D
                |
                v
         Collective Growth
```

This graph contains:

* intelligence objects,
* agents,
* contexts,
* perspectives,
* transformations,
* outcomes,
* growth.

It is not merely a knowledge graph.

It is a graph of intelligence computation.

---

# Part IX — Core Principles

## 53. Principle 1 — Relay Context Is Intelligence

> **The conditions and consequences of an intelligence transfer are themselves reusable intelligence.**

---

## 54. Principle 2 — Provenance Is Necessary but Insufficient

> **Knowing where intelligence came from does not tell us why it became productive in a particular receiving intelligence.**

---

## 55. Principle 3 — Relay Edges Can Be PIRPs

> **A relation describing how one PIRP was continued can itself become a portable intelligence object.**

---

## 56. Principle 4 — Qualification Is Contextual

> **An intelligence is not universally qualified; it may possess Structural Comparative Advantage for particular PIRP structures under particular contexts.**

---

## 57. Principle 5 — Perspective Is Part of Relay

> **The same PIRP may produce different growth when viewed through different structural perspectives.**

---

## 58. Principle 6 — Failure Is Relay Training Data

> **Unproductive relay events help improve future localization.**

---

## 59. Principle 7 — Transfer Inspiration Can Be Learned

> **Cross-domain perspective transfers that repeatedly produce useful growth can become reusable structural patterns.**

---

## 60. Principle 8 — Knowledge Is a Trajectory

> **Current Known-Knowledge is more informative when its derivation, relay history, failed alternatives, and open branches are preserved.**

---

## 61. Principle 9 — Collective Learning Includes Learning How to Relay

> **A mature intelligence system improves not only its knowledge structures, but its ability to route intelligence toward productive continuation.**

---

## 62. Principle 10 — Relay Is Computation Across Intelligence Boundaries

> **A chain of humans, AIs, tools, and PIRUs can collectively perform computation that no single participant completes alone.**

---

# Part X — Research Questions

## 63. Relay Representation

What is the minimum useful Relay Context?

---

## 64. Perspective Representation

How should a perspective be encoded without forcing it into an overly rigid taxonomy?

---

## 65. Capability Signatures

How should agent capabilities be represented and updated from actual relay outcomes?

---

## 66. Structural Comparative Advantage

How can contextual comparative advantage be estimated without reducing agents to static rankings?

---

## 67. Relay Quality

What constitutes a high-quality relay?

Possible dimensions include:

```text id="op8p4d"
useful structural delta
continuation cost
validation quality
novelty
portability
future reuse
```

---

## 68. Relay Failure

How should mislocalization and unproductive relays influence future dispatch?

---

## 69. Recursive PIRPs

How should PIRPs representing edges, subgraphs, and graphs be nested and referenced?

---

## 70. Privacy and Governance

Which Relay Context fields should remain private, aggregated, anonymized, or policy-restricted?

---

## 71. Structural Folding

How can large Relay Graphs be folded into reusable relay patterns?

---

## 72. Collective Intelligence Runtime

Can Knowledge CallingGraph + Relay CallingGraph become an executable runtime for distributed intelligence growth?

These questions lead directly to the next stage:

> **Relay Localization.**

---

# 73. Conclusion

Portable Intelligence creates a new class of computational history.

It is not enough to preserve:

```text id="v7pxi3"
PIRP-A -> PIRP-B
```

We increasingly want to preserve:

```text id="eaz9r9"
PIRP-A
   |
   | received by
   v
Agent-B
   |
   +---- Context C
   +---- Perspective P
   +---- Capability K
   +---- Tool T
   |
   v
Structural Delta D
   |
   v
PIRP-B
```

This structure tells us not only what intelligence changed, but how Collective Intelligence produced that change.

That history can reveal:

* Structural Comparative Advantage,
* productive cross-domain transfer,
* hidden capabilities,
* repeated failure patterns,
* useful perspectives,
* productive tool combinations,
* and future relay opportunities.

The result is a transition:

```text id="agx3uh"
Citation Graph
      |
      v
Knowledge CallingGraph
      |
      +
Relay CallingGraph
      |
      v
Collective Intelligence CallingGraph
```

The central principle is:

> **The history of how intelligence was received, interpreted, transformed, and continued is itself reusable intelligence.**

Once this history becomes explicit, every relay event becomes more than a collaboration event.

It becomes a learning event for the intelligence system itself.

The system can gradually learn:

```text id="8g6bmu"
which PIRPs
should go to
which intelligences
under which contexts
through which perspectives
to produce useful structural growth
```

At that point, Collective Learning acquires a new capability:

> **it learns how to relay.**

The next question is therefore no longer merely how to record relay.

It is:

> **How can a PIRP actively find the next intelligence most structurally qualified to continue its growth?**

That is the problem of Relay Localization.

---

## Next Article

**PIRP-PIRU-007 — Relay Localization and Computational Growth Dispatch**

The next article develops two complementary forms of localization:

> **Structural Localization — Where is the relevant intelligence?**

and:

> **Relay Localization — Who or what should continue this intelligence?**

It then develops a broader Computational Growth Localization problem in which PIRP, Knowledge, Agent, Tool, Context, and Policy are jointly localized toward productive Structural Growth.

