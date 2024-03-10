CMPE-277 – Assignment 1:

Activity Lifecycle

In this app, we've set up a system where the thread counter increases each time the Main Activity is reinitiated. This is to show that when a new activity (like Activity B or Activity C) is launched and then we return to the initial activity, the onRestart() method gets triggered, leading to a 5-point increment in the thread counter.

Conversely, if a dialog Activity is launched and we revert to the previous activity, the onRestart() method doesn't activate, resulting in no change to the thread counter.

Home screen:
</br>
<img width="200" alt="Screenshot 2024-03-10 at 1 14 32 PM" src="https://github.com/nimom38/CMPE-277---Activity-Life-Cycle/assets/54052992/6c1a249a-9875-4a8b-a02c-20175a6df29c">
</br>
</br>
Activity B opened:
</br>
<img width="200" alt="Screenshot 2024-03-10 at 1 14 39 PM" src="https://github.com/nimom38/CMPE-277---Activity-Life-Cycle/assets/54052992/6562ea6d-745c-413e-93c4-f1feaecdbcb3">
</br>
</br>
Count incremented by 1:
</br>
<img width="200" alt="Screenshot 2024-03-10 at 1 14 49 PM" src="https://github.com/nimom38/CMPE-277---Activity-Life-Cycle/assets/54052992/b1adb474-4bd1-432c-a3d4-74612f0c8344">
</br>
</br>
Activity C opened:
</br>
<img width="200" alt="Screenshot 2024-03-10 at 1 14 57 PM" src="https://github.com/nimom38/CMPE-277---Activity-Life-Cycle/assets/54052992/b01d2fcf-3cfe-4d98-a631-d2bf9ca06580">
</br>
</br>
Count incremented to 2:
</br>
<img width="200" alt="Screenshot 2024-03-10 at 1 15 03 PM" src="https://github.com/nimom38/CMPE-277---Activity-Life-Cycle/assets/54052992/5033daa3-7786-44cd-b777-10286cd1098e">
</br>
</br>
Dialog opened:
</br>
<img width="200" alt="Screenshot 2024-03-10 at 1 15 09 PM" src="https://github.com/nimom38/CMPE-277---Activity-Life-Cycle/assets/54052992/ea9c30c7-88cc-4ef0-b7d7-dc53a1f441e4">
</br>
</br>
Count remains unchanged:
</br>
<img width="200" alt="Screenshot 2024-03-10 at 1 15 17 PM" src="https://github.com/nimom38/CMPE-277---Activity-Life-Cycle/assets/54052992/e5c3670e-0373-4f9c-95ae-c35895bfee0e">
