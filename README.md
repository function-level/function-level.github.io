## From Function-Level Programming to Pointfree Style

[**Functional Programming**](https://en.wikipedia.org/wiki/Functional_programming) is [with Lambdas](https://en.wikipedia.org/wiki/Lambda_calculus) ([value-level](https://en.wikipedia.org/wiki/Function-level_programming))\
[**Function-level Programming**](https://en.wikipedia.org/wiki/Function-level_programming) is [without Lambdas](http://dirkgerrits.com/publications/john-backus.pdf#section.8) ([function-level](https://en.wikipedia.org/wiki/Function-level_programming))\
**Function-level Algebra:** With the renunciation of lambda variables, an algebra and its rules emerge (if not? --> tell us [Issues](https://github.com/function-level/function-level.github.io/issues))

![John-Backus](https://raw.githubusercontent.com/function-level/function-level.github.io/main/data/John-Backus.png) \
**"Can programming be liberated from the von Neumann style? \
a functional style and its algebra of programs"**, [Backus-Turing-Award-Lecture](https://dl.acm.org/doi/pdf/10.1145/359576.359579)

### A Collection of Links
- Function Level Programming and the FL Language, [Video](https://archive.org/details/JohnBack1987)
- [FL Language Manual, Parts 1 and 2](https://theory.stanford.edu/~aiken/publications/trs/RJ7100.pdf)
- Wikipedia: [Function-level Programming](https://en.wikipedia.org/wiki/Function-level_programming)
- Dirk Gerrits: [John Backus](http://dirkgerrits.com/publications/john-backus.pdf#section.10)
- dl.acm.org: [Programming Language Semantics and Closed Applicative Languages](https://dl.acm.org/doi/pdf/10.1145/512927.512934)
- dl.acm.org: [Function Level Programs as Mathematical Objects](https://dl.acm.org/doi/pdf/10.1145/800223.806757)
- SpringerLink: [From function level semantics to program transformation and optimization](https://link.springer.com/content/pdf/10.1007/3-540-15198-2_5.pdf?pdf=inline%20link)
- MacLennan/POPL [Chapter 10](http://web.eecs.utk.edu/~bmaclenn/POPL/ch10.pdf) page 359ff
- MacLennan/Functional Programming: Practice and Theory, [borrow eBook](https://archive.org/details/functionalprogra0000macl), Page 221ff: Higher-Order Functions
- Instance variables, a [way out](https://esolangs.org/wiki/FP_trivia) of the variable abstinence --> "Why didn't the ALGOL Committee" in EWD692
- Dijkstra EWD692: [A review of the 1977 Turing Award Lecture by John Backus](https://www.cs.utexas.edu/users/EWD/transcriptions/EWD06xx/EWD692.html)
- [FP](http://www.math.bas.bg/~bantchev/place/fp.html) (english)
- [Introduction to FL and PLaSM](https://media.johnwiley.com.au/product_data/excerpt/29/04718994/0471899429.pdf)
- [The FL Project: Design of a Functional Language](http://theory.stanford.edu/~aiken/publications/trs/FLProject.pdf)

### Last Years of John Backus
Oral History of John Backus
- Interview, [Text](https://archive.computerhistory.org/resources/access/text/2013/05/102657970-05-01-acc.pdf)
- Interview, [Video](https://www.youtube.com/watch?v=dDsWTyLEgbk)

**Reactions on Grady Boochs instrumentalization of Backus statement**
- [Reddit](https://www.reddit.com/r/programming/comments/8zgq3j/i_interviewed_john_backus_shortly_before_his/)
- [Twitter](https://twitter.com/Grady_Booch/status/1016041695501139968)

### Advantages and Disadvantages of Pointfree Style
- LtU: [Advantages of Pointfree](http://lambda-the-ultimate.org/node/3233)
- stack**overflow**: [Advantages and Disadvantages of Pointfree Style](https://stackoverflow.com/questions/5671271/what-are-advantages-and-disadvantages-of-point-free-style-in-functional-progra)
- [Ultra Structured Programming](https://backus-fp.github.io/lambda-vs-function-level/)

### Algebraic Programming
- [Algebraic Identities for Program Calculation](https://www.researchgate.net/profile/Richard-Bird-2/publication/220458641_Algebraic_Identities_for_Program_Calculation/links/57c7f67108ae28c01d4ff3a1/Algebraic-Identities-for-Program-Calculation.pdf)
- [Point-Free Program Calculation](http://repositorium.sdum.uminho.pt/bitstream/1822/2869/1/tese.pdf)
- [Algebra of Programming](https://ks3-cn-beijing.ksyun.com/attachment/0ed5f41c9bf19f39a9fb3fcf6ddd8bd8)
- [Pearls of Functional Algorithm Design](https://doc.lagout.org/programmation/Functional%20Programming/Pearls%20of%20Functional%20Algorithm%20Design.pdf)
- [Bird-Meertens Formalism](https://en.wikipedia.org/wiki/Bird%E2%80%93Meertens_formalism)

### Concatenative languages
- [Factor](https://factorcode.org/)
- [OForth](http://www.oforth.com/)
- [Joy](https://en.wikipedia.org/wiki/Joy_(programming_language))
- [Kitten](https://kittenlang.org/)
- [PostScript](https://en.wikipedia.org/wiki/PostScript)
- [Why Concatenative Programming Matters by Jon Purdy](http://evincarofautumn.blogspot.com/2012/02/why-concatenative-programming-matters.html)
- Wiki for [concatenative.org](https://concatenative.org/wiki/view/Front%20Page)

### Code Golf languages (many of which are stack-based and/or point-free)
- [Code Golf Stack Exchange](https://codegolf.stackexchange.com/)
- [Husk](https://github.com/barbuz/Husk)
- [Jelly](https://github.com/DennisMitchell/jellylanguage)

### Array Languages (which support point-free style)
- [Notation as a Tool of Thought](https://www.eecg.utoronto.ca/~jzhu/csc326/readings/iverson.pdf) -- must read!
- [Stages of Denial by John Earnest](http://nsl.com/papers/denial.html)
- [APL](https://www.dyalog.com/)
- [J](https://www.jsoftware.com/#/)
- [K](https://github.com/JohnEarnest/ok)
- [Q](https://code.kx.com/q/learn/tour/)

### Libraries that support point-free style
- [Ramda.js](https://ramdajs.com/)
- [Ramda Python port](https://pypi.org/project/ramda/)

### Some Implementations to FP, FL and Pointfree
- Interpreter in Java: [INTERACTIVE FP](https://www.cse.sc.edu/~bays/group9/index1.html) and [Help](https://www.cse.sc.edu/~bays/group9/help.html)
- [FP-Interpreter-in-Lisp](https://code.google.com/archive/p/fp-interpreter-in-lisp/) and in [GitHub](https://github.com/jfacorro/fp-interpreter-in-lisp)
- Compiler to C: [Furry Paws](https://web.archive.org/web/20180106183517/http://www.call-with-current-continuation.org/fp/) and in [BitBucket](https://bitbucket.org/bunny351/furry-paws/src/master/)
- to FL: [PLaSM](http://www.dia.uniroma3.it/~paoluzzi/plasm/download/) and [Docs](http://www.dia.uniroma3.it/~paoluzzi/plasm/docs/) and Book: [Introduction to FL and PLaSM](https://media.johnwiley.com.au/product_data/excerpt/29/04718994/0471899429.pdf)
- [FP-Interpreter](https://pointfree-interpreter.github.io/) in Delphi and in Lazarus
- Pointfrip [Calculator](https://github.com/pointfrip/calculator) für Android, (German help)
- Executable implementation of [Joy](https://github.com/Wodan58/Joy) and subset of Joy for graphics programming [mjoy](https://github.com/fpstefan/mjoy)

### Some Link Collections
- [Link-Sammlung-1](https://flinks-72c22.firebaseapp.com/)
- [Link-Collection-2](https://medium.com/@christoph.sachse/the-fp-and-fl-programming-languages-assorted-resources-linkdump-e310914221a9)


\
Picture: (cc-by-sa-4.0) Wikipedia
