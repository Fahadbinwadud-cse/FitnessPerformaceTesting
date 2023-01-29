# FitnessPerformaceTesting
**I used Fithub site for performance testing:**

![React App](https://user-images.githubusercontent.com/90126212/215306706-2bed0fce-98d7-4843-91e1-1b31a9764aad.png)


![React App (1)](https://user-images.githubusercontent.com/90126212/215306767-4cbb6061-c87c-43a9-885d-a002e1a08aa6.png)


====================================================================

Dear, 

I’ve completed the performance test on Fithub.
Test executed for the below-mentioned scenario in server [FitHub](https://fithub-snikhil2001.vercel.app/)

100 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 5.1 And Total Concurrent API requested: 600.
200 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 6.4  And Total Concurrent API requested: 1200.
250 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 16.5  And Total Concurrent API requested: 1500.
300 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 19 And Total Concurrent API requested: 1800.

While executing 300 concurrent requests, I found 24 requests got connection timeout, and the error rate is 1.33%. 

Summary: The server can handle almost a concurrent 1600 API calls with almost zero (0) error rate.

Please find the details report in the attachment and let me know if you have any further queries. 


