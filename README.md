# CS340-Client-Server-Development

How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?

I like to separate concerns into their own components. The CRUD python module is a good example because I isolated the operations into a single class and named each method for that operation. For example, project Two didnt need to know how MongoDB worked internally. It called db.read(). It made the code readable and its functionality is clear. This module could be used in the future for any application that needs to query a database. 


How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?

The approach for this project required me to build from the ground up. Breaking each problem into layers I started with the database and CRUD operations. With the data layer built I could then build on top of that having a solid foundation to work with. Previous coursework was often setup as a single script so I can use this build from the ground up approach for future projects. Starting with data modeling before working on interface type code. 



What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

Computer Scientist solve real problems by building systems to make data useful. In the case of my project it meant turning a database into a interactive interface. Without the tool I developed the process for finding information within the database would be very slow and manual. In the long run I think by saving time it can save lives. In this case it was finding qualified rescue animals. 
