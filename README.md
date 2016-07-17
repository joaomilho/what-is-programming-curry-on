# What is programming

## Dining philosophers

Five philosophers sit at a round table with bowls of spaghetti. Forks are placed between each pair of adjacent philosophers. Each philosopher must alternately think and eat.

The first philosopher thinks for a bit and says
> Programming is like the ideal city: the architecture is ideally planned, everyone does everything to the best interest to the community and no vices are allowed. This city will create an unbeatable army by selecting only the strongest and bravest and train them through the most rigid discipline. This city must be ruled by Computer Scientist who are well rounded in Mathematics and Logic.

The second philosopher thinks for a bit and says
> Programming is like the real city: is starts by chance and evolves based on real needs. There's no big master plan but there may be periods of consolidation. Smaller parts are constantly changing and sometimes bigger parts are built and rebuilt. The city will react to external threats by building defenses according to strategy and it's diversity will be it's strength. This city must be ruled by leaders who understand the cosmos and it's natural harmony hidden behind appearances.

The third philosopher thinks for a bit and says
> Programming is like the human body: there are parts that conduct actions, like hands and legs, but these are commanded by a central control, the mind. The mind is not only capable to command the body to perform tasks, but to produce ideas and to think about this ideas in the most abstract ways and understand the world around us. We can know about ourselves both by reflection and direct contact to our ideas, feelings and sensations, but also investigating ourselves as objects in the world.

The fourth one:
> Programming is a 'postmodern' activity. All your suggestions are grand schemes, and are simply 'lies-to-children'. Real programming has no grand schemes. Programs are actually systems: constellations of part built in completely different ways, connected arbitrarily. While you are discussing your grand schemes people continue building "big balls of mud". Let's instead study mud and improve from there.

The fifth one:
> Hey guys. Can you pass the forks? I'm starving.

And there he stood and died.

## Agenda

1. Programming and philosophy
2. Paradigm wars
3. Programming as science
4. Programming as mathematics
5. Programming as engineering

## 1. Programming and philosophy

First of all, let me clarify a certain way I think philosophy can contribute to Computer Science. There are many ways in which philosophy and Computer Science already intersect, specially in the philosophy of mind slash artificial intelligence world, but also tangentially on, say, computer ethics. But in this presentation I will be focusing on another way. I'll lay out this way using a citation from Timothy Colburn:

> …computer science is ripe for the good old-fashioned analysis that philosophy can provide for any science. Thus, a perfectly reasonable role of philosophy is to attempt to place computer science within the broad spectrum of inquiry that constitutes science. The concern here is to deal with the inevitable identity crises that crop up in the self-image of any adolescent, which computer science certainly is. Philosophy should address questions like: What is the relation between mathematics and computer science? Is there a sense in which computer science is experimental science? … What are the ontological implications of computer science concepts? 
>
> -- <cite>Timothy Colburn, Methodology of Computer Science</cite> <sup>1</sup>

## 2. Paradigm wars

It appears that there is no consensus on what programming is about. It seems reasonable to be so, after all it is an activity that exist for a relatively short period of time.

In this time, it changed the way we perform almost all of our other activities and it carries no smaller promises than virtual worlds, artificial inteligence and immortality.

On the other hand the disagreements are huge and irreconcilable.

> Computer science textbooks, classics, … articles, conferences, and curricula … are dominated by radically different methods of conducting research and teaching … Mathematical methods of investigation guide the research in computability, automata theory, computational complexity, and the semantics of programming languages; design rules of thumb, extensive testing suites, and regimented development methods dominate the branches of software engineering …; and the methods of natural sciences, which combine mathematical theories with scientific experiments, govern the research in AI, machine learning, evolutionary programming, artificial neural networks, artificial life, robotics, and modern formal methods. …in some research institutes computer science is a department in … mathematics, in others it is a part of the engineering …, while other … departments are … with the natural sciences.
> 
> -- <cite>Amonn Eden, Three paradigms of Computer Science</cite> <sup>2</sup>

| paradigm | ontology | knowledge | method | department |
|---|---|---|---|---|
| scientific | [mental] process | law-like | empirical | science |
| rationalist | mathematical object | a priori, certain | deduction | math |
| technocratic | artifact | a posteriori, probable | design | engineering |

So how can it be that programming is seen in so many different ways? A simple, and rather lazy explanation, is that these are three activities are distinct. But before jumping into conclusions, we can take a look at the development of other areas of knowledge.

