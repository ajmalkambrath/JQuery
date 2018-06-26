# JQuery

## 1 .closest() Vs .parents() selectors
closest is more resistant to refactoring the HTML code than parent

parent returns the immediate parents (one for each element in the caller object) or nothing if the parent does not match the selector. closest returns the closest ancestor matching ancestor for each element (which can be the original element). The third similar function, parents, returns all matching ancestors (not including the element itself).
