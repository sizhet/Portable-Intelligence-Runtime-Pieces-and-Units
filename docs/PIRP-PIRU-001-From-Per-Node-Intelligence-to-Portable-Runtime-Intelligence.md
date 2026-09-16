# PIRP-PIRU-001 — From Per-Node Intelligence to Portable Runtime Intelligence

## Abstract

As structural intelligence systems move from static representation toward runtime triggering, localization, and computational growth, a recurring abstraction gap becomes increasingly visible.

A runtime node may produce a value.  
It may produce a state transition.  
It may trigger another computation or structural branch.

But increasingly, a node may produce something richer:

> a bounded piece of intelligence that carries structure, state, executable behavior, trigger semantics, memory, policy, interfaces, and potential for further growth.

Traditional abstractions such as state, function, class, service, agent, CallingGraph node, CCC, or DNA capture important perspectives of this object, but none of them fully names the object itself.

This article introduces two working concepts:

- **PIRP — Portable Intelligence Runtime Piece**
- **PIRU — Portable Intelligence Runtime Unit**

PIRP emphasizes the discovery and preservation of runtime intelligence before forcing it into a predefined computational category.

PIRU emphasizes the formalization of such intelligence into a bounded, typed, testable, reusable, and composable runtime unit.

The central hypothesis is that portable runtime intelligence may deserve treatment as a first-class computational object.

This perspective extends Per-Node Intelligence toward a broader runtime model in which intelligence can be instantiated, executed, observed, transferred, localized, composed, published, and structurally grown.

---

## 1. The Missing Runtime Object

Structural intelligence research repeatedly encounters an object that is easy to recognize operationally but difficult to name precisely.

We often know what it does.

It may:

- receive local context,
- inspect state,
- evaluate structural conditions,
- invoke a CCC,
- select a CallingPath,
- trigger another node,
- apply a policy,
- preserve local memory,
- produce an action,
- expose evidence,
- create a new branch,
- or modify the structure through which future computation proceeds.

Yet when we try to describe this object using conventional software terminology, the description becomes fragmented.

Is it a function?

Partly.

Is it state?

Partly.

Is it an object?

Possibly.

Is it a rule?

Sometimes.

Is it a CallingGraph node?

It may live at one.

Is it a CCC?

It may contain or invoke one.

Is it an agent?

Usually that term is too large and carries assumptions that are not required.

The problem is not that these concepts are wrong.

The problem is that each describes only one perspective of a richer runtime phenomenon.

The missing abstraction is the runtime intelligence itself.

---

## 2. From Per-Node Computation to Per-Node Intelligence

A conventional computational node can be modeled approximately as:

```text
Input
  |
  v
Node
  |
  v
Output
````

The node performs computation and returns a result.

A more advanced runtime may allow the node to modify state:

```text
Input + State
      |
      v
     Node
      |
      v
Output + New State
```

Structural intelligence adds another dimension.

A node may determine not only a value, but also the structure of subsequent computation:

```text
Context
   |
   v
Per-Node Intelligence
   |
   +----> Value / State
   |
   +----> Structural Trigger
   |
   +----> Next Node / Branch / CallingPath
```

This is already more than ordinary functional computation.

The node participates in deciding:

> What computation should exist next?

When computational growth is added, the problem becomes deeper.

A node may contribute not merely to selecting an existing structure, but to producing, specializing, composing, or growing new runtime intelligence.

At that point, "node output" becomes too weak a description.

---

## 3. Three Classes of Per-Node Output

A useful starting point is to distinguish three broad forms of output.

### 3.1 Value or State Output

The first form is conventional:

```text
Node
  |
  v
Value / State
```

Examples include:

* classification,
* score,
* probability,
* status,
* measurement,
* decision value,
* updated local state.

The primary question is:

> **What is true, computed, or stored now?**

This remains essential, but it does not describe structural intelligence by itself.

---

### 3.2 Structural Trigger Output

The second form determines subsequent computation:

```text
Node
  |
  v
Trigger
  |
  +----> Branch A
  |
  +----> Branch B
  |
  +----> CallingPath C
