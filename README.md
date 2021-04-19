Phase 4 Contexts
---
We accidentally left the scope tests `TeamQuiz` in for `team_quiz_test.rb` and this is now causing some confusion.  Let me answer some questions that have come up:

1. You can use these for your own tests if you want, but you need to transfer these scope tests to `team_quiz_scope_test.rb`.  We also suggest you remove these six tests from `team_quiz_test.rb`.  But if you want to write your own set of tests, that is totally fine too (just remove ours).

2. This has raised a lot of questions, so in this repo we are providing you _all the contexts_ that we used in our solution. **You are NOT required to use these contexts** -- that is entirely your choice.  You can use them as is, or learn from them to inform your own contexts, or just ignore them altogether -- again, it is entirely your choice.  Our goal in providing them now is to make things easier and reduce confusion.

3. If you are trying to understand our naming convention for team_quizzes (similar to other contexts), it is pretty clear. Take the object `@acac_s1_e1_s1_r1` for example:

  - `@acac_s1` is for ACAC's senior team 1;
  - `..._e1` is for event 1;
  - `..._s1` is for room 'senior 1';
  - `..._r1` is for round 1.

4. There have been some questions about the `create_more_...` methods in some of earlier contexts for Phase 3 that were included in the starter code.  These methods were only used for Cucumber testing and not needed or used in any of the unit testing we are doing in this phase.  Feel free to ignore these methods.

Again, we want to stress that these are provided to help reduce confusion and answer some questions you have, but you are not required to use them -- the choice of how to use this is up to you.

Qapla'

Prof. H & Prof. GS