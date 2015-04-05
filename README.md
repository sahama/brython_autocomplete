# brython_autocomplete <br>
just some code to use in IDE's (eclipse or pycharm for instance) for enabling autocomplete.<br>
put the browser.py behind your others .py code
this code should to not run. i test it and there was no problem but i put "if False" in first line of it.<br>
this code should to not be in production code. it's usage in development<by>
you can use this like this:(or something else that you khow)

in index.html
---
```xml
<html>
<head>
    <script type="text/javascript" src="brython/brython.js"></script>
</head>
<body onload="brython(1)">
<script type="text/python3" src="brython.py"></script>
</body>
</html>
```


in brython.py
---
```python
import browser

# here your code
```
and now you see your IDE have autocompletion for module browser
