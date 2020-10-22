# Important papers in the history of artificial intelligence
We are reading through some of the great papers in the history of artificial intelligence. The reading list is intentionally broad pulling from computer science, mathematics, philosophy, lingustics, and cognitive science, and we have a preference for older papers (i.e. written before the year 2000). The only other selection criterion is they have to be shortish papers (< 15 pages), so sorry, no books! The goal is broad understanding of the research that forms the foundations for present day AI, and an a deeper understanding of the context in which each paper was written. 


## Journal club papers to date
- Paper: __An Inductive Inference Machine__ <br />
  Author(s): Ray Solmonoff <br />
  Year: 1956 <br />
  Date: July 14th, 2020 <br />
  Presenter: Joe Hakim <br />
  Link: http://raysolomonoff.com/publications/indinf56.pdf <br />
  Slides: https://docs.google.com/presentation/d/14whQ2ZuEjGtz2hRvwvHKhj6eGbzKWRABUjeFxn7RhKM/edit?usp=sharing<br />
  __tl;dr:__ A description of an algorithm that can perform prediction on grids of numbers and operations. Works by using prior examples and specific transformations thereof to produce predictions favoring 'utility' and 'consistency'. Some brief philosophical discussion towards making the algorithm more "AI-like" and theoretical properties. <br />
  __Important because:__ Early (earliest?), truly probabilistic treatment of machine learning. <br />
- Paper: __Generalization of Pattern Recognition in a Self-Organizing System__ <br />
  Authors: WA Clark, BG Farley  <br />
  Year: 1955 <br />
  Date: August 11th, 2020 <br />
  Presenter: Eric Chen <br />
  Link: https://pdfs.semanticscholar.org/616b/9f5b957de2249ed1ae433b9be1bf1d45cdef.pdf<br />
  Slides: https://www.dropbox.com/s/6u8qzp0zmodjr71/08112020_journalclub.pptx<br />
  __tl;dr:__ Clark and Farley present two experiments on the application of neural nets to the generalization of pattern recognition. The first experiment demonstrates that the net can be successfully trained (“organized”) on input patterns subjected to random variation, while the second experiment demonstrates that a trained net can successfully classify new input sequences into three classes based on observed behavior. The authors use many techniques that are similar to modern machine learning techniques.  <br />
  __Important because:__ Early application of neural nets to the generalization of pattern recognition/classification; precursor to modern machine learning techniques (noise injection, data augmentation, model ensembles)<br />
- Paper: __Minds, brains, and programs__ <br />
  Author(s): John Searle  <br />
  Year: 1980 <br />
  Date: September 24th, 2020 <br />
  Presenter: Matthew Lee  <br />
  Link: http://cogprints.org/7150/1/10.1.1.83.5248.pdf<br />
  Slides: https://drive.google.com/file/d/1h8SESVBIBc7B8I-2fXw62hcyh1rUShQC/view?usp=sharing<br />
  __tl;dr:__ John Searle presents his famous thought experiment, the Chinese Room Argument. The Chinese Room Argument is a position that argues against "Strong AI" or AI that truly understands. The argument is simple, a man is in a room with formal rules to correlate Chinese symbols with other Chinese symbols, when he receives an "input" script of Chinese symbols he is able to correctly map the symbols to the correct "output" answers in Chinese symbols, the man however still does not understand Chinese. This philosophical paper explores artificial intelligence and whether or not a computer is able to understand or is simply manipulating formal symbols.   <br />
  __Important because:__ A famous thought experiment, similar to the Turing test, that explores a machine capabilities to achieve human-like intelligence. <br />
- Paper: __MPrediction and Entropy of Printed English__ <br />
  Author(s): Claude Shannon  <br />
  Year: 1950 <br />
  Date: October 22nd, 2020 <br />
  Presenter: Ben Kompa <br />
  Link: http://languagelog.ldc.upenn.edu/myl/Shannon1950.pdf<br />
  Slides: https://docs.google.com/presentation/d/1sidRSdmpqW1uGkmEUh5NSy_1UBaXIWYHtwlONJeDulo/edit?usp=sharing<br />
  __tl;dr:__ Shannon provides an early analysis of the entropy of English language that holds true even today. He begins by defniing the entropy of an N-gram, which is simply N letters of English. Then, he considers two careful experiments. The first experiments consists of a participant attempting to guess the next letter of a text with only one chance at guessing the letter before moving on. The second experiment allows the participant to guess as many times as necessary until the correct letter is chosen. After deriving theoretical bounds on the N-gram entropy of English, Shannon is able to use the results of the second experiment to provide upper and lower bounds on N-gram entropy that are relevant even today.  <br />
  __Important because:__ Early exploration of the entropy of langugae, releveant to language models today. <br />



