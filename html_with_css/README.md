CSS can be either in-line, where you describe element characteristics right in the tag:

<p style="color: blue;">This is blue text</p>

internal, where you write CSS contents inside of your literal HTML (crazy):

```
<!DOCTYPE html>
<html>
    <head>
        <style>
            p {
                color: blue;
            }
        </style>
    </head>
    <body>
        <p>This is blue text</p>
    </body>
</html>
```

or as a separate file with all style data, which you need to connect to HTML in order
for it to be used. This is the variant which will be used in this document
