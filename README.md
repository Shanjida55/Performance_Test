# Overview
This repository contains performance tests for an API that offers four key features: creating a booking, retrieving booking details, updating booking information, and deleting a specific booking. The tests are conducted using HTTP requests, including POST, GET, PUT, and DELETE.

# Testing Workflow
## 1. Create Booking:
-Perform a POST request to create a booking.
-Extract the booking ID from the JSON response using a JSON Extractor.
## 2. Retrieve Booking Details:
-Use the booking ID obtained from the creation step in a GET request.
-Measure the performance of retrieving booking details.
## 3. Update Booking Information:
-Utilize the booking ID and a token generated during the initial POST request.
-Perform a PUT request to update specific booking details.
-Use a JSON Extractor to handle the response.
## 4. Delete Booking:
-Use the booking ID created in the first step.
-Employ the token from the initial POST request.
-Execute a DELETE request to remove a specific booking.
# Performance Measurement
-Utilize JMeter's various listeners to capture performance metrics, including response times, throughput, and error rates.
-Analyze the performance data to identify potential bottlenecks and areas for improvement.

# Conclusion
This performance testing exercise provides valuable insights into the responsiveness and efficiency of the customer CRUD operations. The results can be used to optimize the API and enhance the overall user experience.

# Instructions for Running Tests
-Clone the repository.
-Open the JMeter project file.
-Configure test parameters and variables as needed.
-Run the tests and monitor the performance metrics in various listeners.



