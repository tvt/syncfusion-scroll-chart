Barebones project showing bug with dynamically enabling scrollbars in Syncfusion's Blazor Chart component.

Problem occurs in App.razor. 
If `_scrollbarEnabled` is initialized as `false` changing it to `true` will not work.
If `_scrollbarEnabled` is initialized as `true` toggling the scrollbar works as expected.