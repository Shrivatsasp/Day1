# Day1
github study
lets learn something
welcome to ece
how are u?
welcme to python
# dayone

github study

lets learn something

Welcome to EC
# Licenses

# Day1
## github study
### lets learn something
welcome to EC
License


1) MIT License
The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT)[6] in the late 1980s.[7] As a permissive license, it puts only very limited restriction on reuse and has, therefore, high license compatibility.[8][9]

The MIT License is compatible with many copyleft licenses, such as the GNU General Public License (GNU GPL). Any software licensed under the terms of the MIT License can be integrated with software licensed under the terms of the GNU GPL.[10] Unlike copyleft software licenses, the MIT License also permits reuse within proprietary software, provided that all copies of the software or its substantial portions include a copy of the terms of the MIT License and also a copyright notice.[9][11] As of 2020, the MIT License was the most popular software license found in one analysis,[12] continuing from reports in 2015 that the MIT License was the most popular software license on GitHub.[13]

Notable projects that use the MIT License include the X Window System, Ruby on Rails, Nim, Node.js, Lua, and jQuery. Notable companies using the MIT License include Microsoft (.NET Core), Google (Angular), and Meta (React).


2)Apache License
The Apache License is a permissive free software license written by the Apache Software Foundation (ASF).[4] It allows users to use the software for any purpose, to distribute it, to modify it, and to distribute modified versions of the software under the terms of the license, without concern for royalties. The ASF and its projects release their software products under the Apache License. The license is also used by many non-ASF projects.


3)GNU License
The GNU General Public License (GNU GPL or simply GPL) is a series of widely used free software licenses that guarantee end users the four freedoms to run, study, share, and modify the software.[7] The license was the first copyleft for general use and was originally written by the founder of the Free Software Foundation (FSF), Richard Stallman, for the GNU Project. The license grants the recipients of a computer program the rights of the Free Software Definition.[8] These GPL series are all copyleft licenses, which means that any derivative work must be distributed under the same or equivalent license terms. It is more restrictive than the Lesser General Public License and even further distinct from the more widely used permissive software licenses BSD, MIT, and Apache


4)BSD 2 Clouse License
Also known as the “simplified BSD license” and "freeBSD license," the 2-Clause BSD license omits the third clause of the BSD 3 (also known as the “non-endorsement clause”). This is the clause that prohibits users from using the name of the project to promote their derivative work (s).

#c coding matrix
include <stdio.h>
int main() {
  int r, c, a[100][100], b[100][100], sum[100][100], i, j;
  printf("Enter the number of rows (between 1 and 100): ");
  scanf("%d", &r);
  printf("Enter the number of columns (between 1 and 100): ");
  scanf("%d", &c);

  printf("\nEnter elements of 1st matrix:\n");
  for (i = 0; i < r; ++i)
    for (j = 0; j < c; ++j) {
      printf("Enter element a%d%d: ", i + 1, j + 1);
      scanf("%d", &a[i][j]);
    }

  printf("Enter elements of 2nd matrix:\n");
  for (i = 0; i < r; ++i)
    for (j = 0; j < c; ++j) {
      printf("Enter element b%d%d: ", i + 1, j + 1);
      scanf("%d", &b[i][j]);
    }

  // adding two matrices
  for (i = 0; i < r; ++i)
    for (j = 0; j < c; ++j) {
      sum[i][j] = a[i][j] + b[i][j];
    }

  // printing the result
  printf("\nSum of two matrices: \n");
  for (i = 0; i < r; ++i)
    for (j = 0; j < c; ++j) {
      printf("%d   ", sum[i][j]);
      if (j == c - 1) {
        printf("\n\n");
      }
    }

  return 0;
}
Run Code
Output

Enter the number of rows (between 1 and 100): 2
Enter the number of columns (between 1 and 100): 3

Enter elements of 1st matrix:
Enter element a11: 2
Enter element a12: 3
Enter element a13: 4
Enter element a21: 5
Enter element a22: 2
Enter element a23: 3
Enter elements of 2nd matrix:
Enter element b11: -4
Enter element b12: 5
Enter element b13: 3
Enter element b21: 5
Enter element b22: 6
Enter element b23: 3

Sum of two matrices: 
-2   8   7   

10   8   6  
In this program, the user is asked to enter the number of rows r and columns c. Then, the user is asked to enter the elements of the two matrices (of order rxc).

We then added corresponding elements of two matrices and saved it in another matrix (two-dimensional array). Finally, the result is printed on the screen.

Share on:
Did you find this article helpful?
Related Examples
C Example

Multiply Two Matrices Using Multi-dimensional Arrays

C Example

Find Transpose of a Matrix

C Example

Multiply two Matrices by Passing Matrix to a Function

C Example

Find Largest Element in an Array


Join our newsletter for the latest updates.
Enter Email Address*
Join


Tutorials
Python 3 Tutorial
JavaScript Tutorial
SQL Tutorial
C Tutorial
Java Tutorial
Kotlin Tutorial
C++ Tutorial
Swift Tutorial
C# Tutorial
Go Tutorial
DSA Tutorial
Examples
Python Examples
JavaScript Examples
C Examples
Java Examples
Kotlin Examples
C++ Examples
Company
About
Advertising
Privacy Policy
Terms & Conditions
Contact
Blog
Youtube
Apps
Learn Python
Learn C Programming
Learn Java
© Parewa Labs Pvt. Ltd. All rights reserved.

   
