---
title: Use the Spread Operator on Arrays
---
## Use the Spread Operator on Arrays

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
<p>Use E6's spread syntax, <code class="language-text">[...arrToCopy]</code>, which allows you to clone the contents of an array.  No changes are made to the original array. This syntax also allows you to add new items <code class="language-text">[...arrToCopy, 'new item1', 'new item2']</code>.  Now you can return the new To Do item at the end of a new array, leaving state unmutated:</p>
<div>
  <pre class="language-react.js">
    <code class="language-react.js">
      return [...state,action.todo];
    </code>
  </pre>
</div>

