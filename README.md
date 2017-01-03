<!DOCTYPE html>
<html>
  <head>
    <title>Timestamp Microservice</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
    </head>
   <body>
   <div class="container">
    <h1 class="header">Timestamp Microservice</h1>
    <img src="https://avatars0.githubusercontent.com/tomzurales?&amp;s=128">
    <h3>By: Tom Zurales</h3>
    <blockquote>
      <h4>User Stories</h4>
      <ul>
        <li> I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016).<br><br></li>
        <li> If it does, it returns both the Unix timestamp and the natural language form of that date.<br><br></li>
        <li>If it does not contain a date or Unix timestamp, it returns null for those properties.</li>
      </ul>
      </blockquote>
        <h2>Example Usage:</h2>
          <h4>Request:</h4><code>https://morning-savannah-26026.herokuapp.com/December%2015,%202016<br></code>
          <code>https://morning-savannah-26026.herokuapp.com/1450137600<br></code>
          <h4>Response:</h4><code>{ "unix": 1483424738, "natural": "January 3, 2017" }</code></p></div></body></html>
