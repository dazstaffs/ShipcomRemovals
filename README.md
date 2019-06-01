# ShipcomRemovals
Another technical test to calculate how many boxes can fit inside a container. Here is the brief:

This exercise has two parts – a development task followed by some enhancements. The development task needs to be delivered as code. Parts do not need to be complete (although it would be nice and would help to be able to execute the solution!). The assessment will take into consideration design principles and it needs to be completed using C# and .Net. It can be a console application. If there are questions you may ask but it is permissible to make reasonable assumptions based on information given here. Candidates are expected to set aside between 2 to 3 hours for this exercise.
Shipcom Removals
A shipping agency Shipcom requires a software to work out container sizes and the number of containers required for removals. There are two standard box sizes that are used for packaging and containers can fit a certain number of these.
There are two container sizes the shipping company uses. Contents are placed in standard size boxes and there are 3 box sizes to select from based on the contents.

Container sizes(m):
-	Standard: 5w x 10d x 2h
-	Large: 5w x 12d x 2h

Box sizes(m):
-	Small: 0.6w x 0.6d x 0.5h
-	Standard: 1w x 1d x 1h
-	Large: 1.2w x 1.2d x 1h

## Task
Shipcom require software that will work out how many containers to use given a number of small, standard and large boxes. The algorithm will determine how to optimally fill up containers such that the number of containers required is minimal. It is the responsibility of the customer to determine how many of each box size they require for their contents.
Assumptions:
-	Boxes can only be placed upright in containers. There is no requirement to turn boxes around to fit optimally (and it helps avoid spills).
-	Boxes are not stacked one on top of the other
-	It is permissible (unavoidable) to have some space in containers that cannot be filled
-	Boxes and containers are rigid – they don’t bend or flex!
-	Ignore wall thickness of container or boxes
-	Assume no gap/space between boxes or the box and container when fitting into a container
-	You are free to make elements of the software configurable or not
 
# Enhancement
Shipcom have a set charge to ship a container and they sell boxes to customers. In addition to the above functionality, they require the software to be enhanced so that it works out the number of boxes and containers such that the cost to the customer is minimised. The customer requests space in cubic meters - e.g. 10 cubic meters. The costs are as follows:

Container:
-	Standard: £250
-	Large: £350

Box:
-	Small: £5
-	Standard: £9
-	Large: £10

## Task
Prepare a quote to show:
1.	The parts of the software that need modifying
2.	The nature of the modifications
3.	Effort in hours to make these modifications. The candidate is expected to demonstrate that the original design is flexible enough to allow for extensions and enhancements without a major overhaul.

Further questions you need to be prepared to answer if selected for next stage of selection process:
1.	What alterations would the software need in order to make the box sizes user configurable? Could this have been achieved upfront and if so how?
2.	What alterations would the software need to make the prices user configurable? Could this have been achieved upfront and if so how?
3.	What if Shipcom want to plug in a different calculation algorithm for working out boxes or containers or both? How would you accommodate this? 
4.	If boxes are sturdy enough to be stacked one on top of the other, how easy would it be to extend the software to allow for stacking?

