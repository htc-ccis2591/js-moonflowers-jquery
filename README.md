# js-moonflowers-jquery

For this assignment, we will update the Moonflower's Coffee shop assignment to use jQuery.

## Moonflower’s Coffee Shop

### Menu Information
The JS file has JSON for the menu information to be presented on the page. You will need to use the data from that object to build an HTML menu to add to the menu section.  

When adding the table, remove the default text that is initially present in the menu section. You will build HTML with a heading and menu table for each category of menu items.

The beverage item table should be first, followed by the bakery items, and the other items should be last.  

The tables should be laid out as follows:

H3 Heading (“Beverage”, “Bakery”, or “Other Products”)
Item 1 name | Price | Image
Item 2 name | Price | Sorry, no image.
Item 3 name | Price | Image

Of there is an image file, add an appropriate HTML image tag with the src and alt text.  However, the image property may not be present in the JSON for some items. In this case, that table cell should contain italicized text saying “Sorry, no image.”

Remember that you can make HTML tables as follows:
```
<table>
    <caption>Basic Table</caption>
    <tr>
        <td>Row 1, Column 1</td><td>Row 1, Column 2</td><td>Row 1, Column 3</td>
    </tr>
    <tr>
        <td>Row 2, Column 1</td><td>Row 2, Column 2</td><td>Row 2, Column 3</td>
    </tr>
    <tr>
        <td>Row 3, Column 1</td><td>Row 3, Column 2</td><td>Row 3, Column 3</td>
    </tr>
</table>
```

### Locations Information
The JS file has JSON for the locations information to be presented on the page. This includes, staff, hours and weekly specials. You will need to use the data from that object to build the HTML as described below.

The Locations section will consist of a heading for each location followed by a list of the weekly hours and information on its staff members.  This data should be added to the “locations” section.  Before adding the headings for each location, remove the default text.

The HTML for each location should be created as follows:

HTML5 Article with class="location"
   H3 Heading for Location Name
   H4 Weekly Hours
   Unordered List of hours data, with each day/time a list item.

   H4 Staff Members
   Div with class="staff row" (One div for each staff member at that location)
      Div with class="col-sm-8"
         H5 Staff Member Name
         Paragraph - Staff Member Text
      Div with class="col-sm-4"

Staff Member Image with class="img-responsive", use "Picture of {staff member name}" as the alt text.
