# Causal Shape Framework (因果形状フレームワーク)

**A method for extracting, classifying, and analyzing causal structures in narratives, events, and systems using energy dynamics.**

---

## Core Concept

Every event — in stories, history, human relationships, markets — has a **causal shape**: a pattern of energy transformation between agents. By reducing complex narratives to simple energy types and tracking their transformations, we can:

1. Compare structurally identical patterns across completely different domains
2. Detect missing or broken causal links in narratives
3. Predict probable next states based on accumulated energy patterns

---

## Energy Classification

| Type | Symbol | Description | Examples |
|------|--------|-------------|----------|
| **Offensive** | A | Energy directed outward — attack, challenge, conquest, decisive action | Anger, ambition, revenge, declaration of war |
| **Defensive** | D | Energy directed inward — protection, acceptance, nurturing, endurance | Fear, trust, caregiving, loyalty, submission |
| **Neutral** | N | Baseline state — equilibrium, daily life, accumulation without direction | Routine, peace, dormancy |

---

## Reactive Dynamics (反動の法則)

The core engine of the framework. Energy received generates a **reactive force** of the same type:

- **D → D Reaction**: Being protected → desire to protect others
- **A → A Reaction**: Being attacked → desire to attack back
- **Confluence**: When multiple reactive forces converge, the resulting action scales with the number of sources

### Key Principles

- **Reaction is not automatic** — it is probabilistic. Being attacked may lead to counterattack *or* submission, depending on context, character, and accumulation.
- **Accumulation matters** — energy builds over time. A single event may not trigger reaction, but sustained pressure will.
- **Confluence amplifies** — when D-reaction and A-reaction converge on the same action, the output is maximal.

---

## Structural Patterns

### Hero Pattern (英雄型)
**Reactive energy flows outward continuously.**

```
N → D(accumulation) → A(conversion) → A vs A(collision) → N(resolution)
```

Reactions point outward and escalate. Energy accelerates in one direction. Result: victory, resolution, happy ending.

### Tragedy Pattern (悲劇型)
**Reactive energy turns inward, back onto the subject.**

```
N → D(protect) → D(be protected) → D(excess/dissolution) → N(collapse) → A(transgression) → D(forced)
```

Reactions fold back. Energy that should flow outward gets trapped and eventually implodes. Result: self-destruction, loss.

### Genre Classification Hypothesis

The **direction of reactive flow** determines narrative genre:
- Reactions consistently directed outward → **Heroic narrative**
- Reactions folding back inward → **Tragedy**
- Reactions oscillating → **Drama / Complex narrative**

---

## Case Study 1: Momotaro (桃太郎)

```
1. [N] Old couple's daily life — neutral equilibrium

2. [N→D] Peach arrives → accepted (reception of the unknown)

3. [D] Child raised with protection and love — energy accumulation phase

4. [External A] Oni attack villages — offensive pressure on the community

5. [D→A CONVERSION POINT]
   Reactive Source 1: D→D (was protected → wants to protect)
   Reactive Source 2: A→A (community attacked → wants to attack back)
   CONFLUENCE → Maximum action output: expedition + alliance building

6. [A accumulation] Kibidango recruits allies — offensive resource gathering

7. [A vs A] Battle at Onigashima — offensive collision

8. [A→D] Oni surrender — their offensive energy collapses into defensive (submission)

9. [A→N] Treasure returned, peace restored — offensive energy resolves to neutral
```

**Pattern**: N → D(accumulate) → A(convert) → A vs A → N
**Key Insight**: Step 5's confluence of two reactive forces (D→D + A→A) explains *why* the action is maximal (distant expedition + alliance), not just local defense.

---

## Case Study 2: Urashima Taro (浦島太郎)

```
1. [N] Fisherman's daily life — neutral

2. [External A → turtle] Children bully turtle — offensive energy directed at a third party

3. [A witnessed → D reaction] Taro protects turtle
   NOTE: Not a reaction to being attacked himself —
   witnessing attack on others triggers defensive reaction

4. [D→D reaction] Turtle reciprocates — "was protected → protects back" (invitation to Ryugu)

5. [D: reception/pleasure] Life in Ryugu — defensive energy consumed, not accumulated
   CONTRAST with Momotaro: there, protection builds strength. Here, it dissolves it.

6. [D excess → N return desire] Taro wants to go home
   Reactive twist: being over-protected triggers rejection of protection

7. [D: conditional] Tamatebako given with prohibition — Otohime's protective energy, but constrained

8. [N→ ?] Returns to beach → opens box immediately

   ⚠️ CAUSAL GAP DETECTED
   No reactive force explains why he opens the box.
   The framework cannot derive this action from prior energy states.

9. [→ D forced] Becomes old man — forced into defensive state (aging/powerlessness)
```

**Pattern**: N → D(protect other) → D(be protected) → D(excess) → N(return) → **[GAP]** → D(forced)

### Causal Gap Analysis

The framework flags Step 8 as structurally broken — there is no reactive force that explains the box-opening. Historical research confirms this:

- **Original (Tango no Kuni Fudoki, 8th century)**: A love story. The box contained the woman's essence. He opened it out of longing for her. *Causal chain intact.*
- **Manyoshu version**: He opened it after discovering 300 years had passed and everyone he knew was dead. Opened in despair. *Causal chain intact (N-collapse → A-reaction).*
- **Meiji textbook version**: Romantic and temporal-displacement elements removed for children's education. Box-opening motivation lost. *Causal chain broken.*

**Conclusion**: The framework's gap detection correctly identified a point of historical narrative corruption. The causal shape was damaged during editorial simplification.

---

## Application to AI

### Training Data for Causal Shape Recognition

Phase 1: Humans extract causal shapes from stories, historical events, interpersonal dynamics, market movements → build labeled dataset of shapes

Phase 2: Train AI on shape dataset — pattern matching level ("I've seen this shape before")

Phase 3: Predictive refinement — given partial shape, predict next energy state. Use prediction accuracy as reinforcement signal.

Phase 4: Novel shape discovery — with sufficient accumulation, detect patterns that don't match any known shape → "this is a new shape"

### Why This Matters for Superintelligence

Current LLMs process language. This framework operates at the level of **structure beneath language** — the causal shapes that are domain-independent. The same A→D→A pattern appears in fairy tales, geopolitics, startup dynamics, and market behavior.

A system that can recognize, predict, and discover causal shapes would have **domain-independent reasoning** — exactly what reinforcement learning needs to move beyond narrow AI.

---

## Framework Status

- **Stage**: Early theoretical framework with initial case studies
- **Origin**: Developed by Kevin (kj-keeley) through extensive pattern analysis across narratives, human cognition, and AI systems
- **Related work**: Information Fluid Dynamics (IFD) — the parent framework from which this observational model derives
- **Repository**: https://github.com/kj-keeley

---

*This framework is part of ongoing research into causal structure recognition for AI systems. The core insight — that reactive energy dynamics can be reduced to simple classifications while preserving structural information — enables cross-domain pattern recognition at a level current AI architectures cannot achieve.*
