<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <!--the next 3 meta elements are used by search engines to index your site with the right info -->
  <meta name="description" content="This Is a Basic Site Designed Using HTML">
  <meta name="keywords" content="HTML">
  <meta name="author" content="Tumelo Rahlau">
  <title>🚩Tumelo's Personal Site</title>
</head>

<body>
  <!-- below table allows you to put the picture in one cell and the text in the other cell -->
  <!-- cellspacing allows for space between the picture and the text -->
  <table cellspacing="20">
    <tr>
      <td>
        <!-- you can add an image from a site by getting an image source link or just upload an image on your HTML project file -->
        <img src="image/me.png" alt="Tumelo's Profile Pic">
      </td>
      <td>
        <h1>Tumelo Rahlau</h1>
        <!-- it's good practice to use "em" instead of "i" for italics -->
        <!-- it's good practice to use "strong" instead of "b" for bold -->
        <p><em>Founder and CEO of <strong><a href="https://www.linkedin.com/feed/">FATURA Group</a>.</strong></em></p>
        <p>I am an iOS and Web Developer. I love the gym and Telecoms networking is my hobby</p>
      </td>
    </tr>
  </table>

  <hr>

  <h3>Education</h3>
  <!-- "ul" and "li" enables you to create bullet points -->
  <ul>
    <li>Mokgome S. School</li>
    <li>Cida City Campus</li>
  </ul>

  <hr>

  <h3>Work Experience</h3>
  <table cellspacing="10">
    <!-- tables have table headers "thead", table footers "tfoot" and table body "tbody" -->

    <!-- within a table you create table rows and table cells
    "tr" this creates a table row
    "td" this creates a table cell within a table row -->

    <thead>
      <!-- inside table headers, you can  create table header cells "th" -->
      <tr>
        <th>Dates</th>
        <th>Work</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2000-2006</td>
        <td>IT Engineer at MTN Business</td>
      </tr>
      <tr>
        <td>2006</td>
        <td>IT Engineer at Vodacom Business</td>
      </tr>
    </tbody>
  </table>

  <hr>

  <h3>Skills</h3>
  <!-- this table does hot have table headings -->
  <table cellspacing="10">
    <tr>
      <td>Business Administration</td>
      <td>✅✅</td>
    </tr>
    <tr>
      <td>IT Networking</td>
      <td>✅✅✅✅✅</td>
    </tr>
    <tr>
      <td>Web Development</td>
      <td>✅✅✅</td>
    </tr>
    <tr>
      <td>Drawing</td>
      <td>✅</td>
    </tr>
  </table>

  <hr>

  <h3>Activities</h3>
  <!-- this creates nested tables, example this is 2 tables within a table-->
  <table cellspacing="10">
    <tr>
      <td>
        <table>
          <tr>
            <td>Tennis</td>
            <td>✅✅</td>
          </tr>
          <tr>
            <td>Soccer</td>
            <td>✅✅✅</td>
          </tr>
        </table>
      </td>
      <td>
        <table>
          <tr>
            <td>Cricket</td>
            <td>✅✅✅✅</td>
          </tr>
          <tr>
            <td>Swimming</td>
            <td>✅</td>
          </tr>
        </table>
      </td>
    </tr>
  </table>

  <hr>

  <a href="hobbies.html">My Hobbies</a></h3>
  <a href="contact-me.html">Contact Me</a></h3>

</body>

</html>
