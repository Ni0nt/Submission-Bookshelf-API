<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Repository_Overview_0"></a>Repository Overview</h1>
<p class="has-line-data" data-line-start="1" data-line-end="2">This repository contains an API for a bookshelf application. The API allows users to perform various operations on a collection of books, such as adding new books, retrieving books by ID, updating book information, and deleting books.</p>
<h2 class="code-line" data-line-start=3 data-line-end=4 ><a id="File_Summary_3"></a>File Summary</h2>
<h3 class="code-line" data-line-start=5 data-line-end=6 ><a id="handlerjs_5"></a>handler.js</h3>
<p class="has-line-data" data-line-start="6" data-line-end="7">The <code>handler.js</code> file contains the implementation of handler functions used to handle requests in the server. The handler functions included are:</p>
<ul>
<li class="has-line-data" data-line-start="8" data-line-end="9"><code>addBookHandler</code>: Adds a new book to the collection.</li>
<li class="has-line-data" data-line-start="9" data-line-end="10"><code>getAllBooksHandler</code>: Retrieves all books from the collection.</li>
<li class="has-line-data" data-line-start="10" data-line-end="11"><code>getBookByIdHandler</code>: Retrieves a book by the provided ID.</li>
<li class="has-line-data" data-line-start="11" data-line-end="12"><code>updateBookByIdHandler</code>: Updates book information based on the provided ID.</li>
<li class="has-line-data" data-line-start="12" data-line-end="14"><code>deleteBookByIdHandler</code>: Deletes a book by the provided ID.</li>
</ul>
<h3 class="code-line" data-line-start=14 data-line-end=15 ><a id="serverjs_14"></a>server.js</h3>
<p class="has-line-data" data-line-start="15" data-line-end="16">The <code>server.js</code> file serves as the entry point to start the server. It initializes a Hapi server with configurations such as the port, host, and CORS settings. The defined routes from <code>router.js</code> are set on the server using the <code>server.route()</code> method.</p>
<h2 class="code-line" data-line-start=17 data-line-end=18 ><a id="routerjs_17"></a>router.js</h2>
<p class="has-line-data" data-line-start="18" data-line-end="19">The <code>router.js</code> file contains the definitions of routes in the Bookshelf API. Each route consists of an HTTP method, path, and corresponding handler to be called when the route is accessed. The defined routes include:</p>
<ul>
<li class="has-line-data" data-line-start="20" data-line-end="21">Route to add a new book.</li>
<li class="has-line-data" data-line-start="21" data-line-end="22">Route to retrieve all books.</li>
<li class="has-line-data" data-line-start="22" data-line-end="23">Route to retrieve a book by ID.</li>
<li class="has-line-data" data-line-start="23" data-line-end="25">Route to update a book by ID.</li>
</ul>
<h3 class="code-line" data-line-start=25 data-line-end=26 ><a id="booksjs_25"></a>books.js</h3>
<p class="has-line-data" data-line-start="26" data-line-end="27">The <code>books.js</code> file contains an array called <code>books</code> that serves as a storage for book data. The books array is used to store information about the added <code>books</code>. Each book is stored as an object with properties such as ID, name, author, and more.</p>
<h3 class="code-line" data-line-start=28 data-line-end=29 ><a id="Installation_28"></a>Installation</h3>
<p class="has-line-data" data-line-start="29" data-line-end="30">To set up and run the Bookshelf API, follow these steps:</p>
<ol>
<li class="has-line-data" data-line-start="31" data-line-end="32">Clone this repository to your local machine.</li>
<li class="has-line-data" data-line-start="32" data-line-end="33">Install the dependencies by running <code>npm install</code>.</li>
<li class="has-line-data" data-line-start="33" data-line-end="34">Start the server by running <code>npm start</code>.</li>
<li class="has-line-data" data-line-start="34" data-line-end="35">Access the API endpoints using a tool such as Postman or a web browser.</li>
<li class="has-line-data" data-line-start="35" data-line-end="37">For more detailed instructions or additional setup requirements, refer to the project’s documentation or README file.</li>
</ol>
<h3 class="code-line" data-line-start=37 data-line-end=38 ><a id="Contributing_37"></a>Contributing</h3>
<p class="has-line-data" data-line-start="38" data-line-end="39">Contributions to this project are welcome. If you find any issues or would like to suggest improvements, please open an issue or submit a pull request.</p>
<h2 class="code-line" data-line-start=40 data-line-end=41 ><a id="Contact_40"></a>Contact</h2>
<p class="has-line-data" data-line-start="41" data-line-end="42">For any inquiries or further information, you can reach out to the project maintainer at <a href="mailto:arf.setiyanto@gmail.com">arf.setiyanto@gmail.com</a></p>
<h3 class="code-line" data-line-start=44 data-line-end=45 ><a id="License_44"></a>License</h3>
<p class="has-line-data" data-line-start="45" data-line-end="46">This project is licensed under the <em>MIT License</em>.</p>
<p class="has-line-data" data-line-start="47" data-line-end="48"><strong>thank you, Yeah!</strong></p>
