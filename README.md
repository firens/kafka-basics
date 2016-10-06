# kafka-basics

Take care to not close the producer before you finish to use it or you will receive see errors like 
```
Error while attempting to send message : org.apache.kafka.common.errors.TimeoutException: Failed to update metadata after 10000 ms.
```
With no other explanations of what happens