Established areas of knowledge had what we call today a "pre-scientific" period. This is defined by a period where their object and method were either mature not enough to produce major breakthoughs or were disputed to the point of not having a general consensus among their practitioners. 

But even mature areas of knowledge, seen from a historical point of view seems to contain a dynamic process of breakthroughs leading to redefining or at least refining the understanding of its object, and by doing so, the activity itself changes.

Look, for instance, at the battle going on in physics departments between the adherents of _particle_ and _string_ theories. Many  claim, specially given its lack of experimental results, that "String theory is not physics"<sup>3</sup>, its rather a branch of mathematics dealing with different objects than physics. Others say that string theory indeed represent a whole new method, but this method still relates to the same objects. This contention is not novel in physics. We can also look to the introduction of probabilities of aggregates by the kinetic theory of gases by the 18th century<sup>4</sup>. After all, what we call "classical physics" was adamantly committed to a deterministic theoretical scheme. And more decisively, even the empirical method was not a central part of what was called physics before that. When Galileo pointed his telescope to the moon and invited the scholastics to look, they appealed to _a priori_ impossibilities of his theory. He complained bitterly to Kepler in a letter:

> My dear Kepler, I wish that we might laugh at the remarkable stupidity of the common herd. What do you have to say about the principal philosophers of this academy who are filled with the stubbornness of an asp and do not want to look at either the planets, the moon or the telescope, even though I have freely and deliberately offered them the opportunity a thousand times? Truly, just as the asp stops its ears, so do these philosophers shut their eyes to the light of truth.
> 
> -- <cite>Galileo, letter to Kepler, August 1610</cite> <sup>5</sup>

But nowadays we don't even equate these early efforts with physics, labeling them "aristotelian physics", "scholastic physics" or some other name to distance them from the new activity that was born by then. What links this pre-scientific physics with physics, is that, at least in general it was interested in the same objects, for none would deny that Aristotle was invested on studying, say, motion. Only that his methods, and the methods of his successors (that consisted in a big part on commenting him) were not fruitful and therefore the activity of studying this object needed to be redefined. Philosophy [as practiced] was both, at least is some sense guilty of creating the centuries of aristotelian dogmatism, and pivotal in dispeling it, by constructing convincing arguments to support the new method, to the point it is common sense nowadays.

What seems to be peculiar to the problem of the nature of programming is that there's wide disagreement both in the definition of object and method. Given we have established sciences, the disagreement that seems to be the most fundamental is the one regarding the object. Since in all presented characterizations, the method simply follows the object, using the established sciences as the reference. It would indeed be very creative if computer scientists would come up with a novel method for this novel object, but I'll confine the following discussion on the established views.

## 3. Programming as science

In the 50s, the majority position about programming was the scientific one.<sup>2</sup> That's certainly related to the fact that the very invention of computers was related to this grand narrative of creating a thinking automaton. In hindsight this seems strange, because by now we're well aware of how hard this goal is. It seems that we put the cart before the horse. But is still remarkable the confidence in which researchers by that time would make analogies and draw quick conclusions relating programming to human though. Take this conclusion, for instance:

> To represent algorithms by symbolic expressions in such a way that significant changes in the behavior represented by the algorithms are represented by simple changes in the symbolic expressions. Programs that are supposed to learn from experience change their behavior by changing the contents of the registers that represent the modifiable aspects of their behavior. From a certain point of view, having a convenient representation of one's behavior available for modification is what is meant by consciousness. 
>
> -- <cite>John McCarthy, A Basis For A Mathematical Theory of Computation</cite> <sup>6</sup>

If programming is to be properly scientifical, it seems that it must have as object some natural entity. The relation of program and mental process is not meant simply as a constructive analogy, but as an identity. The nature of this identity is hard to phatom, but must be based on the possibility of translation of pattern encoded as programs in a machine and patterns of neural states in our brains:

> If software is pattern first, and material embodiment of pattern second, then it can be ported from one substratum to another. It is liftable. The pattern embodied in magnetic fields on a disk can be lifted from the disk and transposed to solids and blanks on the cells of punched cards, and vice versa. …
>
> It is this property of software that gives workers in the field of … AI their hope of success. If the mind is reducible to the brain, and the brain is a complicated pattern of neural switches, then the mind … can be lifted and reinstalled in a silicon substratum.
> 
> -- <cite>Peter Suber, What is Software?</cite> <sup>7</sup>

