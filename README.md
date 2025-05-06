# sie507-midterm-project-solved
**TO GET THIS SOLUTION VISIT:** [SIE507 Midterm Project Solved](https://www.ankitcodinghub.com/product/sie507-midterm-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97931&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SIE507 Midterm Project Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Assignment

1. Create a function menu() that displays a user selection menu.

The first function menu() shows an input menu for a user with the following options: D) display a cruise ship cabin chart, B) book a cabin or D) quit the menu. (see image below):

The menu() function should check for valid inputs, that is, if the user enters a nonvalid option (like “123”) it should notify the user that the option was invalid and exit the program.

The cruise ship has 3 decks, each deck has 24 rows and each row has 2 cabins.

Initially, the program starts with an empty cabin chart. Booking are only made when the user actually books a cabin via this program. Thus, once the user books a cabin deck, row and number, the cabin chart is updated and a booking list is updated with the passenger booking info, that is, the last name, first name and cabin assignment are added to a (initially empty) booking list.

Both the cabin chart and the booking list are written to files once they are updated (after each update!). For a new run, the program reads the current bookings and the cabin chart from the files and now these files are updated (and not created from scratch).

The program should be structured into a set of functions.

2. Write a function display() that displays the current cabin chart

This function should display the current cabin chart for all the decks. Note, the cabin chart is always read from the cabins.csv file to display the latest version (initially, this cabin chart only shows empty cabins, indicated by a “.”).

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3. Write a function book() that allows the user to reserve a new cabin based the available cabins

The book() function should prompt the user for the following input: selection of a deck, a cabin (defined by row and side of the ship). If the cabin is available, ask the user for his/her first name and last name. If the cabin is not available, it should ask the user if he/she wants to select another cabin. If not, the program should exit. The function optionally can show the cabin chart at this point (that is, call the display() function).

Once the user books a valid, available cabin, the function book() should update the cabin.csv chart and add an “X” at the booked cabin. Furthermore, it should append a new booking record to the end of the file booking.txt. This line should contains the passenger’s lastname, firstname, deck, row, and column (1 or 2).

The function book() should write both files again.

Now, the function book() should confirm the successful booking to the user and return to the main menu.

4. Write the function main() which executes the whole program logic

The function main() should contain the entire program logic and call the previously

programmed functions menu(), display() and book().

The main() function basically handles the user provided selection offered to the user via the menu() function. The main() function calls the display() function if the user selects “D”, and book() if the user selects “B” and quits if “Q” is selected.

The main() program might need more auxiliary functions such as initialize the cabin.csv file.

Also think about other parts of the program that you might structure as a function and can call in the book() function or the main() function.

Deliverables

1. The python program file and a screenshot of the created cabin chart and booking file.

</div>
</div>
</div>
