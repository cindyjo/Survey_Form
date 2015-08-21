# Survey Form

An application that has the form for the user to fill out
- server render views/index.ejs
- user fills out the form and submits
- The submitted form gets sent to /result
- The server recognizes when someone posts things to /result, grabs information from the POST, and sends the POST data back as its renders views/results.ejs