```

Possible outputs include:

* trigger,
* route,
* branch,
* CallingPath,
* next node,
* structural dispatch,
* search direction,
* growth direction.

The primary question becomes:

> **What should execute next?**

This is a major step from value computation toward structural intelligence.

---

### 3.3 Portable Runtime Intelligence Output

The third form is more complex.

A node may produce or expose a runtime structure such as:

```text
+----------------------------------+
| Portable Runtime Intelligence    |
|                                  |
|  Structure                       |
|  State                           |
|  Computation                     |
|  Trigger Semantics               |
|  Local Memory                    |
|  Policy                          |
|  Interfaces                      |
|  Evidence                        |
|  Growth Hooks                    |
+----------------------------------+
```

This object is neither merely a value nor merely a trigger.

It may itself be executable.

It may carry state.

It may contain structural knowledge.

It may move to another runtime context.

It may be localized to another node.

It may be composed with other runtime intelligence.

It may be observed, validated, modified, branched, published, reused, or grown.

The primary question is no longer merely:

> What is the result?

or:

> What executes next?

It becomes:

> **What bounded piece of intelligence now exists and can continue to participate in computation?**

This is the abstraction gap addressed by PIRP and PIRU.

---

## 4. PIRP — Portable Intelligence Runtime Piece

We introduce the working term:

> **PIRP — Portable Intelligence Runtime Piece**

A preliminary definition is:

> **A PIRP is a recognizable piece of runtime intelligence that can carry enough structure, context, state, behavior, or growth potential to be transferred, instantiated, continued, composed, or evolved beyond the immediate computation that produced it.**

The word **Piece** is intentional.

It does not require that the object already satisfy a rigid engineering specification.

A newly emerging intelligence structure may be:

* irregular,
* partially bounded,
* context-dependent,
* heterogeneous,
* incompletely typed,
* only partially understood,
* or still structurally growing.

Such an object should not be discarded merely because it does not yet fit an existing computational category.

PIRP therefore emphasizes preservation before normalization.

A useful principle is:

> **Preserve the runtime intelligence piece first; understand and formalize it second.**

---

## 5. PIRU — Portable Intelligence Runtime Unit

A second working term is:

> **PIRU — Portable Intelligence Runtime Unit**

PIRU describes the more formal side of the same research space.

A PIRU should normally have clearer properties such as:

* explicit identity,
* defined boundaries,
* typed inputs and outputs,
* known runtime requirements,
* observable behavior,
* testable semantics,
* reusable interfaces,
* composition rules,
* lifecycle rules,
* governance constraints.

A preliminary definition is:

> **A PIRU is a bounded, formalized, executable, portable, composable, observable, and evolvable unit of runtime intelligence.**

The distinction can be summarized as:

| PIRP                | PIRU                      |
| ------------------- | ------------------------- |
| discovered          | formalized                |
| emergent            | normalized                |
| open-boundary       | bounded                   |
| heterogeneous       | typed                     |
| growth-first        | interface-aware           |
| identity may emerge | identity is explicit      |
| preserves novelty   | supports controlled reuse |

PIRP and PIRU should therefore not be treated prematurely as competing names.

They may describe different phases of the same intelligence lifecycle.

---

## 6. PIRP and PIRU as a Duality

A possible lifecycle is:

```text
Emergent Runtime Intelligence
            |
            v
           PIRP
            |
            | recognition
            | boundary discovery
            | validation
            | typing
            | interface extraction
            v
           PIRU
            |
            | reuse
            | localization
            | composition
            | execution
            v
     Runtime Interaction
            |
            | new evidence
            | specialization
            | structural growth
            v
        New PIRP(s)
```

This suggests a recurring loop:

> **PIRP -> PIRU -> Runtime -> Growth -> New PIRP**

PIRP protects emerging intelligence from premature classification.

PIRU makes sufficiently understood intelligence operationally manageable.

Both are needed.

Too much PIRP without formalization can produce uncontrolled complexity.

Too much PIRU without PIRP preservation can suppress structural novelty.

The duality therefore reflects a deeper balance between:

* discovery and engineering,
* emergence and normalization,
* open-ended growth and controlled execution.

---

## 7. Why Existing Software Concepts Are Not Enough

Traditional abstractions remain useful, but they answer different questions.

| Abstraction  | Primary Question                                         |
| ------------ | -------------------------------------------------------- |
| State        | What is stored?                                          |
| Function     | What computation is performed?                           |
| Class        | What object structure is defined?                        |
| Service      | What capability is exposed?                              |
| Rule         | What condition maps to what consequence?                 |
| Model        | What mapping or representation has been learned?         |
| Agent        | What entity acts toward goals?                           |
| CallingGraph | What calls or computational relations exist?             |
| CallingPath  | What execution path is followed?                         |
| CCC          | What structural relation or control knowledge is folded? |
| DNA          | How can structural dispatch or triggering be encoded?    |
| PIRP/PIRU    | What bounded intelligence exists and acts here?          |

PIRP/PIRU does not replace these abstractions.

Instead, it provides a possible runtime carrier within which several of them may coexist.

For example:

```text
PIRP
 |
 +-- State
 |
 +-- Function
 |
 +-- CCC
 |
 +-- Trigger
 |
 +-- Policy
 |
 +-- CallingPath fragment
 |
 +-- Local memory
 |
 +-- Growth interface
