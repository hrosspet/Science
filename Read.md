* http://izhikevich.org/publications/dastdp.htm
	- STDP
	
* http://www.izhikevich.org/publications/reentry.pdf
	- neuronal groups given by spacio-temporal spiking patterns
	- enables learning with variable synapse length and solves the distal reward problem

* Learning in SNN by Reinforcement of Stochastic Synaptic Transmission.pdf
	- enables learning with probabilistic synapses (~ mutation in evolution)
	
* http://artificial-intuition.com/
	- intelligence - intuition - highly connected to prediction
	- my thoughts: classical approaches can be used for AN training (fast generation of logically deducted states)
	
* https://www.youtube.com/watch?v=AyzOUbkUf3M
	- restricted boltzman machines + backprop for fine-tuning -> extract features (unsupervised)
	- restrictive = no lateral interactions (bipartite graph between layers)
	-> also generative models	~ train a model that explains the input
	- machine learning + hashing -> similar documents maps to similar hash code -> approximate search
	- partially restricted boltzman machines - 
	
* https://www.youtube.com/watch?v=_m97_kL4ox0
	- Polyworld
	- simulated world of critters, which have neural networks to evolve
	
* https://www.youtube.com/watch?v=Tx1G4BNd4dw&list=WL&index=25
	- Evolving Regular, Modular Neural Networks
	- learning in brain not only for fine-tuning, but also because it is hardly possible to encode billions of neurons in a genome, which has ~25k genes
	- world is very regular, there are regularities everywhere. Generative encoding can capture regularities in problems to solve them better/easier
	- modularity ~ encapsulations of parts of the systems, well functioning modules are repeated
		- imagine building an operating system as a single function, not composed of many small function - it is a mess, it there is no modularity
			-> imagine neural network as a module, we could evolve the topology of a bigger network by reusing smaller networks
		- it makes sense, if you take a network as a function with some nice properties - by combining them you can get better results
		- adding a constraint of connection cost (between neurons) biases evolution to evolve more modular solutions (modular solutions are more efficient in connections)
		- modular solutions adapt faster to changing environment
		
* http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0090821
	- application of spiking NN with reward modulated STDP to a problem of foraging food in artificial environment
	- they somehow solved the problem of stability of weights (so they are not bimodal - at the limits of synapse strength)
	- "synaptic noise and random perturbations of synaptic connectivity during training phase are both required to achieve maximal network performance after training"
	
* http://worrydream.com/#!2/LadderOfAbstraction
	- When I was looking for some info about how humans do their abstraction, I came to this article. After a while I found out it is more about user interface than
	about how we think. But after going through the whole article I realized, that these two thinks are not different. A good user interface must be close to how we think,
	otherwise it wouldn't work.
	- Anyway, what I like about this article is, that it describes very well the method of analyzing problems and understanding them, which is essential for finding
	solutions. This can be useful for our research.
	
* http://www.coredemia.com/
	- scientific articles + discussion?
	
* https://www.youtube.com/watch?v=FDCQZj7_Tho
	- Noam Chomsky (and 5 others from MIT) On Artificial Intelligence , Cognitive Science , and Neuroscience
		- 0 General info about the 6 speakers
		- 15:40 Sydney Brenner
		- 29:20 Marvin Minsky
		- 42:40 Noam Chomsky
		- 1:14:10 Emilio Bizzi
		- 1:27:10 Barbara H. Partee
		- 1:39:00 Patrick H. Winston
		- 1:55:00 Questions

* http://jeremykun.com/main-content/
	- interesting blog about mathematics, machine learning, hacks, etc.
	
* http://www.illc.uva.nl/Research/Publications/Dissertations/DS-2007-01.text.pdf
	- in \Literature: Statistical Inference Through Data Compression - 2007
	- using data compression to obtain similarity measure on files
	- using google search results (number of hits) as a compressor, resulting in extraction of semantic meaning
	
* http://en.wikipedia.org/wiki/Universal_artificial_intelligence
	- Hutter says compression of text is the same problem as general AI
	
* http://mattmahoney.net/dc/rationale.html
	- relationship between AI and compression explained
	
* http://www.technologyreview.com/news/529691/ibm-chip-processes-data-similar-to-the-way-your-brain-does/
	- IBM neuronal chip
	
* https://www.youtube.com/watch?v=z6r3ekreRzY
	- Numenta CLA (Cortical Learning Algorithm)
	- "compression of input so that similar inputs are represented similarily, kind of opposite of what hash functions do."
	
