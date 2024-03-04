## FlexBox

#### Flex Grow

- flex grow is an easy way of adding a width to your box.
- flex-direction doesn't even matter.

#### Flex Basis

- we have to add flex-basis instead of width to a flex child.
- By default it sets to auto.
- If `flex-direction: row`, it will work on width,
- If `flex-direction: column` it will work on height.

#### Flex Shrink

- By default `flex-shrink:1`, which means everything shrinks normally
- If we add `flex-shrink:0`it will not be shrink no matter what.

#### Flex

-We can used the combination of all the above three to `flex: flex-grow, flex-shrink, flex-basis` for example: `flex: 1 1 20rem`

#### order

- Order property is used on the children of the parent whose display is flex, through which you can change the order of the children
