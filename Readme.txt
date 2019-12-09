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
