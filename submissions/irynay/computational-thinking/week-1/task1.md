## Task 1
### Problem:
 As problem example i want take a furniture factory. So as factory can produce different furniture, owner must solve where and how much he must buy the materials, where i can have a best place for selling his furniture and how many workers he need. 

### Decomposition: 
 1. Plan how many furniture to make this month
 2. Calculate how many materials need for this
 3. Shop for the materials
 4. Make workpieces
 5. Produce products
 6. Delivery to the store

### Pattern recognition:
 Here is an example pattern of chair creating. Using this pattern, we can create chairs of different shapes or colors.
 1. Create a chair legs
 2. Create a chair cover
 3. Create a chair back
 4. Attach everything with nails
 5.  Painting

### Data representation and abstraction:
 1. product height
 2. product width
 3. color
 4. count
 5. costs for material, work
 
 Not including data: 
 1. how much material is left
 2. paint or material number

### Algorithm
 1. get all orders
 2. buy materials
 3. create a furniture
 4. if it doesn't meet the requirements, repeat step 3. Else, create next furniture
 5. if it meet the requirements, then make delivery


## Task 2

1. I think, that the primary sub-problems that need to be solved is
string irerate  and compare each word with thesaurus.

2. Every time we need repeat two things: 
  - iterate string
  - compare word with collection of synonyms.

3. I think, that thesaurus would be represented as collection of synonyms and corpus must be converted in array.

4. Algorithm:
  a) Initialize the variable counte = 0.
  b) Create an array of words from corpus.
  c) Take firs word and compare it with thesaurus.
  d) If thesaurus includes this word then increase counter.
  e) If there is no much, go to the next word.
  f) If the whole array has passed, return counter value.


5. A problem similar to this occurs when searching for a word on a page / document.