```

The exact composition is not fixed.

Different PIRPs may contain different combinations.

This heterogeneity is not necessarily a defect.

It may be an intrinsic property of runtime intelligence.

---

## 8. Minimum Properties of Portable Runtime Intelligence

If PIRP/PIRU is to become a useful research abstraction, it must not become a synonym for "anything intelligent."

Several properties are therefore important.

### 8.1 Identifiable

A PIRP must be distinguishable sufficiently to be referred to, transferred, observed, or continued.

Identity does not necessarily require a rigid class definition.

But there must be enough continuity to say:

> This is the intelligence piece being examined.

---

### 8.2 Executable or Operationally Actionable

A PIRP should participate in computation or enable computation.

Pure passive data alone is insufficient.

Operational participation may include:

* execution,
* triggering,
* routing,
* transformation,
* evaluation,
* structural search,
* decision support,
* generation,
* validation,
* growth.

---

### 8.3 Portable

Portability is fundamental.

At minimum, the intelligence should have the potential to survive movement across some boundary:

```text
Node A       -> Node B
Runtime A    -> Runtime B
Context A    -> Context B
Agent A      -> Agent B
System A     -> System B
```

Later articles will extend this idea beyond computational portability toward portability across intelligences.

---

### 8.4 Composable

A PIRP should be capable, at least in principle, of participating in larger intelligence structures.

For example:

```text
PIRP-A + PIRP-B
        |
        v
Composite PIRP-C
```

or:

```text
PIRP-A
   |
   v
PIRP-B
   |
   v
PIRP-C
```

Composition may be:

* sequential,
* hierarchical,
* graph-based,
* policy-governed,
* context-conditioned,
* or dynamically localized.

---

### 8.5 Observable

Runtime intelligence should expose enough information to support:

* tracing,
* validation,
* debugging,
* comparison,
* governance,
* learning.

A useful trace might contain:

```text
PIRP-ID
Input
Context
State-Before
Trigger
Computation
Output
Evidence
State-After
Structural-Delta
Growth-Event
```

Without observability, runtime intelligence becomes difficult to validate or govern.

---

### 8.6 Evolvable

This property becomes critical under Computational Growth Intelligence.

A PIRP/PIRU may support operations such as:

```text
specialize
branch
compose
merge
replace
update
promote
retire
```

The exact operations depend on the runtime and policy environment.

The key point is that the intelligence unit is not necessarily immutable.

It may participate in its own structural evolution.

---

## 9. From Structural Growth to Intelligence Growth

A major motivation for PIRP/PIRU appears when asking a deceptively simple question:

> **What exactly is growing in Computational Growth Intelligence?**

Possible answers include:

* the CallingGraph,
* the number of nodes,
* the CCC structure,
* the DNA structure,
* the policy space,
* the memory,
* the search tree,
* the runtime state.

All can be correct from particular perspectives.

But PIRP/PIRU introduces another possibility:

> **The population and structure of runtime intelligence itself may be growing.**

Consider:

```text
PIRP-0
  |
  | experience
  v
PIRP-1
  |
  | specialization
  +----------+
  |          |
  v          v
PIRP-1A   PIRP-1B
  |          |
  +----+-----+
       |
       | composition
       v
     PIRP-2
       |
       | formalization
       v
     PIRU-2
