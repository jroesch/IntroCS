# Computer Science
### Introduction
The other day I overheard my younger brother's conversation about Computer Science with a friend. 
The were dicussing the experince of learning Computer Science in highschool and were feeling that
they lacked a certain amount of conceptual understanding. Not necessarily the fault of the circculum
or their teacher but another example of the failings of our education system at identitfying 
the unique places people get stuck, in combination of teaching specific problem solving heuristics
instead of focusing on developing understandings of the abstractions in the most general sense. 
Like computer science is focused around building and composing abstractions, with generality being
an important trait of abstractions. We should focus on building generic abstract understandings. 
This is an attempt at writing a work that is pitched at the true beginner but intends to divorce
their learning from whatever cirrculum, and instead focus on building knowledge. 

### The Machine
Even though Computer Science can be done without the presence of a computer, look no further then the progenitors of the field. 
They were all Mathmaticians, and Logicians such as Alan Turing, Alonzo Church, and John McCarthy(... more ex). The machine whether abstract 
or concrete is our essential abstraction. 

As someone who is starting an education in Computer Science you most likely use your computer all the time, if you
are a young student you have probably never even known life without a computer, or a life withtout internet. 
Unfortunately modern personal computers are so abstracted away from their core, the actual nature of the machine has been obfuscated. 
Computer Architecture has evolved greatly and hardware nuts will blabber about their new RAM, GPUs, CPUs, Cooling Systems, HDs,
SSDs, Caches, and so on. Again we can apply the fundamental idea of abstraction and remove all this real world complexity. It is similar
to physics where one will use an idealized model of a system to help develop intuition and understanding.

At its core your computer is essentially comprised of some sort of CPU that is able to perform computations,
a memory system that allows you to store and fetch information, and I/O(Input/Ouput) which allows for communication to
the outside world. The processor is the key component, both memory and the I/O system are merely ways to store and fetch the data
that the processor acts  on. The CPU provides the base behavior of the computer implemented physically as circuits. At this level 
the only operations that exist are moving, loading, and storing data, as well as perfomring arithematic.

/* Elaborate on the base nature of of the machine 
   Explain how everything is built upon base primatives
   Abstraction allows us to mask specialization and opitmization, cite memory layout 
   Refrain from too much detail we will revisit the machine as we build back down towards it */
   
 
### Computation 
Many introductory texts focus soley on one Programming Language or environment for a context in which to expose you to the
the subject. Instead I would like to expose you to many because you should see the underlying ideas of what you are doing
as seperate from the what is actually being performed. That is the point of abstraction to seperate the what from the how.
Look at something in the real world, like painting a house for example. I should just be worried about the what(painting & color),
not how you paint brush, roller, spray. 

So you may ask at this point what is Computer Science? what does it mean to Compute something? is this just programming? where does software-engineering fit in? is this a science? what kind of research is done in the field? what are its applications?

You may have answers to some, or all of these questions, that may be why you are reading this, if not don't worry, hopefully all these
questions and more will be answered as you progress through the pages of this book. We will answer the first question now, What is Computer
Science? It is very rarely given a consistent definiton(by lay people and undergrads) because it is internally such a diverse field, people will tell you its very close to math, or more like an engineering discpline or that its about writing programs. At its core, it is about just what it says: understanding and examining computation. So you may then ask what is computation? it can be thought of as calculation or tabulation, evalutation of a formula to produce a hopefully well defined result. You spent most of your time in primary school "math" doing computation,
computing a quanity like the area of a surface, the graph of function, a derivative. The field began out of attempts in Mathematics at examining computable things, and theortical ways of generalizing(!) and abstracting computation. This basis of computing mathematical quanities would eventually become our basis for building computation machines or computers as we know. These formalisms fundamentally describe computable things, 
and we are able to show that if it "can" be computed, we can do it with computers(a physical device mimicing a Turing machine).

-- TODO: Clean Up, make a clear description
  
### Programming Languages 

-- Idea of a Language 
-- Assembly (Descp. Only)
-- Compilation/Intereptation 
-- Levels of Abstraction 
-- As abstraction increases, the machine becomes less visible/important
```haskell
-- Reads very much like Math we describe the variables, and then provide an expression.
let a = 3, b = 4, c = 5 in a^2 + b^2 == c^2 -- result: True, yes this is a right triangle 
```

```cpp
bool is_right(int a, int b, int c) {
  return pow(a, 2) + pow(b, 2) == pow(c, 2);
```

### Object-Orented Programming

### Functional Programming 





