The task system isn't good.
Tasks are abstract and 'static' despite their complex structures being dependant on the execution environment.
This lead to a weird 'mutable' caching system.

New system will be:
- Methods: the abstract static objects
- Tasks: part of the pipeline, copied and instanced from the method.