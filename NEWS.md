# wiesbaden

# Version 1.2.0 (2019-10-14)

* Database usernames and passwords are now stored securely via keyring package instead of a file in the root directory. 

# Version 1.1.1 (2019-10-14)

* Allow to retrieve 2500 value labels when using `retrieve_valuelabel()` (instead of only 500)

# Version 1.1.0 (2019-10-13)

* Added a vignette and revised documentation for some functions.
* `read_header_genesis()` uses `stri_trans_general()` for non-ASCII character replacement 
* All `dplyr` dependency removed and reduced number of dependencies
* Code for `read_gv100()` rewritten using only base functions

# Version 1.0.0

* First release