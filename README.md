# Design Patterns

These are design patterns in their simplest form.
Currently the **bold** items are ones I have examples for.

More will come later on.

- abstract_factory - Creates families of related objects.
- adapter - Lets classes work together that don't have compatible interfaces.
- **builder** - Separate construction of complex objects.
- command - Add parameters to clients with different requets, and undoable
  operations.
- composite - Composer objects in a tree structure and handle them individually.
- decorator - Add more responsibility to objects dynamically.
- facade - Makes subsystems easier to use.
- **factory** - Creates a single subclass with that are similar.
- front_controller - Most MVC's and web applications use this pattern.
- iterator - Access elements of an aggregate object without knowing whats under
  the hood. 
- **memento** - No encapsulation, allows you to change an objects internal state
  and restore it.
- **observer** - (aka Publish/Subscribe) One to Many Dependency to notify that
  an object has changed.
- **prototype** - Create new object by cloning from a skeleton of an object.
- proxy - laceholder for another object to acccess it.
- **singleton** - Only allow one instance for an objects lifespan.
- state - Alter an object when it changes state.
- template method - Subclasses can redfine certain steps of without messing up
  the main structure.
- visitor - New operations defined without change classes or elements it
  operates on.

## About the Patterns
This is made to understand patterns as simple as possible. So here are a few things to know:

- Notes are provided in the class.
- Examples are provided at the bottom of the class.
- The name of the pattern is the name of the class.
- Classes not requiring Abstract Classes and Interfaces are not included to keep it simple.
- You would generally:
  - Change the actual name of the class(es).
  - Put classes in separate files.

  --

  (c) 2016 Jesse Boyer | MIT License
