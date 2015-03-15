# QuickIni
QuickIni is a class that has an API similar to IniFile, but instead of reading the INI file every time a value is retrieved, it reads the file once, storing the data in a HashMap. This makes retrieval very quick. The contents of the file can be updated with this class, but all comments are discarded when the file is first read.

The source code is released under the MIT license.
