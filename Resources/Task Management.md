---
tags :
- Resource
creation date : 2022-10-24 12:44 
---

## Plan
make pages for each note we want to mention, link hierarchy. 

once hierarchy is made, we can start accumulating points and explaining links

## Pages
### Pages to Format
```dataview
list
from "Pages" and #Page/Linked/Formatted/Unedited and -#Page/Linked/Formatted/Unedited/Unresearched
sort file.name asc
```

### Pages to Link
```dataview
list
from "Pages" and #Page/Linked/Formatted and -#Page/Linked/Formatted/Unedited and -#Page/Linked/Formatted/Unedited/Unresearched
sort file.name asc
```

### Pages to Research
```dataview
list
from "Pages" and #Page/Linked/Formatted/Unedited/Unresearched
sort file.name asc
```

## References
### References to Format
```dataview
list
from "Pages" and #Reference/Linked/Formatted/Unedited
sort file.name asc
```

### References to Link
```dataview
list
from "Pages" and #Reference/Linked/Formatted and -#Reference/Linked/Formatted/Unedited
sort file.name asc
```

## TODO List
```dataview
list
from "Pages" and #TODO
sort file.name asc
```

---
##### Hierarchy
###### Up
up:: [[Resources]]
###### Down
down:: 
###### Same
same:: 
###### Next
next:: 
###### Previous
prev:: 