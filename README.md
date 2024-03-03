<h1>Nodejs API with mongoDB</h1>
<p>This is a rest api  for creating ,finding students  for a school.</p>
<h1> Installation </h1>
1.clone repository<br>
git clone https://github.com/jenifferakinyi/StudentApi<br>
2.install dependancies<br>
cd NODE  <br>
npm install <br>
3.Build and run project <br>
npm start <br>
4.Navigate to: http://localhost:4000
<h1>Project Structure</h1>
<table>
<tr>
<th>Name</th>
<th>Description</th>
</tr>
<tr>
<td>auth.js</td>
<td>Contains the schema authentication for email and password and generated keys for data protection</td>
</tr>
<tr>
<td>Controllers</td>
<td>Controllers define functions to serve various express routes.</td>
</tr>
<tr>
<td>helpers</td>
<td>contains the mongoDB connection and jsonwebtokens</td>
</tr>
<tr>
<td>model</td>
<td>Models define schemas that will be used in storing and retrieving data from Application database</td>
</tr>
<tr>
<td>routes</td>
<td>Defines the routes endpoint</td>
</tr>
<tr>
<td>index.js</td>
<td>Entry point to express app</td>
</tr>
</table>
