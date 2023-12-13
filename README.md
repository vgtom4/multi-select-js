# Custom Multi-Select JavaScript Component

In the HTML page  :
             
        <link rel="stylesheet" href="multi-select.css">
        <div id="multi-select">
            <label for="items-selected" style="display: none;">Chamber(s) selected</label>
            <div id="items-selected" data-items-selected></div>
            <label for="items-available">Chamber(s) available</label>
            <div id="items-available" data-items-available></div>
        </div>
        <script src="multi-select.js"></script>
        <script>
            <!-- button settings -->
            titleAvailable = "<custom_text_hover_for_button_available>";
            titleSelected = "<custom_text_hover_for_button_selected>";
            innerHTMLLeftAvailable = "<custom_text_on_the_left_of_item_text_available>";
            innerHTMLLeftSelected = "<custom_text_on_the_left_of_item_text_selected>";
            innerHTMLRightAvailable = "<custom_text_on_the_right_of_item_text_available>";
            innerHTMLRightSelected = "<custom_text_on_the_right_of_item_text_selected>";
            idItem = "<custom_id_of_item>";

            listItemsUpdateStr = list of items available;
            listAllItemsStr = list of all items;

            // init
            UpdateItems(listItemsUpdateStr, listAllItemsStr);
        </script>

## Preview

![](img-project/preview_available.png)
![](img-project/code_available.png)

![](img-project/preview_available_and_selected.png)
![](img-project/code_available_and_selected.png)

![](img-project/preview_selected.png)
![](img-project/code_selected.png)