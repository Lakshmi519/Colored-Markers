# Colored-Markers
Learnt to build set of colored markers using different ways to set colors.

# CSS Colors
Selecting the correct colors for your webpage can greatly improve the aesthetic appeal to your readers.
There are different ways to ste colors and how to pair colors with each other.
  # 1) rgb function
    rgb(red, green, blue)
  Each red, green, and blue value is a number from 0 to 255. 0 means that there's 0% of that color, and is black. 255 means that there's 100% of that color.
  # 1a) rgba function
    rgba(red, green, blue, alpha)
    example: rgba(255,0,0,0.5);
  alpha works like opacity, it has value as 0 - 1.
  # 2) hexadecimal or hexa values
   Hex color values start with a # character and take six characters from 0-9 and A-F. The first pair of characters represent red, the second pair represent green, and the     third pair represent blue. For example, #4B5320. With hex colors, 00 is 0% of that color, and FF is 100%. So #00FF00 translates to 0% red, 100% green, and 0% blue, and is the same as rgb(0, 255, 0).
  # 2a) hexadecimal with alpha
     #00FF00CC - last 2 characters(CC) represnts alpha value.
  # 3) hsl function
    hsl(hue, saturation, lightening)
    example: hsl(223,35%,50%);
  The CSS hsl function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness. 
  Saturation is the intensity of a color from 0%, or gray, to 100% for pure color. You must add the percent sign % to the saturation and lightness values.
  Lightness is how bright a color appears, from 0%, or complete black, to 100%, complete white, with 50% being neutral.
  # 3a) hsla function
    hsla(hue, saturation, lightening, alpha)
    example: hsla(223, 35%,50%,0.5);
  # 4) linear-gradient
    linear-gradient(gradientDirection, color1, color2,...)
    example: linear-gradient(180deg, red, blue)
  GradientDirection is the direction of the line used for the transition. color1 and color2 are color arguments, which are the colors that will be used in the transition
  itself. These can be any type of color, including color keywords, hex, rgb, or hsl.
  Color-stops allow you to fine-tune where colors are placed along the gradient line. They are a length unit like px or percentages that follow a color in the linear
  gradient function.

    Example: linear-gradient(90deg, red 90%, black);
  In this red-black gradient, the transition from red to black takes place at the 90% point along the gradient line, so red takes up most of the available space.

  # box-shadow
    box-shadow: offsetX offsetY blurRadius spreadRadius color;
  Here's how the offsetX and offsetY values work:
  1. both offsetX and offsetY accept number values in px and other CSS units
  2. a positive offsetX value moves the shadow right and a negative value moves it left
  3. a positive offsetY value moves the shadow down and a negative value moves it up
  4. if you want a value of zero (0) for any or both offsetX and offsetY, you don't need to add a unit. Every browser understands that zero means no change.
