# MDG Prompt Templates

**How to use these templates:** Replace `[TOPIC]` with any knowledge domain, technology, theory, or system. Each template produces a different kind of insight through diagrams. All output follows MDG v1.0 conventions automatically when the skill file is installed.

These templates work with any LLM that has MDG loaded. They're designed to reveal structure, not just illustrate it.

---

## Template 1: The Eight Views

Generate eight diagrams of the same subject, each through a different cognitive lens.

```
Using MDG, create 8 Mermaid diagrams about [TOPIC], one for each lens:

1. Component Map — every major part and how they connect
2. Process Flow — what happens step by step, from trigger to outcome
3. System Architecture — layers, boundaries, and interfaces
4. Concept Relationship Map — how the core ideas relate to each other
5. Evidence Chain — what we know and how we know it
6. Assumption Map — what's being taken for granted
7. Contrarian View — what the standard understanding gets wrong or misses
8. Zoom Stack — the same phenomenon at three different scales
```

### Example: The Eight Views of CRISPR Gene Editing

```
Using MDG, create 8 Mermaid diagrams about CRISPR gene editing, one for each lens:

1. Component Map — Cas9, guide RNA, PAM sequence, target DNA, repair pathways
2. Process Flow — from guide RNA design through cell transfection to edited organism
3. System Architecture — molecular layer, cellular layer, organism layer, regulatory layer
4. Concept Relationship Map — how precision, off-target effects, delivery, and ethics relate
5. Evidence Chain — key experiments from Doudna/Charpentier through clinical trials
6. Assumption Map — what's assumed about delivery efficiency, long-term stability, mosaicism
7. Contrarian View — why base editing or prime editing may obsolete Cas9 cleavage
8. Zoom Stack — single nucleotide edit → cell population dynamics → population genetics
```

### Example: The Eight Views of Microservices Architecture

```
Using MDG, create 8 Mermaid diagrams about microservices architecture, one for each lens:

1. Component Map — services, API gateway, message broker, databases, load balancer
2. Process Flow — user request through gateway to service mesh to response
3. System Architecture — infrastructure layer, platform layer, application layer, API layer
4. Concept Relationship Map — how coupling, cohesion, resilience, and observability relate
5. Evidence Chain — Netflix, Amazon, Spotify case studies and what they actually measured
6. Assumption Map — what's assumed about team size, deployment frequency, network reliability
7. Contrarian View — when a monolith is actually the right answer
8. Zoom Stack — single service internals → inter-service communication → organizational structure
```

---

## Template 2: The Depth Ladder

Four diagrams at increasing analytical depth — from napkin sketch to gap analysis.

```
Using MDG, create 4 Mermaid diagrams about [TOPIC] at increasing depth:

1. The Napkin Sketch — explain it in 5-7 nodes, core concept only
2. The Working Model — 15-20 nodes with key relationships and feedback loops
3. The Full Architecture — all major components, flows, dependencies, and boundary conditions
4. The Gap Map — what's missing, assumed, unresolved, or systematically overlooked
```

### Example: The Depth Ladder for Blockchain Consensus Mechanisms

```
Using MDG, create 4 Mermaid diagrams about blockchain consensus mechanisms at increasing depth:

1. The Napkin Sketch — Proof of Work vs Proof of Stake, core tradeoff
2. The Working Model — PoW, PoS, DPoS, PBFT with energy, speed, decentralization tradeoffs
3. The Full Architecture — validator selection, block proposal, finality, fork resolution, slashing
4. The Gap Map — what's unresolved about MEV, validator centralization, long-range attacks
```

### Example: The Depth Ladder for Cognitive Behavioral Therapy

```
Using MDG, create 4 Mermaid diagrams about Cognitive Behavioral Therapy at increasing depth:

1. The Napkin Sketch — thought → feeling → behavior cycle
2. The Working Model — automatic thoughts, cognitive distortions, behavioral experiments, schema
3. The Full Architecture — assessment, formulation, intervention techniques, relapse prevention, therapeutic alliance
4. The Gap Map — what CBT assumes about rationality, what it misses about embodiment and social context
```

---

## Template 3: The Evidence Spectrum

Diagrams arrayed from strongest evidence FOR a position to strongest evidence AGAINST it. Forces balanced, rigorous thinking.

