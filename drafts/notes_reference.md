# Notes from conversation with Paul

 more leaves fold better
 what features might be breaking levinthal's?
 the landscape must be funneled in order for these to fold
 how can we make these landscapes funnel better
 paul actually went to wales' group to make disconnectivity graphs
 wales code is really unwieldy-- would take much more time to make code efficient than it would be worth
 had some preliminary trees,but ultimately bailed because it was too complex
 disconnectivity should be its own paper with Wales, Morgan
 Sharon doesn't like Wales, he's kind of weird, Wales is really hands on, even with code development (Paul likes him)
 leaves were once called nucleation sites for folding in an earlier draft of Paul's paper
 Leaves are edges that are next to each other (local) that need to form-- so lots of leaves means a net seeded with lots of local, native bonds

 did some simulations seeding the net (icosahedra, which never folded on their own)
 one connection still wasn't enough, needed more
 interesting question-- how much do you need to add?
 specificity efficiency would be interesting

 critical bonds are related to the isostatic structure of the net-- fewest number of bonds that i need to make it rigid
 with triangle faces, look at the all the matches of the edges-- for it to be minimal and rigid you have to glue enough edges together so that no vertex has been glued twice, but sufficient that each vertex has been glued once
 cube and dodecahedra are trickier-- some cuts don't introduce degrees of freedom
 cutting trees / gluing trees -- probably a greedy algorithm that will do this faster than brute force

 understanding the rigidity of the structure is the key question
 what are the minimal bonds needed to make a structure rigid?
 some of the cubes have like, one bond that you can make and it will fold completely 

 Information:
 Paul tried having an interaction matrix between all edges of a net
 edges aren't independent... so run into trouble
 maybe you can play a game of adding one bond at a time?
 binary symmetric channels (0 is folded, 1 is unfolded or something)
 could be a simplistic model of like, a protein signalling 
 long-term view of molecular information and robotics

 enumeration algorithm already exists based on the two heuristics
 calculate the different paths you could take
 that kind of works
 this is how that last graph was calculated
 taking that-- could you like, seed with the first two folds for an icosahedra

 disconnectivity

 pluripotent materials -- no one really has a good way of doing this on a colloidal level
 how do we go from one sheet to another
 magnetic particles for reconfiguration might have been used

 diabolos, paul's presentation from august 8-15



# Notes from meeting with Sharon
- High information pathway points
	- flesh out the nets, do totally systematically
- Disconnectivity graph from john
- Folding, with shapes

Questions:
- What does it mean for material to have information?
- Can we determine if some starting points (structures, arrangements, etc) have more information than others
	- Can analyze with disconnectivity graph
- Machine learning to high-likelihood initial configurations
- Application: build "best" starting point for various end configurations

# Brainstorming for prelim meeting with Sharon

Three parts of venn diagram from before.

Theme: Synthetic Intelligence/designed intelligence
1) Information: entropy, storage, retrieval
2) Biomimicry: pluripotency, complex signaling capabilities, CRISPR-like error correction
3) Non-equilibrium systems: agent-based models (minimal models), collection motion

Information storage, retrieval, and action

- Reconfigurability
- How do we embed information in a material?
- How can we embed reconfigurability in a material?
- What information is already embedded in a material building block's properties?

Shape memory materials have a dual-domain system, in which one is always elastic (the elastic domain), while the other (the transition domain) is able to change its stiffness remarkably if a right stimulus is presented.

"The material is the machine": super cool, [here](http://science.sciencemag.org/content/307/5706/53/tab-pdf)

This review addresses recent developments in actively moving materials based on stimuli-responsive polymers on the scale from single molecules to polymer networks. The examples of application of stimuli-responsive polymers for design of actuators, sensors, active elements in microfluidic devices, materials with switchable optical properties as well as biomaterials are discussed. [link](http://pubs.rsc.org/en/content/articlelanding/2010/jm/b922718k#!divAbstract)

### Older notes
Sharon’s suggestion: reconfigurability
 
What world do I envision?
Colloidal robotics:
            Encode information in wet computing
Leverage self-assembly trends to enable particles to run on their own accord—imagine that we could build engineer particles, not just materials, backwards—say that we want this behavior, what shape do we need to do this?
 
Previous work to build off of
Lock and key binding (paper showing different kinetic pathways)
Allophilic shaping—used to improve the self-assembly of desired phases without the use of functionalization external fields, or other types of intrinsic inter-particle interactions
Digital colloids, wet computing

The components of entropy generation in non-equilibrium systems is a fundamental hard problem

Thoughts:
	- Block copolymers phase separate so that similar sides of the strand are in a band-- what would happen with anisotropic shapes where each side would typically have a very different behavior?
