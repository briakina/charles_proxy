# Charles Proxy
This repository contains examples of how I used Charles Proxy during the testing of the [DemoShopping](https://qa.demoshopping.ru/) web application.
1. Traffic interception and modification on a desktop computer ([Recording](https://github.com/briakina/charles_proxy/blob/main/Web%20App%20traffic%20modifying%20-%20Charles%20Proxy.mp4))
   - Changing the number of items in the cart (the request sends "2 items," but "500" is returned).
   - Simulating a situation where the server returns a 403 status code when accessing web app.
   - Redirecting a request from the Prod environment to the QA environment.
2. Traffic interception and modification on an Android smartphone ([Recording](https://github.com/briakina/charles_proxy/blob/main/Web%20App%20traffic%20modifying%20(mobile)%20-%20Charles%20Proxy.mp4))
   - Intercepting and modifying the request to remove an item from the cart.
   - Simulating a situation where the user sees any image in the browser when accessing web app.
   - A screenshot of an intercepted HTTPS request with device information in the user-agent header.