```

Growth is no longer represented only as graph expansion.

It may include:

* differentiation,
* specialization,
* composition,
* replacement,
* migration,
* formalization,
* reuse,
* structural mutation.

This changes the unit of analysis.

Instead of asking only:

> How did the computational graph change?

we can also ask:

> **How did the runtime intelligence population change?**

---

## 10. The AI-Protein Analogy

A useful but deliberately limited analogy can be made with biological systems.

Structural encodings such as CCC or DNA-like dispatch structures can be viewed as forms of reusable structural specification.

PIRP/PIRU can be viewed as active runtime machinery derived from, carrying, interacting with, or modifying such structural information.

Conceptually:

```text
CCC / DNA
Structural Encoding
      |
      | localization
      | instantiation
      | unfolding
      v
PIRP / PIRU
Active Runtime Intelligence
      |
      | execution
      | interaction
      | evidence
      v
Runtime Behavior
      |
      | adaptation
      | structural growth
      v
New Structure
```

In this limited sense, PIRP/PIRU may play a role analogous to an **AI protein**:

> not merely storing structural information, but participating directly in runtime behavior.

The analogy should not be interpreted literally.

Biological DNA, RNA, proteins, cells, regulation, and development form a far richer system than this computational abstraction.

The value of the analogy is structural:

> **encoding and active machinery are different roles.**

PIRP/PIRU helps make the active runtime role explicit.

---

## 11. Size Should Not Define the Concept

The word "Piece" should not imply that PIRPs must be tiny.

A PIRP may represent:

* one trigger,
* one rule,
* one CCC,
* one localized algorithm,
* one runtime component,
* one CallingPath fragment,
* one unresolved problem,
* one reusable reasoning structure,
* one research artifact,
* or a much larger bounded intelligence structure.

The relevant criterion is not byte size or code size.

The important question is:

> **Can the intelligence be treated as a sufficiently coherent identity that can be carried, received, localized, continued, composed, validated, or grown?**

A small trigger may qualify.

A large research artifact may also qualify.

This allows PIRP/PIRU to operate across multiple scales.

---

## 12. Portability Is More Than Code Portability

The first interpretation of portability is naturally technical:

```text
detach
store
move
load
instantiate
execute
reuse
```

But portable intelligence potentially has a broader meaning.

An intelligence structure may move:

```text
across nodes
across runtimes
across applications
across domains
across agents
across humans and AIs
across organizations
across generations
```

This broader interpretation becomes especially important when intelligence is published and reused by others.

A portable intelligence object does not merely survive movement of code.

It may survive a change of:

* owner,
* context,
* runtime,
* perspective,
* implementation,
* or generation.

This observation will become central to the broader PIRP/PIRU ecology.

---

## 13. From Runtime Object to First-Class Intelligence Object

The deeper proposal of PIRP/PIRU is therefore not merely to introduce another software class.

The proposal is to consider whether runtime intelligence itself should become a first-class object.

Such an object could potentially be:

```text
identified
stored
searched
localized
loaded
executed
observed
compared
validated
composed
published
transferred
branched
grown
retired
```

Once these operations become explicit, several previously separate research problems begin to connect.

For example:

```text
Structural Search
       |
       v
Find PIRP/PIRU
       |
       v
Localization
       |
       v
Runtime Execution
       |
       v
Observation
       |
       v
Structural Growth
       |
       v
New PIRP/PIRU
```

This provides a possible bridge between:

* Structural Intelligence,
* Per-Node Intelligence,
* Structural Triggering,
* Localization,
* Folding and Unfolding,
* Runtime Intelligence,
* and Computational Growth Intelligence.

---

## 14. A Preliminary Canonical Model

A preliminary conceptual model can be written as:

```text
                 Context
                    |
                    v
          +-------------------+
          |    PIRP / PIRU    |
          |-------------------|
          | Identity          |
          | Structure         |
          | State             |
          | Computation       |
          | Trigger           |
          | Memory            |
          | Policy            |
          | Evidence          |
          | Interfaces        |
          | Growth Hooks      |
          +-------------------+
             |      |      |
             |      |      |
             v      v      v
          Action  Relay   Growth
             |      |      |
             +------+------+
                    |
                    v
             Runtime Delta
                    |
                    v
              New Context
