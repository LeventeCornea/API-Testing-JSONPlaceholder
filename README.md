# 🔗 Postman API Testing – JSONPlaceholder

This project contains **API testing performed in Postman** using the public API:  
https://jsonplaceholder.typicode.com  

It validates GET, POST, PUT, and DELETE endpoints with **test scripts written in the "Scripts → Post-request" section**, which run automatically after the response is received. The tests check status codes, response structure, and required fields (`id`, `title`, `body`, `userId`).  

Tools: Postman, JavaScript (for test scripts), Git & GitHub.  

All requests are organized in the **collection file** located in the `collections` folder:  
Test results can be viewed in Postman's **Test Results** panel after executing the requests. Screenshots or observations can be added to the README to showcase results. Future CI/CD integration using GitHub Actions will automate these API tests.

**Author:** Levente Cornea
