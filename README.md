# Java-4.26-Task1
task to implement a racing game that has various cars available
The cars are instances of classes which form a class hierarchy. This
hierarchy can be described as follows:
• Each Car has a current speed, a maximum speed and a definded acceleration.
• After instantiation, each car has a current speed of 0.
• Each Car has an acceleration of 10.0.
• Each Car has a method getSpeed to query the current speed.
• Each Car has the method doAccelerate, which modifies the current speed with the acceleration value.
• No Car can accelererate beyond its maximum speed.
• There is no possibility to make an instance of Car.
• There is a DefaultCar which has a maximum speed of 200 and a RocketCar which has a maximum speed of
400.
• In addition, the RocketCar has a boost method which increases the acceleration used in doAccelerate to
20.0. After a single call to boost, the method does not do anything anymore (i.e. boost can be used only
once in the game). The boosted acceleration is used in doAccelerate one single time and then reverts back
to the default acceleration.
All numerical data is stored as variables of type double. With this information, you have to implement the classes
using best object oriented programming practices.
