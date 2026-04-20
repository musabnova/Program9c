# Program 9c - Session Tracking using URL Rewriting

## Objective
Develop a program to demonstrate session tracking using URL rewriting in JSP.

## Files
- index.html
- second.jsp
- welcome.jsp

## Source Code
- HTML: https://github.com/musabnova/Program9c/blob/master/src/main/webapp/index.html
- JSP 1: https://github.com/musabnova/Program9c/blob/master/src/main/webapp/second.jsp
- JSP 2: https://github.com/musabnova/Program9c/blob/master/src/main/webapp/welcome.jsp

## Concept Used
- JSP
- URL Rewriting
- Request parameters
- Session tracking without cookies

## How it Works
1. User enters name in index.html
2. Data is passed in URL to second.jsp
3. URL rewriting is used to send data to next page
4. welcome.jsp displays the final output

## How to Run
1. Deploy project on Apache Tomcat
2. Open:
   http://localhost:8080/Program9c/
3. Enter data and submit
4. Observe URL containing parameters

## Output

### Input Page
<img src="https://github.com/musabnova/Program9c/blob/master/1.png" width="400"/>

### URL Rewriting Page
<img src="https://github.com/musabnova/Program9c/blob/master/2.png" width="400"/>

### Final Output Page
<img src="https://github.com/musabnova/Program9c/blob/master/3.png" width="400"/>

## Result
Session tracking is successfully demonstrated using URL rewriting.
