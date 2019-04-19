---
title: Use the Spread Operator on Arrays
---
## Use the Spread Operator on Arrays

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
<p>Use E6's spread operator, <code class="language-text">[...arrToCopy]</code> to easily return an updated array without mutating state. In your <code class="language-text">case 'ADD_TO_DO'</code> use:</p> 
<div class="gatsby-highlight" data-language="react.js">
 <pre class="language-react.js">
  <code class="language-react.js">
  return [...state,action.todo];
  </code>
 </pre>
</div>
