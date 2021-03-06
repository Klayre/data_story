<h1>Looker Datastory one-pager</h1>

This basically generates a bunch of cards for each public Look, allowing you to add a title and a description.

<h2>How to</h2>

<p>
  This 'datastory' is created live from a Google Spreadsheet. <a href="https://docs.google.com/spreadsheets/d/1fic861v6Sl5Z8b-Q0RbLIQvOIHRYB2B9LJcw7zQCSg0" target="_blank">Here</a>'s an sample spreadsheet with some public looks.
</p>
<p>
  To use your own data, copy the sample spreadsheet and <a href="https://support.google.com/docs/answer/37579">publish it to the web</a>. Then get the spreadsheet ID (found in the URL: <code>https://docs.google.com/spreadsheets/d/[SPREADSHEET_ID]/edit#gid=0</code>)
</p>
<p>
  You can pass this ID as a URL parameter: <code>?spreadsheet_id=123</code> (<a href="https://docs.google.com/spreadsheets/d/1fic861v6Sl5Z8b-Q0RbLIQvOIHRYB2B9LJcw7zQCSg0">example</a>), or update the spreadsheet ID using the datastory options on the page.
</p>

<h2>Format of the spreadsheet</h2>

There's three expected columns: **title**, **description** and **embed_id**
The first row is the Story title & description (and your instance URL), any row after that renders as a separate card on the story. The 'embed_id' is the public ID given by Looker when you make the Look public (`{{instance_url}}/embed/public/{{look_public_id}}`).


<h2>Demo</h2>

[Try it out here!](https://github.com/Klayre/data_story/blob/master/datastorylooker/index.html)

This story lives in [this spreadsheet](https://docs.google.com/spreadsheets/d/1Zfe9-vwsvKzywPhduXgncFFnR25ra61LUDr5O9nUey8)