```
Using MDG, create 5 Mermaid diagrams about [CLAIM OR POSITION], arranged from strongest support to strongest challenge:

1. Strongest Evidence FOR — the most compelling data, experiments, or logical arguments supporting this position
2. Supporting Context — the conditions, mechanisms, or frameworks that make the position plausible
3. The Contested Middle — where evidence is ambiguous, conflicting, or subject to interpretation
4. Challenging Context — the conditions, mechanisms, or alternative frameworks that weaken the position
5. Strongest Evidence AGAINST — the most compelling data, experiments, or logical arguments challenging this position
```

### Example: The Evidence Spectrum for "Remote Work Increases Productivity"

```
Using MDG, create 5 Mermaid diagrams about the claim that remote work increases productivity:

1. Strongest Evidence FOR — Stanford/Bloom study (13% increase), Owl Labs data, reduced commute time studies
2. Supporting Context — deep work conditions, async communication benefits, talent pool expansion
3. The Contested Middle — productivity measurement problems, selection bias in studies, role-dependent variation
4. Challenging Context — collaboration decay over time, mentorship gaps, innovation reduction signals
5. Strongest Evidence AGAINST — Microsoft/Yang study (siloed networks), Raj Choudhury geographic flexibility vs full-remote distinction, return-to-office mandates as revealed preference
```

### Example: The Evidence Spectrum for "Large Language Models Understand Language"

```
Using MDG, create 5 Mermaid diagrams about the claim that large language models understand language:

1. Strongest Evidence FOR — emergent reasoning, zero-shot task transfer, coherent multi-step planning
2. Supporting Context — scaling laws, representation geometry, in-context learning mechanisms
3. The Contested Middle — benchmark saturation vs real-world brittleness, stochastic parrots debate, Chinese Room thought experiment
4. Challenging Context — adversarial fragility, hallucination persistence, lack of grounding
5. Strongest Evidence AGAINST — Bender/Koller form-meaning gap, systematic compositionality failures, inability to verify own outputs
```

### Example: The Evidence Spectrum for "Nuclear Power Is Essential for Decarbonization"

```
Using MDG, create 5 Mermaid diagrams about the claim that nuclear power is essential for decarbonization:

1. Strongest Evidence FOR — baseload reliability data, lifecycle emissions analysis, land use efficiency vs renewables
2. Supporting Context — grid stability requirements, capacity factor comparisons, SMR cost projections
3. The Contested Middle — cost overrun patterns (Vogtle, Hinkley) vs fleet learning curves (South Korea, France), energy storage trajectory uncertainty
4. Challenging Context — construction timeline vs climate urgency, waste storage unresolved, insurance subsidy dependency
5. Strongest Evidence AGAINST — renewable + storage cost crossover data, Lazard LCOE trends, political/social license barriers as structural constraint
```

---

## Template 4: The Spectrum of Understanding

Three diagrams showing how different audiences understand the same subject.

```
Using MDG, create 3 Mermaid diagrams about [TOPIC] showing how understanding varies:

1. The Textbook Version — how this is conventionally taught and understood
2. The Practitioner Version — what people who actually work with this know that textbooks don't capture
3. The Frontier Version — where the open questions, active debates, and emerging ideas are
```

### Example: The Spectrum of Understanding for Machine Learning

```
Using MDG, create 3 Mermaid diagrams about machine learning:

1. The Textbook Version — supervised/unsupervised/reinforcement taxonomy, train-test-validate pipeline
2. The Practitioner Version — data quality dominates, feature engineering matters more than model choice, deployment is the hard part, monitoring is the ongoing cost
3. The Frontier Version — scaling laws debate, emergent capabilities, mechanistic interpretability, synthetic data bootstrapping, reasoning vs retrieval
```

### Example: The Spectrum of Understanding for Supply Chain Management

```
Using MDG, create 3 Mermaid diagrams about supply chain management:

1. The Textbook Version — supplier → manufacturer → distributor → retailer → customer, just-in-time, safety stock formulas
2. The Practitioner Version — bullwhip effect is real, dual-sourcing tradeoffs, the ERP system is never accurate, relationships matter more than contracts
3. The Frontier Version — digital twins, autonomous procurement, climate-risk-adjusted routing, nearshoring vs resilience vs cost optimization trilemma
```

---

