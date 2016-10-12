## Questions

1. What is the difference between new and create for a model?
	Create instantiates the new object, validates it, and saves it to the database, but new only creates the local object and doesn't attempt to validate/save it to the database. 
2. What command combined with new will emulate the same behavior as create?
	save 
	
3. What is the default integer column that exists on every table but we did NOT define?
	id 

4. What single line of ruby code can insert a cat with the name "Kira" in the database?
	Cat.create(:name=>'kira')
5. How did you like this homework in comparison with the previous homeworks?
	Links to documentation were helpful, but more details in the walkthrough about setting up the view woul have been helpful. 