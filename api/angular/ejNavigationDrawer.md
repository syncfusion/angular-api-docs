---
layout: post
title: Properties, Methods and Events of ejNavigationDrawer Widget
description: API reference for ejNavigationDrawer
documentation: API
platform: angular-api
keywords: NavigationDrawer, ejNavigationDrawer, syncfusion, NavigationDrawer api 
---

# ejNavigationDrawer




The Navigation Drawer is a sliding panel that displays the list of navigation options on demand. That is, by default, it is not visible but you can display it onto the left/right side of the screen by swiping or by clicking with desired target icon.

















#### Example








#### Requires



* module:jQuery


* module:ej.core.js


* module:ej.navigationdrawer.js


* module:ej.listview.js




## Members





### ajaxSettings  `Object`
{:#members:ajaxsettings}

Specifies the ajaxSettings option to load the content to the NavigationDrawer control.

#### Default Value

* null

#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>



### ajaxSettings.async `boolean`
{:#members:ajaxsettings-async}

It specifies, whether to enable or disable asynchronous request.

### ajaxSettings.cache `boolean`
{:#members:ajaxsettings-cache}

It specifies the page will be cached in the web browser.

### ajaxSettings.contentType `string`
{:#members:ajaxsettings-contenttype}

It specifies the type of data is send in the query string.

### ajaxSettings.data `Object`
{:#members:ajaxsettings-data}

It specifies the data as an object, will be passed in the query string.

### ajaxSettings.dataType `string`
{:#members:ajaxsettings-datatype}

It specifies the type of data that you're expecting back from the response.

### ajaxSettings.type `string`
{:#members:ajaxsettings-type}

It specifies the HTTP request type.


### contentId `string`
{:#members:contentid}








Specifies the contentId for navigation drawer, where the AJAX content need to updated




#### Default Value







* null








#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>










### cssClass `string`
{:#members:cssclass}








Sets the root class for NavigationDrawer theme. This cssClass API helps to use custom skinning option for NavigationDrawer control. By defining the root class using this API, we need to include this root class in CSS.




#### Default Value







* ""








#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
    </div>










### direction `enum`
{:#members:direction}



<ts name="ej.Direction" />




Sets the Direction for the control. See <a href="global.html#Direction">Direction</a>



<table class="props">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Default</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">
Left</td>
<td class="type">string</td>
<td class="default">left</td>
<td class="description">Used to set Direction as Left</td>
</tr>
<tr>
<td class="name">
None</td>
<td class="type">string</td>
<td class="default">none</td>
<td class="description">Used to set Direction as None</td>
</tr>
<tr>
<td class="name">
Right</td>
<td class="type">string</td>
<td class="default">right</td>
<td class="description">Used to set Direction as Right</td>
</tr>
</tbody>
</table>



#### Default Value







* left








#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>










### enableListView `boolean`
{:#members:enablelistview}








Sets the listview to be enabled or not




#### Default Value







* false








#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>










### items `Array`
{:#members:items}








Specifies the listview items as an array of object.




#### Default Value







* []








#### Example

{% highlight html %}



<div >



   <div class="list"> Home </div>




<div class="list"> Communities </div>



</div>
</div>










### listViewSettings `Object`
{:#members:listviewsettings}








Sets all the properties of listview to render in navigation drawer





#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>


lvset: any;

el: boolean;
constructor() {

this.el = true;

this.lvset = { width: 300 };

}









### position `string`
{:#members:position}








Specifies position whether it is in fixed or relative to the page. See <a href="global.html#Position">Position</a>




#### Default Value







* normal








#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>










### targetId `string`
{:#members:targetid}








Specifies the targetId for navigation drawer




#### Default Value







* ""








#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>

</div>


}




### type `string`
{:#members:type}








Sets the rendering type of the control. See Type




#### Default Value







* overlay








#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>










### width `number`
{:#members:width}








Specifies the width of the control




#### Default Value







* auto








#### Example

{% highlight html %}
<div ej-navigationdrawer id="navpane" targetId="butdrawer" [enableListView]="el" [width]="width" >





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>


}





### isPaneOpen `boolean`
{:#members:ispaneopen}


Navigation pane opened initially when isPaneOpen property is true.

#### Default Value

* false

#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>




## Methods








### close()
{:#methods:close}








To close the navigation drawer control





#### Example

{% highlight html %}
<div ej-navigationdrawer id="navpane" [enableListView]="el">



### loadContent(id,url)
{:#methods:loadcontent}


To load AJAX content into NavigationDrawer container.


#### Example

{% highlight html %}
<div ej-navigationdrawer id="navpane" [enableListView]="el">





### open()
{:#methods:open}








To open the navigation drawer control





#### Example

{% highlight html %}
<div ej-navigationdrawer id="navpane" [enableListView]="el">








### toggle()
{:#methods:toggle}








To Toggle the navigation drawer control





#### Example

{% highlight html %}
<div ej-navigationdrawer id="navpane" [enableListView]="el">






## Events





### ajaxComplete
{:#events:ajaxcomplete}




Event triggers after the AJAX content loaded completely.

<table>
<tr>
<th>
Name</th><th>
Type</th><th>
Description</th></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
Set this option to true to cancel the event.</td></tr>
<tr>
<td>
model</td><td><ts ref="ej.NavigationDrawer.Model"/>
Object</td><td>
Instance of the navigation drawer model object.</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
Name of the event.</td></tr>
<tr>
<td>
URL</td><td>
string</td><td>
URL of the content.</td></tr>
<tr>
<td>
data</td><td>
string</td><td>
Response content.</td></tr>
</table>


#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>



### ajaxError
{:#events:ajaxerror}




Event triggers when the AJAX request failed.

<table>
<tr>
<th>
Name</th><th>
Type</th><th>
Description</th></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
Set this option to true to cancel the event.</td></tr>
<tr>
<td>
model</td><td><ts ref="ej.NavigationDrawer.Model"/>
Object</td><td>
Instance of the navigation drawer model object.</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
Name of the event.</td></tr>
<tr>
<td>
URL</td><td>
string</td><td>
URL of the content.</td></tr>
<tr>
<td class="name">data</td>
<td class="type"><ts ref="ej.NavigationDrawer.Model"/><span class="param-type">Object</span></td>
<td class="description last">
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">responseText</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">Error page content.</td>
</tr>
<tr>
<td class="name">status</td>
<td class="type"><span class="param-type">number</span></td>
<td class="description last">Error code.</td>
</tr>
<tr>
<td class="name">statusText</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description last">The corresponding error description.</td>
</tr>
</tbody>
</table>
</td>
</td>
</tr>
</table>


#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
    </div>



### ajaxSuccess
{:#events:ajaxsuccess}




Event triggers after the AJAX content loaded successfully.

<table>
<tr>
<th>
Name</th><th>
Type</th><th>
Description</th></tr>
<tr>
<td>
cancel</td><td>
boolean</td><td>
Set this option to true to cancel the event.</td></tr>
<tr>
<td>
model</td><td><ts ref="ej.NavigationDrawer.Model"/>
Object</td><td>
Instance of the navigation drawer model object.</td></tr>
<tr>
<td>
type</td><td>
string</td><td>
Name of the event.</td></tr>
<tr>
<td>
URL</td><td>
string</td><td>
URL of the content.</td></tr>
<tr>
<td>
data</td><td>
string</td><td>
Response content.</td></tr>
</table>


#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>



### beforeClose
{:#events:beforeclose}








Event triggers before the control gets closed.

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">
argument</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description">Event parameters from Navigation Drawer
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">
cancel</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">
model</td>
<td class="type"><ts ref="ej.NavigationDrawer.Model"/><span class="param-type">Object</span></td>
<td class="description">returns the Navigation Drawer model</td>
</tr>
<tr>
<td class="name">
type</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description">returns the name of the event</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>








### open
{:#events:open}








Event triggers when the control open.

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">
argument</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description">Event parameters from Navigation Drawer
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">
cancel</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">
model</td>
<td class="type"><ts ref="ej.NavigationDrawer.Model"/><span class="param-type">Object</span></td>
<td class="description">returns the Navigation Drawer model</td>
</tr>
<tr>
<td class="name">
type</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description">returns the name of the event</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
</div>








### swipe
{:#events:swipe}








Event triggers when the Swipe happens.

<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">
argument</td>
<td class="type"><span class="param-type">Object</span></td>
<td class="description">Event parameters from Navigation Drawer
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name">
cancel</td>
<td class="type"><span class="param-type">boolean</span></td>
<td class="description">if the event should be canceled; otherwise, false.</td>
</tr>
<tr>
<td class="name">
model</td>
<td class="type"><ts ref="ej.NavigationDrawer.Model"/><span class="param-type">Object</span></td>
<td class="description">returns the Navigation Drawer model</td>
</tr>
<tr>
<td class="name">
type</td>
<td class="type"><span class="param-type">string</span></td>
<td class="description">returns the name of the event</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>




#### Example

{% highlight html %}





<ul>






<li data-ej-text="Home" id="navhome"></li>






<li data-ej-text="People" id="navPeople"></li>






<li data-ej-text="Profile" id="navProfile"></li>






<li data-ej-text="Photos" id="navPhotos"></li>






<li data-ej-text="Communities" id="navCommunities"></li>





 </ul>
    </div>



