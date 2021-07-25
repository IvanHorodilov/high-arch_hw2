Simple application which consists from:
  - ASP Core API (C#)
  - Nginx
  - Elastic Search
  - Mongo
  - TIG stack

General logic:
call to http://localhost:4000/api/books/ uses:
  - nginx as a proxy
  - elastic search
  - mongo search
  - asp core C# as backend service

To simulate load use script 'make run'

Monitoring results:
![alt text](https://github.com/IvanHorodilov/high-arch_hw2/blob/main/images/1.png)
![alt text](https://github.com/IvanHorodilov/high-arch_hw2/blob/main/images/2.png)
![alt text](https://github.com/IvanHorodilov/high-arch_hw2/blob/main/images/3.png)
![alt text](https://github.com/IvanHorodilov/high-arch_hw2/blob/main/images/4.png)
![alt text](https://github.com/IvanHorodilov/high-arch_hw2/blob/main/images/5.png)
![alt text](https://github.com/IvanHorodilov/high-arch_hw2/blob/main/images/6.png)
