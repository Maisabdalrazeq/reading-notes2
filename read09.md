# Welcome to the read09 page ..

**forms in HTML..**

*HTML Forms are required, when you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name, email address, credit card.*

*A form will take input from the site visitor and then will post it to a back-end application such as CGI, ASP Script or PHP script etc. The back-end application will perform required processing on the passed data based on defined business logic inside the application.*

*There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes.*
 
**How To Creat form in html?**

**Example:**

`<'form action = "Script URL" method = "GET|POST">
   form elements like input, textarea etc.
<'/form>`

**HTML Form Controls**

***There are different types of form controls that you can use to collect data using HTML form:***

- Text Input Controls
- Checkboxes Controls
- Radio Box Controls
- Select Box Controls
- File Select boxes
- Hidden Controls
- Clickable Buttons
- Submit and Reset Button

![img](https://mobile.htmlgoodies.com/imagesvr_ce/1902/HTML%20Form.PNG)

**Tables in HTML..**

*The HTML tables allow web authors to arrange data like text, images, links, other tables, etc. into rows and columns of cells.*

*The HTML tables are created using the <'table> tag in which the <'tr> tag is used to create table rows and <'td> tag is used to create data cells. The elements under <'td> are regular and left aligned by default*

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcR35MfzclfmlMxJ7d7drfjF6l-AcwW4xiipig&usqp=CAU)

**How to creat table in HTML?**

**Example:**

`<table>`

  `<tr>`

    `<th>Month</th>`

    `<th>Savings</th>`

  `</tr>`

  `<tr>`

    `<td>January</td>`

    `<td>$100</td>`

  `</tr>`

`</table>`

**Lists In HTML..**

*HTML offers web authors three ways for specifying lists of information. All lists must contain one or more list elements. Lists may contain :*

1. `<ul>` − An unordered list. This will list items using plain bullets.

2. `<ol>` − An ordered list. This will use different schemes of numbers to list your items.

3. `<dl>` − A definition list. This arranges your items in the same way as they are arranged in a dictionary.

![IMG](https://ways2web.weebly.com/uploads/5/4/4/8/54485903/8033093_orig.png)


 **Events in JavaScript..**

*Events are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them in some way if desired. For example, if the user selects a button on a webpage, you might want to respond to that action by displaying an information box.*

**Ways of using web events..**

- Event handler properties.
*The onclick property is the event handler property being used in this situation. It is essentially a property like any other available on the button ( btn.textContent, or btn.style), but it is a special type — when you set it to be equal to some code, that code is run when the event fires on the button.*

**Example:**

`const btn = document.querySelector('button');`

`function bgChange() {`
 ` const rndCol = 'rgb(' + random(255) + ',' + random(255) + ',' +`
 `random(255) + ')';`
 ` document.body.style.backgroundColor = rndCol;`
`}`

`btn.onclick = bgChange;`


- addEventListener() and removeEventListener().

*The newest type of event mechanism is defined in the Document Object Model (DOM) Level 2 Events Specification, which provides browsers with a new function — addEventListener(). This functions in a similar way to the event handler properties, but the syntax is obviously different.*

**Example:**

`document.getElementById("myBtn").addEventListener("click", function() {`
  `document.getElementById("demo").innerHTML = "Hello World";});`

  ![img](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events.png)

