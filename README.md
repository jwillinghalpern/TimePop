# TimePop
Timepicker Filemaker Module


# ---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---
# TIMEPOP
# 
# ABOUT:
# TIMEPOP is a simple filemaker module for setting a time field or variable. It uses an intuitive interface to streamline the user experience. The look and feel are inspired by the JQuery time picker used in javascript apps.
# 
# 
# 
# 
# INSTALLATION:
# 1. Copy GLOBALS table, or copy the 5 global fields into an existing table called GLOBALS.
2. Copy script module folder.
3. Copy the popover button object. Set the popover's OnObjectEnter script parameter to reference the time field you want to edit. Use GetFieldName(<yourField>) for field names.
# 
# To set additional fields, just change the OnObjectEnter script parameter to GetFieldName(<yourField>) of the field you want to target.
# 
# To set variables, just change the OnObjectEnter script parameter to the literal variable name like "$$GLOBAL_VARIABLE"
# 
# 
# 
# 
# HISTORY:
# CREATED: 2017-03-16   Joshua Willing
UPDATED: 2018-03-16   Joshua Willing only uses global fields. No global variables.
# 
# 
# 
# 
# DEPENDENCIES: 
none
# 
# 
# ---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---<>---
# 
