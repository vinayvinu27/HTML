# HTML
<!DOCTYPE html>
<html>

<head>
    <title>My frist web site</title>
    <meta name="UTF-8">
    <meta name="Description" content="Free HTML course for begnners">
    <meta name="keywords" content="HTML,begnners,course">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <!-- <meta http-equiv="refresh" content="2"> -->
</head>

<body>
    <h1>This my frist web site</h1>
    <hr>
    <h1>Hello world</h1>
    <br>
    <video controls autoplay src="https://www.youtube.com/watch?v=qswIMbzyLQw&t=0s"></video>
    <br>
    <br>
    <audio autoplay controls loop muted src="Ice & Fire - King Canyon.mp3"></audio>
    <h2>Hello world</h2>
    <br>
    <a href="https://www.google.com" target=_self title="This will take to google">google
        <br>

    </a>
    <h3>Hello world</h3>
    <br>
    <a href="https://www.google.com">
        <img src="img.jpg" height="300" alt="this picture" title="this will take u to google">
    </a>
    <h4>Hello world</h4>
    <br>
    <h5>Hello world</h5>
    <br>
    <h6>Hello world</h6>
    <br>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab, tempore dignissimos ad numquam eius, molestias
        corrupti nostrum similique facere cumque impedit totam sit laudantium nesciunt fuga temporibus quod porro.
        Perferendis, alias cupiditate! Amet, animi!</p>

    <p>This is normal text</p>
    <p>This is <b>Bold</b> text</p>
    <p>This is <i>Italic</i> text</p>
    <p>This is <big>big</big> text</p>
    <p>This is <small>small</small> text</p>
    <p>This is <sub>subscript</sub> text</p>
    <p>This is <sup>superscript</sup> text</p>
    <p>This is <ins>insert</ins> text</p>
    <p>This is <del>delete</del> text</p>
    <p>This is <mark>mark</mark> text</p>

    <h1>Unordered list</h1>
    <ul>
        <li>pizza dough</li>
        <li>tomato sauce</li>
        <li>cheese</li>
        <li>topping
            <ul>
                <li>pepperoni</li>
                <li>mushrooms</li>
                <li>peppers</li>
            </ul>
        </li>
    </ul>
    <br>
    <h1>Ordered list</h1>
    <ol type="A">
        <li>eat breakfast</li>
        <li>take shower</li>
        <li>leave for work</li>
    </ol>
    <br>
    <h1>Description List</h1>
    <dl>
        <dt>HTML</dt>
        <dd>This adds structure to a webpage</dd>
        <dt>CSS</dt>
        <dd>This adds style to a webpage</dd>
    </dl>
    <br>
    <h1>Creating table </h1>
    <table bgcolor="black" width="700">
        <tr bgcolor="gray">
            <th width="100">Sunday</th>
            <th width="100">Monday</th>
            <th width="100">Tuesday</th>
            <th width="100">Wedbesday</th>
            <th width="100">Thursday</th>
            <th width="100">Friday</th>
            <th width="100">Saturday</th>
        </tr>
        <tr bgcolor="lightgray" align="center">
            <td>Closed</td>
            <td>9-5</td>
            <td>9-5</td>
            <td>9-5</td>
            <td>9-5</td>
            <td>9-5</td>
            <td>Closed</td>
        </tr>
    </table>
    <br>
    <h1 style="background-color:black; color:green">Coloring the text </h1>
    <h1 style="color:red">Hello</h1>
    <h1 style="color:rgb(66, 245, 245)">Hello</h1>
    <h1 style="color : #0cf01b">Hello</h1>
    <p style="background-color:black; color:wheat">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nobis
        debitis minima suscipit perferendis minus autem
        iusto, aspernatur corporis soluta laboriosam, neque dolore tempora quisquam.</p>
    <br>
    <hr>
    <h1>Span = adds markup to text or portion of a document</h1>
    <hr>
    <h1>div = defines a division of a document</h1>
    <h1>hello</h1>
    <div style="background-color:black; color:aliceblue">
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorem eum, fuga accusamus odio quasi laborum esse
            asperiores rerum, dolor mollitia unde adipisci totam nam.</p>
        <p><span style="color:#0cf01b">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</span> Dolorem eum,
            fuga accusamus odio quasi laborum esse asperiores rerum, dolor mollitia unde adipisci totam nam.</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorem eum, fuga accusamus odio quasi laborum esse
            asperiores rerum, dolor mollitia unde adipisci totam nam.</p>
    </div>
    <br>
    <h1>About meta data</h1>
    <br>
    <h1>About Iframe</h1>
    <h1>iframe = embed content from another source into an HTML document</h1>
    <dd>
        <h1>ex. used for ads, Used in many hacking techinques.</h1>
    </dd>
    <h1>By using iframe we can post ads and post inside the web page</h1>
    <iframe src="img.jpg" width="250" height="300" style="border:0"></iframe>
    <br>
    <br>
    <iframe src="https://www.bing.com" width="500"></iframe>
    <br><br>
    <h1>Creating button</h1>
    <a href="https://www.google.com">
        <button style="background-color: black;color:#0cf01b; border-radius:10px">
            <h1>Click me</h1>
        </button>
    </a>
    <h1>Other way of buttton</h1>
    <button onclick="doSomething()" style="background-color: black;color:#0cf01b; border-radius:10px">
        <h1>Click me</h1>
    </button>
    <h1 id="test">Hello guys!</h1>
    <br><br>
    <h1>creating Forms</h1>
    <form action="">
        <div>
            <label for="fname">Frist Name </label>
            <input type="text" id="fname" name="fname" placeholder="Enter Name" required>
        </div>
        <div>
            <label for="lname">Last Name </label>
            <input type="text" id="lname" name="lname" placeholder="Enter lastName" required>
        </div>
        <div>
            <label for="pname">Password Name </label>
            <input type="password" id="pname" name="pname" placeholder="Enter Password" maxlength="8" required>
        </div>
        <div>
            <label for="email">email  </label>
            <input type="email" id="email" name="email" placeholder="Enter Email ID" required>
        </div>
        <div>
            <label for="phone"> Phone No </label>
            <input type="tel" id="phone" name="phone" placeholder="Enter phone Number" required>
        </div>
        <div>
            <label for="date">Date  </label>
            <input type="date" id="data" name="data"  required>
        </div>
        <br>
        <div>
            <input type="submit">
            <input type="reset">
        </div>
        <div>
            <label for="payment">payment</label>
            <select name="payment" id="payment">
                <option value="visa">visa</option>
                <option value="Mastercard">Mastercard</option>
                <option value="giftcard">giftcard</option>
            </select>
        </div>
        <br>
        <div>
            <label for="title">title:</label>
            <br>
            <label for="Mr." >Mr. </label>
                <input type="radio" id="Mr." name="title" value="Mr.">
           
            <label for="Mrs.">Mrs.</label>
            <input type="radio" id="Mrs." name="title" value="Mrs.">
            <label for="phD." >phD.</label>
            <input type="radio" id="phD." name="title" value="phD.">
        </div>
        <br>
        <div>
            <label for="Check box">Check Box</label>
            <input type="checkbox">
        </div>
      
        <!-- <div>
            <input type="submit">
        </div> -->
    </form>
    <br>

    <script>
        function doSomething() {
            document.getElementById("test").innerHTML = "GoodBye Guys@"
        }
    </script>
</body>

</html>
