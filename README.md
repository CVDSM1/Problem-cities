# Problem-cities
problem class

Each year each person in the city decides whether to stay or to leave. With 
probability 50% the person will stay where (s)he lives. With probability 50% 
(s)he will decide to relocate to a city selected at random. In such case the 
person will relocate depending on the result of the following computation: if 
pop1 (resp. pop2) is the population of the city where the person lives (resp. the 
other city), then the person will move if a positive integer number chosen at 
random in the set containing all positive integers not larger than pop1+ pop2, 
comes up larger than the value of pop1

Person current city:



public Class Go2BiggerCity {









Go2BiggerCity();
Go2BiggerCity(Catastrophe,Catastrophe)
computeMoves2a():int
computeMoves2b():int
updateCityA():void
updateCityB():void
updateBothCities():void



public Class Catastrophe {

casualties:int

Catastrophe();
Catastrophe(int,double,int)
updateCitySizeByCata():void
setCasualties(int):void
getCasualties():int

