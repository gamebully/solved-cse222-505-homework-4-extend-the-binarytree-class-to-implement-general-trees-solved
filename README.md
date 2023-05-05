Download Link: https://assignmentchef.com/product/solved-cse222-505-homework-4-extend-the-binarytree-class-to-implement-general-trees-solved
<br>
<strong>Homework 04  </strong>

Part 1-

Consider the binary tree representation of general trees in our textbook where the left branch of a node is the first child, and each right branch is connected to the next sibling (if any).

<ul>

 <li>Extend the BinaryTree class to implement general trees</li>

 <li>Write an add method that takes a parentItem and a childItem and inserts the childItem as the last child of the parentItem if the parentItem is already in suach a tree structure. The method returns true if insertion is successful and false if the parentItem is not in the tree.</li>

 <li>Write the following methods to search an item in such a general tree structure:</li>

</ul>




<ol>

 <li>levelOrderSearch (): Traverses the tree in level order; First the root node (i.e., the node in the first level), then the children of the root node (i.e., nodes in the second level), then the children of the nodes in the second level (i.e., nodes in the third level), and so on.</li>

 <li>postOrderSearch (): Traverse a node before traversing its subtrees starting from the root node. Search for the item during traversal. Return the Node reference if the item is in the tree and null if it is not in the tree.</li>

</ol>

<ul>

 <li>Override the preOrderTraverse method to traverse to obtain the string representation of the tree.</li>

 <li>As a test construct at least two separate trees by adding 12 new items in the tree. You should try to cover all possible cases with these insertions. You should check the resulting tree by converting it into a string after each insertion.</li>

 <li>Analyze time complexity of your methods</li>

</ul>

<u>Note that, method representations are not the prototypes of methods.</u>







<h1>Part 2-</h1>

Construct a general search tree structure where the tree includes multidimensional items. Each level of a mds tree (multidimensional search tree) splits all children along a specific dimension, using a hyperplane that is perpendicular to the corresponding axis. At the root, all children will be split based on the first dimension (i.e. if the first-dimension coordinate is less than the root it will be in the left-subtree and if it is greater than the root it will be in the right-subtree). Each level down in the tree divides on the next dimension, returning to the first dimension once all others have been exhausted. So, every internal node can be thought of as implicitly generating a splitting hyperplane that divides the space into two parts, half-spaces. The items to the left of this hyperplane are represented by the leftsubtree of that node and items right of the hyperplane are represented by the right subtree. For example, in a 3-dimensional tree, the root would have an <em>x</em>-aligned plane, the root’s children would both have <em>y</em>-aligned planes, the root’s grandchildren would all have <em>z</em>aligned planes, the root’s great-grandchildren would all have <em>x</em>-aligned planes, the root’s great-great-grandchildren would all have <em>y</em>-aligned planes, and so on.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/882.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/882.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>




Extends the BinaryTree class to implement mds trees. Your class should implement the SearchTree interface.

<strong>Note:   </strong>

<ul>

 <li>Obey OOP principles</li>

 <li>Use meaningful and related class, variable, method etc. names</li>

 <li>Use intelliJ IDE on the given VM. VM download link can be found on moodle(in HW1)</li>

 <li>Your submission is HW04_studentnumber.zip and include following files:</li>

</ul>

o intelliJ project file o Report.pdf o Javadoc

<ul>

 <li>The report must be in format “ReportFormat.doc” which was used in HW1</li>

 <li>The implementations will be 75 points and the report is 25 points out of 100</li>

 <li>Submit your homework until the last submission date</li>

</ul>


