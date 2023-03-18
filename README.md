# html
<div class="parent">
  <div class="child"></div>
  <div class="child"></div>
  <div class="child"></div>
  <div class="child"></div>
</div>
 

.parent {
  display: flex; /* Set display property to flex */
}

.child {
  width: 25%; 
  height: 100px; /* Set a fixed height for the child divs */
  background-color: #ddd; /* Set a background color to visualize the divs */
  border: 1px solid #999; /* Add a border to separate the child divs */
  box-sizing: border-box; /* Include the border in the width calculation */
}
