1. It will print 3 because the variable i is declared using “var” so it's visible in the entire function.
2. It will print 100 because the variable discountedPrice is declared using “var” so it's visible in the entire function.
3. It will print 100 because the variable finalPrice is declared using “var” so it's visible in the entire function.
4. It will return [50, 100, 150]. It's the desired output. The function use each item in the in put list multipling to (1 - discount) to get new prices and push it to the result list.
5. The code returns an error because the variable i is defined using let thus only available in the for loop.
6. The code returns an error because the variable discountedPrice is defined using let thus only available in the for loop.
7. It will print 100 because the variable finalPrice is available in the entire function.
8. It will return [50, 100, 150]. It's the desired output. The function use each item in the in put list multipling to (1 - discount) to get new prices and push it to the result list.
9.  There will be an error because the variable i is defined using let thus only available in the for loop.
10. It will print 3 because the variable length is declared using "const" so it's visable in the block.
11. It will return [50, 100, 150]. It's the desired output and that's because we can push value to a const variable, we just can't reassign it.
12. A. student.name
B. student[‘Grad Year’]
C. student.greeting()
D. student[‘Grad Year’].name
E. student.courseLoad[0]
13. A. “32”, since integer is mapped to the string representation and cast together with the string.
B. 1, since the string '3' is converted to the integer representation.
C. 3, since null can be represent as integer 0.
D. '3null', null is automatically casted to string.
E. 4, since the integer representation of true is 1.
F. 0, since both integer representation of false and null are 0.
G. '3undefined', since undefined will be converted to string automatically
H. NaN, since when doing nuemrical conversions, undefined object is casted to NaN.
14. A. True, since the string '2' is converted to the integer representation and 2 > 1.
B. False, first character "1" is smaller than the first character "2".
C. True, since the string '2' is converted to the integer representation.
D. False, === is only true when data type is same.
E. False, since the integer representation of true is 1.
F. True, since boolean value of non empty values are ture.
15.  The difference is that == will not care about data type while === is only true when data type is same.
16.  Please look at the picture.
17.  [2, 4, 6], because in the function modifyArray, the for loop basically applies the doSomething method (multiply number by 2) to every elemtns in the array and stored it in newArr.
18.  Please look at the picture.
19.  the output would be 1,4,3,2 because setTimeout will delay the content inside by a certain period so 1 and 4 will print first, and since 3 has a shorted delay time, 3 is printed after4 and 2 is printed last.


