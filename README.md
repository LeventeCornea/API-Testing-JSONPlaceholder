# 🔗 Postman API Testing – JSONPlaceholder

This project contains **API testing performed in Postman** using the public API:  
https://jsonplaceholder.typicode.com  

It validates GET, POST, PUT, and DELETE endpoints with **test scripts written in the "Scripts → Post-request" section**, which run automatically after the response is received. The tests check status codes, response structure, and required fields (`id`, `title`, `body`, `userId`).  

Tools: Postman, JavaScript (for test scripts), Git & GitHub.  

All test requests are included in the collection file: 
`collections/JSONPlaceholder API Testing Project – Levente Cornea.postman_collection.json
Test results can be viewed in Postman's **Test Results** panel after executing the requests. Screenshots or observations can be added to the README to showcase results.

## ⚙️ CI/CD Integration

This project includes a **GitHub Actions workflow** that automatically validates the Postman collection setup on each push or pull request.  
The workflow file is located at:
.github/workflows/ci.yml

The pipeline:
- Sets up the Node.js environment.  
- Verifies the presence and structure of the Postman collection.  
- Confirms that the repository is ready for automated API testing integration.  
- Displays results directly in the **Actions** tab on GitHub.
  

**Author:** Levente Cornea
