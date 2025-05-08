# Load Test StreamTube
StreamTube is a video-sharing web application that was built using Django Framework. Django Rest framework is used to develop API endpoints. The application was hosted in a render web hosting platform.

## Testing Setup
To check performance, Apache JMeter is used and ran tests on a cloud hosting. 
- Thread Count: Ranging from 100 to 6000, simulating different numbers of users.
- Ramp-Up Time: 120 seconds, gradually increasing the load.
- Duration: 120 seconds per test for consistency.

## Metrics Analyzed
•	Response Time: Measuring how long each version took to respond to requests under varying loads.
•	Throughput: The number of requests processed per second, showing how well application can handle high demand.
•	Sample processed: The number of requests processed per second.

## Test Results

### Response Time
![Response Time (ms) vs  Number of Threads (1)](https://github.com/user-attachments/assets/db73240b-620d-4b93-ab76-822b97bbbbc3)

### Throughput
![Throughput vs  Number of Threads](https://github.com/user-attachments/assets/81afc474-9915-4534-b9f6-a78edf44525b)

### Sample Processed 
![Sample Processed vs  Number of Threads](https://github.com/user-attachments/assets/7c7f3acb-7c98-450c-aa42-2a832e4478fa)


