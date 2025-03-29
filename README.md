# NXTwave_1
FLEXBOX :

Flexbox Properties
1. Flexbox Container
The Bootstrap class name d-flex defines a Flexbox Container. The direct HTML elements in the Flexbox Container are called flex items.


-The HTML container element with the class="d-flex" is a Flexbox Container.
-The HTML container element div in Flexbox Container is a flex item. Because it is directly inside the Flexbox Container.
-The HTML main heading, paragraph, and button elements are not flex items. Because these elements are not directly inside the Flexbox Container.

2. Flex Direction
The Flex Direction specifies the direction of the flex items in the Flexbox Container.

Class Name	Direction of the flex items in a Flexbox Container
flex-row	Horizontal
flex-column	Vertical
2.1 flex-row
The Bootstrap class name flex-row is used to move the flex items horizontally in the Flexbox Container


<div class="d-flex flex-row">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>

2.2 flex-column
The Bootstrap class name flex-column is used to move the flex items vertically in the Flexbox Container.



Note:
The Bootstrap class name flex-row is the default Flex Direction for the Flexbox Container. So, once d-flex is specified, all the flex items in the Flexbox Container display horizontally.

3. Justify Content
The Justify Content specifies the alignment of flex items along the Flex Direction in a Flexbox Container.

3.1 justify-content-start
The Bootstrap class name justify-content-start is used to align the flex items at the start of the Flexbox Container either horizontally or vertically based on the Flex Direction.

Flex Direction	Alignment of flex items in a Flexbox Container
flex-row	Align flex items horizontally to the left
flex-column	Align flex items vertically to the top

<div class="d-flex flex-column justify-content-start">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>

3.2 justify-content-center
The Bootstrap class name justify-content-center is used to align the flex items at the center of the Flexbox Container either horizontally or vertically based on the Flex Direction.

Flex Direction	Alignment of flex items in a Flexbox Container
flex-row	Align flex items horizontally to the center
flex-column	Align flex items vertically to the center

<div class="d-flex flex-column justify-content-center">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>



3.3 justify-content-end
The Bootstrap class name justify-content-end is used to align the flex items at the end of the Flexbox Container either horizontally or vertically based on the Flex Direction.

Flex Direction	Alignment of flex items in a Flexbox Container
flex-row	Align flex items horizontally to the right
flex-column	Align flex items vertically to the bottom

<div class="d-flex flex-column justify-content-end">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>


DEVELOPING LAYOUT IN BOOTSTRAP:
