### To Reproduce

1. Run the project
2. Click on the `StateHasChanged` button
3. The expected result is to update the DateTime


Since the passed ChildComponent is placed inside a RenderFragment which is part of the ParentComponent - I expect ParentComponent to be rerendered.
