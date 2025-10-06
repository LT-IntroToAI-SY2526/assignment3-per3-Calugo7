# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
The key programming concepts that I learned while completing this assignmentare the action functions and how a database works. I am completly new to this coding language so the slides and the set examples that were provided were really helpful.

2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
The overall movie chatbot system works by listing an element of a movie (director, year, etc) and the system brings up all of the movies that would fit the given criteria. The user gives they specific needs, the action functions go through to find what was given and using what was given to fetch the movies that fit the criteria. Depending what was wanted from the user, it will fetch different elements of a movie.

3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
Some real-world applications where this type of pattern-matching chatbot system could be useful is in a library database. When a book needs to be found and to be checked if it is available, they can use this exact system to find the writer or the title of the book. This will be extremely helpful for the librarians and other workers who work with the organization of books.