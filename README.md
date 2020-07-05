# URL-ParamCheck

Check paramaters from url, pass them to firebase to authenticate with.

We are checking the params we can get out of the Smartschool Frames API, see what we can do with them.

Possibilities:

- Username: $UNAME$
- Full Name: $FNAME$
- Internal user number: $INUM$
- User Classes: $CLIST$

example: `<a href="https://www.school.be/scriptje.php?smsID=$INUM$">...</a>`
result: `<a href="https://www.school.be/scriptje.php?smsID=3254">...</a>`

Using https://gomakethings.com/getting-all-query-string-values-from-a-url-with-vanilla-js/ as a guide.
