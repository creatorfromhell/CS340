# Project 2 Reflection

## How do you write programs that are maintainable, readable, and adaptable?  
*Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?*

Writing programs that are maintainable, readable, and adaptable requires a focus on clear structure, meaningful naming conventions, and modular design. In my work on the CRUD Python module for Project One, I implemented these principles by creating a dedicated AnimalShelter class that encapsulates all database interactions. Each CRUD operation—Create, Read, Update, Delete—was defined as a distinct method, making the code easy to follow and modify if necessary. When connecting the dashboard widgets to the database in Project Two, this separation of concerns proved highly advantageous. I could reuse the same well-tested methods without duplicating code or introducing inconsistencies. It also meant that any changes to how data was accessed or stored only required updates within the AnimalShelter class, rather than across the entire project.

In the future, this CRUD module could be repurposed for any application that needs to interface with a MongoDB collection. For example, if a different project involved managing an inventory or tracking client interactions, I could adapt the AnimalShelter class with minimal changes, simply by adjusting the connection parameters and collection references. Its structure makes it flexible for various data-driven applications beyond animal shelter records.

---

## How do you approach a problem as a computer scientist?  
*Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?*

When approaching a problem as a computer scientist, I begin by carefully analyzing the requirements and breaking down the problem into smaller, manageable components. In the case of Grazioso Salvare’s database and dashboard requests, I started by mapping out exactly which database operations were needed and which user interactions had to be supported on the front end. Compared to previous assignments in other courses, this project demanded a more client-centered approach, where understanding user needs was just as important as writing code. In earlier projects, the focus was often purely technical; here, I had to think about usability and long-term maintainability. Going forward, I would continue using a combination of early requirement gathering, modular development, and thorough testing to create databases tailored to client needs, ensuring flexibility for future enhancements.

---

## What do computer scientists do, and why does it matter?  
*How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?*

Computer scientists solve problems by designing logical solutions, often using software, that meet real-world needs. This matters because technology increasingly drives decision-making, efficiency, and communication in almost every industry. Through this project, my work helped Grazioso Salvare by streamlining their ability to access, update, and manage animal records. An efficient CRUD module and dashboard mean faster processing of adoptions and better data tracking, ultimately allowing the company to save more animals and operate more effectively. In a broader sense, projects like this show how thoughtful software design directly supports organizational goals and mission success.
