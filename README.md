# Basic Browser JavaScript - Click Counter Calamity

[Cookie Clicker](https://orteil.dashnet.org/cookieclicker/)

Welcome to Module 4, JavaScript Time!

## The Scenario - Welcome to Coo Coo Computing Challengers!
You have been contracted by Coo Coo Computing Challengers to take a concept, Click Counter Calamity, from the drawing board to the browser. Coo Coo Computing Challengers is a company that spends more time creating alliterative puns than actual writing software and they need our help.  They want you to create a webpage that keeps track of user clicks, but they have some strange requirements for _'Clicking Companions'_ and _'Collective Culmination Compounders'_.  They have a list of requirements for us, but they are too busy trying to change the words in their company's mission statement to words that start with the letter 'C' exclusively to give us guidance on how to implement these requirements.

## The Application Requirements
- You must create a website that tracks the amount of times the clicking button has been clicked.
- You must implement a feature called _'Clicking Companions'_.
    - _Clicking Companions_ are bought with clicks from your click total.
    - Each _Clicking Companion_ that is purchased increases the cost of the next _Clicking Companion_.
    - The initial cost should be around 100 clicks.
    - For each _Clicking Companion_ that has been purchased the count of clicks goes up by one every second.  This is a cumulative effect, so having 100 _Clicking Companions_ would result in having 100 clicks automatically added to the total every second.
- You must implement a feature called _'Collective Culmination Compounders'_.
  - _Collective Culmination Compounders_ are bought with clicks from your click total.
  - Each _Collective Culmination Compounder_ that is purchased increases the cost of the next _Collective Culmination Compounder_.
  - The initial cost should be around 10 clicks.
  - The first _Collective Culmination Compounder_ increases the value of a click from `1x` to `1.2x`.
  - Every subsequent _Collective Culmination Compounder_ increases the value of a click by squaring the previous value.  For example, the second _Collective Culmination Compounder_ will increase the value of a click to `1.2x * 1.2x` or `1.44x`.
- You must be able to reset the game state.  This action should reset the game to zero clicks, zero _Clicking Companions_, and zero _Collective Culmination Compounders_.

## Resources

### Jasmine and BDD
- [Jasmine Testing Framework Guide](https://wecancodeit.github.io/java-slides/frontend/js-jasmine-testing/index.html#/)
- [Jasmine Official Documentation](https://jasmine.github.io/)

