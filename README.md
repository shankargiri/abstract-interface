Very simple example of Abstract&Interface. 

########################

1.) User.php is an abstract class with two methods defined. 

########################


2.) Admin.php and Member.php are two classes that extends User.php abstract class. [ You should use extends when you need to user abstract class]

########################


3.) Admin.php and Member.php both have extended abstract class named User.php, extended the methods named userAge() and userAddress() and both have further 
defined the extended methods as per the requirements.

########################


4.)UserInterface.php is an interface and it has been implemented in Member.php class using implements keyword. 

########################


5.)Any class that implements an interface has to define methods declared in that interface. [ Two methods declared in UserInterface.php and defined in Member.php are : getUserId() and getUserName() ].