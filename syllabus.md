# Adaptive Manufacturing Systems: Theory and Practice

## An Interdisciplinary Seminar

**Course Description**

This seminar explores the emerging paradigm of adaptive manufacturing—production systems designed for reconfiguration, resilience, and distributed coordination rather than scale and standardization. Drawing on control theory, operations research, economics, and design theory, students will develop a conceptual toolkit for understanding why manufacturing paradigms shift, what enables new paradigms to survive, and how adaptive systems might reshape the geography and economics of production.

The course pairs theoretical foundations with primary sources, fiction, and case studies. Students will engage with both the "what" (technical mechanisms) and the "why" (economic and social forces that make paradigms viable or obsolete).

**Prerequisites**

No specific technical background required. The seminar assumes intellectual curiosity across disciplines and comfort with ambiguity. Students from engineering, business, design, policy, and the humanities are equally welcome.

---

## Unit 1: Why Paradigms Shift (Weeks 1-3)

### Week 1: The History of Manufacturing Transitions

**Core question:** What causes the center of manufacturing to relocate?

**Theory:**
- Technological revolutions as paradigm shifts, not incremental improvement
- The relationship between enabling technologies and geographic advantage
- Path dependence and why incumbents struggle to adapt

**Reading:**
- Suzanne Berger, *Making in America*, chapters 1-3
- William Janeway, *Doing Capitalism in the Innovation Economy*, chapter on speculation and technological transitions

**Discussion:**
- Interchangeable parts → American ascendance
- Containerization + JIT + telecom → Chinese ascendance
- What's next?

---

### Week 2: The Failure Modes of Centralized Systems

**Core question:** Why do optimized systems become fragile?

**Theory:**
- Legibility and its costs
- Metis (local, practical knowledge) vs. techne (formal, transferable knowledge)
- Why central planning fails at the edges

**Reading:**
- James C. Scott, *Seeing Like a State*, chapters 1, 2, 9, and 10
- Donella Meadows, *Thinking in Systems*, chapters 1-3

**Discussion:**
- Mass production as high-modernist project
- What knowledge lives in a factory that can't be written down?
- The vulnerability of "designed in California, made in China"

---

### Week 3: Resilience and Networked Production

**Core question:** What's the alternative to centralized optimization?

**Theory:**
- Resilient communities as productive units
- Networked vs. hierarchical organization
- Degradation modes: graceful vs. catastrophic

**Reading:**
- John Robb, *Brave New War*, chapters on resilient communities
- Speculative Technology, "Leapfrogging Industrial Production" (and related essays)

**Fiction:**
- Cory Doctorow, *Walkaway*, Part 1

**Discussion:**
- The minimum viable unit of production
- What can resilient communities actually make?
- The role of crisis in paradigm adoption

---

## Unit 2: The Grammar of Adaptive Systems (Weeks 4-7)

### Week 4: Control Theory Fundamentals

**Core question:** How do machines behave?

**Theory:**
- Open-loop vs. closed-loop control
- Feedback, stability, oscillation
- PID control as the universal kludge
- What happens when controlled systems interact

**Reading:**
- Karl Åström and Richard Murray, *Feedback Systems*, chapters 1-3 (available free online)
- Historical: James Watt's governor as paradigm case

**Lab/Exercise:**
- Simulate a simple feedback system; observe stability and instability
- Discuss: what aspects of a manufacturing cell need closed-loop control?

---

### Week 5: Queuing Theory and the Flow of Work

**Core question:** How do jobs move through a system?

**Theory:**
- Arrival rates, service rates, utilization
- Why high utilization creates long waits (the nonlinear curve)
- Little's Law
- Theory of constraints: the bottleneck governs the system
- The mechanisms of production efficiency: what levers actually exist

