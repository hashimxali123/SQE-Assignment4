# Modularity Requirments of our FLEX:

## 1- Decomposability of modules
To decompose anything simply is to reduce it to smaller parts. Modular decomposability is the ability to systematically divide a problem into its various subproblems. It can be challenging to address a huge problem; however, deconstruction aids in lowering the complexity of the issue and creates distinct sub-problems. This assists in implementing the fundamental concept of modularity.

As far as our Flex Academic management system is concerned, we will add up the modularity by setting up  our github and dividing the modules and 
it's source code in an efficient manner, as done by other open-source platforms like `Dolibar`.

<img width="960" alt="Screenshot_20221209_064822" src="https://user-images.githubusercontent.com/105812482/206716685-bc2065a9-c590-4e0c-99b5-0839f72e0985.png">

Now, if it comes to the modularity of Dolibar, in the scripts, it is arranged in modular structure as evident from the above image, we
will also be achieving this thing in our `FLEX`.

## Requirments:
###    1.  System shall have modular structure.   
####   1.1 System shall have only 1 source file in each folder.
###    2.  System shall have scripts managed in different folders.
####   2.1 System modules should be 90% independent.
####   2.2 System should have separate independent runnable module of header. 
####   2.3 System should have separate independent runnable module of footer.


## 2- Modular Comprehensibility
Simply, the word "understandability" refers to the capacity for comprehension. Modular understandability refers to making each module simpler for the user to grasp so that software development and customization are incredibly simple. Because of their complexity and substantial size, process models can occasionally be difficult to comprehend. It is simpler to understand the problem effectively and without any problems when using modularity understandability.

Now, if it comes to the Modular strcutre of our Flex, we will be managing it as it Dolibar is managing. They are actually having a separte module
of scripts and in which all the other modules like accountacy, bank, company etc are there. User can easily nagivate to their respective module.
If it comes to the code, each module folder contains it's own code, in `PHP` if it is the case of `Dolibar`.


<img width="960" alt="Screenshot_20221209_065720" src="https://user-images.githubusercontent.com/105812482/206718437-254a388d-bb52-43b4-9b89-f1348148aef7.png">

When suppose, one opens the module of `Accountancy`, there is only one file of PHP, corresponding to that, which is really good and 
convenient for user to understand the stuff going around, and it is also not too complex with respect to user.


## Requirments:
###    1.  System shall have proper naming conventions.   
####   1.1 System shall have all the modules folders named with a word.
###    2.  System shall a code with proper readability.
####   2.1 System should have code with proper naming conventions.
####   2.2 System should have code with proper commenting.



## 3- Modular Security
To safeguard something simply is to keep it safe from dangers, to guard against unsavoury methods or damage. Modular protection refers to safeguarding other modules against anomalous circumstances that might arise in a certain module while it is running. An error or failure, sometimes known as a run-time error, might represent an anomalous circumstance. These errors have limited aftereffects that are contained within the module.

When it comes to Dolibar, modules must be secured from drastic changes and vulnerability, so Dolibar uses the platform like `Github` to make it 
more secures so that whenever changes are made, owner must know and no one can commit changes to main branch without push request and allowance 
by the admin.

We will also be using the Github platform for open-souce our project, as it is really necessary for the Academic portal to be secured so that
not all persons can access and edit the code or changes the stuff.


## Requirments:
###    1.  System shall have the secure modules.   
####   1.1 System shall have all the modules divided and must have a owner of a module taking care of particular one.
###    2.  System shall have a proper platform for sharing modules.
####   2.1 System should use github to open-source modules.
####   2.2 System should have proper admin of github for reviewing push and pull requests.

