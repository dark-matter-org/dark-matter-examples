# Dark Matter Data Overview #

<table border='0'>
<tr>
<td width='120' valign='top'>
<img src='http://www.dark-matter-data.org/images/dmd-100x100.png' />
</td>
<td>

So much attention is focused on the <a href='http://code.google.com/webtoolkit/doc/latest/DevGuideMvpActivitiesAndPlaces.html'>MVP</a>/<a href='http://vesprogstuff.wordpress.com/2010/03/19/ext-gwt-mvc-pattern-explained/'>MVC</a> aspects of applications, whereas the handling of data (the model) is mentioned as an afterthought. This is despite the fact that the presentation and manipulation of data is the primary reason for the existence of the user interface.<br>
<br>
The Dark Matter Data project addresses this disparity by defining a schema driven framework that provides a consist, easy to understand, mechanism for defining your data model, generating Java objects that represent that data and a standard protocol for Creating, Retrieving, Updating, Deleting and receiving Events about those objects. Instead of just <a href='http://en.wikipedia.org/wiki/Create,_read,_update_and_delete'>CRUD</a>, one might say you get CRUDE, where the E stands for events. And we all understand how valuable crude is these days.<br>
<br>
If Dark Matter were simply another rehash of the <a href='http://java.sun.com/blueprints/corej2eepatterns/Patterns/TransferObject.html'>Transfer Object Pattern</a>, there would be little added value. But Dark Matter goes beyond the basic Data Transfer Object (DTO) mechanisms by providing ways to use Dark Matter Objects (DMOs) in different operational contexts and to extend the DMOs with behaviour that is appropriate to the given context.<br>
<br>
By "operational context" here, I mean that you can use DMOs in a Java server implementation, in a Java client, in a GWT-based browser application or any other context where Java is supported. The difference between Dark Matter and most other frameworks is that you can add behavior to your DMOs in each of these contexts by using the Dark Matter Wrapper (DMW) concepts provided by the framework.<br>
<br>
Since each context has its own limitations/advantages, this means that you can tailor the behavioral aspects of your objects to their environment without polluting the data representation. By using the standardized (but extensible) Dark Matter Protocol (DMP) all communications associated with your CRUDE interactions can take place between your various operational contexts.<br>
<br>
<table width='100%' border='0'>
<tr align='center'>
<td>
<img src='http://dark-matter-data.org/images/dmoOverview.png' />
</td>
</tr>
</table>

</td>
</tr>

</table>