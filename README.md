# Functional Programming 101

## Q & A

### Does functional programming (FP) versus object-oriented programming (OOP)?

One often misunderstanding of FP is that it's the opposite of OOP. Even occasionally in a job interview, the interviewer might ask whether you prefer FP or OOP.

FP and OOP is not a choosing one over another relationship, they can get along well together, because FP is to avoid imperative programming and boilerplate code, it's not to against OOP. OOP and FP are two abstraction from different point of views.

OOP thinks from object perspective, so it encapsulates state (data) inside an object, expose and modify state via object instance's methods. Which results in object's data and behavior coupled together in somehow cohesion format. Also, to prevent state from being changed, OOP has to onboard private, protected properties.

FP abstracts the operations and control flow (e.g. for loop, if-else, switch...case, etc.) over the data. FP makes the data and behaviors decoupled. The advantage of the functional programming approach is that it clearly separates the data from the logic (i.e. the functions filter, map, and reduce). Contrast that with the object-oriented code that blends data and functions in the form of objects with methods. Also, because of its immutability, state (data) doesn't need to be hidden from callers.

In practice, FP doesn't mean to overturn OOP, and vice versa, they can get along well for a better result. I think, an OOP class is holding the state or data, functional programming is in charge of the transformation of data. Angular is a good example.

In fact, some FP concepts are implemented in OOP approach, like a specific monad.

### Does function programming have no if...else...?

### Does function programming throw errors?
