# Monolith 
When all the workings of a system is built into one service , this type of Architecture is called monolith architecture. Here only one codebase handle it all.


Structure: 
  

### Advantages
 - As everything lives in a single system, monolith architecture is simpler for deploying and testing.
 - As there is no external dependency and whole system is  based on single programming language/ framework, It decreases the probaboloty of crosss cutting.

### DisAdvantages
 - As full application relies upon only one codebase, it can be a lot more harder for maintainence
 - Limited reuse
 - Scaling can be challenging (Horizontal specially)
 - CI/CD can not be implemented
 - Have to update whole application even for a small bug fix.
 - As whole service is built upon onne framework, Dev's can miss many tools from that particular framework
 - Agility is not effortless
