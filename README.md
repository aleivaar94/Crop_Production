# Supply and disposition of grains in Canada

Source: Statistics Canada - [Supply and disposition of grains in Canada](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210001301)


# THIS or THAT?

Grouped bar charts are great for comparing categories and subcategories, showing differences within and across groups.

However, when there are many categories it becomes too cluttered and the differences cannot be seen easily.

In this case, a better alternative is to use a bubble chart. The bubble size adds a dimension and helps to show the differences in magnitude.

<img src="https://github.com/aleivaar94/Crop_Production/blob/main/assets/this_or_that.gif" alt="Grouped Bar Chart vs. Bubble Chart" width="700" height="600">


# On the Use of Color
I was revisiting the bubble chart and noticed ways to improve it. I used red for low values and blue for high values. 

In some contexts this can be effective when you want to highlight deficits or where low values represent problems requiring attention.

Generally, a color scale that transitions from red (low values) to blue (high values) is counter intuitive. Typically, red suggests “more of”, while blue conveys “less of”. 

In the original bubble chart, this reversal doesn’t create a lot of cognitive friction because the size of the bubble conveys high values. 

So in this case, let’s use red for higher values along with the size of the bubble to reduce the cognitive friction and make your plot much faster to understand.

<img src="https://github.com/aleivaar94/Crop_Production/blob/main/assets/On the use of color - Part 1.png" width="700" height="900">


## Sequential or Diverging color scales?

A sequential color scale uses a progression of colors to represent ordered data that ranges from low to high values. It’s  appropriate for most continuous data.

A diverging color scale uses two different sequential color scales that extend from a shared neutral color in the middle. It’s appropriate for continuous data that has a natural midpoint.

In the bubble chart below, a sequential color scale makes the low values hard to read (highlighted inside the square box). In this data, the values don’t have a natural midpoint, but a diverging scale makes these values much easier to read and understand.

<img src="https://github.com/aleivaar94/Crop_Production/blob/main/assets/On the use of color - Part 2.png" width="700" height="900">