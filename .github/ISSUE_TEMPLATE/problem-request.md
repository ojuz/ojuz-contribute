---
name: Problem request
about: Suggest new problems to be uploaded
title: PROB
labels: ''
assignees: ''

---

Please try to answer all the questions. You can request several problems at once, but in that case, the request should contain all the necessary information.

**Where does the problem come from?**
If the problem is from a contest, please give me the name of the competition. If the authors explicitly disallow uploading their tasks (e.g., USACO), we will reject the request.

**How to get test data?**
Write the link to the test data. Preferably in Polygon package format, or in `${name}.in` / `${name}.out` format. Give me the naming rules of each test.

**If the problem contain subtasks, how to divide each input into subtasks?**
I should be able to do the job **only with the filename**. Also, beware that some tests can be in multiple subtasks, you should tell me about that too.
- Good description: "Test 1-3 goes to subtask 1; test 4-8 goes to subtask 2, ..." 
- Bad description: "Tests with N <= 100 goes to subtask 1; Tests with queries of type 1 goes to subtask 2; ..."

**If the problem requires checker, how to get checker?**
Checker should be based on [testlib.h](https://github.com/MikeMirzayanov/testlib). 
If the tasks are in Polygon format, the checker might be in the Polygon package.

**If the problem is interactive, how to get interactor?**
Interactor should be based on [testlib.h](https://github.com/MikeMirzayanov/testlib), too. But if the proposing task a library-based problem (as in recent IOIs), you can give me the library instead.

**If the problem requires library code, how to get that library code?**
Does the user download some code written by problem authors and write a function to solve the problem (as in recent IOIs)? 
If yes, how to get that library? There should be a "public" one that users can download and a "secret" one that the server uses to judge the solution.
Also, due to technical difficulties, the "secret" library MUST read from standard input and print to standard output.

**Additional context**
Add any other context or screenshots about the problem request here.
