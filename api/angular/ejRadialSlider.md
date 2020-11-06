---
layout: post
title: ejRadialSlider
documentation: API
platform: angular-api
keywords: ejRadialSlider, API, Essential JS RadialSlider
---

# ejRadialSlider

The RadialSlider provides an optimized interface for selecting a numeric value using a touch interface. Value is returned based on direct needle selection or needle move. It can also be customized as a full circle, half circle, or any portion of a circle, based on startAngle and endAngle





#### Example





#### Requires

* module:jQuery

* module:ej.core

* module:ej.touch

* module:ej.radialslider


## Members

### autoOpen `boolean`
{:#members:autoopen}


To show the RadialSlider in initial render.


#### Default Value:

* false


#### Example

{% highlight html %}





### cssClass `string`
{:#members:cssclass}


Sets the root class for RadialSlider theme. This cssClass API helps to use custom skinning option for RadialSlider control. By defining the root class using this API, we need to include this root class in CSS.


#### Default Value:

* ""


#### Example 

{% highlight html %}



### enableAnimation `boolean`
{:#members:enableanimation}


To enable Animation for Radial Slider.


#### Default Value:

* true


#### Example

{% highlight html %}






### enableRoundOff  `boolean`
{:#members:enableroundoff}


Enable/Disable the Roundoff property of RadialSlider


#### Default Value:

* true


#### Example

{% highlight html %}







### endAngle  `number`
{:#members:endangle}


Specifies the endAngle value for radial slider circle.


#### Default Value:

* 360




#### Example

{% highlight html %}




### inline  `boolean`
{:#members:inline}


Specifies the inline for label show or not on given radius.


#### Default Value:

* false




#### Example

{% highlight html %}




### innerCircleImageClass `string`
{:#members:innercircleimageclass}


Specifies innerCircleImageClass, using this property we can give images for center radial circle through CSS classes.


#### Default Value:

* null




#### Example

{% highlight html %}




### innerCircleImageUrl `string`
{:#members:innercircleimageurl}


Specifies the file name of center circle icon


#### Default Value:

* null


#### Example

{% highlight html %}




### labelSpace `number`
{:#members:labelspace}


Specifies the Space between the radial slider element and the label.


#### Default Value:

* 30



#### Example

{% highlight html %}





### locale `string`
{:#members:locale}

Change the Radial Slider ticks value based on the given culture.

#### Default Value

* "en-US"

#### Example

{% highlight html %}




### radius `number`
{:#members:radius}


Specifies the radius of radial slider


#### Default Value:

* 200



#### Example

{% highlight html %}





### showInnerCircle  `boolean`
{:#members:showinnercircle}


To show the RadialSlider inner circle.


#### Default Value:

* true




#### Example

{% highlight html %}






### startAngle  `number`
{:#members:startangle}


Specifies the endAngle value for radial slider circle.


#### Default Value:

* 0




#### Example

{% highlight html %}





### strokeWidth  `number`
{:#members:strokewidth}


Specifies the  strokeWidth for customize the needle, outer circle and inner circle.


#### Default Value:

* 2


#### Example

{% highlight html %}




### ticks `Array`
{:#members:ticks}


Specifies the ticks value of radial slider


#### Example

{% highlight html %}







### value `number`
{:#members:value}


Specifies the value of radial slider


#### Default Value:

* 10



#### Example

{% highlight html %}







## Methods




### show()
{:#methods:show}

To show the radialslider



#### Example

{% highlight html %}





### hide()
{:#methods:hide}


To hide the radialslider



#### Example

{% highlight html %}




## Events




### change
{:#events:change}


Event triggers when the change occurs.

<table class="params" border="1">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>

<tbody>

<tr>
<td> model </td>
<td> Object </td>
<td> returns the Radialslider model </td>
</tr>

<tr>
<td> cancel </td>
<td> boolean </td>
<td> if the event should be canceled; otherwise, false. </td>
</tr>

<tr>
<td> oldValue </td>
<td> number </td>
<td> returns the initial value of Radial slider </td>
</tr>

<tr>
<td> type </td>
<td> string </td>
<td> returns the name of the event </td>
</tr>

<tr>
<td> value </td>
<td> number </td>
<td> returns the current value of the Radial slider </td>
</tr>

</tbody>
</table>


#### Example

{% highlight html %}





### create
{:#events:create}


Event triggers when the radial slider is created.

<table class="params" border="1">
<thead>
<tr>
<th> Name </th>
<th> Type </th>
<th> Description </th>
</tr>
</thead>

<tbody>
<tr>
<td> cancel </td>
<td> boolean </td>
<td> if the event should be canceled; otherwise, false. </td>
</tr>

<tr>
<td> model </td>
<td> Object </td>
<td> returns the Radialslider model </td>
</tr>

<tr>
<td> type </td>
<td> string </td>
<td> returns the name of the event </td>
</tr>

</tbody>
</table>


#### Example

{% highlight html %}





### mouseover
{:#events:mouseover}


Event triggers when the mouse pointer is dragged over the radial slider.

<table class="params" border="1">
<thead>
<tr>
<th> Name </th>
<th> Type </th>
<th> Description </th>
</tr>
</thead>

<tbody>
<tr>
<td> cancel </td>
<td> boolean </td>
<td> if the event should be canceled; otherwise, false. </td>
</tr>

<tr>
<td> model </td>
<td> Object </td>
<td> returns the Radialslider model </td>
</tr>

<tr>
<td> selectedValue </td>
<td> number </td>
<td> returns the value selected </td>
</tr>

<tr>
<td> type </td>
<td> string </td>
<td> returns the name of the event </td>
</tr>


<tr>
<td> value </td>
<td> number </td>
<td> returns the current value selected in Radial slider </td>
</tr>

</tbody>
</table>



#### Example

{% highlight html %}





### slide
{:#events:slide}


Event triggers when the Radial slider slides.

<table class="params" border="1">
<thead>
<tr>
<th> Name </th>
<th> Type </th>
<th> Description </th>
</tr>
</thead>

<tbody>
<tr>
<td>
cancel
</td>
<td> boolean </td>
<td> if the event should be canceled; otherwise, false. </td>
</tr>

<tr>
<td> model </td>
<td> Object </td>
<td> returns the Radialslider model </td>
</tr>

<tr>
<td> selectedValue </td>
<td> number </td>
<td> returns the value selected in Radial slider </td>
</tr>

<tr>
<td> type </td>
<td> string </td>
<td> returns the name of the event </td>
</tr>

<tr>
<td> value </td>
<td> number </td>
<td> returns the currently selected value </td>
</tr>

</tbody>
</table>


#### Example

{% highlight html %}





### start
{:#events:start}




Event triggers when the radial slider starts.

<table class="params" border="1">
<thead>
<tr>
<th> Name </th>
<th> Type </th>
<th> Description </th>
</tr>
</thead>

<tbody>

<tr>
<td> cancel </td>
<td> boolean </td>
<td> if the event should be canceled; otherwise, false. </td>
</tr>

<tr>
<td> model </td>
<td> Object </td>
<td> returns the Radialslider model </td>
</tr>

<tr>
<td> type </td>
<td> string </td>
<td> returns the name of the event </td>
</tr>

<tr>
<td> value </td>
<td> number </td>
<td> returns the current value selected in Radial slider </td>
</tr>

</tbody>
</table>


#### Example

{% highlight html %}





### stop
{:#events:stop}


Event triggers when the radial slider stops.

<table class="params" border="1">
<thead>
<tr>
<th> Name </th>
<th> Type </th>
<th> Description </th>
</tr>
</thead>

<tbody>

<tr>
<td> cancel </td>
<td> boolean </td>
<td> if the event should be canceled; otherwise, false. </td>
</tr>

<tr>
<td> model </td>
<td> Object </td>
<td> returns the Radialslider model </td>
</tr>

<tr>
<td> type </td>
<td> string </td>
<td> returns the name of the event </td>
</tr>

<tr>
<td> value </td>
<td> number </td>
<td> returns the current value selected in Radial slider </td>
</tr>

</tbody>
</table>


#### Example

{% highlight html %}
