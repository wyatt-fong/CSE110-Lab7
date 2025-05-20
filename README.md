# CSE 110 - Lab 7

## Members
- Wyatt Fong

## Questions
1. I would fit my automated tests within a GitHub action that runs whenever code is pushed in my Recipe project development pipeline. This is optimal because it ensures code quality throughout development, allows for incremental testing, and helps catch bugs early. Automated testing on every push is a key part of continuous integration, making sure new code does not break existing functionality. 
<br>

2. I would not use end to end testing to check whether is returning the correct output. A more appropriate testing method to test the correctness of a function would be a unit test. This is because E2E testing is typically used for testing an entire application where unit tests individual functions. As we want to test the validity of a specific function, unit tests would work best.
<br>

3. Navigation mode tests how a page loads and behaves as a user navigates to it, including all scripts, resources and dynamic content. It simulates how a real user visits a site from scratch. Snapshot mode captures the current state of a page at a specific moment, without reloading or navigating. It is useful for testing statis content or the state of the page after certain interactions.
<br>

4. 3 things we can do to improvise the CSE 110 shop site based on the Lighthouse results are:
- Properly size images (Save memory)
- Use more legible font sizes
- Include a meta descriptions for search result summary


