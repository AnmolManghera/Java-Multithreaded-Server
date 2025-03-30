# Java-Multithreaded-Server
The java.net package provides two classes -- Socket and ServerSocket that implement the client side of the connection and the server side of the connection respectively.

An endpoint is a combination of an IP Address and a port number. 

We load test the server using Apache JMeter

![image](https://github.com/user-attachments/assets/0ec07950-888d-4327-9199-3f6a079e446e)

For Single Threaded Server

   ![image](https://github.com/user-attachments/assets/cb24f7b7-e470-4413-8ad2-15ee5e39ca4b)

For Multithreaded Server

1. 5000 requests/min
   ![image](https://github.com/user-attachments/assets/4491e0ab-cc4a-4440-be1f-cdaae7436e95)

2. 50000 requests/min
   ![image](https://github.com/user-attachments/assets/654bbd1d-eed8-4e83-bfa4-58d092ad2cdf)

3. 100000 requests/min
   ![image](https://github.com/user-attachments/assets/c58660af-2bdf-42f7-8606-2e89b3a2895c)

For Thread Pool using Executor Service

1. 50000 requests/min - Thread Pool Size - 10
   ![image](https://github.com/user-attachments/assets/abca1d77-3d30-4ff9-bc69-e0f45bb0cb0b)
     
2. 100000 requests/min - Thread Pool Size - 10
   ![image](https://github.com/user-attachments/assets/52915bd2-620c-46d4-8cd5-7597a7845774)

3. 500000 requests/min - Thread Pool Size - 10
   ![image](https://github.com/user-attachments/assets/03e5f542-b639-4521-a952-999b5838358d)

4. 500000 requests/min - Thread Pool Size - 100
   ![image](https://github.com/user-attachments/assets/39aefcd1-a944-40c8-b99d-8f7eb1bde91a)
