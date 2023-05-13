# UIPATH_Extract_And_Replace
This is simple robot using UIPATH which extracts the name and the country of a person from a List of strings and uses this data to replace a text from another string. After extraction and replacements robot displays correct message in Message Box.
# Task: Extract and replace
Step-by-step guide
Create a robot which extracts the name and the country of a person from a List of strings and uses this data to replace a text from another string.
After extraction and replacements robot displays correct message in Message Box.

Create a list which has data in string format:
new List(of String) from {"Name of the person: Nikolaus Kopernikus, country of origins: Poland.","Name of the person: Jules Verne, Country of origins: France."}

Create a string variable with data.
Hello Mr. <lastname>. To our knowledge your given name is <forename> and you were  born in <country>, which is famous for its beauty."

In For Each loop:
Extract forename and lastname of a person and his country of birth and save this data to variables. This is done to every item in list.

Replace <lastname>, <forename> and <country> with previously extracted information stored in variables.

In message box display correct message at the end of each loop.
