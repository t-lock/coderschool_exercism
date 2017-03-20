## Topics: Strings and Arrays

* Arrays: ordered lists of items often used for sequential lists
* Strings: sequences of character data.

### Required tasks

**Strings**

- [x] Read String Questions in Interviews.
  - *Using a few sentences, describe what you've learned:*
  - ummm. interviewing for a programming job is potentially a lot harder than I imagined.
  - functions are judged by their runtime, so in the case of strings, their runtime as a function of how many characters are in the stream.
  - Linear would be considered good because it doesn't grow exponentially as n increases
  - Quadratic is not good because n^2 means the runtime "explodes" as the number of charaters increases.
  - Factorial (!) is the worst (I think)
  - Iteration is the scary part of these functions, so the target will be to find a way to solve the problem with the least amount of iteration. one pass is the goal.
  - String Buffer is a way to use memory to reduce the amount of iteration (but i didnt fully understand all of these code examples)


- [x] Watch [Memoization and Dynamic Programming](https://www.youtube.com/watch?v=P8Xa2BitN3I) video
  - *Using a few sentences, describe what you've learned:*
  - recursion is when you call a function in itself, which can help solve problems like fibonacci that would be really messy if written in an iterative way instead.
  - recursion can case exponential runtime problems if you are calculating the same things multiple times
  - memoization is the technique to store values in memory so that you can use recursion without recalculating the same values over adn over, you just return the memo.
  - Dynamic programming example was comparing two different methods to solve the same problem. *_but I didn't really grasp the 'take home message' of that example_*

- [x] Watch [Anagram Problem Solution](https://www.youtube.com/watch?v=3MwRGPPB4tw) video
  - *Using a few sentences, describe what you've learned:*
  - I learned _exactly_ what an anagram is :)
  - How to think about an anagram problem and break it into parts to see exactly what needs to happen in steps to reach the desired outcome

**Arrays**

- [ ] Read Sorting Algorithms
  - Can you memorize one algorithm? What is it?
- [x] Watch [Introduction to Sorting](https://www.youtube.com/watch?v=pkkFqlG0Hds) video
  - Importance of sorting data not only for user readability, but also time and resources required for computation search etc on data structures (linear vs binary search)
  - There are many more sort algorithms than I realized.
  - They can be classified by
    - runtime complexity
    - space complexity (memory usage)
    - stability (do equal ranked sorted items retain relative position from position prior to sort)
    - Internal vs External (internal means all records are in memory, external they may be on disk)
    - Recursive vs Non-recursive
- [ ] Watch [Merge Sort](https://www.youtube.com/watch?v=KF2j-9iSf4Q) video
  - Using a few sentences, describe what you've learned

**Coding**

- [ ] Set up `exercism` and complete at least 2 exercises using `exercism submit`.

### Optional tasks

- [ ] Do more tasks on exercism
- [ ] Set up an account on Interviewbit.com and start the [Programming course](https://www.interviewbit.com/courses/programming/)
- [ ] Finish [Time Complexity chapter](https://www.interviewbit.com/courses/programming/topics/time-complexity) in Level 1 of Interviewbit
- [ ] Finish [Arrays chapter]((https://www.interviewbit.com/courses/programming/topics/arrays/)) in Level 2 of Interviewbit
- [ ] Finish [Math chapter](https://www.interviewbit.com/courses/programming/topics/math/) in Level 2 of Interviewbit.

Optional
