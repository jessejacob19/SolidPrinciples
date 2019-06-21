# SolidPrinciples
solid principles of c#


Things you don't want to happen in code:
- code can become rigid and fragile
- code becoes difficult to reuse
- code becomes difficult to modify/extend
- changes to classes causes problems in other classes
- change introduces many bugs that are difficult to track down

Single Responsibility Principal:
- There should never be more than one reason for a class to change
- A class should only have one job to perform
- Chance of any one class containing bugs is lower, therefore change is less fragile
- Classes become smaller and cleaner
- Simpler to understand and maintain

Open / Closed Principle:
- Open to Extension
- Closed for Modification
- Use interfaces
- Limits the need to change code once it has been tested and debugged
- Reduces risks of introducing new bugs
- Reduced coupling

Liskov Substitution Principal:
- Use Derived classes without knowing it
- Subclasses must operate in the same manner as their base class
