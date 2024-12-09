### How to Run the Test

The test pipeline is already set up for you. Follow these simple steps to run the test:

1. **Navigate to the Actions tab** in your GitHub repository.
2. **Select the workflow file** you want to run.
3. Once the script has finished executing, a test report will be automatically generated.
4. You can **download the generated report** from the **Artifacts section**.



### Test Result Summary:
The test failures are attributed to infrastructure issues, including endpoints returning 500 Internal Server Errors and some being inaccessible.
All automation test scripts for the endpoints have been implemented, and successful execution of these tests is expected once the endpoints are functional.

|                          | Executed       | Failed         |
|--------------------------|----------------|----------------|
| Iterations               | 1              | 0              |
| Requests                 | 57             | 14             |
| Test Scripts             | 91             | 0              |
| Prerequest Scripts       | 63             | 0              |
| Assertions               | 121            | 37             |
|--------------------------|----------------|----------------|
| Total Run Duration       | 24.2s          |                |
| Total Data Received      | 29.01 kB (approx) |             |
| Average Response Time    | 562ms [min: 42ms, max: 8.3s, s.d.: 1349ms] |

