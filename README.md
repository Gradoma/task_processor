# task_processor
1. Tasks have different time to complete
2. Each task assigned for particular user
3. Tasks for particular user has to be processed in the same order it was aded to queue. Task 1 should be completed before start of Task 2.
4. Tasks for each particular user has to be processed in the separate thread
5. Threads have to be stored in a pool. Pool has to be increased on demand.
