# YARA_Rules
Collection of YARA rules to find evil

## Webshell Yara rule
The webshell yara rule can be used with the Generic.Detection.Yara.Glob Velociraptor artefacts.
Please make sure, that you used the following extension to check: \.(php|aspx|asp|asmx|jsp)$

If you really want to get some false/positives, you can also add js to the list. This will trigger a lot in user profiles because of cached js files and they are usually false/positive.
