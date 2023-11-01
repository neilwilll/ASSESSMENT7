Results for the tinyArray
insert 14.833 μs
append 40.791 μs

Results for the smallArray
insert 24.166 μs
append 50.667 μs

Results for the mediumArray
insert 124.583 μs
append 83.75 μs

Results for the largeArray
insert 7.874292 ms
append 516.291 μs

Results for the extraLargeArray
insert 5.118859083 s
append 1.569958 ms

After going through test runs we came to the conclusion which arrays were the fasted and slowest. TinyArray is the fasted insert with 14.833 micro seconds. The slowest insert Array was the extraLargeArray with 5.118859083 seconds.

Also for append seconds the fastest were TinyArray 40.791 micro second and the slowest were ExtraLargeArray 1.569958 milli second. 

As we can see insert function is better for small array and append is better for large array.