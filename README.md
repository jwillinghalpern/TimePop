# TimePop
Timepicker Filemaker Module



# ABOUT:
TIMEPOP is a simple filemaker module for setting time or timestamp fields and variables. It uses an intuitive interface to streamline the user experience. The look and feel are inspired by the Bootstramp Datetime picker used in web apps.

Now supports timestamps thanks to Jeremiah Small


# INSTALLATION:
1. Copy GLOBALS table, or copy the fields into a table called GLOBALS.
2. Create an empty layout called "TimePop Window" based on GLOBALS. Don't copy the layout objects from this file yet.
2. Copy script module folder.
3. Copy the popover buttons and regular buttons above. 
	a. Set the popover's OnObjectEnter script parameter to reference the time field you want to edit. Use GetFieldName(<yourField>) for field names
	b. Set the script parameter for the regular buttons to GetFieldName(<yourField>)
4. Copy the layout objects from "TimePop WIndow" in this solution to your layout of that name. You can also change the layout context now, but it doesn't matter.

To set additional fields, just change the OnObjectEnter script parameter to GetFieldName(<yourField>) of the field you want to target.

To set variables, just change the OnObjectEnter script parameter to the literal variable name like "$$GLOBAL_VARIABLE"




# DEPENDENCIES: 
none


