
# Blog Planning

## General Tips

* Why am I writing it? To educate my generation who don’t have a strong interest in AI on the amazing applications of AI. To express my own passions. To improve my vocabulary and writing style.
* Do you want to encourage questions? Yes, why not!
* Effective title: 5 things I learned …. Spoliers in title / intro are good.
* Know audience: Educated individuals from other subject fields. Consider when picking title, selecting images, etc. Drop technical expressions accordingly
* Concise: translate entire arguments into points. Use photos, videos, etc to break up any images. Subtitles, make it skimable.
* Social media: include links to accounts.
* Write the occasional blog about you
* Encourage criticism, listen to readers
* Outline mathematical assumptions made regarding the reader
* Proofread, get feedback before publishing
* Tag posts!
* Educational blogs: Interactive, embed quizzes, link interesting material

## Key Questions 

Ask myself these everytime I write a blog.

1.	What were the achievements?
2.	What were the previous failures?
3.	What are the key points?
4.	What the technology?
5.	What’s the surprising story that the data shows?
6.	What’s the most interesting thing to the average reader?
7.	What cool visualizations, interactive content or quizzes can I include?
8.	Link to sustainability?
9.	What’s the impact?
10.	Negative implications?
11.	Future work?


## Why am I doing this?

1.	Educate my generation, whom I have discovered don’t understand the field e.g. Musk, autonomous vehicles, systems that self-modify and take over the world
2.	Express my passions in my own way e.g. AlphaFold: first time an AI project encouraged me to research an entirely new field
3.	Personal development: haven’t improved my writing style and vocabulary in years

## The name? What is AI?

1.	AI: Definition. See venn diagram.
2.	For my friends: This blog was one of the many ideas I had whilst travelling Latin America. Its amazing how far your brain can wonder during the 8th hour of a bumpy, gravel track in a minibus without airconditioning and a sleeping European next to you falling on you every 5 minutes!

## Audience?

1.	My friends. Educated but not in a mathematical field. Maybe some basic matrix multiplication. I’ll try and stick as Englishy as possible.

## Topic Ideas

* AlphaFold
* Bayesian networks for identifying dead bodies
* Face paper
* Longitude / latitude: genomic data PCA
 
## AlphaFold Notes

### Key Questions

1.	What were the achievements? Noble prize. 50-year grand challenge. Nature quote, Forbes quote. 
2.	What were the previous failures? Determining structure: 2 methods: sequence -> protein -> crystallisation -> structure. Shortcut sequence -> structure. 
3.	What are the key points? Proteins: sequence, uses. Sequence -> structure (forces of physics). Importance of structure (link to function). 
4.	What the technology? Deep RL. Chess example. 
5.	What’s the most interesting thing to the average reader? The use cases.
6.	What cool visualizations, interactive content or quizzes can I include?
7.	Link to sustainability? Use case of breaking up plastics. Link to Unfolded.
8.	Negative implications? Bioterrorism.
9.	Future work? Model a cell.

###  Spoiler 
Noble prize.
4 years x 2 million proteins. 
50 year grand challenge of molecular biology. 
Predict structure, important link to function. Nature quote, Forbes quote. Made the database.
Forbes Quote: https://www.forbes.com/sites/robtoews/2021/10/03/alphafold-is-the-most-important-achievement-in-ai-ever/?sh=51afa9816e0a

### Notes  (from Demis pod with Lex)

#### Molecular biology

Background: proetiens, sequence, uses. Sequence -> structure (forces of physics). String of beads folds up into a ball. Structure: (1) important to target, you need to know location of target to bind to it, (2) linked to function. Importance of structure (link to function). Include visualization. Animations of how proteins work. 

Protein folding problem: done experimentally, crystalise protein (some can’t be crystalisaed), expensive electromicroscopes, painstaking work to visualise structure. 1 PhD entire PhD for 1 protein. AlphaFold, a few seconds.
In 1961, Anfinsen proved that the sequence of amino acids, in itself, determines the way the chain folds itself and that no additional genetic information is required in this process. Said we can computationally determine the structure given the sequence.

#### Technology

Deep reinforcement learning. Why it suits AI? Search space, common patterns, training data, laws of Physics.

#### Use cases

Link Unfolded. Discuss breaking up plastics. Bioterrorism.

#### Conclusion

Massive achievement. Yet to see the benefits of this. Every biologist in the world has used the database. Just the start: future work.

### More Notes 

Bioinformatics: Dr Antunes: Protein Folding & AlphaFold2 podcast

- Structure is maintained more than sequence across organisms, i.e. 2 proteins with similar function in different organisms are likely to have structural similarities.
- Sequences tend to fold in the same way, so can copy structure from other proteins if sequence tends to be the same.
- AlphaFold2 key evolutionary idea: if 2 proteins share a sequence of amino acids that are key to each protein’s function, then if one of the acids mutates, the other one must too (in order to maintain function).

- Nature: this will change everything article headline. Forbes: the most important achievement in AI ever
- reference to plastic in ocean per year
- Proteins: workforce behind everything in human body. Immune system: antibodies. Insulin: allows glucose absorption. Haemoglobin: ships oxygen around the body.
- 20 types of amino acids. Protein is a line of these. 
- Within milliseconds, Forces of physics force this sequence into a 3D shape.
- 1-d shape gives little clue about function. 3-d shape gives many clues regarding function. E.g. drugs bind to proteins in a certain way.
- 2 methods: sequence -> protein -> crystallisation -> structure. Shortcut sequence -> structure. 
- Demis inspired by friend who was obsessed with this problem.
- Problem suited AI: common patterns in how similar sequences create similar structure, infinite large search space, training data from decades of work
- Key-lock analogy: enzymes

Will release help creation of new bio weapons or increase potency of existing ones. If someone is intent on committing bioterrorism, they are many ways easier than understanding than getting to grips with the biochemistry of protein folding.

Uncertainty; some proteins have never been seen before. Measure of uncertainty included.

Genomics, nuclear fusion, mathematics, chemistry and a new climate team. 
Motivation