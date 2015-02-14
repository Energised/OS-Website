#Real-time Operating System (RTOS)

Where the inputs are processed in a timely manner. This means that the outputs can affect the source of the
inputs. A real life example of this could be balancing a chair with your hand. You are constantly making
corrections to keep the chair steady,

These are characterised by the following four requirements:

* They must support non sequential application programs (this means that they do not follow the START=PROCESS-END
structure)

* They have to deal with a number of events that happen simultaniously abd at unpredictable moments

* They have to carry out processing and produce results within a specified time interval

* Some systems are safety-critical, so they must be fail-safe

Examples of an RTOS include: 

* An airline reservation system. Up to 1000 messages can arrive from any one of the 11,000 to 
12,000 terminals situated all over the world. The response time must be fast - at the moment we have that down to 3
seconds.  

* Controlling machinery that have a limited user interface and no end-user utilities

Some RTOS are programmed so that all oeprations happen in the same amount of time every time it occurs. In a complex
machine, having a part move faster than it should just because system resources are availale can be just as bad as 
having a part not move due to delays.

This above concept is usually described by the phrase:

`the right answer late is wrong`  