## Template 5: The Cross-Domain Bridge

Two diagrams showing how a pattern in one domain maps to a completely different domain.

```
Using MDG, create 2 Mermaid diagrams showing a structural parallel:

1. [DOMAIN A] — show the key pattern, structure, or dynamic
2. [DOMAIN B] — show how the same pattern appears in a completely different context

Then create a third diagram mapping the correspondence: which elements align, where the analogy holds, and where it breaks down.
```

### Example: Cross-Domain Bridge between Immune Systems and Cybersecurity

```
Using MDG, create 3 Mermaid diagrams:

1. Biological Immune System — innate immunity, adaptive immunity, memory cells, antigen recognition, autoimmune failure modes
2. Cybersecurity Defense Architecture — firewalls, intrusion detection, threat intelligence, incident response, zero-trust, false positive problem
3. Correspondence Map — what maps cleanly (innate = firewall, adaptive = ML-based detection, memory = threat signatures) and where the analogy breaks (no "autoimmune" equivalent in most security architectures — or is there?)
```

### Example: Cross-Domain Bridge between Evolution and Startup Ecosystems

```
Using MDG, create 3 Mermaid diagrams:

1. Evolutionary Biology — variation, selection, retention, niche construction, adaptive radiation, extinction events
2. Startup Ecosystem — founding diversity, market selection, scaling/retention, platform creation, vertical expansion, market crashes
3. Correspondence Map — what maps (variation = founding diversity, selection = market fit, extinction events = recessions) and where it breaks (startups have intentional strategy; evolution doesn't)
```

---

## Template 6: The Temporal Triptych

Three diagrams showing past, present, and possible futures.

```
Using MDG, create 3 Mermaid diagrams about [TOPIC] across time:

1. How We Got Here — the key events, decisions, or forces that created the current state
2. Where We Are Now — the current landscape, players, tensions, and dynamics
3. The Branching Futures — 2-3 plausible scenarios and what would cause each one
```

### Example: The Temporal Triptych for Artificial Intelligence

```
Using MDG, create 3 Mermaid diagrams about AI development:

1. How We Got Here — Turing, perceptrons, AI winters, backprop revival, ImageNet, transformers, GPT scaling
2. Where We Are Now — frontier lab competition, open-source vs closed, regulation emerging, enterprise adoption, capability vs alignment tension
3. The Branching Futures — (a) gradual integration as tooling, (b) capability discontinuity forcing rapid governance, (c) open-source parity eroding moats
```

### Example: The Temporal Triptych for Antibiotics

```
Using MDG, create 3 Mermaid diagrams about antibiotics:

1. How We Got Here — Fleming/penicillin, golden age of discovery (1940s-60s), pharma exit from antibiotics R&D, resistance emergence
2. Where We Are Now — WHO priority pathogen list, last-resort drugs, agricultural overuse, market failure for new development, phage therapy revival
3. The Branching Futures — (a) new economic incentives (pull mechanisms) restart pipeline, (b) resistance outpaces discovery and routine surgery becomes dangerous, (c) alternative approaches (phage, antimicrobial peptides, CRISPR-based) leapfrog traditional antibiotics
```

---

## Combining Templates

The real power comes from combining templates. Try:

- **Depth Ladder + Evidence Spectrum:** "Give me the Napkin Sketch, then the full Evidence Spectrum for the most contested claim in that sketch"
- **Eight Views + Cross-Domain Bridge:** "Give me the Eight Views of [Topic A], then bridge View #7 (Contrarian) to a completely different domain"
- **Temporal Triptych + Gap Map:** "Show me how we got here, then map what's systematically missing from the current understanding"

---

## Tips for Getting the Best Results

1. **Be specific about your topic.** "Machine learning" produces generic diagrams. "Why gradient descent works despite non-convex loss landscapes" produces insight.
2. **Name the audience.** Adding "for a CTO evaluating vendor claims" or "for a biology PhD student" changes what the diagrams emphasize.
3. **Request iteration.** "Now take diagram #5 and expand the contested middle into its own full diagram" is how you go deep.
4. **Combine with your own knowledge.** "Here's what I know about X. Create diagrams that show me what I'm missing" is the highest-leverage prompt.
5. **Challenge the output.** "What would someone who disagrees with diagram #3 say? Create that diagram." This is where the real thinking happens.
