# Scaling 
We need to scale a system , so that it can handle large amount of request and response them accordingly without failing. 
So, A system is called Scalable when it can handle a large amount of traffic without any failure.

### Horizontal vs Vertical Scaling 
|  Horizontal Scaling 	|   Vertical scaling	|
|---	|---	|
|We need to load balance as there exists more than one resources   	| we don't need load balancing as there is  not many resources are used 	|
|  As there is multiple resources this design is a resillient design	| As there is one resources that was optimized this design is not a resillient design  	|
| It has a proper scalability as there is multiple hardware  	|  There is a limit to scale a system y this technique as every hardware has some limits  	|
| Here, multiple resources are handling the data, so the data can be inconsistent	| here only one resource is handling the data, so the data is consistent here |
|As we need to communicate beetweenn machines this system requires networking which is prone to fail	| As there is only one resource, we don't need network calls a   	|




#### Resources,I got this from :

 - [Vertical and Horizontal Scaling in System Design blog by Spencer](https://medium.com/@spencerwgoodman/vertical-and-horizontal-scaling-in-system-design-718cabb80a1a)
 - [Video by Gaurav Sen](https://youtu.be/xpDnVSmNFX0)
