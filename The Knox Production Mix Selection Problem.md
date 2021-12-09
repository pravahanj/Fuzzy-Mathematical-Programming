# The Knox Production Mix Selection Problem

Let us consider a product-mix selection problem . 
Suppose that the Knox Mix company has the option of using one or more of four different types of production processes. 
The first and second processes yield items of product A, and the third and fourth yield items of product B. 
The inputs for each process are labor measured in man-weeks, pounds of material Y, and boxes of material Z. 
Since each process varies in its input requirements, the 81 profitabilities of the process differ, even for 
processes producing the same item. The manufacturer's decision on a week's production schedule is limited in 
'the range of possibilities by the available amounts of manpower and both kinds of raw materials.

![alt text](https://github.com/pravahanj/Fuzzy-Mathematical-Programming/blob/cd95740e60f20a86b45e6876aba7f8a550c2bfd1/Images/The%20Knox%20Production%20Mix%20Selection%20Problem%20-%20Table.png)


## Formulation of Optimization Problem

With production levels in processes 1, 2, 3, 4 as x1, x2, x3, x4 respectively. The problem can then be formulated as <br />
```      
                z = 4x1 + 5x2 + 9x3 + 11x4			(Profit)
                Max z subject to constraints 
		
g1(x)  =   x1 + x2 + x3 + x4   <  15			        (Man Weeks) 
g2(x)  =   7x1 + 5x2 + 3x3 + 2x4  <  120		        (Material Y) 
g3(x)  =   3x1 + 5x2 + 10x3 + 15x4  < 100		        (Material Z)
```

We then solve this linear programming problem by use of the Simplex Method - (using Tora Software) . 
The optimal solution is: 

![alt_text](https://github.com/pravahanj/Fuzzy-Mathematical-Programming/blob/e01ee84d45dddbef009d176bcc7a8a2dd118467b/Images/Simplex%20Solution%20of%20Knox%20Problem.PNG)

```x* = (50 / 7, 0, 55 / 7, 0)  =  (7.14, 0, 7.86, 0) and z* = $ 695 / 7 = $99.29. The actual resources used are  15, 73.57 and 100 units for manweeks, material Y and material Z, respectively``` 
