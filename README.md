# CS-340

When writing sustainable code it is important to remember that somethings will not stay consistant such as login information, queries, current program versions, or other such examples. In these cases it is best to plan for the future and make the need for future changes less frequent and easier by keeping them separate as much as possible. An example of this is not hardcoding in login information or specific parameters when possible. By making these variables, future users will have an easier time finding spots that need to be changed. By using an external python file I found it easier that working in Jupyter Notebook because it was familiar and faster. In the future it the CRUD file could do more such as an initial filter of the data that is being passed back into the application so that for example Cats are not included in the initial data table. The CRUD file can also work with other similar projects with some editing to the database connection part of the code.

I try to approach problems as a computer scientist by first understanding the problem. Normally the compiler or common sense will give me a starting point through error codes or what I can see. If the problem is not obvious then I will need to find the problem, this process can either be simple or complex depending on the problem. As an example I will use two problems I encountered while completing Project 2. The first problem is that I was consistantly getting a hanging load when I tried to run the dashboard application, I was not getting any error codes or other tips what would help me find where the problem was occuring so I needed to go step by step through my code to find where the problem was. In this instance the problem was coming from the way that json is formatted that I did not take into account. The other problem I will talk able is one that I did not find a solution for. When running the dashboard application on Windows I found that the interactive mapp would not load onto the output with the rest of the dashboard components. After research and testing I found a few community forum posts describing similar issues. At this point I came to a logical conclusion that I had found a bug in the dash_leaflet package and made note of it in my write-up. 
