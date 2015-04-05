# brython_autocomplete <br>
just some code to use in IDE's for enabling autocomplete.<br>
this code should to not run so "if False" is necessary.<br>
this code should to not be in production code. it's usage in development<by>
you can use this like this:(or something else)
----
in index.html
<html>
<head>
    <script type="text/javascript" src="brython/brython.js"></script>
</head>
<body onload="brython(1)">
<script type="text/python3" src="brython.py"></script>
</body>
</html>


--- 
#in brython.py
import browser

# here paste brython_autocomplete content

# here your code