```

This is intentionally not yet a rigid implementation schema.

Its purpose is to expose the research object.

Different systems may instantiate only subsets of these components.

Future engineering work can determine which properties are mandatory for particular classes of PIRU.

---

## 15. A New Question for Runtime Intelligence

Traditional computation asks:

> What does this function return?

Structural computation asks:

> What structure should execute next?

Portable runtime intelligence asks a broader question:

> **What intelligence now exists here, and what can happen to it next?**

Possible answers include:

```text
execute it
move it
localize it
publish it
compose it
validate it
specialize it
branch it
grow it
replace it
retire it
```

This shifts attention from computation as isolated transformation toward intelligence as an evolving runtime object.

---

## 16. Research Hypothesis

The central hypothesis of this article is:

> **As AI systems become increasingly structural, localized, compositional, and growth-capable, a first-class abstraction for portable runtime intelligence becomes necessary.**

PIRP and PIRU are proposed as working concepts for exploring that abstraction.

PIRP emphasizes intelligence as discovered and preserved.

PIRU emphasizes intelligence as formalized and operationalized.

Together they suggest a transition:

```text
Computation
    |
    v
Structural Computation
    |
    v
Per-Node Intelligence
    |
    v
Portable Runtime Intelligence
    |
    v
Composable Intelligence
    |
    v
Computational Growth
```

---

## 17. Open Questions

This first formulation leaves many questions deliberately unresolved.

### 17.1 Boundary

Where does one PIRP end and another begin?

### 17.2 Identity

What must remain invariant for a growing PIRP to preserve identity?

### 17.3 Granularity

Can a trigger, a CCC, a CallingPath, a repository, and a research problem all be PIRPs at different scales?

### 17.4 Portability

What context must travel with a PIRP for another runtime or intelligence to use it correctly?

### 17.5 Formalization

When should an emergent PIRP be promoted into a PIRU?

### 17.6 Composition

How can independently created PIRPs be safely combined?

### 17.7 Growth

When should a PIRP be updated, branched, replaced, or retired?

### 17.8 Governance

Who or what may execute, modify, publish, compose, or propagate a PIRP?

### 17.9 Collective Learning

Can PIRPs become transferable units through which humans and AIs accumulate intelligence collectively?

### 17.10 Open Intelligence

Can unresolved questions, failed attempts, counter-evidence, and partially developed structures themselves become portable intelligence objects?

These questions motivate the remainder of this research series.

---

## 18. From PIRP/PIRU to an Intelligence Ecology

Once portable runtime intelligence becomes explicit, a larger possibility emerges.

PIRPs and PIRUs may eventually be:

```text
created
published
discovered
searched
localized
received
executed
validated
relayed
composed
grown
republished
```

At sufficient scale, this is no longer merely a collection of software components.

It becomes an **intelligence ecology**.

Such an ecology could include:

* humans,
* AI models,
* specialized algorithms,
* tools,
* repositories,
* structural memories,
* open problems,
* validation systems,
* and runtime intelligence units.

The intelligence of the overall system would not reside exclusively in any single participant.

It would also reside in:

* the portable intelligence pieces,
* their relationships,
* their transfer histories,
* their localization mechanisms,
* and the structures through which they continue to grow.

This broader ecology is developed in subsequent articles.

---

## 19. Conclusion

Per-Node Intelligence exposes an important transition in AI systems.

A node need not merely compute a value.

It may determine structural execution.

And beyond structural triggering, it may produce or host something richer:

> **a portable piece of runtime intelligence capable of continuing its existence beyond the computation that produced it.**

PIRP and PIRU provide two complementary perspectives on this object.

**PIRP** preserves emerging intelligence before its final computational category is known.

**PIRU** formalizes sufficiently understood intelligence into a bounded and reusable runtime unit.

The distinction creates a bridge between emergence and engineering:

```text
Emergence
   |
   v
PIRP
   |
   v
Formalization
   |
   v
PIRU
   |
   v
Execution / Composition / Localization
   |
   v
Computational Growth
   |
   v
New PIRP
```

The larger implication is that intelligence may increasingly need to be treated not only as something represented, learned, or computed, but as something that can be:

> **bounded, carried, instantiated, executed, observed, localized, transferred, composed, published, and grown.**

That shift—from intelligence as output to intelligence as a portable runtime object—is the starting point of the PIRP/PIRU framework.

---

## Next Article

**PIRP-PIRU-002 — Pre-Categorical Intelligence and the PIRP/PIRU Duality**

The next article examines a deeper hypothesis:

> **Intelligence may exist before human-designed computational categories are imposed upon it.**

From this perspective, PIRP represents intelligence as encountered in runtime reality, while PIRU represents a later act of boundary discovery, formalization, and engineering.

