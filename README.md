# Java_All


## Notes for SOLID Software Design Principles in Java
By Dan Geabunea

### Contents 

*Problems when no SOLID principles used 

*Technical Debt 

*Benefits of writing SOLID Code 

*Description of the Sample application 




### It is not enough for code to Work - Robert C Martin \n

If code is unmaintainable then fixing bugs , or writing new code is difficult. 
Therefore SOLID Principles comes in picture.

### Code Fragility - Tendency of the software to break in many places every time it is changed.
### Code Rigidity -  Tendency of software to be difficult to change,even in simple ways. Every change causes a cascade of subsequent changes in dependent modules.

### High Technical Debt - Fragility and Rigidity are symptoms of this.
### Technical Debt - Silent Killer
                 The cost of prioritising fast delivery over code quality for long periods of time.  
                >Choice to make 
                >1) FAST Delivery 
                    Easiest fix/Fast 
                    Poor Written Code 
                >2) Code quality 
                    Takes more time
                    Adds a bit of complexity
                    Maintainable 

Sometimes you can choose 1) but  if always chosen Project/Product becomes difficult to evolve.

### Cost of change 
It should be kept minimum with time .\nFor high Tech debt Projects Cost of change goes on increasing with time .\nIt grows so much that becomes not manageable. 

### Customer Responsiveness-
At beginning we are able to response to customers fast but for high technical debt Projects this increases with time.  

### Technical Debt Facts -
No matter how good team is , tech debt accumulate over time.\n\nLeft uncontrolled , it will kill project 
Key is to keep under control.

### Solution - 
Write Code -> Pay debt ( refactor ) -> Write more Code  -> Pay debt ( refactor )

### SOLID Principles - 
1) single responsibility principle, 
2) open closed principle, 
3) Liskov substitution principle, 
4) interface segregation principle, 
5) dependency inversion principle. 

### Benefits of SOLID CODE -
It is easier to understand and reason about. Changes are faster and have a minimal risk level. \nThe code is highly maintainable over long periods of time. \nAnd it is also cost-effective

### Other ways to keep architecture clean - 
1) Constant refactoring 
2) Design Patterns 
3) Unit testing ( TDD)


