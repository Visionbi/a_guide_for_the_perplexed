# Integration tests :

### Do you remember the fundamentals of unit testing ? 
One of them is “isolation”. This is the exact difference between unit tests and integration tests.
Integration tests are when software modules/units are combined and tested as a group.
For example, a unit test for database access code would not connect to a real database, but an integration test would.

Integration tests are written with code exactly like unit tests but they take longer due to the added complexity .
You should have fewer integration tests than unit tests and mainly use them if you need to test two separate systems together, or if a piece of code is too complex to unit test.

Now that you have developed unit tests and integration tests you can use them for **“regression tests”** to verify that the software you developed and tested still performs 
the same way after it was changed.


# System tests and functional tests :
	
In one sentence – “execute the real life scenarios of the software” .  
It is a type of “black box” testing which means that you don’t have to be familiar with the code.
Here are some of the basic principles :
-	System tests are checking whether the software is made according to the customer needs.
-	System tests are done mostly in a staging/pre-production environment .
-	It can be done by a test engineer, QA, PM or someone who cares enough .
-	It will also include performance, security, regulation, localization, maintenance and privacy scenarios.


# Alpha tests and beta tests :

**Alpha Testing {optional}**  is usually done by internal staff – long before the product is even released 
to external testers or customers. 
Answer these questions: Does the product work? Did we build the product in the right way – does it make sense ?
In this phase you’ll test the software from user perspective. You will conduct **experience assurance not a quality assurance**.
Can be done at the end of each sprint or even after a ‘nightly’ build is ready .

**Beta Testing**, also known as “field testing” or UAT [user acceptance tests], takes place in the customer’s environment and involves some extensive testing by a group of customers 
who use the system in their environment.
Answer these questions: how does the product behave in the customer's environment? Do customers like the product?

Alpha and Beta Testing are done before the software is released to all customers.



### Have you ever heard of the term “dogfooding” ?

This is shortest way to say “eating your own dog food” which means using your own product before going public.
Dogfooding is a form of alpha-testing.

**Using your own software, turns out to be a great way to determine not only if you’re building the thing right, 
but also whether you’re building the right thing.**
 