* http://aob.oxfordjournals.org/content/92/1/1.full
	- Mindless Mastery - Aspects of Plant Intelligence, Anthony Trewavas

* http://www.tedxvienna.at/blog/parasitic-mind-control/?fb_action_ids=10152210952946286&fb_action_types=og.likes
	- mindcontroll by parasites

* http://cs.stanford.edu/people/ang/papers/nips10-TiledConvolutionalNeuralNetworks.pdf
	- explanation of convolutional networks

* http://www.wired.com/2014/08/scientists-turn-bad-mice-memories-into-good/
	- memories consist of 2 parts: spatial information and emotional information. The emotional part has been changed in mice (bad -> good and good -> bad)

* Input Prediction and Autonomous Movement Analysis in Recurrent Circuits of Spiking Neurons
	- in Education\Prediction
	- using "Liquid state machine" (liquid ~ analogy with stone thrown in water -> movement of the stone is then encoded in the water waves) - kind of reservoir nets
	- implementation details in Literature\Real-time computing without stable states A new framework for neural computation based on perturbations - Maass - 2002.pdf
	- the pool of randomly connected recurrent neurons serves as a) general-purpose temporal integrators, b) kernels (i.e., nonlinear projections into a higher dimensional space)
	- "In fact, if all correctly predicted components of the input stream are surpressed before they can enter "higher" neural systems, the sensory input stream is recoded by such circuit into a neural code that is closer to
		a theoretically optimal code which reserves the shortest "words"– in this case the fewest spikes – for reporting the most frequently occurring events 		(comparable with the Huffman code, see e.g. [Cover and Thomas, 1991])."

* http://vimeo.com/33014198
	- Noise in Biological Systems - Gordon Pipa, Max Planck Institute for Brain Research
	- Liquid State Machines tweaked
	- STDP -> learning sequences, but no longer predictive
	- IP (Intrinsic Plasticity) -> homeostasis ~ noise, but predictive
	- STDP + IP -> robustness in predicting sequences

* http://devblogs.nvidia.com/parallelforall/accelerate-machine-learning-cudnn-deep-neural-network-library/
	- Cuda Deep Neural Network Library
	- ready to use with no coding or for including in any project

* http://www.ted.com/talks/daniel_wolpert_the_real_reason_for_brains#t-346851
	- the motivation of evolving brain is to precisely control movement

* https://www.rdmag.com/news/2014/09/new-foundation-mathematics
	- prof. Voevodsky suggests the theory of homotopy is more useful for expressing and deriving proofs
	- in this known theory (used for describing transformations/deformations of geometrical objects) any mathematical objects can be expressed, but as opposed
		to other theories used for theorem proving such as Zermelo-Frankel set theory it can map better to computers
	- it expresses not only equivalence of objects as a=b, but also the transformation how a can be obtained from b, etc.

* http://dslr.dimakrasner.com/
	- very tiny linux -> very fast, also for old machines

* http://senselab.med.yale.edu/modeldb/
	- huge online database of various neural models

* https://github.com/niuzhiheng/caffe/
	- Caffe library for win (MSVC)

* http://www.nytimes.com/books/first/h/hoffman-man.html
	- Erdös - the mathematician
	- also in \Literature

* http://memkite.com/deep-learning-bibliography/
	- DeepLearning.University – An Annotated Deep Learning Bibliography

* http://arxiv.org/pdf/1310.1531v1.pdf
	- DeCAF - library specially for extracting features

* http://www.micropsi.com/
	- cognitive artificial intelligence - the MicroPsi Project
	- emotions are just the actual configuration (state) of mind, which modulates the cognition.

* http://io9.com/why-our-brain-takes-risks-in-the-face-of-uncertainty-1639030771
	- Your Decision-Making Processes Are a Lot More Random Than You Realize
	- isn't it more like in default the distribution of decisions is uniform (random) and when learning from experiences shifts the probability to certain points?
	- link to "bad decisions" of human in depression

* How to Build a Brain
	- Good Oldfashioned Artificial Intelligence [GOFAI]) - mind as computer - symbolic approach
	- Connectionism - also known as the Parallel Distributed Processing [PDP] approach - mind as brain
	- Dynamicism - mind as Watt Governor - dynamic/chaotic system like weather

	- basal ganglia ~ action selection
	- thalamus - gating/control of information flow -> also used in action selection (cortex-basal ganglia-thalamus loop)
	
	- SPA does not identify a settled “level of abstraction”, you can switch between levels as you need

