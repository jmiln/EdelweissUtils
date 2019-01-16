# EdelweissCatalogFilter

Filters out old catalogs from the list in the `Orders > Edit > Advanced` pop-up page

The defaults for the filters are just set to filter out anything that's got a date from 2000-2017, assuming that those are not needed anymore.
Also has editable filters so you can set your own in the add-on's settings

Default filters are : 
```
// Anything with a date between 2000 and 2017
201[0-7]
200[0-9]

// Any catalog from Spring/ Summer/ Fall/ Winter 00 to 17
(Spring|Summer|Fall|Winter)(0[0-9]|1[0-7])
(Sp|S|F|FL|W)(0[0-9]|1[0-7])
```
