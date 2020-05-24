<h1> API-sample </h1>

<h2>The Application</h2>
Just an example of 6 API End Points that allows to Create, Read, Update and Delete resources.  <strong>(.NET Core 3.1)</strong>
<br><br>
<div>
<h2>End Points</h2>
<table style="width:100%">
  <tr>
    <th>URI</th>
    <th>Verb</th>
    <th>Operation</th>
    <th>Description</th>
    <th>Success</th>
     <th>Failure</th>
  </tr>
  <tr>
    <td>/api/commands</td>
    <td>GET</td>
    <td>READ</td>
    <td>Read all resources</td>
    <td>200 OK</td>
    <td>400 Bad Request<br> 404 Not Found</td>
  </tr>
  <tr>
    <td>/api/commands/{id}</td>
    <td>GET</td>
    <td>READ</td>
    <td>Read a single resource</td>
    <td>200 OK</td>
    <td>400 Bad Request<br> 404 Not Found</td>
  </tr>
  <tr>
    <td>/api/commands</td>
    <td>POST</td>
    <td>CREATE</td>
    <td>Create a new resource</td>
    <td>201 Created</td>
    <td>400 Bad Request<br> 405 Not Allowed</td>
  </tr>
   <tr>
    <td>/api/commands/{id}</td>
    <td>PUT</td>
    <td>UPDATE</td>
    <td>Update an entire resource</td>
    <td>204 No Content</td>
    <td>...</td>
  </tr>
  <tr>
    <td>/api/commands/{id}</td>
    <td>PATCH</td>
    <td>UPDATE</td>
    <td>Update partial resource</td>
    <td>204 No Content</td>
    <td>...</td>
  </tr>
  <tr>
    <td>/api/commands/{id}</td>
    <td>DELETE</td>
    <td>DELETE</td>
    <td>Deletes a single resource</td>
    <td>200 OK<br>204 No Content</td>
    <td>...</td>
  </tr>
</table>
</div>

<h2>Application Architecture</h2>
<img src="/images/ApplicationArchitecture.PNG">

<h2>Technology Utilized</h2>
<ul>
  <li>MVC</li>
  <li>REST</li>
  <li>Repository Pattern</li>
  <li>Dependency Injection</li>
  <li>Entity Framework</li>
  <li>Data Transfer Objects (DTOs)</li>
  <li>AutoMapper</li>
</ul>

<h2>Used Packages</h2>
<ul>
  <li><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/5.0.0-preview.4.20220.10">Microsoft.EntityFrameworkCore</a></li>
  <li><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/5.0.0-preview.4.20220.10">Microsoft.EntityFrameworkCore.Design</a></li>
  <li><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/5.0.0-preview.4.20220.10">Microsoft.EntityFrameworkCore.SqlServer</a></li>
  <li><a href="https://www.nuget.org/packages/AutoMapper.Extensions.Microsoft.DependencyInjection/">AutoMapper.Extensions.Microsoft.DependencyInjection</a></li>
  <li><a href="https://www.nuget.org/packages/Microsoft.AspNetCore.Mvc.NewtonsoftJson/5.0.0-preview.4.20257.10">Microsoft.AspNetCore.Mvc.NewtonsoftJson</a></li>
  <li><a href="https://www.nuget.org/packages/Microsoft.AspNetCore.JsonPatch/5.0.0-preview.4.20257.10">Microsoft.AspNetCore.JsonPatch</a></li>
</ul>

