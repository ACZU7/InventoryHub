# InventoryHub Reflection

In this project, I used Microsoft Copilot to help build and improve InventoryHub, a full-stack inventory management system using a Blazor front-end and a Minimal API back-end.

Copilot helped generate the initial integration code by suggesting how to use HttpClient in Blazor to call the back-end API and deserialize the JSON response into a Product class. This made it easier to connect the front-end and back-end and display product details in the browser.

During debugging, Copilot helped identify and resolve issues such as incorrect API routes, CORS restrictions, and malformed JSON responses. I updated the front-end route from /api/products to /api/productlist, added CORS support in the Minimal API, and included try-catch blocks to handle API and JSON errors more safely.

Copilot also assisted in structuring the JSON response by adding a nested category object for each product. This improved the quality of the API response and made the data more realistic and organized.

For performance optimization, Copilot suggested reducing unnecessary API processing by using caching in the back-end. I added memory caching so the product list can be reused instead of being recreated on every request. This helps reduce server load and improves efficiency.

One challenge I faced was making sure the JSON structure from the API matched the Product class in the Blazor application. Copilot helped by suggesting matching model classes and using case-insensitive JSON deserialization.

Overall, I learned how to use Copilot effectively as a development assistant for full-stack projects. It helped me generate code faster, debug common integration problems, improve JSON structure, and apply simple performance optimizations while still requiring me to test and understand the code myself.
