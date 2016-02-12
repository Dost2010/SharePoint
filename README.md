# SharePoint client side widgets
The repository contains various client side code useful to embed in your portals/teamsite or any other project. Suggestion for building new client side widgets are welcome!
1. TypeAhead.html  --> This is angular + bootstrap code to typeahead(Autofill) text box which read data from the sharepoint list. 
follow the following step in order to embed this code in yoru sharepoint pages.
a. Create a new custom list with default "Title" column and add a few values in it.
b. Copy the content of the file TypeAhead.html and past it in your favorite editor.
c. Change the value of the following variable to the name of your list

              var listName="CustomerList" //change the list name to your list name
d. Copy the code and insert JSlink webpart in your sharepoint page. Save the changes
e. Enjoy!!!!
