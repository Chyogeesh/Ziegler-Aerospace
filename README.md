# Ziegler-Aerospace
It is a internship assignment
Here’s a solution guide to complete the performance testing, functional testing, responsive, and resolution testing of the provided URL https://demoqa.com/. I'll break down the test cases, along with code snippets, testing strategy, and reporting instructions.

1. Test Cases and Functional Testing
Create test cases for navigating through different sections of the website such as “Forms,” “Widgets,” and “Interactions.” Here are some sample test cases:
2. Responsive and Resolution Testing
Test across multiple devices and resolutions, either manually or using tools like Chrome DevTools or BrowserStack. Here’s a recommended checklist:

Resolutions: 1920x1080, 1366x768, 768x1024, 360x640
Browsers: Chrome, Firefox, Safari, Edge
Responsive Behavior:
Menu collapses into a mobile-friendly format on smaller screens.
Buttons and Inputs are accessible and readable on all screen sizes.
Content is scrollable without horizontal overflow.
3. Load and Stress Testing
Using JMeter, we can set up a load and stress test as described:
4. Performance Monitoring and Analysis
Metrics to Track:

Response Time: Track the response time for each request under both load and stress testing.
Error Rate: Note any failures during testing.
Throughput: Record the requests per second handled by the server.
CPU/Memory Usage: Monitor the server’s CPU and memory usage if accessible.
Expected Outcomes:

Load Testing: The site should maintain consistent response times with minimal latency.
Stress Testing: There may be an increase in response time as the load reaches higher levels, but the application should remain stable.
5. Test Report Format (Excel)
Here’s a suggested Excel format to document test cases, performance data, and observations:

Section	Metric	Value	Observation
Functional Testing			
Test Case ID			
TC-001	Expected Outcome	Actual Outcome	Pass/Fail
Performance Testing			
Load Test	Avg. Response Time	[Enter Value] ms	Average response for 100 users over 10 min
Stress Test	Avg. Response Time	[Enter Value] ms	Highest sustainable load observed
Stress Test	Error Rate	[Enter Value]%	Percentage of errors observed during peak load
Stress Test	CPU Usage	[Enter Value]%	Server’s average CPU usage during stress testing
Responsive Testing			
Device/Resolution			Observations (e.g., text overlaps, buttons not clickable)
Load Test Summary: Attach response time graph and table generated by JMeter.
Stress Test Summary: Include a graph showing response times, errors, and CPU/memory usage trends over time.
Submission Links:
Netlify URL: <Enter URL>
Admin Login Credentials: <Enter credentials>
GitHub Repository: <Enter repo link>
Demo Video/Proof: <Link to video or screenshots>
