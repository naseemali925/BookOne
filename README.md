# BookOne

**A Project Made For Java Assignment**

**Technologies Used**
<ul>
  <li>Servlets</li>
  <li>Java</li>
  <li>JSP</li>
 </ul>
 
 **Direction for use**
 <ol>
	<li>Move to <b>\BookOne\src\java\dit\ReaderServlet.java</b> </li>
  <li>Change the location for the file in which all details will be written</li>
 </ol>
 
 **The change to be done**
 ```java
	 @Override
    public void init() throws ServletException {
        super.init(); //To change body of generated methods, choose Tools | Templates.
        file = new File("C:\\Users\\hp\\Desktop\\books.txt");
    }
```
