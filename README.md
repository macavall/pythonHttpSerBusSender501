# Python Function App Performance Example
  - Function App is using:
    -  Input: Http Trigger
    -  Output: Service Bus Topic (Non-Partitioned, Non-Batching)
      -  Output is not a `binding`
      -  Output is done using a **Static Service Bus Client**

![image](https://github.com/user-attachments/assets/8b1eb517-8de1-43a1-80af-c9d723eab1e0)

