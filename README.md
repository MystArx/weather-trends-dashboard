git clone https://github.com/your-username/weather-trends-dashboard.git
    cd weather-trends-dashboard
    ```
2.  **Open in your browser:**
    Simply open the `index.html` file in your preferred web browser.
    ```bash
    # Example for opening directly (may have limitations with local file access)
    open index.html
    ```
    *For local development and to avoid potential CORS issues with data loading, it is highly recommended to serve the files using a simple local HTTP server:*
    ```bash
    # Using Python 3 (built-in)
    python -m http.server
    # Then navigate to http://localhost:8000 in your browser
    ```
    ```bash
    # Using npm's http-server (if you have Node.js installed)
    npm install -g http-server
    http-server .
    # Then navigate to http://localhost:8080 (or similar)