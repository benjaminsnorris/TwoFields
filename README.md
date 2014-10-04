TwoFields
=========

A simple example of auto layout with two textfields that split the screen

###Quick Lesson: Control Drag in Storyboard.
- Ctrl click and drag within a view 
  - For width (ctrl click and then drag to side) 
  - For height (ctrl click and drag up or down)
- Ctrl click and drag from one view to another to align attributes
  - You can change the attributes in the dropdown in the inspector
  - For example, you could click and drag to align the center x of two views, but then change it so that it aligns the center of one view with the leading (or trailing) edge of another.

###Instructions

- Add two textfields to the top of the view in the storyboard
- Add the following constraints:
  - Center Y alignment between the fields
  - Vertical Y alignment between the first field and top layout guide (hint: the editor will give this one to you)
  - First field's Trailing with the center x of it's superview with a constant of -5 (hint: you'll ctrl click to give them the same center x, and then adjust it to trailing in the inspector.)
  - First field's Leading with the superview's leading and a constant of 10
  - Second field's Leading with the center x of it's superview with a constant of 5
  - Second field's Trailing with the superview's traling and a constant of -10

###Good luck

![Portrait](http://cl.ly/image/1k1Q1Z1u2v0q/Portrait.png)
![Landscape](http://f.cl.ly/items/0W3t3c0Z0e1z3u1Y0j3A/Landscape.png)
