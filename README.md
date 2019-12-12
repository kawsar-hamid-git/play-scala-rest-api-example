<strong>This tutorial teaches the basics of building a web API with the Scala Play Framework.</strong>

In this tutorial, you learn how to:

<ul>
<li> Create a web API project.</li>
<li> Add a model class and a database context.</li>
<li> Create a controller with CRUD methods.</li>
<li> Configure routing, URL paths, and return values.</li>
<li> Call the web API with Postman.</li>
<li> In the end, you have a web API that can manage "to-do" items stored in a database. </li>
</ul>

<strong>Overview</strong>

This tutorial creates the following API:

<table>
	<thead>
		<tr>
			<th>API</th>
			<th>Description</th>
			<th>Request body</th>
			<th>Response body</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>GET /api/todos</td>
			<td>Get all to-do items</td>
			<td>None</td>
			<td>An array of to-do items</td>
		</tr>
		<tr>
			<td>GET /api/todos/{id}</td>
			<td>Get an item by ID</td>
			<td>None</td>
			<td>To-do item</td>
		</tr>
		<tr>
			<td>POST /api/todos/add</td>
			<td>Add a new item</td>
			<td>To-do item</td>
			<td>To-do item</td>
		</tr>
		<tr>
			<td>PUT /api/todos/{id}</td>
			<td>Update an existing item</td>
			<td>To-do item</td>
			<td>None</td>
		</tr>
		<tr>
			<td>DELETE /api/todos/{id}</td>
			<td>Delete an item</td>
			<td>None</td>
			<td>None</td>
		</tr>
	</tbody>
</table>

<p>The following diagram shows the architecture of the app.</p>
<br />
<img src="https://ixorasolution.com/images/blog_images/53/b2ap3_thumbnail_scala-rest-api-architecture.jpg" />
<br/>

<p><strong>Prerequisites</strong></p>
<ul>
<li>SBT 1.3.3</li>
<li>Scala 2.13.0</li>
<li>Play Framework</li>
</ul>

<p>
<a href="https://ixorasolution.com/blog/how-to-build-rest-api-with-scala-play-framework-1">Click Here</a> for full documentation.
</p>
