## Tools_TM

Collection of generic methods.  
As I often needs these methods in various applications I placed them in a component  

Documentation for methods see [Methods](Project/Sources/Documentation)

Documentation for:
Git handling see [UsingGit](Documentation/UsingGit.md)

Structure helper tools see [Structure access](Documentation/Structure.md)

### Historic note

Previous versions included much more methods, such as `HTTP_Download` or File name/path/extension routines, which are now obsolete as included in 4D.

### Note

* Project requires 4D v18.
* Included binary build is compiled with v17 R6, requires recompilation to be useable with R5
* Unit testing done with Ajar's UnitTest component, see [Unit Test](https://ch-de.4d.com/ajtoolsunittest) - Component can be removed for deployment of Tools_TM, only needed if you modify/recompile the component.

### Todo

* Unit Tests only added for some already existing methods, not for all. This was done to test the Unit Test component, future method changes or additions needs to have tests method upfront. Adding tests for existing methods would be good to do.
