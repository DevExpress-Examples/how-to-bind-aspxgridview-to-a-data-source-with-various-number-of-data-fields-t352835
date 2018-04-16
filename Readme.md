# How to bind ASPxGridView to a data source with various number of data fields


<p>This example shows how to use <a href="https://documentation.devexpress.com/#AspNet/clsDevExpressWebASPxGridViewtopic"><strong>ASPxGridView</strong></a> with several predefined columns and automatically add the rest of them. The current implementation uses a custom <strong>ColumnUpdater</strong> class for saving and updating a column collection of the <a href="https://documentation.devexpress.com/#AspNet/clsDevExpressWebASPxGridViewtopic"><strong>ASPxGridView</strong></a>. For this purpose, the grid was subscribed in the <strong>ASPxGridView.Init</strong> event with the <strong>ColumnUpdater</strong> class.<br>In this example, the grid is loaded in the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebASPxCallbackPanel_Callbacktopic"><strong>ASPxCallbackPanel.Callback</strong></a> event. To show the grid, please click the button.</p>

<br/>


