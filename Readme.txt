Selectors

1.Element	h1
2.class		.class
3.id		#id


Specificity
Order 
1.Id		1.Inline
2.class		2.Internal
3.element	3.External


Psuedo Selectors

1. :first-child
2. :nth-child(no.)
3. :last-child
4. :only-child
5. :hover
6. :link
7. :visited

Advance selectors

1.sibling selector e1+e2
2.sbiling class selector e1 ~ e2
3.children 	ul>li
4.descendent 	ul li 

Attribute Selectors

1.element[attr = value]
2.ele[attr ^= value ] starts with
3.ele [attr $= value] ends with
4.ele[attr *= value] includes
5.ele[attr ~= value] white space
6.ele[attr |= value] includes and starts with

CSS general rule

selector{
    //code block
    property: value;
}

Colors

1.normal
2.rgb() 0-255
3.hex # 0-F 

Background

1.Background: url('path')
2.Background-color 
3.Background-size: cover
                   contain
                   height width
4.Background-repeat: repeat(default)
                     no-repeat

Opacity
rgba(r,g,b,a) rgb 0-255; alpha(a) 0-1;

Gradient
1.Linear-Gradient
Background:linear-gradient(direction, color1,color2,.....)

2.Radial-Gradient
Background:radial-gradient(direction, color1,color2,.....)

Units
1.Absolute: cm       centimeter
            mm       milimeter
            inch     inches
            px       pixels
            pt       point
            pc       1pc = 12pt

2.Relative: %       percentage
            em      1em = 16px
            rem     relative to root
            vw      view-width
            vh      view-height

Text Manipulation

1.Text-transform:capitalize
                :lowercase
                :uppercase
                
2.text-decoration:none
                 :underline
                 :line-through
                 :overline

3.text-align:center;
            :left
            :right
            :justify

Font Manipulation

1.font-family:'times new roman'
2.font-weight:0-600
3.font-style:italic
            :oblique
4.font-style:px

CSS Box Model

1.content
2.padding:top right bottom left;
3.border :size style color
4.margin-side:

Display
Float

Flex-Box

display:flex;
1.Container
2.Item

Container
1.flex-direction:row (default)
                :column
                :row-reverse
                :column-reverse
                
2.flex-wrap:nowrap(default)
           :wrap

3.justify-content:flex-start (left)
                 :flex-end(right)
                 :center
                 :space-between
                 :space-around
                 
4.align-items:stretch(default);
             :flex-start(top)
             :flex-bottom(bottom)
             :center
             :baseline

Items
1.order: 0 (default)
2.flex-basis: min-width;
3.flex-grow: 0 (default)
4.flex-shrink: 1 (default)

flex : grow shrink basis;

5.align-self: flex-start(top)
            : flex-end(bottom)
            :center
