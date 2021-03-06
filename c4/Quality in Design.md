#### Q: The logical (intended) dependency is that observer depends on subject.

- [x] ***True***
- [ ] False

#### Q: Up until now, the great state of Foo has held a lottery to help fund education in the state. The corporation tasked with the drawing of these numbers (the non-televised ones) is XYZ Numerical Tasking.  You are the technical lead for the system which handles the drawings for the state's lotteries. One of your developers, with a mathematical tilt, comes to you with a proposal: change how the random numbers are generated. He suggests that the generation of random numbers could be better. NASA has released a random number generator which has been proven to be better than the one used by the company. He suggests that you make the change. One of your more senior developers notes that using the new generator will require a change. He suggests that the team connect the existing lotto system, as seen in Figure 1, to the new generator (Figure 2) using the Facade pattern. Figure 1 Figure 2 Facade, which seeks to simplify complex processes for a client by providing a API which hides the complicated calls/work needed, doesn't seem to fit.  What pattern does?

- [x] Adapter

#### Q: Within the Custodial Management System, there are are a variety of items that are being watched at any given time. Certain items can receive notifications that a response is needed immediately (rather than just tracking whether the regular upkeep has been done that week/month/etc.). These items may then need one of several possible actions: rapid cleaning, bodily fluid containment and/or removal, addressing traction/slip-danger, urgent repair, etc. Each of these actions fit the same profile (action) but not necessarily the same steps.Which pattern would fit well as a solution to this systems needs?

- [x] Observer

#### Q: Early in our proof-of-concept work on the new game we are building, we effectively hard-coded the game to ask the user what action to take next, for both players. In this case, both users are tied into a single account, so that we can play against ourselves while we build out the game.Now, however, we want to add a new player type to the system, EasyDifficultyBot. While the \"player\" actions fit the same high-level format for both humans and our AI, the details of making it happen vary pretty widely.In order to allow for this change, we want to make use of a pattern that will allow this kind of expansion while minimizing changes to the existing code.What pattern would be best here?

- [x] Strategy

#### Q: Consider the statement \"In the Strategy pattern, the context should hold references to the ConcreteStrategies.\"Under what circumstances would this be true? Select all that apply.

- [x] ***When the context is tasked with deciding which strategy to use***
- [ ] When using a Factory object to create Strategies
- [ ] Under no circumstances should the Context hold references to the ConcreteStrategies
- [ ] When the client is tasked with deciding which strategy to use
- [ ] When the Strategy base class uses a static method to return the correct derived type

#### Q: In the Observer pattern, one difficulty is that the Subject cannot pass an instance of itself to the Observer being updated, due to circular dependencies.

- [ ] True
- [x] ***False***

#### Q: Once a class has been had an Adapter pattern solution applied, it cannot be adapted again.

- [ ] True
- [x] ***False***

#### Q: Factories are no longer useful when you apply the Strategy Pattern to a family of algorithms.

- [ ] True
- [x] ***False***

#### Q: Observer is an implementation of the Dependency Inversion principle.

- [x] ***True***
- [ ] False

#### Q: Strategy Pattern helps maintain the Open/Closed Principle.

- [x] ***True***
- [ ] False

#### Q: Notes: For questions 11-14, the diagram is a standard UML Class Diagram. You can view a larger version by right clicking and selecting \"View image\" (or similar) or by holding on the image and selecting \"Open image in new tab\" (or similar) if you're on mobile. Use up to 3 significant digits (e.g. .5 for 1/2 and .333 for 1/3 are acceptable).For the following class diagram, calculate the Instability value for the Bus class. 

- [x] .714

#### Q: For the following class diagram, calculate the Instability value for the Stop class. Use up to 3 significant digits (e.g. .5 for 1/2 and .333 for 1/3 are acceptable).

- [x] .333

#### Q: For the following class diagram, calculate the Instability value for the PassengerUnloader class. Use up to 3 significant digits (e.g. .5 for 1/2 and .333 for 1/3 are acceptable).

