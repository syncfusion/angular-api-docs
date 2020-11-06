---
layout: post
title: Properties,Methods and Events of Essential JS ejSignature Widget
description: Methods, members, events available in ejSignature
documentation: API
platform: angular-api
keywords: ejSignature, API, Essential JS Signature 
---

# ejSignature

The ejSignature is a JavaScript Plugin used to capture or drawing the smooth signatures, it captures signature as vector outlines of strokes. 
Using ejSignature we can customize the background, stroke width and stroke color and also convert captured signature to an image format. 


#### Example


#### Requires

* module:jQuery

* module:ej.core.js

* module:ej.signature.js

* module:ej.touch.js


## Members

### backgroundColor `string`
{:#members:backgroundcolor}

This property is used to set the background color for the signature.  

#### Default Value: 

* "#ffffff"

#### Example 




### backgroundImage `string`
{:#members:backgroundimage}

This property is used to set the background image for the signature.  

#### Example 




### enabled `boolean`
{:#members:enabled}

Enables or disables the **Signature** textbox widget.

#### Default Value: 

* true

#### Example 



 
### height `string`
{:#members:height}

Sets the height of the Signature control.

#### Default Value:  

* "100%"

#### Example  



 
### isResponsive `boolean`
{:#members:isresponsive}

 Enables/disables responsive support for the signature control (i.e) maintain the signature drawing during the window resizing time.

#### Default Value:

* false

#### Example  



 
### saveImageFormat `enum`
{:#members:saveimageformat}

<ts name = "ej.Signature.SaveImageFormat"/>

Allows the type of the image format to be saved when the signature image is saved.

<table>
<tr>
<th>Name<br/><br/></th>
<th>Description<br/><br/></th>
</tr>
<tr>
<td>PNG<br/><br/></td>
<td>To save the signature image with PNG format only.<br/><br/></td>
</tr>
<tr>
<td>JPG<br/><br/></td>
<td>To save the signature image with JPG format only.<br/><br/></td>
</tr>
<tr>
<td>BMP<br/><br/></td>
<td>To save the signature image with BMP format only.<br/><br/></td>
</tr>
<tr>
<td>TIFF<br/><br/></td>
<td>To save the signature image with TIFF format only.<br/><br/></td>
</tr>
</table>

#### Example  





### saveWithBackground `boolean`
{:#members:savewithbackground}

Allows the signature image to be saved along with its background.

#### Default Value:  

* false

#### Example  



 
### showRoundedCorner `boolean`
{:#members:showroundedcorner}

Enables or disables rounded corner.

#### Default Value:  

* true

#### Example  



 
### strokeColor `string`
{:#members:strokecolor} 

Sets the stroke color for the stroke of the signature.

#### Default Value:  

* "#000000"

#### Example  



 

### strokeWidth `number`
{:#members:strokewidth} 

Sets the stroke width for the stroke of the signature.

#### Default Value:  

* 2

#### Example  



 
 
### width `string`
{:#members:width} 

Sets the width of the Signature control.

#### Default Value:  

* "100%"

#### Example  





## Methods

### clear()
{:#methods:clear}

Clears the strokes in the signature.

N> This method does not accept any arguments.

#### Example  




### destroy()
{:#methods:destroy}

Destroys the signature widget.

N> This method does not accept any arguments.

#### Example  




### disable()
{:#methods:disable}

Disables the signature widget.

N> This method does not accept any arguments.

#### Example  




### enable()
{:#methods:enable}

Enables the signature widget.

N> This method does not accept any arguments.

#### Example  




### hide()
{:#methods:hide}

Hides the signature widget.

N> This method does not accept any arguments.

#### Example  



            
### redo()
{:#methods:redo}

redo the last drawn stroke of the signature

N> This method does not accept any arguments.

#### Example  




### save(filename)
{:#methods:save}

used to save the drawn image.

<table>
<tr>
<th>Name<br/><br/></th>
<th>Type<br/><br/></th>
<th>Description<br/><br/></th>
</tr>
<tr>
<td>Filename<br/><br/></td>
<td>string<br/><br/></td>
<td>The file name of the signature to be downloaded.<br/><br/></td>
</tr>
</table>

 N>  This method accepts string as an argument and this is optional. If the argument filename is not given then the signature will be downloaded with any random name.

#### Example  




### show()
{:#methods:show}

Used to Show the signature widget, if it is already hided. 

N> This method does not accept any arguments.

#### Example  




### undo()
{:#methods:undo}

undo the last drawn stroke of the signature.

N> This method does not accept any arguments.

#### Example  




## Events

### change
{:#events:change}

Triggers when the stroke is changed.

<table>
<tr>
<th>Name<br/><br/></th>
<th>Type<br/><br/></th>
<th>Description<br/><br/></th>
</tr>
<tr>
<td>cancel<br/><br/></td>
<td>boolean<br/><br/></td>
<td>Set this option to true to cancel the event.<br/><br/></td>
</tr>
<tr>
<td>model<br/><br/></td>
<td><ts ref="ej.Signature.Model"/>Object<br/><br/></td>
<td>Instance of the signature model object.<br/><br/></td>
</tr>
<tr>
<td>type<br/><br/></td>
<td>string<br/><br/></td>
<td>Name of the event.<br/><br/></td>
</tr>
<tr>
<td>lastImage<br/><br/></td>
<td>string<br/><br/></td>
<td>Gives the last stored image<br/><br/></td>
</tr>
</table>

#### Example  

{% highlight html %}


### mouseDown
{:#events:mousedown}
Triggered when the pointer is clicked or touched in the signature canvas.
<table>
<tr>
<th>Name<br/><br/></th>
<th>Type<br/><br/></th>
<th>Description<br/><br/></th>
</tr>
<tr>
<td>cancel<br/><br/></td>
<td>boolean<br/><br/></td>
<td>Set this option to true to cancel the event.<br/><br/></td>
</tr>
<tr>
<td>model<br/><br/></td>
<td><ts ref="ej.Signature.Model"/>Object<br/><br/></td>
<td>Instance of the signature model object.<br/><br/></td>
</tr>
<tr>
<td>type<br/><br/></td>
<td>string<br/><br/></td>
<td>Name of the event.<br/><br/></td>
</tr>
<tr>
<td>value<br/><br/></td>
<td>object<br/><br/></td>
<td>returns all the event values<br/><br/></td>
</tr>
</table>

#### Example  

{% highlight html %}


### mouseMove
{:#events:mousemove}
Triggered when the pointer is moved in the signature canvas.
<table>
<tr>
<th>Name<br/><br/></th>
<th>Type<br/><br/></th>
<th>Description<br/><br/></th>
</tr>
<tr>
<td>cancel<br/><br/></td>
<td>boolean<br/><br/></td>
<td>Set this option to true to cancel the event.<br/><br/></td>
</tr>
<tr>
<td>model<br/><br/></td>
<td><ts ref="ej.Signature.Model"/>Object<br/><br/></td>
<td>Instance of the signature model object.<br/><br/></td>
</tr>
<tr>
<td>type<br/><br/></td>
<td>string<br/><br/></td>
<td>Name of the event.<br/><br/></td>
</tr>
<tr>
<td>value<br/><br/></td>
<td>object<br/><br/></td>
<td>returns all the event values<br/><br/></td>
</tr>
</table>

#### Example  

{% highlight html %}



### mouseUp
{:#events:mouseup}
Triggered when the pointer is released after click or touch in the signature canvas.
<table>
<tr>
<th>Name<br/><br/></th>
<th>Type<br/><br/></th>
<th>Description<br/><br/></th>
</tr>
<tr>
<td>cancel<br/><br/></td>
<td>boolean<br/><br/></td>
<td>Set this option to true to cancel the event.<br/><br/></td>
</tr>
<tr>
<td>model<br/><br/></td>
<td><ts ref="ej.Signature.Model"/>Object<br/><br/></td>
<td>Instance of the signature model object.<br/><br/></td>
</tr>
<tr>
<td>type<br/><br/></td>
<td>string<br/><br/></td>
<td>Name of the event.<br/><br/></td>
</tr>
<tr>
<td>value<br/><br/></td>
<td>object<br/><br/></td>
<td>returns all the event values<br/><br/></td>
</tr>
</table>

#### Example  

{% highlight html %}

