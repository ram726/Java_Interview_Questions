# Java_Interview_Questions

Q) Why is the Java main method static?

Ans) It is because the object is not required to call a static method. If it were a non-static method, JVM creates an object first then call main() method that will lead the problem of extra memory allocation.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Q) Can we execute a program without main() method?

Ans) No, one of the ways was the static block, but it was possible till JDK 1.6. Since JDK 1.7, it is not possible to execute a Java class without the main method.

Q. Which operator is use to create memory space in java?
Ans> new operator is use to create dyanmic memory space in java.