**Reading:**
- Eliyahu Goldratt, *The Goal*, chapters 1-15 (yes, it's a novel)
- Wallace Hopp and Mark Spearman, *Factory Physics*, Part II chapters 7-9:
  - Chapter 7: Basic Factory Dynamics (the relationship between WIP, cycle time, and throughput)
  - Chapter 8: Variability Basics (sources and measures of variability)
  - Chapter 9: The Corrupting Influence of Variability (why variability degrades performance and what to do about it)
- Brian Potter, *The Origins of Efficiency*, chapters 1-6 (the framework for how production processes improve, and the specific strategies available)

**Discussion:**
- Why "keep the machines busy" is wrong
- Buffer inventory as information storage
- The relationship between batch size and lead time
- Potter came to his framework after Katerra failed—what did they miss?
- How do the Factory Physics "laws" relate to Potter's efficiency strategies?

---

### Week 6: Mechanism Design and Distributed Coordination

**Core question:** How do independent agents produce good outcomes?

**Theory:**
- Markets as information processors
- Incentive compatibility
- Auctions and allocation mechanisms
- Market-based control for manufacturing

**Reading:**
- Alvin Roth, *Who Gets What and Why*, chapters 1-4
- Academic paper: "Market-based control of manufacturing systems" (Wellman or similar)

**Discussion:**
- How might manufacturing cells "bid" on work?
- Price signals vs. central scheduling
- When markets fail: coordination problems, externalities

---

### Week 7: Networks, Graphs, and Topology

**Core question:** How do cells connect?

**Theory:**
- Nodes, edges, directed vs. undirected graphs
- Centralized, decentralized, distributed topologies
- Resilience: what happens when nodes fail?
- Small-world networks and scale-free networks

**Reading:**
- Albert-László Barabási, *Linked*, chapters 1-5
- Internet protocol design as case study (RFC 791 or accessible summary)

**Discussion:**
- The factory as network vs. the factory as hierarchy
- What would TCP/IP for manufacturing look like?
- Failure modes and recovery

---

## Unit 3: The Physical Substrate (Weeks 8-10)

### Week 8: Reconfigurable Manufacturing Systems

**Core question:** What does "designed for change" look like?

**Theory:**
- Koren's six characteristics: modularity, integrability, customization, convertibility, scalability, diagnosability
- The difference between flexible and reconfigurable
- Setup time as the enemy

**Reading:**
- Yoram Koren, *The Global Manufacturing Revolution*, chapters 4-7
- Case studies of RMS implementations

**Discussion:**
- Why hasn't RMS achieved wider adoption?
- The gap between reconfigurable and truly adaptive
- What's missing from Koren's framework?

---

### Week 9: Metrology and the Meaning of Precision

**Core question:** How do you know you made the right thing?

**Theory:**
- Precision vs. accuracy
- Geometric dimensioning and tolerancing (GD&T) concepts
- Tolerance stackup and why it matters
- In-process measurement vs. post-process inspection

**Reading:**
- Selections from a GD&T primer (conceptual, not certification-level)
- Historical: the development of interchangeable parts and the role of gauges

**Discussion:**
- Measurement as the foundation of trust
- When is "good enough" good enough?
- The cost of over-specification

---

### Week 10: Actuation, Sensing, and the Cell as Organism

**Core question:** What are cells made of?

**Theory:**
- Motors, actuators, and the conversion of energy to motion
- Sensors and the cell's perception of itself and its environment
- The control loop at the cell level
- State machines and mode transitions

**Reading:**
- Rodney Brooks, *Flesh and Machines*, chapters on subsumption architecture
- Survey of actuator types and tradeoffs

**Fiction:**
- Ted Chiang, "Seventy-Two Letters"

**Discussion:**
- The actuator as muscle fiber, the cell as organism
- What sensors does an adaptive cell need?
- When do you have to design your own machines?

---

## Unit 4: Design, Craft, and Composition (Weeks 11-13)

### Week 11: Patterns and Composability

**Core question:** How do you design things that fit together?

**Theory:**
- Pattern languages as design methodology
- Composability vs. integration
- The module boundary problem
- Interfaces and contracts

**Reading:**
- Christopher Alexander, *A Pattern Language*, selections (patterns on workshops, small factories, flexible space)
- Unix philosophy as pattern language for software

**Discussion:**
- What patterns exist for manufacturing cells?
- How do you design an interface between cells?
- The tradeoff between standardization and adaptation

---

### Week 12: Craft, Skill, and Tacit Knowledge

**Core question:** What do humans contribute that machines can't?

**Theory:**
- Tacit vs. explicit knowledge
- The role of the craftsman in adaptive systems
- Machines as teachers (Sennett)
- Skill acquisition and the Dreyfus model

**Reading:**
- Richard Sennett, *The Craftsman*, chapters on the workshop and machine
- Matthew Crawford, *Shop Class as Soulcraft*, selections

**Fiction:**
- Becky Chambers, *A Psalm for the Wild-Built*

**Discussion:**
- Is the goal to eliminate human involvement or to amplify it?
- What skills matter in an adaptive manufacturing context?
- The aesthetics of production

---

### Week 13: Adaptation Over Time

**Core question:** How do buildings—and factories—learn?

**Theory:**
- Shearing layers: site, structure, skin, services, space plan, stuff
- Low-road vs. high-road buildings
- Adaptation as design criterion
- The long now perspective

**Reading:**
- Stewart Brand, *How Buildings Learn*, chapters on shearing layers and low-road buildings

**Discussion:**
- What are the shearing layers of a manufacturing cell?
- Designing for the unknown future
- The Rust Belt as low-road industrial space

---

## Unit 5: Integration and Application (Weeks 14-15)

### Week 14: The Full Loop—From Order to Shipment

**Core question:** What makes a cell a complete productive unit?

**Theory:**
- The cell as autonomous agent
- Handoff costs and friction
- Packaging, documentation, logistics as cell responsibilities
- The vision: receive order → produce → package → ship, lights-out

**Reading:**
- Revisit Robb on resilient communities
- Case studies on lights-out manufacturing (FANUC, etc.)

**Discussion:**
- What's the minimum viable full-loop cell?
- Scaling from one cell to many
- The network as factory

---

### Week 15: Telling the Story

**Core question:** How do paradigms become legible?

**Theory:**
- The role of narrative in technological adoption
- Finding your villain, your hero, your setting
- The leapfrog thesis as story
- Who needs to believe, and what do they need to hear?

**Reading:**
- Revisit Janeway on speculation and narrative
- Selections on technology rhetoric and adoption

**Fiction:**
- Vernor Vinge, *A Deepness in the Sky*, Qeng Ho sections

**Final project:**
- Students develop and present a pitch for an adaptive manufacturing venture, policy intervention, or research program
- Emphasis on narrative clarity, theoretical grounding, and practical viability

---

## Unit 6: The Moral Economy of Making (Week 16)

### Week 16: What Is Manufacturing For?

**Core question:** What is manufacturing *for*?

**Theory:**
- The theology of work: labor as participation in creation, not just production of goods
- Subsidiarity: decisions should be made at the lowest competent level (the cell as subsidiarity in action)
- The common good vs. aggregate utility—why the framing matters
- Technology as servant, not master: the principle of subordination
- Stewardship of creation: manufacturing that doesn't merely extract

**Reading:**
- Pope Leo XIII, *Rerum Novarum* (1891), selections—the original Catholic engagement with industrial capitalism
- Pope John Paul II, *Laborem Exercens* (1981), sections on the priority of labor over capital and the meaning of work
- Pope Francis, *Laudato Si'* (2015), chapter 3 on technology and chapter 5 on integral ecology
- E.F. Schumacher, *Small Is Beautiful*, chapter on "Buddhist Economics" (yes, Buddhist—but deeply compatible; Schumacher was Catholic)

**Optional deeper reading:**
- Alasdair MacIntyre, *After Virtue*, chapter on practices and institutions
- Wendell Berry, essays on economics and locality (*What Are People For?* or *The Art of the Commonplace*)
- Dorothy Day's writings on work and dignity

**Fiction:**
- Walter M. Miller Jr., *A Canticle for Leibowitz*, Part 1 ("Fiat Homo")—monks preserving technical knowledge after collapse; the relationship between making, meaning, and continuity

**Discussion questions:**
- The humanoid robot thesis implicitly asks: how do we replace human labor? What if that's the wrong question?
- Subsidiarity suggests distributed, local decision-making. How does this map onto adaptive cell architecture?
- What does "integral human development" mean in a manufacturing context? Is there a version of automation that *elevates* rather than displaces?
- Reshoring as solidarity: what would it mean to design supply chains around relationship rather than pure efficiency?
- The "Gospel of work"—can manufacturing be a witness? To what?

**Provocation:**
The secular discourse on automation asks: how do we maximize output while minimizing labor cost? Catholic Social Teaching asks: how do we design systems where work remains meaningful, where workers retain dignity, where technology serves human flourishing rather than subordinating it?

These are not the same optimization target. They produce different factories.

**Exercise:**
Redesign a manufacturing cell—or a network of cells—with subsidiarity, dignity, and stewardship as primary constraints rather than throughput and cost. What changes? What stays the same?

---

## Supplementary Reading List

### Fiction (Complete)
- Cory Doctorow, *Walkaway*
- William Gibson, *The Peripheral*
- Becky Chambers, *A Psalm for the Wild-Built*
- Neal Stephenson, *The Diamond Age*
- Kim Stanley Robinson, *The Ministry for the Future*
- Vernor Vinge, *A Deepness in the Sky*
- Ted Chiang, "Seventy-Two Letters"
- Walter M. Miller Jr., *A Canticle for Leibowitz*

### Additional Theory
- Carlota Perez, *Technological Revolutions and Financial Capital*
- Clayton Christensen, *The Innovator's Dilemma*
- Vaclav Smil, *Making the Modern World*
- Tracy Kidder, *The Soul of a New Machine*
- Martin Ford, *Rise of the Robots*
- Brian Potter, *The Origins of Efficiency* (also assigned in Week 5)
- Wallace Hopp and Mark Spearman, *Factory Physics* (also assigned in Week 5)

### Primary Sources and Papers
- Georg von Krogh et al., papers on open source robotics ecosystems
- Wellman et al., market-based control literature
- ROS documentation and design philosophy
- RFC 791 and internet architecture documents

---

## Assessment

- **Participation (30%):** Engaged discussion, evidence of reading, intellectual generosity
- **Weekly responses (30%):** Short written reflections connecting readings to core questions
- **Final project (40%):** A pitch—written and presented—for something that matters

---

## A Note on Interdisciplinarity

This seminar intentionally crosses boundaries that academia usually respects. Control theorists don't read James C. Scott. Economists don't read science fiction. Designers don't study queuing theory.

The premise is that adaptive manufacturing is an inherently interdisciplinary problem, and the people who will solve it need to be comfortable with partial knowledge across many domains rather than complete knowledge in one.

You will feel like a beginner in every unit. That's the point. The goal is not mastery but orientation—knowing enough to ask good questions, recognize patterns, and learn quickly when you encounter these ideas in the wild.

The real work begins after the seminar ends.
