<!-- 
This class diagram using Mermaid has been created
for instructional purposes. 

Explanations can be found in the comments, denoted by %%.

We bookend this file, starting with ```mermaid and ending with ```
to signify that this file uses Mermaid.
-->

```mermaid
classDiagram
    class Door
    %% The attribute below is public (+) and of type String
    Door : +String color
    Door : +String shape
    Door : +Float height
    Door : +Float width
    %% The parentheses indicate that this is a function/method
    Door : +OpenDoor(user)
    Door : +CloseDoor(user)
    Door : +SlamDoor(wind)
```