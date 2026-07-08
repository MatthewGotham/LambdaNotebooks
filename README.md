# Lambda Notebooks

This is where I share &lsquo;digital fragments&rsquo; that I have developed to implement Linguistics ideas using Kyle Rawlins' [Lambda Notebook](https://github.com/rawlins/lambda-notebook). Follow that link for installation instructions, after which you should be able to run the files.

## Contents

### [Copredication](https://github.com/MatthewGotham/LambdaNotebooks/blob/master/Copredication.ipynb)

This is a workbook for for looking at the compositional semantics of copredication, especially as regards quantification. It contains a demonstration of some ideas found in Gotham 2014; 2018; 2022.

### [DynamicContinuations](https://github.com/MatthewGotham/LambdaNotebooks/blob/master/DynamicContinuations.ipynb)

This workbook exemplifies the idea of handling dynamic semantics using continuations, as is done e.g. by Groenendijk & Stokhof (1990) and de Groote (2006). The underlying idea in these papers is that if $a$ is your type for tracking discourse referents, then sentence meanings are of type $\langle a,\langle\langle a,t\rangle,t\rangle$. That means that in principle, a sentence $S$ can place the sentence following it within the scope of operators contained in $S$, which is how you get dynamic binding.

### [Dynamics-TTS-in-STT](https://github.com/MatthewGotham/LambdaNotebooks/blob/master/Dynamics-TTS-in-STT.ipynb)

This is a workbook for dynamic semantics that takes as its starting point some ideas from type-theoretical semantics/dependent type semantics (e.g. Sundholm 1986; Ranta 1991; Bekki 2014), implementing them in (more or less) simple type theory. It then moves beyond that into other applications: generalized quantifiers and quantificational subordination. It contains a demonstration of some ideas found in Gotham 2018; 2019, plus a section on both sentence-exteral and sentence-interal _different_ that hasn't to my knowledge been published elsewhere.

### [EventRelatedReadings](https://github.com/MatthewGotham/LambdaNotebooks/blob/master/EventRelatedReadings.ipynb)

This notebook shows derivations for object-related and event-related readings of examples like Krifka's celebrated &lsquo;Four thousand ships passed through the lock&rsquo; (Krifka 1990). It is based on Gotham 2021, and includes a compositional-semantic treatment of _different_ in these examples.


## References

- Bekki, Daisuke (2014). [Representing Anaphora with Dependent Types](https://doi.org/10.1007/978-3-662-43742-1_2). In Nicholas Asher & Sergei Soloviev (eds.), _Logical Aspects of Computational Linguistics_, 14&ndash;29. Lecture Notes in Computer Science 8535. Berlin/Heidelberg: Springer.
- Gotham, Matthew (2014). [Copredication, Quantification and Individuation](https://matthewgotham.github.io/linguistics/MG-thesis.pdf). PhD Dissertation, University College London.
- Gotham, Matthew (2017). [Composing Criteria of Individuation in Copredication](http://academic.oup.com//jos/article/doi/10.1093/jos/ffw008/2555474/Composing-Criteria-of-Individuation-in?guestAccessKey=62fb866e-7bd4-47ae-b6b6-cc1be28a5aeb). _Journal of Semantics_ 34(2):333–371.
- Gotham, Matthew (2018). [A Model-Theoretic Reconstruction of Type-Theoretic Semantics for Anaphora](https://matthewgotham.github.io/linguistics/#FG2017). In Annie Foret, Reinhard Muskens & Sylvain Pogodalla (eds.), _Formal Grammar: FG 2017_, 37–53. Lecture Notes in Computer Science 10686. Berlin, Heidelberg: Springer.
- Gotham, Matthew (2019). [Quantificational Subordination as Anaphora to a Function](https://matthewgotham.github.io/linguistics/#FG2019). In Raffaella Bernardi, Greg Kobele & Sylvain Pogodalla (eds.), _Formal Grammar: FG 2019_, 51–66. Lecture Notes in Computer Science 11668. Berlin, Heidelberg: Springer.
- Gotham, Matthew (2021). [Event-related readings and degrees of difference](https://ojs.ub.uni-konstanz.de/sub/index.php/sub/article/view/940/864). In Patrick Georg Grosz, Luisa Martí, Hazel Pearson, Yasutada Sudo & Sarah Zobel (eds.), _Proceedings of Sinn und Bedeutung 25_, 325–339. 
- Gotham, Matthew (2022). [Property Inheritance, Deferred Reference and Copredication](https://doi.org/10.1093/jos/ffab020). _Journal of Semantics_ 39(1):87–116.
- Groenendijk, Jeroen & Martin Stokhof (1990). [Dynamic Montague Grammar](https://eprints.illc.uva.nl/id/eprint/1148/). Technical Report LP-1990-02, University of Amsterdam.
- de Groote, Philippe (2006). [Towards a Montagovian Account of Dynamics](https://journals.linguisticsociety.org/proceedings/index.php/SALT/article/view/2952/2692). In Masayuki Gibson & Jonathan Howell (eds.), _Proceedings of SALT_ 16:1–16.
- Krifka, Manfred (1990). [Four thousand ships passed through the lock: Object-induced measure functions on events](https://doi.org/10.1007/BF00627291). _Linguistics and Philosophy_ 13:487–520
- Ranta, Aarne (1991). _Type-Theoretical Grammar_. Oxford: Oxford University Press.
- Sunholm, Göran (1986). [Proof Theory and Meaning](https://doi.org/chapter/10.1007/978-94-009-5203-4_8). In Dov Gabbay & Franz Guenther (eds.), _Handbook of Philosophical Logic_, Volume 3, 471–506. Dordrecht: D. Reidel.
