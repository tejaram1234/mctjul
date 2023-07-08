It is an project which shows the result of leaderboaed
first we should take the input data of players by creating the div and number of inputs using <input> tag.
Create the button as AddPlayer to save the data 
create div for alert and add p tag and add another dive with ID outerCard to print input data.

Now create a function as addplayer() in javascript to insert the data of inputs.
get the data by getelementbyId() from html
Now we generate the date,year,month,day by (new date(),getFullYear(),getMonth(),getDay())
create constent monthnames using const monthNames=["January","February","March","April","May","June","July","August","September","October","Novemb","December"];

crate a cardData element to get card data and push the data using card.push(cardData)
create an alert if the inputs are not correct by getting the alert .
Now we create a condition to validate the data using if condition and print the data by getting the outercard  and printing the data by card.innerHTML.The process continues by using count++.
In the card we have to create three buttons function deleate,addFive,removeFive
here delete button has function to delete the outer card
addFive function adds the rating 5 to the player and removeFive less the rating of five from the player only when the previous rating is greater than or equal to 5.
we add else condition when the above condition not satisfies.
