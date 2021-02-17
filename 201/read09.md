

# Read09
## From the Duckett HTML book:

## Chapter 7: “Forms” (p.144-175)
Forms are used to collect data from websites visitors. There are many shapes of forms on the web, such as google search box, registeration forms and signing up in sites forms. We can use different form controls which allow you to add text such as text input form, password input forms, text area to fill in forms, ore forms that allow making choices such radio buttons to choose something and checkboxes and drop-down boxes, and there are submitting forms such as submit buttons and image buttons and forms for uploading files.
The way forms work is about recieving the  users submitted data and then sending it to a server where it gets processed using a programming language such as PHP, and finally it returns a new page to the user based on his input.
Forms can be written in HTML using **form** tag which includes an action attribute, a method and an Id attribute, in the action attribute there must be the url of the server page whichh will recieve the form, and in the method we can use only *get* or *post* method.
within the form tag **input**tag is used to determin what type of input will be entered using three atributes inside it, type and name and size attributes in addition to maxlength.


## Chapter 14: “Lists, Tables & Forms” (pp.330-357)

#### Specify the type of bullet p oint or numbering on lists
Using the **list-style-type** property determins how a bullet point(marker) looks, and we can use it with ol, ul, and li. With ul we can use the values: none, disk, circle, and square. with ol we can ues the vlaues decimal, decimal-leading zero, upper-alpha, lower-alpha,upper-roman and lower-roman.
And we can add images for bullets using **list-style-image** property.

#### Add borders to table cells
 When we have empty cells and we want to make it look without a border we use empty-cells propert with hide value, and when we want to put border around the empty cell  we use show value with the empty-cells property.
border-spacing property is used to change the space between cells, and if we use border-collapse the border spacing gets removed.


#### Control the appearance of form controls
 Forms can be styled using CSS to make them look more attractive so that people are more likely to fill them, and to make consistency for their look across different browsers.We can style the text input by fonts and background colors, border and hover and background images, and we can style submit buttons with shadow and coler and background color.



## From the Duckett JS book:

## Chapter 6: “Events” (pp.243-292)
When people are dealing with webpages many things can occur, which causes what is called **Events**. Firstly interactions happen when you make an action such as hover click something or resize your window and they create event, this event triggers code such as making the text flow vertically when you resize the window to be smaller, and then code responds to users by making changes.
There are different types of events such as **UI events** which includes loading, uploading, error, scrolling, and resizing, and there are **keyboard events** such as keyup, keydown, and keypress, and there are **mouse events**  such as click, double click, mousedown, mouseup, mousemove, mouseover, and mouseout .In addition to many other events such as **focus events**, **form events** and **mutation events**.