# WebSeries-Backend
 
<h2>Obective</h2>
<p>Springboot app to implement an api that returns a list of objects according to the query</p>
<h2>Requirement</h2>
<p>This app must produce data (JSON object) as per the following crioteria:
  <ul>
    <li>card data, available statically on frontend for now</li>
    <li>search data , for when series search bar is implemented</li>
    <li>filtered data, as per selected category</li>
  </ul>
</p>
<h2>Stack</h2>
<ul>
  <li>Java8 along with spring framework</li>
  <li>Maven for build automation and dependency management</li>
  <li>Data Source (currently no database initialised, so extracting data from predefined json file)</li>
  <li>Possible noSQL DB option is MongoDB</li>
</ul>
<h2>Recommended IDE's</h2>
<ol>
  <li>IntelliJ licenced version(or free version)</li>
  <li>VSCode</li>
  <li>STS</li>
</ol>
<h2>Deployment</h2>
<p>As the UI is deployed as a static side, server side scripting is incompatible.</p>
<p>For now this application acts as a decoupled webservice</p>
<p>Options for deployment:
  <ul>
    <li>Firebase.io</li>
    <li>Heroku</li>
  </ul>
</p>
