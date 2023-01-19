# Base64-Python-Rev-Shell-Yara-Rule
Here is an example of a Yara rule that could be used to detect a base64 encoded python reverse shell

This rule will look for the strings "base64.b64decode" and "subprocess.Popen" in the scanned files, these strings are commonly used to encode and execute a reverse shell in python. If the rule finds both of those strings, it will trigger a match.

It's important to note that this is a basic example, and it might need to be fine-tuned and test it in your specific environment to properly detect the base64 encoded python reverse shell.
