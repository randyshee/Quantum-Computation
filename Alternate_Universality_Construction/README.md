# Alternate Universality Construction
This project is an implementation of Problem 4.3 of [Quantum Computation and Quantum Information](https://www.cambridge.org/core/books/quantum-computation-and-quantum-information/01E10196D0A682A6AEFFEA52D53BE9AE) by Nielsen and Chuang. The method in Problem 4.3 provides a systematic way to output a quantum circuit from any unitary matrix. And I used this method to solve [2020 May IBM Quantum Challenge](https://www.ibm.com/blogs/research/2020/04/ibm-quantum-challenge/) Exercise 4 and got a cost of 239 if ordered properly.

The unordered quantum circuit has a cost of 359 and the ordered quantum circuit has a cost of 239.
| *Unordered Quantum Circuit* | *Ordered Quantum Circuit* |
|------------|-------------|
| <img src="https://github.com/randyshee/Quantum-Computation/blob/main/Alternate_Universality_Construction/image/cost%3D359.png" width="500"> | <img src="https://github.com/randyshee/Quantum-Computation/blob/main/Alternate_Universality_Construction/image/cost%3D239.png" width="500"> |

See the image below for math background from a screenshot of the book.
| *Problem 4.3 from Quantum Computation and Quantum Information* |
|:--:| 
| ![Problem 4.3](https://github.com/randyshee/Quantum-Computation/blob/main/Alternate_Universality_Construction/image/Problem%204.3%20N%26C.png) | 
