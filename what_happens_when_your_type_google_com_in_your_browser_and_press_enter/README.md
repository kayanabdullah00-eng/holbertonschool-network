# What Happens When You Type `https://www.google.com` in Your Browser and Press Enter?

This project explains what happens behind the scenes when a user types `https://www.google.com` into a web browser and presses `Enter`.

The goal is to understand the complete request flow from the browser to the server and back to the user.

## Topics Covered

The project covers the following concepts:

- DNS resolution
- TCP/IP connection
- Firewall
- HTTPS / SSL / TLS
- Load balancer
- Web server
- Application server
- Database
- Browser rendering

## Request Flow

The general flow of the request is:

`Browser → DNS → TCP/IP → Firewall → HTTPS/TLS → Load Balancer → Web Server → Application Server → Database → Response → Browser`

## Files

### `0-blog_post`

Contains the URL to the published blog post explaining what happens when typing:

`https://www.google.com`

in a browser and pressing `Enter`.

### `1-what_happen_when_diagram`

Contains the URL to a diagram illustrating the complete request flow.

The diagram includes:

- DNS resolution
- Server IP and port 443
- Encrypted HTTPS traffic
- Firewall
- Load balancer
- Web server
- Application server
- Database
- Response back to the browser

## Diagram

The diagram visually represents the complete communication process between the user's browser and the web infrastructure.

It shows how the browser first resolves the domain name using DNS, establishes a TCP/IP connection, communicates securely using HTTPS/TLS, passes through a firewall and load balancer, and finally reaches the web server, application server, and database.

The response is then returned to the browser and rendered as a web page.

## Repository

GitHub repository:

`holbertonschool-network`

Directory:

`what_happens_when_your_type_google_com_in_your_browser_and_press_enter`

## Author

Holberton School Network Project