This assumes that:
  
  1. the mind is reducible to the brain
  2. brain patterns are deterministic *and* understandable

This position also may require the assumption that there is, or there will be a solution to the "hard problem of consciousness". Simply put, the problem is that a functional explanation of the brain doesn't seem to account for our subjective experiences<sup>8</sup>.

There are indeed different views of programming as science that doesn't rely on this ontology of mental processes.

> Each … program … is an [experiment] … and its behavior offers clues to an answer. Neither machines nor programs are black boxes; they are artifacts that have been designed, both hardware and software, and we can open them up and look inside. We can relate their structure to their behavior and draw many lessons from a single experiment. … Inspection of the program in the light of a
few runs reveals … [flaws] and lets us proceed to the next attempt. 
>
> -- <cite>Allen Newell & Herbert A. Simon, Computer Science as Empirical Inquiry: Symbols and Search</cite> <sup>9</sup>

In this account, programming is scientific simply because we apply an  experimental method.

The difficulty of this specific formulation is multifold. If a program is an experiment and its behaviour offers clues to an answer, we can rightfully ask: an answer to what? For if a program is an artifact there is a clear disanalogy with Natural Science, for these are sciences occupied with nature and if they test artifacts it is only to accertain their correcteness as a mean to ensure the experiments yield reliable information about its ultimate objects. An even more importantly, it seems that any knowledge that we derive from testing a program is about this program (and following Quine, everything "behind" it<sup>10</sup>), and not general hypothesis. 

> …computers of the present day [are] very complicated and rather poorly defined. As a result, it is usually impractical to reason logically about their behavior. Sometimes, the only way of finding out what they will do is by experiment. Such experiments are certainly not mathematics. Unfortunately, they are not even science, because it is impossible to generalize from their results or to publish them for the benefit of other scientists.
> 
> Tony Hoare, Mathematics of Programming, Program Verification: Fundamental Issues in Computer Science<sup>11</sup>

With time, the naive enthusiasm of the scientific view started to fade. Here's Fred Brooks assessment:

> It is time to recognize that the original goals of AI were not merely extremely difficult, they were goals that, although glamorous and motivating, sent the discipline off in the wrong direction.
>
> -- <cite>Fred Brooks, The Computer Scientist as Toolsmith II</cite> <sup>12</sup>

In any event, this view haven't yet died, or, at least, its main goal still motivates, and will always motivate, even if our aspirations are lower. But its survival, as a full-blown paradigm depends on major breakthoughs in our understanding of the concept of mind.

### 4. Programming as mathematics

Many computer scientists have expressed the opinion that computer science is simply a branch of mathematics. Let us first establish the position:

> Computer programming is an exact science in that all the properties of a program and all the consequences of executing it can, in principle, be found out from the text of the program itself by means of purely deductive reasoning.
> 
> -- <cite>Tony Hoare, An Axiomatic Basis for Computer Programming</cite> <sup>13</sup>

How to use "purely deductive reasoning" doesn't really need to be defined here. Suffice to say this position depends on the idea that in some sense a program can be seen as an ideal entity, that is, as a general characterization, something that doesn't have a spacial location or causal power. In any event, the most convincing way of doing this in the realms of logic and mathematics is by formal methods:

> A proof, as defined in logic, is a finite sequence of formulas of a formal theory satisfying certain conditions. It is a deduction of the conclusion from the axioms of the theory by means of the axioms and rules of logic. Most mathematicians and philosophers believe that any acceptable proof can be formalized.
>
> -- <cite>Thomas Tymoczko, The Four-Color Problem and Its Philosophical Significance</cite> <sup>14</sup>

There are indeed many different arguments against the possibility of "finding all the consequences of a program by means of purely deductive reasoning". The most straightforward is the "the argument of complexity":

> Back in the real world … the specifications for any reasonable compiler or operating system fill volumes and no one believes that they are complete. … The input assertions for these algorithms are not even formulable, let alone formalizable.
> 
> -- <cite>DeMillo, Lipton and Perlis, Social Processes and Proofs of Theorems and Programs</cite> <sup>15</sup>

But on further inspection, although these arguments put some almost unsurmountable difficulties for it, none of these really refute the thesis of programming as a branch of mathematics. A more crucial point is what was presented by Fetzer:

> …algorithms [logical structures of the type function suitable for the derivation of outputs when given inputs] … are subject to absolute verification by means of deductive procedures. This possibility occurs because the properties of abstract machines … can be established by definition, …. In this sense, the abstract machine under consideration simply *is* the abstract entities and relations thereby specified. …programs [a causal model of an algorithm obtained by implementing that function in a form that is suitable for execution by a machine] … are merely subject to relative verification, at best, by means of deductive procedures. Their differences from algorithms arise precisely because… the properties of the abstract machines they represent… stand for physical machines whose properties can only be established inductively.
> 
> …The very idea of program verification trades upon an equivocation. 
> 
> -- <cite>James H. Fetzer, Program Verification: The Very Idea</cite> <sup>16</sup>

In sum, any proof related to ideal entities does not apply unreservedly to natural ones. As put elsewhere "There is no way to deduce logically that bridges stand, or that airplanes fly, or that power stations deliver electricity"<sup>14</sup>. When a physicist (or engineer) calculates the movement of a cannonball, he doesn't expect to have proven it.

This refutation doesn't exclude the possibility of studying programs in an abstract way. But precisely because it only considers them in abstract, it is not a science strictly speaking about programs. The mathematical ingredients involved in the movement of a cannonball don't talk about movement, let alone about cannonballs. They talk about the parabola.

## 5. Programming as engineering

The failure of the two views just presented to yield a proper method for programming coupled with the growing need to solve immediate problems has led to a more pragmatical view:

> That distinction [between science and engineering] lies not so much in the activities of the practitioners as in their purposes. A high-energy physicist may easily spend most of his time building his apparatus; a spacecraft engineer may easily spend most of his time studying the behavior of materials in vacuum. Nevertheless, the scientist builds in order to study; the engineer studies in order to build.
> 
> -- <cite>Frederick Brooks, The Computer Scientist as Toolsmith II</cite> <sup>12</sup>

Brooks pictures programming as an engineering activity while also giving an explanation on why some may think programming is about mathematics or science. That's because being an engineering discipline doesn't rule out the usage of formal or empiric methods, but in a constrained way. In his account, for an activity to be considered a form of engineering, we don't look so much at the methods employed, but to its purpose: anything whose goal is to build must be other than science and mathematics.

This distinction conforms with the classical view of engineering as simply applied science. We have distinguished chemistry and chemical engineering, biology and genetic engineering, etc, in the same vein, even if these are radically distinct from other forms in creating natural entities artificially. 

But simply defining this enquiry doesn't solve the ontological programs. In the same way that adding "science" to something's name, like in "computer science", it doesn't make it so, adding "engineering" doesn't explain away what this thing is.

##### Program as data

An alternative is to assume a more naturalistic ontology to programs, in opposition the scientific and the rationalist views:

> A program … is … information only when it is executed. Before it's really executed as a program in the machine it is handled, carried to the machine in the form of a stack of punch cards, or it is
transcribed, … it is … just as a bunch of data.
>
> -- <cite>Van der Poel, Software Engineering - Report on a conference sponsored by the NATO Science Comitte</cite> <sup>17</sup>

The problem of this characterization is that it can't account for the designer's intentions. To illustrate this point imagine a book that we know for a fact that was written by someone long ago in a language that no one currently understands. We would still call this a book regardless of the current possibility of it being interpreted. If we find a way to interpret it in the future, we would say "now we can read this book" instead of "now this book, that was just data for a long time, is readable".

This captures our common usage for the word book, that is used conversely to denote a specific book or the abstract notion of a book. When we look at a friend's library, and we say "I also have this book", we're talking about this abstract notion. And the same applies to software. This nature is what creates countless issues for software as intelectual property. <sup>18</sup>