## Potential paper list
Papers we hope to cover eventually, listed in a semi-random order:

- Paper: __Computing machinery and intelligence__ <br />
  Author: Alan Turing <br />
  Year: 1950 <br />
  Link: http://www.cse.chalmers.se/~aikmitr/papers/Turing.pdf#page=442
- Paper: __Learning Representations by Back-propagating Errors__ <br />
  Author: David E. Rumelhart, Geoffrey E. Hinton & Ronald J. Williams  <br />
  Year: 1986 <br />
  Link: http://www.cs.toronto.edu/~hinton/absps/naturebp.pdf
- Paper: __Maximum Likelihood from Incomplete Data Via the EM Algorithm__ <br />
  Author: A. P. Dempster, N. M. Laird and D. B. Rubin  <br />
  Year: 1977 <br />
  Link: http://www.markirwin.net/stat221/Refs/dlr1977.pdf
- Paper: __The perceptron: a probabilistic model for information storage and organization in the brain__ <br />
  Author: A. P. Dempster, N. M. Laird and D. B. Rubin  <br />
  Year: 1958 <br />
  Link: https://www.cs.cmu.edu/~epxing/Class/10715-14f/reading/Rosenblatt.perceptron.pdf
- Paper: __A learning algorithm for Boltzmann machines__ <br />
  Author: David H Ackley, Geoffrey E Hinton, Terrence J Sejnowski  <br />
  Year: 1985 <br />
  Link: https://onlinelibrary.wiley.com/doi/pdf/10.1207/s15516709cog0901_7
- Paper: __Support-Vector Networks__ <br />
  Author: Corinna Cortes, Vladimir Vapnik  <br />
  Year: 1995 <br />
  Link: https://link.springer.com/content/pdf/10.1007%252FBF00994018.pdf
- Paper: __The use of multiple measurements in taxonomic problems__ <br />
  Author: RA Fisher  <br />
  Year: 1936 <br />
  Link: https://onlinelibrary.wiley.com/doi/pdf/10.1111/j.1469-1809.1936.tb02137.x
- Paper: __An essay towards solving a problem in the doctrine of chances__ <br />
  Author: Thomas Bayes  <br />
  Year: 1763 <br />
  Link: https://www.ias.ac.in/article/fulltext/reso/008/04/0080-0088
- Paper: __Prediction and entropy of printed English__ <br />
  Author: Claude Shannon  <br />
  Year: 1951 <br />
  Link: http://languagelog.ldc.upenn.edu/myl/Shannon1950.pdf
- Paper: __A theory of the learnable__ <br />
  Author: Leslie Valiant  <br />
  Year: 1984 <br />
  Link: http://axon.cs.byu.edu/~dan/678/papers/Learning%20Theory/Valiant.pdf
- Paper: __Statistical modeling: The two cultures__ <br />
  Author: Leo Breiman  <br />
  Year: 2001 <br />
  Link: https://projecteuclid.org/download/pdf_1/euclid.ss/1009213726
- Paper: __Intelligence without representation__ <br />
  Author: Rodney Brooks  <br />
  Year: 1996 <br />
  Link: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.89.5683&rep=rep1&type=pdf
- Paper: __Elephants don't play chess__ <br />
  Author: Rodney Brooks  <br />
  Year: 1990 <br />
  Link: https://www2.cs.sfu.ca/~vaughan/teaching/894/papers/elephants.pdf
- Paper: __Some studies in machine learning using the game of checkers__ <br />
  Author: Arthur L. Samuel  <br />
  Year: 1959 <br />
  Link: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.368.2254&rep=rep1&type=pdf
- Paper: __Why the future doesn't need us__ <br />
  Author: Bill Joy  <br />
  Year: 2000 <br />
  Link: http://science.slc.edu/~jmarshall/courses/2007/fall/singularity/readings/bill_joy_wired.pdf
- Paper: __As we may think__ <br />
  Author: Vannevar Bush  <br />
  Year: 1945 <br />
  Link: https://www.theatlantic.com/magazine/archive/1945/07/as-we-may-think/303881/
- Paper: __Deep Blue__ <br />
  Author: Murray Campbell, Joseph Hoane Jr., Feng-hsiung Hsu  <br />
  Year: 2002 <br />
  Link: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.99.2714&rep=rep1&type=pdf
- Paper: __The paradoxical success of fuzzy logic__ <br />
  Author:Charles Elkan <br />
  Year: 1995 <br />
  Link: https://www.aaai.org/Papers/AAAI/1993/AAAI93-104.pdf
- Paper: __Programs with common sense__ <br />
  Author: John McCarthy  <br />
  Year: 1959 <br />
  Link: http://www-formal.stanford.edu/jmc/mcc59.pdf
