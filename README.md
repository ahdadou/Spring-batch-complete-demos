# SpringBatch
All the spring batch related code base available here

### 08_SpringBatch_Demo3_ReadingFromDBWritingIntoFile:
  - Read from database use SQL and write it into a file "CSV" .
### 10_SpringBatch_Demo5_MultiStepJob
   - make more than one step .
   - Using multi steps we can solve complex problem by dividing in sub step. 
### 11_SpringBatch_Demo6_JobExecutionContext
    - This the feature to deal with transfer and access the data from one step to another steps while job execution. This similar to map which will store key value pair data.
### 12_SpringBatch_Demo6_SkipPolicy 
    - for example we have int but in file string so we can skip this error
    - SkipPolicy will provide the fault tolerance feature to Spring Batch jobs. It will prevents job to be failed in case of any bad record or error occurred in any of the steps.        We can define our own rule to deal with skip policy. 
### 13_SpringBatch_Demo7_Listeners
   - Job Listener is used to intercept the job execution flow so we can add some logic which will used before and after job execution. 
### 14_SpringBatch_Demo8_StepsListeners
   - Step Listener is used to intercept the steps execution flow so we can add some logic which will used before and after step execution. 
    - ItemReadListener intercept the flow of reading step. And also handle the error.
    - ItemProcessListener intercept the flow of processing step. And also handle the error.
    - ItemWriteListener intercept the flow of writing step. And also handle the error.
### 15_SpringBatch_Demo9_FixedLengthRecordAndSkipLineCallback
     - how to skip the first line and the same time how can we get that data while further steps execution. We can assign a callback for this skip record and later we can read       the skipped record.
     - read the file which have fixed length record. 
### 16_SpringBatch_Demo10_Tasklet
   - WE DONT HAVE A READ AND WRITE JUST PROCESSORS
### 17_SpringBatch_Demo11_Scheduler
    - Scheduler for authomatic our jobLuncher for example make it work every 10s






