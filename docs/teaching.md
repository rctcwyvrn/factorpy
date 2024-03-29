#Teaching

Why factorpy
---
1. Mimics reality. Younger students might have trouble imagining the unintuitive flow of a computer program, factorpy _might_ be better because of how grounded in reality it is. Things run concurrently, pieces of data are physical things that are moved around, it doesn't execute line by line
2. Can still be used to teach programming. factorpy is very different but it can still be used to teach basic algorithms, like sorting, or basic coding ideas like recursion.
3. Translates well to visual programming


Problems I forsee
---
1. It's too different. ~~factorpy is completely different (to my knowledge anyway) to any other programming language, at least any mainstream one.~~ factorpy belongs to dataflow programming, which has historically been used for education and visualization purposes. Ideally a course using factorpy would be structed such that the students can learn the very basics of coding, and then as they get more familiar with how programs work then they can move towards abstractions. factorpy should just be a jumping off point, since it _hopefully_ will be able to be modified to mimic imperative and functional programming.

A sample course outline
---
1. Introduction to factorpy and how students should think about their code (that it's just factories with ins and outs)
2. Basic syntax + a list of the built-in functions.
3. Spend some time with toy problems that can be solved with clever combinations of built-in functions
4. Introduce user defined factories
5. Introduce students to ideas of using encapsulation to reduce repetition and using recursion to solve problems of arbitrary length
6. Tell students that programming with this mindset is called the functional programming paradigm
7. Introduce let syntax
8. Same idea, to introduce students to imperative programming styles. I'm not sure how well this will work however, so maybe this part could be shifted to be in python
9. Move on to a different language. Maybe racket for the functional minded, python for the imperative minded?