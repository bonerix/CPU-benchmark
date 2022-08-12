# CPU-benchmark
This is a simple C# code to test the performance of your CPU.


The operations run 10 seconds, then the program will calculate avg. operations per second and thread.


To find how much Logical Processors your CPU has - open "Task Manager", click the "Performance" tab and look for "Logical processors: ".
*I will maybe do an auto-detection for Logical Processor number.*

If you accidentaly write a bigger number of threads than your CPU has, don't worry, nothing bad will happen.


!! The test isn't accurate, this program tests only for a specific task that your CPU can do !!
