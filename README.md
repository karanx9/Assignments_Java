# Evaluation_submission_karansoni

Project title = Cypress

Name = Karan Soni

Description : Difference Between Selenium and Cypress Advantages of using cypress for web App Testing Explain the architecture of cypress.


1) Differences between Selenium and Cypress:

Selenium:

Multi-language support (Java, Python, C#, etc.)
Supports multiple browsers
Executes tests outside the browser

Cypress:

JavaScript-based only
Runs inside the browser
Provides real-time reloading
Built-in waiting mechanisms
Simpler setup and faster execution


2) Advantages of using Cypress for web app testing:

a) Ease of setup: Cypress is easier to set up compared to Selenium.
b) Fast execution: Tests run faster as Cypress operates directly in the browser.
c) Real-time reloading: Changes to tests are immediately reflected, speeding up the development process.
d) Automatic waiting: Cypress automatically waits for elements to be ready, reducing the need for explicit waits.
e) Time-travel debugging: Cypress takes snapshots at each step, allowing you to see exactly what happened at each stage of your test.
f) Consistent results: Cypress architecture leads to fewer flaky tests compared to Selenium.
g) Excellent documentation: Cypress provides comprehensive and well-organized documentation.
h) Modern JavaScript stack: Uses modern JavaScript, making it appealing to front-end developers.

3) Architecture of Cypress:

a) Browser-based: Unlike Selenium, which operates outside the browser, Cypress runs directly inside the browser. This allows it to have native access to everything happening in your application.
b) Node.js server process: Cypress uses a Node.js process to:

Manage the test environment
Perform network operations
Execute system commands

c) Direct control: Cypress can directly control the browser, giving it more reliable control over the application under test.
d) No serialization: There's no need for serialization of commands over a network, which is a common source of flakiness in Selenium tests.
e) Same loop: Both the test code and application code run in the same run loop, allowing Cypress to respond to application events in real-time.
f) Execution model:

Commands are enqueued and run asynchronously
Automatic retries and waits are built into the command execution

g) Plugins: Cypress has a plugin architecture that allows extending its functionality.
