### Day - 15th Sep 2015
1. Trying to setup jetty with intellij
2. Thinking of writing a data modelling library for angular( or probably framework agnostic) similar to ember data.
3. Configuring Jetty
	a) unzip the jetty distribution in whatever directory you want( /opt )
	b) in intellij open edit configurations and click on "+" select jetty( local ), then click on configure, this should open a explorer, select the 
	location of jetty distribution, this should auto populate all the details
	c) Go to deployment tab and change the context and select ( webwar: exploded)
	c) Click on run -> name of configuration and you are good to go
4. Resolving dependency issue with javax.servlet 
	a) pres cmd + ; this would open a prompt, select "modules" section 
	b) now go to dependency tab and click on "+" to select the jar/directory to add 
	c) go to jetty's lib folder and select servlet-api.jar 
5. Mapping servlet to url
   a) Add a servlet-mapping section like following
    <servlet-mapping>
        <servlet-name>HelloWorld</servlet-name>
        <url-pattern>/hello</url-pattern>
    </servlet-mapping>
6. In doGet or whatever get the response writer from "response" object 
	ex - response.getWriter().write("Hello World");
		response.getWriter().flush();

### Day - 16th Sep 2015
1. Reading about java's classloader

### Day - 17th Sep 2015
1. Read about class loaders

### Day - 18th Sep 2015
1. Doing CSS today

### Day - 19th Sep 2015
1. Reading about parsing

### Day - 20th Sep 2015
1. Wasted most of the day watching useless stuff
2. Completed a website on codecademy

### Day - 21st Sep 2015
1. Wrote some css @codecademy

### Day - 22nd Sep 2015
1. Wrote some css @codecademy

### Day - 23rd Sep 2015
1. Learning about esprima