- [x] .5

#### Q: For the following class diagram, calculate the Instability value for the Simulator class. Use up to 3 significant digits (e.g. .5 for 1/2 and .333 for 1/3 are acceptable).

- [x] .8

#### Q: While calculating LCOM4, we ignore constructors and destructors. Constructors and destructors frequently set and clear all variables in the class, making all methods connected through these variables, which increases cohesion artificially.LCOM4 = 1 indicates a cohesive class, which is the \"good\" class.LCOM4 >= 2 indicates a problem. The class should be split into so many smaller classes.LCOM4 = 0 happens when there are no methods in a class. This is also a \"bad\" class.Calculate the value of the LCOM4 measurement for the following code:48495051525354  return *iter;  // resolving the iterator gets you the Stop * from the list} int Route::GenerateNewPassengers() {  // returning number of passengers added by generator  return generator_->GeneratePassengers();}Enter to Rename, Shift+Enter to Preview.monaco-list.list_id_1:focus .monaco-list-row.focused { background-color: #d6ebff; }\n.monaco-list.list_id_1:focus .monaco-list-row.focused:hover { background-color: #d6ebff; }\n.monaco-list.list_id_1:focus .monaco-list-row.selected { background-color: #0069d1; }\n.monaco-list.list_id_1:focus .monaco-list-row.selected:hover { background-color: #0069d1; }\n.monaco-list.list_id_1:focus .monaco-list-row.selected { color: #ffffff; }\n\n\t\t\t\t.monaco-drag-image,\n\t\t\t\t.monaco-list.list_id_1:focus .monaco-list-row.selected.focused { background-color: #0074e8; }\n\t\t\t\n\n\t\t\t\t.monaco-drag-image,\n\t\t\t\t.monaco-list.list_id_1:focus .monaco-list-row.selected.focused { color: #ffffff; }\n\t\t\t\n.monaco-list.list_id_1 .monaco-list-row.focused { background-color:  #d6ebff; }\n.monaco-list.list_id_1 .monaco-list-row.focused:hover { background-color:  #d6ebff; }\n.monaco-list.list_id_1 .monaco-list-row.selected { background-color:  #e4e6f1; }\n.monaco-list.list_id_1 .monaco-list-row.selected:hover { background-color:  #e4e6f1; }\n.monaco-list.list_id_1:not(.drop-target) .monaco-list-row:hover:not(.selected):not(.focused) { background-color:  #f0f0f0; }\n\n\t\t\t\t.monaco-list.list_id_1.drop-target,\n\t\t\t\t.monaco-list.list_id_1 .monaco-list-rows.drop-target,\n\t\t\t\t.monaco-list.list_id_1 .monaco-list-row.drop-target { background-color: #d6ebff !important; color: inherit !important; }\n\t\t\t\n.monaco-list-type-filter { background-color: #efc1ad }\n.monaco-list-type-filter { border: 1px solid rgba(0, 0, 0, 0); }\n.monaco-list-type-filter.no-matches { border: 1px solid #be1100; }\n.monaco-list-type-filter { box-shadow: 1px 1px 1px #a8a8a8; }

- [x] 2

#### Q: Cyclomatic complexity is calculated by the formula:M = E − N + 2P,where E = the number of edges of the graph.N = the number of nodes of the graph.P = the number of connected components.  Calculate the cyclomatic complexity for the following control flow graph:

- [x] 3

#### Q: Cyclomatic complexity is calculated by the formula:M = E − N + 2P,where E = the number of edges of the graph.N = the number of nodes of the graph.P = the number of connected components.  Calculate the cyclomatic complexity for the following control flow graph:

- [x] 4

#### Q: Cyclomatic complexity is calculated by the formula:M = E − N + 2P,where E = the number of edges of the graph.N = the number of nodes of the graph.P = the number of connected components.  Calculate the cyclomatic complexity for the following control flow graph:

- [x] 4