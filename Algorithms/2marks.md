# If the marks obtained by a student in three different subjects are input through the keyboard, find out the aggregate marks and percentage marks obtained by the student. Assume that, maximum marks that can be obtained by a student in each subject is 100. 
Hint: Use subjects as Hindi, English and Mathematics.
____________
### Algorithm
________
1. Input  subjects as Hindi, English and Mathematics, Aggregate marks(grand total) and Percentage.
2. Calculate Aggregate marks= Hindi + English + Mathematics
3. Calculate Percentage = Aggregate /300 * 100
4. Print Aggregrate marks
5. Print Percentage 

________
### Flow-Chart
__________

```mermaid
graph TD;
   Start-->InputSubjectsHindi,EnglishandMathematics,AggregatemarksandPercentageB;
    InputSubjectsHindi,EnglishandMathematics,AggregatemarksandPercentageB--> CalculateAggregatemarksHindi+English+Mathematics;
    CalculateAggregatemarksHindi+English+Mathematics-->CalculatePercentageAggregate/300*10;
    CalculatePercentageAggregate/300*10--> PrintAggregratemarks;
 PrintAggregratemarks-->PrintPercentage
PrintPercentage-->End
```








____
### C++ code
________
