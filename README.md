# Skills Network Graph

## Notes



HTML files need to be accessed in a server environment to load local JSON files. If you try to open the HTML file locally, the browser will block this action for security reasons.

## Installation

To run the project, follow these steps:

1. Install Node.js and npm.

2. `sudo npm install -g http-server`
3. Navigate to the project directory. `cd dir`
4. Start the server.  `http-server`
5. Visit `localhost` in your browser to access the Skills Network Graph.

## Troubleshooting

If you make changes to the JSON file and the updates are not reflected when you refresh the page, you may need to force the browser to ignore the cached version. Here are a few methods you can try:

1. Force Refresh: Press `Ctrl + Shift + R` (Windows / Linux) or `Command + Shift + R` (Mac) in your browser to perform a force refresh. This will ignore the cache and reload all files.

2. Clear Browser Cache in your browser settings.

3. Modify the URL or Add Query Parameters: Add a query parameter to the URL, such as `?version=123`, to ensure that the URL is different each time you access it. This will force the browser to reload the file without using the cache.

These methods should help you view the updated JSON file when you refresh the page.