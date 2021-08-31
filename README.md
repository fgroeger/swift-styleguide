# Swift Styleguide
This document describes how I want to write Swift code and which style decisions I prefer.

## Use implicit self
Whenever possible, I try to avoid the `self` keyword, with one exception. Inside initializers I still use the `self` keyword to make clear I instantiate the property.
Avoiding the `self` keyword whenever possible gives me some advantages:
