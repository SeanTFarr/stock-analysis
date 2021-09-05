# VBA Challenge

## Overview of Project
After analyzing green energy stock data for Steve to consider diversifying, he appreciated the workbook prepared for him. He now wants to explore the entire stock market. Noticing that there were only a few stocks involved with our code, the realization that it may not be fast enough for running additional stocks, perhaps thousands, became apparent. In refactoring the code, we should be able to improve it, which would make a quicker run through a larger dataset. 

## Results.

### The Run Times
With the original code, the run times were 0.6484375 seconds for 2017 and 0.6640625 seconds for 2018

<img width="296" alt="Run time for 2017" src="https://user-images.githubusercontent.com/88861780/132142039-b0deb14f-ddce-42c0-98a9-c9125204eca0.png">



<img width="294" alt="Run time for 2018" src="https://user-images.githubusercontent.com/88861780/132142041-a7819f15-c4c2-45e5-b49c-b2e1035106db.png">


After the code was refactored, the run times were lower at 0.09375 seconds for 2017 (0.5546875 seconds faster) and 0.09375 seconds for 2018 (0.5703125 seconds faster). Whereas it seems a small difference, we must keep in mind this is a small dataset. With a larger dataset, the run time difference would show a greater significance.

<img width="292" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/88861780/132141988-81414b2f-e9be-411a-9efb-688ded849948.png">


<img width="290" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/88861780/132141989-4ccdfa46-71fe-4fb5-92ec-23a6a53b905a.png">

### The Code

In the original code, a nested For Loop was utilized to go through the tickers, one by one.

<img width="682" alt="Screenshot of original code" src="https://user-images.githubusercontent.com/88861780/132142425-a42d41aa-fefd-4586-9414-ce8e8da90977.png">

The refoctored code created 3 output arrays to run final output. These arrays helped organize the data that would ultimately be displayed.

<img width="637" alt="Screenshot of refactored code" src="https://user-images.githubusercontent.com/88861780/132142428-d0c88af0-2c07-4c6d-8fc8-a00996c7bfb3.png">

## Summary

There is an obvious time saving advantage in refactoring a code, show by the reduction in time, but the time saved may not be enough to justify the additional time editing the original code.

The original code will get the job done, so the tendency would be to leave it alone, though it isn't optimal. Whereas with refoctoring the code, you can reap the benefits of saving both run time and file space, but you do spend more time running through code and editing it.