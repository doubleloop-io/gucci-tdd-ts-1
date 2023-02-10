## Description
We are developing an editor and one of the features is to show a list of recently opened files. Your task is to write a software component in TDD.

The features are: 
- We need to be able to add stuff to it. 
- We need a way to access the elements so that a UI component can render them
- Elements retrieved are in a LIFO order
- If I add the same element to the list it's moved to the top 
- The number of elements is capped (we think 10 is enough).

### TODO (aka test list)
- What's the first test?
