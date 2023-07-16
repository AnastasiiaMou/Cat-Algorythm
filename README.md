<h1>Cats with Hats Puzzle</h1>
<h2>This is a Python solution to the "Cats with Hats" puzzle. The puzzle involves 100 cats standing in a circle, each initially wearing a hat facing the back. A person walks around the circle and performs specific actions that flip the cats' hats. After 100 passes, we want to determine which cats end up with their hats facing front.</h2>

<h3>Solution Explanation</h3> </br>
<!-- </br> -->
<ul>
  <li>The solution uses a Python function called cats_with_hats(num_cats), which takes one argument num_cats, representing the total number of cats.</li>
  <li>Initialize the cats list: We create a list called cats of size num_cats, where each element represents a cat. All cats are initially initialized with their hats facing the back (False).</li>
  <li>Perform the passes: We use two nested for loops. The outer loop iterates over the passes, starting from pass number 1 and going up to num_cats (inclusive). The inner loop selects the cats the person touches based on the current pass number.</li>
  <li>Flip the hats: For each touched cat, we flip the state of its hat. If the cat's hat is facing the back (False), we change it to face the front (True), and vice versa.</li>
  <li>Determine the result: After all the passes are completed, we check the cats list to determine which cats have their hats facing front (True). We create a new list result containing the numbers of those cats whose hats are facing front.</li>
  <li>Return the result: The function returns the result list, which contains the numbers of the cats with their hats facing front after 100 passes.</li>
</ul>





