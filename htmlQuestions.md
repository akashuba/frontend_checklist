* **What does a doctype do?**   
  Doctype is required tag it helps browser to understand what kind of document opened. It could be HTML 5, HTML 4.01, XHTML
* **How do you serve a page with content in multiple languages?**  
  There are plenty libraries exist for managing multi language sites, generally it uses set of JSON files, like a dictionary, with constant fields names
  and translations. Then in the project we just use field names.
* **What kind of things must you be wary of when designing or developing for multilingual sites?**   
  The same answer as above. 
* **What are data- attributes good for?**  
  Data attributes helps with add some extra information to elements, and them interact with them in js.
  Could be used by frameworks and test libs. 
* **Describe the difference between <script>, <script async> and <script defer>.**   
    * <script> loaded synchronously and block page parsing until the script will be downloaded and executed.    
    * <script async> didn't stop html parsing but it does during js execution.   
    * <script defer> didn't stop html parsing and execution after html parsing finished, and it also saved the scripts queue.      
* **Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?**.  

  <script defer> could be placed on top of document. 
* **What is progressive rendering?**   
    Progressive rendering is the name given to techniques used to render content for display as quickly as possible.
    General idea is sending data by chunks, prioritize visible part of interface. Using SSR, lazy load. 
* **Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.**   
    One or more strings separated by commas, indicating possible image sources for the user agent to use. It use screen size
    
