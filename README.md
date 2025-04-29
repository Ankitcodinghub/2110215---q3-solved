# 2110215---q3-solved
**TO GET THIS SOLUTION VISIT:** [2110215 – Q3 Solved](https://www.ankitcodinghub.com/product/2110215-q3-75-minutes-10-30-11-45-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109268&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;2110215 - Q3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. Instruction

1. Create a Java Project named “2110215_Final_Q3”.

2. Copy folders inside “toStudentQ3” to your project directory src folder.

3. Example command line parameter is given in file “vmArgument.txt”

4. You are to implement the following classes (detail for each class is given in section 3 and 4)

a) ImageButton (component package)

b) TitlePane (component package)

c) Todo (component package)

d) AdderBar (component package)

e) Main (application package)

5. To submit:

a) go to src folder that you actually do the coding for this question.

b) Zip this question’s src folder. Name it YOUR-ID_Q3.zip (for example, 6332112121_Q3.zip)

c) Submit the zipped file as an assignment on MyCourseville.

2. Problem Statement: Jotaro Kujo’s note

Sample screenshot of the application when starts.

How the application works:

Step 1: input to-do task to text field.

Step 1

Step 2: Click add button to add to-do task to list view.

Step 2

Step 3: Click remove button to remove its corresponding to-do task from list view. (You can remove in any row if there are more than one)

Step 3

3. Implementation Detail:

Detailed GUI of the Application.

The class package is summarized below.* In the following class description, only details of IMPORTANT fields and methods are given. *

3.1 Package Logic

3.1.1 public class TodoLogic: This class contains a useful button method to complete some parts of the application. /* ALREADY PROVIDED */

Method

Name Description

+ void addTodo (String todoText) This method should be called by ImageButton with ADD mode, it will add a to-do task to TodoListView.

+ void removeTodo (ImageButton imageButton) This method should be called by ImageButton with REMOVE mode, it will remove a to-do task from TodoListView.

3.2 Package component

3.2.1 public class RootPane: This class represents a Pane that groups the essential components. /* ALREADY PROVIDED */

Field

Name Description

– TitlePane title Representing the TitlePane.

– AdderBar adderBar Representing the AdderBar.

– TodoListView todoListView Representing the TodoListView.

Constructor

Name Description

+ RootPane() Constructor method, which is already provided.

Method

Name Description

+ getter/setter for each field. Already provided.

3.2.2 public class ImageButton: This class represents an ImageView to be an either ADD button or REMOVE button. You must implement 2 methods for this class.

Field

Name Description

– String addButtonUrl Url for the add button image.

– String removeButtonUrl Url for the remove button image.

Constructor

Name Description

+ ImageButton() This method is already provided.

Method

Name Description

– void

initImageButton(ImageButtonType imageButtonType) /* FILL CODE */

Initialize image button with the following

specifications:

– set fit width to 26.

– set fit height to 26.

– set image to match the image button type.

– void

initEventHandler(ImageButtonType imageButtonType) /* FILL CODE */

image button event handler with the

set cursor with “Cursor.HAND”.

set mouse clicked event to call correct method in

Please see the TodoLogic class for the necessary

class to use some methods to get

CLASS&gt;.this” can be used to invoke “this”

of outer class in anonymous class.

Initialize following specifications:

–

–

TodoLogic class.

#HINT1

method.

#HINT2

Please see the Main the information that you want.

#HINT3

“&lt;OUTER-

+ getter/setter for each field. These methods are already provided.

3.2.3 public class TitlePane: This class represents a BorderPane that can group the essential components. You must implement 2 methods for this class.

Field

Name Description

– Text title Representing the title text.

Constructor

Name Description

+ TitlePane()

/* FILL CODE */

Initialize with the following specifications:

Constructor method.

– Initialize super class.

– Initialize title text with initTitle() method.

– set title pane background with “BackgroundFill(Color.DARKSLATEBLUE, null, null)”.

– set title pane preference height to 100.

– add the title text to the center of TitlePane, using method setCenter.

Method

Name Description

– void initTitle()

/* FILL CODE */

Initialize title with the following specifications:

– set title font with name=“Roboto” and size=48

– set title text value=“Todo App”

+ getter/setter for each field. These methods are already provided.

3.2.4 public class Todo: This class represents a BorderPane that can group the essential components. You must implement 1 method for this class.

Field

Name Description

– ImageButton imageButton Representing the image button.

– Text text Representing the text value in Todo.

Constructor

Name Description

+ Todo(Text text, ImageButton imageButton)

/* FILL CODE */

Constructor method.

Initialize with the following specifications: – Initialize super class.

– set imageButton.

– set text.

– add text to the left of BorderPane, using method setLeft.

– add imageButton to the right of BorderPane, using method setRight.

Method

Name Description

+ ImageButton getImageButton() Getter of imageButton.

+ getter/setter for each field. These methods are already provided.

3.2.5 public class AdderBar: This class represents a HBox that can group the essential components. You must implement 3 methods for this class.

Field

Name Description

– TextField textField Representing the text field.

– ImageButton imageButton Representing the ADD image button.

Constructor

Name Description

+ AdderBar() /* FILL CODE */

Constructor method.

Initialize with the following specifications:

– Initialize super class.

– Initialize textField with initTextField() method.

– Initialize imageButton with initImageButton() method. – set preference height to 50.

– set padding with “Insets(9)”

– set spacing to 8

– set alignment with “Pos.CENTER”

– add textField and imageButton to “this” with correct order.

Method

Name Description

– void initTextField() /* FILL CODE */

Initialize textField with the following specifications:

– set preference width to 640. – set preference height to 35.

– void initImageButton() /* FILL CODE */

Initialize imageButton with the following specifications:

– set imageButton with “ImageButtonType.ADD”.

#HINT

Please see the ImageButton implementation.

+ TextField getTextField()

Getter of textField.

+ getter/setter for each field. These methods are already provided.

3.2.6 public class TodoListView: This class represents a ListView&lt;Todo&gt;. /* ALREADY PROVIDED */

3.3 Package Application

3.3.1 public enum ImageButtonType: This enum contains image button type. /* ALREADY

PROVIDED */

3.3.2 public class Main: This class contains the main method. It is an entry point of the application. You must implement 1 method for this class.

Field

Name Description

– RootPane rootPane Representing the root pane.

Method

Name Description

+ void start(Stage stage) /* FILL CODE */

At the TODO section, you must fill the code to

complete the start method with the following:

(1) set the scene with the root pane as a child with width=640 and height=480.

(2) set resizable with false.

(3) set title with “Todo App”.

(4) show the stage

+ String getAdderBarCurrentText() Getter of AdderBar current text value.

+ getter/setter for each field. These methods are already provided.

Scoring Criteria (15 points, will be scaled to 5)

TitlePane

• (1 mark ) TitlePane is visible at its correct size and location.

• (1 mark) TitlePanne has the correct color. • (1 mark) TiplePane has text “Todo App”.

• (1 mark) The text is at the center.

AdderBar

• (1 mark) AdderBar appears below, next to TitlePane.

• (1 mark) text field is to its left

• (1 mark) “+” button is to its right.

• (1 mark) text field can fill one line of character.

• (1 mark) text field is long until it reaches the “+” button.

• (2 mark) When a “+” button is pressed, a new to-do item is added as the last item (the lowest)

• (1 mark) New to-do item has “-“ appearing at its end.

To-do Item

• (2 mark) When a “-“ button is pressed, the corresponding to-do item disappears.

• (1 mark) Other items must shift to take its place.
