The "FacebookLikeBox.component" in "src\components" of the attached zip contains the component code.
This code can be copied into a new component and can directly be used.
Attributes:
	pageUrl		: this is a required attribute and expects a facebook page for which the facebook like box has to be shown
	header		: expects a true/false to toggle rendering the header
	show_faces	: expects a true/false to toggle rendering the pictures of people who already liked
	stream		: expects a true/false to toggle rendering the stream from the given facebook page

Usage Example:
<c:FacebookLikeBox pageUrl="http://www.facebook.com/cloudspokes"/>

Insert the above line of code in a vf page to see it working. Change the name of the component if it is created with a different name.

Alternatively
The src folder may be deployed using ant.