* http://blogchain.fr/programmarket-en/
	- decentralized proof market / program market

* http://www.micron.com/about/innovations/automata-processing
	- A Massively Parallel Computing Solution
	- new architecture for parallel computing

* http://cr.yp.to/talks/2014.10.18/slides-djb-20141018-a4.pdf
	- Making sure crypto stays insecure
	- also in \off\crypto is not secure

* http://arxiv.org/abs/1410.5401.pdf
	- http://arxiv.org/pdf/1410.5401v1.pdf
	- Neural turing machines
	- both content based addressing and location based addressing
	- NN with external memory learning following algorithms: copy, nested copy (iterate given number of iterations), priority sort, N-grams?

* Scaling up deep networks
	- also on http://www.iro.umontreal.ca/~bengioy/talks/KDD2014-tutorial.pdf
	- first ~82 pages recapitulation of neural networks, then state of the art deep networks and future possibilities

* Spatial Pyramid Pooling in Deep Convolutional Networks
	- also on * http://arxiv.org/pdf/1406.4729v1.pdf
	- different kind of pooling for deep nets for higher efficiency (25x - 200x faster)

* http://xuanji.appspot.com/isicp/
	- Structure and Interpretation of Computer Programs
	-Interactive Structure and Interpretation of Computer Programs. Online version of SICP with a built-in scheme interpreter to allow readers to edit and run the code embedded in SICP. (Work in progress)

* http://www.andrewbadr.com/log/24/delegative-democracy-a-scalable-voting-model/
	- delegative democracy

* http://www.bbc.com/earth/story/20141111-plants-have-a-hidden-internet
	- wood wide web - internet between plants made of fungi

* How to do Research at MIT AI lab
	- in Literature folder, or https://people.cs.umass.edu/~emery/misc/how-to.pdf
	- useful rules of thumb for doing research in general

* http://www.reddit.com/r/MachineLearning/comments/2lmo0l/ama_geoffrey_hinton/
	- Geoffrey Hinton answering questions on reddit

* http://hilbert-lang.org/
	- https://github.com/gogotanaka/Hilbert
	- programming language for mathematics, can be used within any widely used languages like Ruby, Haskell, Scala, Java, Python and even TeX

* https://github.com/arrayfire/arrayfire
	- API for GPGPU

* http://arxiv.org/pdf/1411.4798v1.pdf
	- Memcomputing NP-complete problems in polynomial time using polynomial resources
	- analog devices inside! careful! :)

* Universally preferable behaviour
	- http://cdn.media.freedomainradio.com/feed/books/UPB/Universally_Preferable_Behaviour_UPB_by_Stefan_Molyneux_PDF.pdf
	- truth is better than falsehood?
	- existence of universally preferable behaviour is based on the argument, that if somebody was trying to convince you, that no such thing exits, it would be a paradox. But what if I don't think it exists and thus
		I am not concerned about it at all (again - I don't care about truth or falsehood), so I don't try to convince anybody
		- this just means that it can not be refuted
	- Circular definition (definice kruhem) - argument based on assertion that everybody has some moral rules (although not all have the same rules) - page 41
	- aha aha, mozna tomu zacinam rozumet: on nedokazuje, ze existuje v kazdem cloveku UPB, ale ze existuje obecne a my se k nemu vice ci mene priblizujeme
		- morality is clearly optional, but objective
	- why does he often compare with "drawing a gun and shooting you", if nobody would take such an extreme action

* http://ventrellathing.wordpress.com/2013/06/18/the-case-for-slow-programming/
	- slow programming
	- interesting references: 
		- pair programming http://en.wikipedia.org/wiki/Pair_programming
		- code reviews http://en.wikipedia.org/wiki/Code_review
		- code refactoring http://en.wikipedia.org/wiki/Code_refactoring

* http://joshmitteldorf.scienceblog.com/2015/01/05/what-is-aging-most-scientists-still-get-it-wrong/
	- aging is natural and precoded in body

* http://www.npr.org/blogs/health/2015/01/05/371894919/what-heroin-addiction-tells-us-about-changing-bad-habits
	- humans use their environment as sort of triggers (shortcuts) for complex behavior
	- this is also connected to addiction

* http://brookeallen.com/pages/archives/1234
	- how to make the hiring process more humane
	- "if you care about people they will care back, and with just a little bit of encouragement most people will eagerly learn what you need them to know"