The analogy of a program and a book is a highly valuable one, and extends to many features of both, except when it comes to be able to causally influence the behaviors of machines, which a book cannot. This can be seen as a difference in intent: while a book is written for readers, and must be human understandable (or at least, excite human understanding, like in Jabberwocky's case<sup>19</sup>) a program is written for a certain machine or a certain compiler that translates it into a certain machine.

Since not all data can be executed, we need some criteria to distinguish data and software. The best criteria seems to be the author's intent.

There's a key difference in saying that when resting software *is* just data and that it *can be seen* as just data. When a program is compiled it is taken by the compiler as just data. Even parts of a program can intercheangibly be taken as data, like functions that are passed to functions. <sup>7</sup> 

##### Programming as writing

Talking about books, apart from the three views presented here there is also a widespread view that programming somehow relates to writing.

> I think of myself as a writer. Sometimes I write in English and sometimes I write in JavaScript.
>
> It all comes down to communication and the structures that you use in order to facilitate that communication. Human language and computer languages work very differently in many ways, but ultimately I judge a good computer program by its ability to communicate with a human who reads that program. …
> 
> -- <cite>Douglas Crockford, on Peter Seibel, Coders at Work</cite> <sup>20</sup>

This view has a lot to do with the fact that under the engineering discipline writing programs is a highly social enterprise and the program needs to function not only as a machine instructor but as a mean of communication between humans. Some modern languages have as a goal to be as close to English as possible and render the code so "readable" that one can eschew comments and documentation. But the analogy of the activity goes as far the analogy of the object goes, and this was already established before.

##### No ontology

A common feeling between software engineers is that this ontological question is not really relevant. This is the, using Feyerabend famous quote, "anything goes" approach: <sup>21</sup>

> Our view is that computer science has "come of age". Computer Science is sufficient for itself: albeit as an 'unrestricted science' from where investigators must be prepared to follow their problems into any other science whatsoever.
> 
> -- <cite>James Noble & Robert Biddle, Notes on Postmodern Programming</cite> <sup>22</sup>

Indeed, some key results of the discipline of software engineering, such as Design Patterns, seem to be judged simply by the criteria of projects applying them being successful. The "anything goes" approach can include a posteriori justification, but it emphasizes the nature of programming as a practical activity, and prima facie it is reasonable to take decisions based on purely practical grounds.

The pragmatism of software engineering and its emphasis on human needs can't be captured better than in Brook's saying:

> That swordsmith is successful whose clients die of old age.
> 
> -- <cite>Frederick Brooks, The Computer Scientist as Toolsmith II</cite> <sup>12</sup>

The "anything goes" approach also advocates a descriptive worldview, that is, one that avoids metaphors and grand schemes. It sees the ontological question not as a question of nature but as a futile attempt to find the most perfect analogy. It also downplay the role of analogies used in the design of languages themselves, like in class-based OO as platonic metaphysics, or prototype-based OO as wittgenstein's theory of "family resemblance"<sup>23</sup>, or a certain form of FRP as whitehead's "process philosophy"<sup>24</sup>.

> …it doesn't seem to make much sense to say that a Bovine object in a program is an "abstraction" of a real cow in a farm…: it doesn’t make sense to say that the object in the program is "implemented" by a cow in reality, or that the objects in the program are special kinds of cows which do not eat, excrete, or expire. Alternatively, following Plato, we could have an abstraction of a cow as the "ideal, immutable, eternal form" of a cow, perhaps corresponding to a Cow class, but, again, this kind of abstraction is not a good description of the relationship between the cow object and the real cow.
> 
> -- <cite>James Noble & Robert Biddle, Notes on Postmodern Programming</cite> <sup>21</sup>

All these analogies are simply "lies-to-children", that is, something that allows students to "climb the first steps" in a subject to only throw away the ladder later. But it is very common that we, in our deeply ingrained desire for simplicity commit the fallacy of analogy, confusing the analogy for the real thing:

> Within modern computer science … there is an intellectual posture that accepts metaphors from other disciplines uncritically, without providing arguments as to why that metaphor should be applicable. In general, this is the result of the modern grand narrative: computer science must conform to some theory, where that theory is carried by metaphor…
> 
> -- <cite>James Noble & Robert Biddle, Notes on Postmodern Programming</cite> <sup>22</sup>

Also Dijkstra has critized harshly the role of analogy in programming courses:

> It is the most common way of trying to cope with novelty: by means of metaphors and analogies we try to link the new to the old, the novel to the familiar. Under sufficiently slow and gradual change, it works reasonably well; in the case of a sharp discontinuity, however, the method breaks down: though we may glorify it with the name "common sense", our past experience is no longer relevant, the analogies become too shallow, and the metaphors become more misleading than illuminating. This is the situation that is characteristic for the "radical" novelty.
> …
> The educational dogma seems to be that everything is fine as long as the student does not notice that he is learning something really new; more often than not, the student's impression is indeed correct. I consider the failure of an educational practice to prepare the next generation for the phenomenon of radical novelties a serious shortcoming.
> 
> -- <cite>Edsger W. Dijkstra, On the cruelty of really teaching computing science</cite> <sup>25</sup>

But again, the dangers of analogy only materialize when the ladder is not thrown away. And given the educational benefits of analogical thinking and even the possibility that we can't really get rid of it, we should instead focus more on clarifying the "relevant features" of any analogy introduced.

One such clear discussion of OOP is presented by Antero Taivalsaari, in "Classes vs. Prototypes: Some Philosophical and Historical Observations"<sup>23</sup>. OO seems to embody the platonic scheme for a very simple reason: a lot of our practical work is related to the problem of ontology. That is, we need to define what are the elementary elements in our applications, their names, their functions and their relations. Once this is recognized one can throw away the analogy. Recognizing clearly the relevant features also helps us advance, for Antero argues that the development of a more scientific understanding on how we classify things, based on contemporary cognitive psychology, leads to something similar to prototype-based OOP instead.

## Final remarks

Whatever programming is, it is certainly a "radical" novelty, in Dijsktra's account <sup>25</sup>. This view makes it imperative for programmers to understand their trade in a reflexive way, for without this reflexivity we can't expect major breakthroughs in an area that is still fixing its roots.

Worst case scenario this kind of knowledge may help us have better answers than the following, to the question: "Do you think of yourself as a scientist or an engineer or a craftsman? Or something else entirely?". I'm putting this answer here not to mock the author, but because I think this sad feeling is widespread in our industry and representative of many other programmer's feelings:

> [I see myself] …definitely not a scientist or engineer because those have very formal connotations. I don’t do a lot of math; I don’t draw blueprints; I don’t prove things. …I write a lot of screen savers…
> 
> -- <cite>Author omitted, on Peter Seibel, Coders at Work</cite> <sup>20</sup>

### References:

1. Timothy Colburn, **Methodology of Computer Science**, The Blackwell Guide to Philosophy of Computing, 2003
2. Amnon Eden, **Three paradigms of Computer Science**, Minds and Machines, 2003
3. Peter Woit, **Not Even Wrong: The Failure of String Theory and the Search for Unity in Physical Law**, 2006 [comment on blog](http://www.math.columbia.edu/~woit/wordpress/?p=141)
4. Daniel Bernoulli, **Hydrodynamica**, 1738
5. Galileo Galilei, **Letter to Kepler**, 1610
6. John McCarthy, **A Basis For A Mathematical Theory of Computation**, 1961-3
7. Peter Suber, **What is Software?**, Journal of Speculative Philosophy, 1988
8. David Chalmers, **Facing Up to the Problem of Consciousness**, Journal of Consciousness Studies, 1995
9. Allen Newell & Herbert A. Simon, **Computer Science as Empirical Inquiry: Symbols and Search**, ACM Turing Lecture Award, 1975
10. Willard Van Orman Quine, **Two Dogmas of Empiricism**, 1951
11. Tony Hoare, **Mathematics of Programming**, Program Verification: Fundamental Issues in Computer Science (edited by Timothy Colburn, J.H. Fetzer, R.L. Rankin), 1993
12. Fred Brooks, **The Computer Scientist as Toolsmith II**, 1994
13. Tony Hoare, **An Axiomatic Basis for Computer Programming**, Communications of the ACM, 1969
14. Thomas Tymoczko, **The Four-Color Problem and Its Philosophical Significance**, The Journal of Philosophy, 1979
15. DeMillo, Lipton and Perlis, **Social Processes and Proofs of Theorems and Programs**, Communications of the ACM, 1979
16. James H. Fetzer, **Program Verification: The Very Idea**, Program Verification: Fundamental Issues in Computer Science (edited by Timothy Colburn, J.H. Fetzer, R.L. Rankin), 1993
17. Van der Poel, **Software Engineering - Report on a conference sponsored by the NATO Science Committee**, Naur & Randell, 1969
18. Stephan Kinsella, **Against Intelectual Property**, 2008
19. Lewis Carroll, **Jabberwocky**, Through the Looking-Glass and What Alice Found There, 1872
20. Peter Seibel, **Coders at Work**, 2009
21. Paul Feyerabend, **Against Method**, 1975
22. James Noble & Robert Biddle, **Notes on Postmodern Programming**, 2002
23. Antero Taivalsaari, **Classes vs Prototypes: Some Philosophycal and Historical Observations**, 1996
24. Rich Hickey, **Are We There Yet?**, 2009 [online](https://www.infoq.com/presentations/Are-We-There-Yet-Rich-Hickey)
25. Edsger W. Dijkstra, **On the Cruelty of Really Teaching Computer Science**, 1988