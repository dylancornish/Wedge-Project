## Feedback 

Nice work on this project, for the pieces I've seen. You didn't submit a true Task 3; your copy is just a duplicate of Task 2. When you commit the real version of 
Task 3, send me a teams message and we'll get this signed off. 
It's a bit odd to do a reflection like this in a notebook rather than a markdown file. Having said that, I really enjoyed reading what you wrote and "Yes", windows 
file paths are annoying. The big problem is that windows prefers the backslash, which is the escape character in programming languages. On a Mac you'd have
`/Users/name/folder/file.ext` but on a PC you'd need to do something like `C:\\Users\\name\\folder\\file.ext`. 

### Task 1

* Smart to use the load-table-from-file. Most people did a pandas `read_csv` followed by some pandas-gbq, but your approach is more efficient in terms of both memory and code. 
* This looks good. You can't really do it in fewer lines of code. 

### Task 2

* Nice job on this task. 
* It'd be worth thinking through how you'd do this the reproducible way. That'd involve selecting distinct card numbers, pulling them down to python, calling `random.sample` and then building a query that could use them all. Let me know if it's not clear how you'd do that. 


### Task 3

* I just have a second copy of Task 2 in here. 
