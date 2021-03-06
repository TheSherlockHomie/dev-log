# dev-log

_My dev log documenting what I do related to software development and computer science._

## Log

---

### August 14, 2020, Friday

**Progress:**

-   Participated in [Educational Codeforces Round 93 (Div 2)](https://codeforces.com/contests/1398). Was able to solve only one question :(

**Thoughts:**

-   Taking it a bit slow after the completion of my #100DaysOfCode.
-   Still think that I _could_ have solved atleast one more question if I had thought hard enough.

---

### August 22, 2020, Saturday

**Progress:**

-   Learned about some standard dynamic programming concepts.

**Thoughts:**

-   Currently quite busy teaching a workshop, yet do need to find more time for programming.

---

### August 23, 2020, Sunday

**Progress:**

-   Participated in [Google Kickstart Round E](https://codingcompetitions.withgoogle.com/kickstart/round/000000000019ff47)
-   Solved the first question.
-   Almost solved the second question. However, in competitive programming, _almost_ doesn't count.

**What I learned:**

-   Constructive Algorithms
-   How to approach constructive algorithm questions.

**Thoughts:**

-   It was an okay round.

---

### August 24, 2020, Monday

**Progress:**

-   Revised Graphs (and taught him some concepts) with Trexxx27

**What I learned:**

-   Apart from revision, learned applications of graph traversal
-   Checking if bipartite using DFS
-   Finding shortest path between two nodes in unweighted graph using BFS
-   Checking connectivity
-   Finding cycles

---

### August 25, 2020, Tuesday

**Progress:**

-   Participated in [Educational Codeforces Round 94 (Div. 2)](https://codeforces.com/contest/1400).
-   Was able to solve only one question during the contest, however, as soon as it was over(🤦‍♂️), solved another question by myself!

**What I learned:**

-   You can run a greedy solution iteratively changing the starting variable between runs and find the best answer among them. (I get that this sounds confusing)

**Thoughts:**

-   Great to have friends who participate in contests with you. It is pretty great to be able to discuss the solutions afterward. [(TREXXX27)](https://github.com/TREXXX27)

---

### August 26, 2020, Wednesday

**Progress:**

-   Revised graphs algorithms (and learned new stuff) with TREXXX27

**What I learned:**

-   Revised shortest path algorithms like Bellman-Ford and Dijkstra
-   Learnt Floyd-Warshall shortest path algorithm
-   Dijkstra has a time complexity of O(e + n log n) (the log n comes from the priority queue)
-   Dijkstra cannot work with negative edges
-   Bellman-Ford can be used to detect negative cycles

**Thoughts:**

-   Floyd-Warshall vs Dijkstra is an interesting comparison. One takes O(n<sup>3</sup>) to find distances between all nodes with each other, the other takes O(e + n log n), but finds shortest distance between only two nodes.

---

### August 27, 2020, Thursday

**Progress:**

-   Learned about Iterative DFS
-   Solved [New Year Transportation](https://codeforces.com/problemset/problem/500/A)
-   Solved [Two Buttons](https://codeforces.com/problemset/problem/520/B) using BFS

**What I learned:**

-   Solved a couple of problems on graph traversal
-   Can do iterative DFS using stacks.
-   We can use a stack data structure in memory instead of the recursion (i.e. fuction call stack) if we want to save up on memory.
-   Some recurrent relation questions can sometimes be solved using BFS?!

**Thoughts:**

-   Filtering by topics on CodeForces is useful.

---

### August 28, 2020, Friday

**Progress:**

-   Participated in [Newton's Coding Challenge August 2020](https://my.newtonschool.co/course/06i3zj8m8o/timeline/)
-   Solved 3 out of 6 questions. The first three were easy, while the last three had an extreme spike in difficulty.

**What I learned:**

-   Sum of all Manhattan Distance can be broken down into linear time using DP as: `curr_sum = prev_sum + (number of previous points)*(manhattan distance between current and last point)`

**Thoughts:**

-   The problems for this contest were not exactly very well defined, nor were the constraints. It was weird seeing not all test cases pass, only for them to get accepted by switching out ints to long longs (even if ints could definitely hold the values, according to the constraints).
-   Only participated in this contest because it was forwarded by the Training & Placement Cell of my college.

### August 30, 2020, Sunday

**Progress:**

-   Participated in [Codeforces Round #666 (Div. 2)](https://codeforces.com/contest/1397)
-   Was able to solve only one question, again :(
-   However, after the contest, TREXXX27 came up with a solution for another problem and I ended up solving that question.

**What I learned:**

-   Sometimes brute-force with a few well places break statements can solve the question under the time limit.

**Thoughts:**

-   Seems like I am stuck in a plateu. Really need to level up.

---

Took a break from logging. Definitely did stuff regarding programming, even managed to secure an interview and get a job, just did not log it.

---

### January 2, 2021, Saturday

**Progress:**

-   Mostly watched videos about CRUD apps using nodejs/express and mongodb
-   Implementing the same using docker

**What I learned:**

-   Interacting with a local database from node
-   MVC design pattern
-   View engines
-   Static vs server side rendering
-   docker compose for a CRUD app

**Thoughts:**

-   Back to logging after a long, long time!
-   Happy new year everyone

---

### January 3, 2021, Sunday

**Progress:**

-   Back to learning typescript! The [Net Ninja TypeScript Tutorial](https://www.youtube.com/watch?v=hcuKd-Q_tP8&list=PL4cUxeGkcC9gUgr39Q_yD6v-bSyMwKPUI&index=11&t=7s) is absolutely great
-   How to renew expired gpg keys to sign your git commits

**What I learned:**

-   DOM and event listeners in typescript.
-   a bit about renewing gpg keys and transferring them and theie trust databases across machines.

**Thoughts:**

-   Whew, the gpg thing took a lot of my time, but it was extremely interesting to learn more about this stuff.

---

### January 4, 2021, Monday

**Progress:**

-   Started [Full Stack Open](fullstackopen.com/en)
-   Completed part0
-   Completed part1: Introduction to React

**What I learned:**

-   Single Page Apps (SPAs)
-   Montoring the transmission using chrome network tab
-   Getting started with react
-   what is jsx
-   components
-   props
-   rendering components
-   passing props to components
-   javascript array.reduce() method

**Thoughts:**

-   Wanted to learn react since I don't even know when. Finally started!
-   Initially was going to learn react completely using typescript. Realised it was better to learn react using js only at first.
-   Full Stack Open is pretty great, in my limited experience till now.

---

### January 5, 2021, Tuesday

**Progress:**

-   Solved [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/)
-   Completed part1: javascript of Full Stack Open
-   Completed part1 assignment: courseinfo!
-   Learned a lot about javascript

**What I learned:**

-   That is best practice to use functional programming when using React
-   `arr.concat()` in js
-   `arr.map()`
-   `...` operator in js
-   a lot about functions in js
-   `this` being weird in js
-   classes in js

**Thoughts:**

-   [MDN Web Docs](https://developer.mozilla.org/en-US/) is amazing
-   [A re-introduction to JavaScript (JS tutorial)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) <-- Amazing

---

### January 6, 2021, Wednesday

**Progress:**

-   Solved [136. Single Number](https://leetcode.com/problems/single-number/) - hashtable & xor
-   Solved [202. Happy Number](https://leetcode.com/problems/happy-number/) - hash set & floyd's cycle detection algorithm
-   part1: Component state

**What I learned:**

-   Destructuring in javascript
-   Re-rendering pages in react
-   React hooks
-   Stateful components

**Thoughts:**

-   Getting back into the groove for competetive programming
-   React has been very interseting thus far, very different from what my view of web development has been.
