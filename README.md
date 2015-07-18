# Grid-vision
This css file will help to create complicated webpage layouts with the concept of grids. The css file contains the layout styling of the classes : line , unit, size-1-1,  size-1-2,  size-1-3, size-2-3, size-1-4, size-3-4, size-1-5, size-2-5, size-3-5 and size-4-5.

WHat the classes mean:

1. "line"- this class refers to a horizontal block houses "unit" inside it.

2. "unit"- this class refers to the small horizontal sections within an element with class "line" that has content such as text, images, etc.

3. "size-1-1", "size-1-2", "size-1-3"...- these classes refer to the size assigned to line or the units. "size-1-1" means the element is assigned a width of 100% of the parent element, "size-1-2" means the element is assigned a width of 50% of the parent element, "size-1-3" means the element is assigned a width of 33.3% of the parent element and so forth.


these classes can be uses to create complicated layouts.
for example, <div class="line size-1-1"></div> creates a div element that spans 100% of the parent width and 
<div class="line size-1-1>
  <div class="unit size-1-2">...</div>
  <div class="unit size-1-2">...</div>
</div>

creates two units with half the width of the line. Similary other size parameters can also be assigned.
