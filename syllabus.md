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

**Optional Viewing:**
- [*American Factory*](https://www.imdb.com/title/tt9351980/) (2019)—Oscar-winning documentary on a Chinese company reopening a GM plant in Ohio; the clash of manufacturing cultures in one building
- [*Connections*](https://archive.org/details/james-burke-connections_s01e01) (1978), Episode 1: "The Trigger Effect"—James Burke on how technological systems create dependencies and enable paradigm shifts ([IMDB](https://www.imdb.com/title/tt0078588/))
- [*The Men Who Built America*](https://www.imdb.com/title/tt2167393/) (2012), episodes on Ford and the assembly line

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

**Optional Viewing:**
- [*Chernobyl*](https://www.imdb.com/title/tt7366338/) (2019), Episodes 1-2—HBO's miniseries is a masterclass in how centralized systems fail: information suppression, misaligned incentives, the cost of legibility over truth
- [*Brazil*](https://www.imdb.com/title/tt0088846/) (1985)—Terry Gilliam's dystopia of bureaucratic optimization; darkly funny, deeply relevant
- [*The Pruitt-Igoe Myth*](https://www.imdb.com/title/tt1788461) (2011)—documentary on the rise and fall of modernist public housing; high-modernist planning meets reality

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

**Optional Viewing:**
- [*Alone in the Wilderness*](https://www.imdb.com/title/tt0437806/) (2004)—Dick Proenneke builds a cabin in Alaska with hand tools; a meditation on self-sufficiency and the minimum viable productive unit
- [*Maker*](https://www.imdb.com/title/tt3758478) (2014)—documentary on the maker movement; optimistic, but raises real questions about what distributed production can achieve
- [*If a Tree Falls*](https://www.imdb.com/title/tt1787725/) (2011)—documentary on the Earth Liberation Front; a darker take on when networked, decentralized groups turn to destruction

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
- Karl Åström and Richard Murray, *Feedback Systems*, chapters 1-3 ([available free online](https://www.cds.caltech.edu/~murray/courses/cds101/fa03/caltech/am03_ch1-27sep03.pdf))
- Historical: ["Remaking History: James Watt and the Flyball Governor"](https://makezine.com/projects/remaking-history-james-watt-and-the-flyball-governor/) (Make Magazine)
- Historical: ["The Centrifugal Governor: Maxwell's Inspiration for Modern Control Theory"](https://medium.com/@robinchristen/the-centrifugal-govenor-james-c-maxwells-inspiration-for-modern-control-theory-f60f2ace833e)

**Lab/Exercise:**
- Simulate a simple feedback system; observe stability and instability
- Discuss: what aspects of a manufacturing cell need closed-loop control?

**Optional Viewing:**
- [*The Secret Life of Machines*](https://www.youtube.com/playlist?list=PLByTa5duIolYRtq3Hqdp29hNiDLKEhVfk) (1988-1993)—Tim Hunkin's eccentric, brilliant series on how machines work; the episodes on the washing machine and the car are particularly good on feedback and control ([IMDb](https://www.imdb.com/title/tt0431571))
- [*The Machine That Changed the World*](https://archive.org/details/the-machine-that-changed-the-world-1-1) (1992)—five-part documentary on the history of computing, including cybernetics and feedback systems ([IMDb](https://www.imdb.com/title/tt0122355/))
- [MATLAB: "What is a PID Controller?"](https://www.youtube.com/watch?v=wkfEZmsQqiA)—elegant visual explanation of the "universal kludge"

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

**Optional Viewing:**
- [Boeing 787 Dreamliner Manufacturing](https://www.youtube.com/watch?v=SLgbOhdmK1I) (Boeing)—factory tour documentaries showing flow, bottlenecks, and the choreography of complex assembly
- [Veritasium: "The Surprising Secret of Synchronization"](https://www.youtube.com/watch?v=t-_VPRCtiUg)—not directly about queuing, but brilliant on how systems find (or fail to find) coordinated states

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
- Michael Wellman, ["Market-Oriented Programming: Some Early Lessons"](https://www.semanticscholar.org/paper/Market-oriented-programming:-some-early-lessons-Wellman/c5314e98ccc4d2e6cb81ae816ba45e9d0509579c) (1996)

**Discussion:**
- How might manufacturing cells "bid" on work?
- Price signals vs. central scheduling
- When markets fail: coordination problems, externalities

**Optional Viewing:**
- [*Inside the Mind of Google*](https://www.imdb.com/title/tt3586136/) (2010)—CNBC documentary touching on auction design for advertising; markets as coordination mechanisms
- [*The Billion Dollar Code*](https://www.imdb.com/title/tt15392100/) (2021)—German miniseries on the origins of Google Earth; tangentially relevant for how decentralized contributors can (or can't) coordinate
- [Numberphile: "The Stable Marriage Problem"](https://www.youtube.com/watch?v=Qcv1IqHWAzg)—accessible introduction to matching markets and mechanism design

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

**Optional Viewing:**
- [*Lo and Behold: Reveries of the Connected World*](https://www.imdb.com/title/tt5275828/) (2016)—Werner Herzog's meditation on the internet; poetic, strange, and surprisingly deep on network architecture
- [*All Watched Over by Machines of Loving Grace*](https://www.imdb.com/title/tt1955162) (2011), Episode 2: "The Use and Abuse of Vegetational Concepts"—Adam Curtis on how network thinking shapes our understanding of systems (warning: Curtis is provocative and partial) ([full series on YouTube](https://www.youtube.com/watch?v=I6EBpLfLHCA&list=PLC4E798CAE3E10597))
- [3Blue1Brown: "But what is a neural network?"](https://www.youtube.com/watch?v=aircAruvnKk)—networks as computational architecture; elegant visualization

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
- ["Reconfigurable Manufacturing Systems: Principles, Design, and Future Trends"](https://link.springer.com/article/10.1007/s11465-018-0483-0) (Springer)
- ["Reconfigurable Manufacturing Systems: From Design to Implementation"](https://www.researchgate.net/publication/334806872_Reconfigurable_Manufacturing_Systems_From_Design_to_Implementation) (ResearchGate)

**Discussion:**
- Why hasn't RMS achieved wider adoption?
- The gap between reconfigurable and truly adaptive
- What's missing from Koren's framework?

**Optional Viewing:**
- [*How It's Made*](https://www.imdb.com/title/tt0835010) (any episode)—the platonic ideal of manufacturing content; watch for what's reconfigurable vs. fixed ([episodes on YouTube](https://www.youtube.com/playlist?list=PL39_ud5aKSvnYDhKdB7wTDUZRiE8RaJat))
- [Inside Tesla's Gigafactory](https://www.youtube.com/watch?v=gPFqyLYf1DU&pp=ygUYaW5zaWRlIHRlc2xhIGdpZ2FmYWN0b3J5) (various)—Tesla's attempt at reconfigurable, rapid-iteration manufacturing; instructive whether you view it as success or cautionary tale

---

### Week 9: Metrology and the Meaning of Precision

**Core question:** How do you know you made the right thing?

**Theory:**
- Precision vs. accuracy
- Geometric dimensioning and tolerancing (GD&T) concepts
- Tolerance stackup and why it matters
- In-process measurement vs. post-process inspection

**Reading:**
- ["GD&T 101: An Introduction to Geometric Dimensioning and Tolerancing"](https://www.fictiv.com/articles/gdt-101-an-introduction-to-geometric-dimensioning-and-tolerancing) (Fictiv)
- ["A Brief History of Interchangeability and Dimensional Measurement in Manufacturing"](https://www.engineering.com/a-brief-history-of-interchangeability-and-dimensional-measurement-in-manufacturing/) (Engineering.com)
- ["230 Years of Interchangeable Parts"](https://www.allaboutlean.com/230-years-interchangeability/) (AllAboutLean)

**Discussion:**
- Measurement as the foundation of trust
- When is "good enough" good enough?
- The cost of over-specification

**Optional Viewing:**
- [Clickspring: "Making the Antikythera Mechanism"](https://www.youtube.com/playlist?list=PLZioPDnFPNsHnyxfygxA0to4RXv4_jDU2)—YouTube series on precision machining with hand tools; meditative and rigorous
- [Machine Thinking: "Why Precision Matters"](https://www.youtube.com/watch?v=gNRnrn5DE58)—short explainer on tolerances and why they compound

---

### Week 10: Actuation, Sensing, and the Cell as Organism

**Core question:** What are cells made of?

**Theory:**
- Motors, actuators, and the conversion of energy to motion
- Sensors and the cell's perception of itself and its environment
- The control loop at the cell level
- State machines and mode transitions

**Reading:**
- Rodney Brooks, *Flesh and Machines*, chapters 2-4 (subsumption architecture)
- ["Comparison of hydraulic, pneumatic and electric linear actuation systems"](https://www.nature.com/articles/s41598-023-47602-x) (*Scientific Reports*, 2023)
- ["Choosing the Right Drive System for Your Robotics Application"](https://www.onlinerobotics.com/news-blog/choosing-right-drive-system-your-robotics-application-electric-hydraulic-and-pneumatic) (GBC Robotics)

**Fiction:**
- Ted Chiang, "Seventy-Two Letters"

**Discussion:**
- The actuator as muscle fiber, the cell as organism
- What sensors does an adaptive cell need?
- When do you have to design your own machines?

**Optional Viewing:**
- [Boston Dynamics](https://www.youtube.com/@BostonDynamics) videos (Atlas, Spot)—the state of the art in integrated actuation and sensing; watch for what's still hard
- [Simone Giertz: "Why I Make Useless Things"](https://www.youtube.com/watch?v=c0bsKc4tiuY)—TED talk; funny, but also a real meditation on the gap between intention and execution in robotics
- [*Fixed: The Science/Fiction of Human Enhancement*](https://www.imdb.com/title/tt2774206) (2013)—documentary on prosthetics, human augmentation, and the body-machine interface

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
- Christopher Alexander, *A Pattern Language*, patterns 146 (Flexible Office Space), 149 (Small Work Groups), 156 (Settled Work), 157 (Home Workshop)
- Eric S. Raymond, [*The Art of Unix Programming*](http://www.catb.org/esr/writings/taoup/html/), especially [Chapter 1: Philosophy](http://www.catb.org/esr/writings/taoup/html/ch01s06.html)

**Discussion:**
- What patterns exist for manufacturing cells?
- How do you design an interface between cells?
- The tradeoff between standardization and adaptation

**Optional Viewing:**
- [*Citizen Architect: Samuel Mockbee and the Spirit of the Rural Studio*](https://www.imdb.com/title/tt1522295/) (2010)—documentary on pattern-based, community-centered architecture; Alexander's ideas in practice
- [The Unix Legacy](https://www.youtube.com/watch?v=tc4ROCJYbm0)—AT&T Archives film on Unix philosophy; composability as design principle
- [*Eames: The Architect and the Painter*](https://www.imdb.com/title/tt1972646/) (2011)—Charles and Ray Eames on design patterns, modularity, and play

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

**Optional Viewing:**
- [*Jiro Dreams of Sushi*](https://www.imdb.com/title/tt1772925/) (2011)—the platonic ideal of craft; tacit knowledge embodied in a lifetime of practice
- [*Samsara*](https://www.imdb.com/title/tt0770802/) (2011)—non-narrative documentary with stunning sequences on manufacturing and craft; the contrast between handwork and automation
- [Primitive Technology](https://www.youtube.com/@primitivetechnology9550) (YouTube channel)—silent videos of a man building things from scratch in the Australian bush; pure tacit knowledge made visible

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

**Optional Viewing:**
- [*How Buildings Learn*](https://www.youtube.com/watch?v=AvEqfg2sIH0) (1997)—Stewart Brand's BBC series based on his book; essential viewing, free on YouTube
- [*My Architect*](https://www.imdb.com/title/tt0373175/) (2003)—Nathaniel Kahn's documentary on his father Louis Kahn; high-road buildings and what they cost
- [*Manufactured Landscapes*](https://www.imdb.com/title/tt0832903/) (2006)—Edward Burtynsky's photographs of industrial transformation; long takes on what change looks like at scale

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
- ["Lights-Out Manufacturing in 2025"](https://standardbots.com/blog/lights-out-manufacturing) (Standard Bots)
- ["Lights-Out Automation: Fact or Fiction?"](https://www.assemblymag.com/articles/94982-lights-out-automation-fact-or-fiction) (Assembly Magazine)
- [FANUC Case Studies](https://www.fanucamerica.com/case-studies)

**Discussion:**
- What's the minimum viable full-loop cell?
- Scaling from one cell to many
- The network as factory

**Optional Viewing:**
- [Inside Amazon's Fulfillment Center](https://www.youtube.com/watch?v=IMPbKVb8y8s) (various)—any of the fulfillment center documentaries; the closest thing to lights-out logistics at scale
- [FANUC Factory Tour: Robots Building Robots](https://www.youtube.com/watch?v=F46GRWuyEy8&pp=ygUSRkFOVUMgRmFjdG9yeSBUb3Vy) (various)—factory tours of robots making robots; the dream and the reality
- [Wendover Productions: "The Insane Logistics of Formula 1"](https://www.youtube.com/watch?v=6OLVFa8YRfM)—not manufacturing, but a masterclass in the full loop from order to execution under extreme constraints

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
- Sheila Jasanoff and Sang-Hyun Kim, ["Sociotechnical Imaginaries and National Energy Policies"](https://law.unimelb.edu.au/__data/assets/pdf_file/0009/3305673/1.-Jasanoff-and-Kim-2015-Dreamscapes-of-Modernity-Sociotechnical-Imaginari.pdf) (chapter from *Dreamscapes of Modernity*)
- Everett Rogers, ["Diffusion of Innovations"](https://diffusion-research.org/research_articles/adoption-of-innovations/) (overview)

**Fiction:**
- Vernor Vinge, *A Deepness in the Sky*, Qeng Ho sections

**Optional Viewing:**
- [*Something Ventured*](https://www.imdb.com/title/tt1737747/) (2011)—documentary on the early days of Silicon Valley venture capital; how stories attract capital
- [*General Magic*](https://www.imdb.com/title/tt6849786) (2018)—documentary on the company that invented the smartphone and failed; narrative, timing, and why being right isn't enough
- [*Print the Legend*](https://www.imdb.com/title/tt3557464/) (2014)—documentary on the 3D printing hype cycle; a case study in how narratives form and collapse

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
- Pope Leo XIII, [*Rerum Novarum*](https://www.vatican.va/content/leo-xiii/en/encyclicals/documents/hf_l-xiii_enc_15051891_rerum-novarum.html) (1891), sections 1-24—the original Catholic engagement with industrial capitalism
- Pope John Paul II, [*Laborem Exercens*](https://www.vatican.va/content/john-paul-ii/en/encyclicals/documents/hf_jp-ii_enc_14091981_laborem-exercens.html) (1981), sections 4-10 on the priority of labor over capital and the meaning of work
- Pope Francis, [*Laudato Si'*](https://www.vatican.va/content/francesco/en/encyclicals/documents/papa-francesco_20150524_enciclica-laudato-si.html) (2015), chapter 3 (sections 101-136) on technology and chapter 5 (sections 137-162) on integral ecology
- E.F. Schumacher, ["Buddhist Economics"](https://centerforneweconomics.org/publications/buddhist-economics/) from *Small Is Beautiful* (yes, Buddhist—but deeply compatible; Schumacher was Catholic)

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

**Optional Viewing:**
- [*Modern Times*](https://www.imdb.com/title/tt0027977/) (1936)—Chaplin's silent comedy on industrialization and human dignity; funny, sad, and still relevant
- [*Dorothy Day: Don't Call Me a Saint*](https://www.imdb.com/title/tt0795373) (2005)—the Catholic Worker movement's vision of work, dignity, and community ([trailer](https://www.youtube.com/watch?v=RKiLCDaCAO))
- [*The Letter: A Message for Our Earth*](https://www.imdb.com/title/tt22660470/) (2022)—documentary on *Laudato Si'* featuring voices from around the world ([free on YouTube](https://www.youtube.com/watch?v=Rps9bs85BII))

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
