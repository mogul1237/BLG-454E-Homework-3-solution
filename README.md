# BLG-454E-Homework-3-solution

Download Here: [BLG 454E  Homework #3 solution](https://jarviscodinghub.com/assignment/blg-454e-homework-3-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. (50 pts.) [PCA]
(a) (3 pts.) What are the main motivations for reducing a dataset’s dimensionality? (b) (3 pts.) How can you evaluate the performance of a dimensionality reduction algorithm on your dataset? (c) (2 pts.) What do you say about the performance of PCA in Figure 1 in terms of classiﬁcation? (d) (2 pts.) What is/are drawback(s) of PCA?
0.5 1.0 1.5 2.0 2.5 3.0 3.5 4.0 0
1
2
3
4
5
6
3 2 1 0 1 2 3 x_values
0.06
0.04
0.02
0.00
0.02
0.04
0.06
y_values
Transformed samples
class1 class2
Figure 1: Original data in 2D (left) and its transformation in 1D (right).
(e) (40 pts.) Implement a PCA projection on given the data.txt. The last attribute of the data.txt is the class label, range from 0..9. • Use the covariance matrix Σ to calculate the PCA components • Plot the transformed data points in 2D as shown in Figure 2. You need to use annotate() like function to write text(class label) at each randomly selected 200 data points • Give all your plots in your report. You are allowed use built-in functions to compute eigenvalues and covariance matrices. However, you are not allowed to use built-in function directly implements PCA.
2. (50pts.) [SVD] You are going to look at compressing the given RGB image, data.jpg, through computing the singular value decomposition (SVD). Each channel (red, green, blue) has 1537×2500 pixels which is a 1537×2500 matrix A. – (35 pts.) Find the SVD of A (one for each channel). – (15 pts.) Display the original image and image obtained from a rank (term) of 1, 5, 20, 50 SVD approximation of A as shown in Figure 3.
Page 1 of 3
BLG 456E Learning From Data Homework #3
40 30 20 10 0 10 20 30 40 First eigenvector
40
30
20
10
0
10
20
30
Second eigenvector
6
5
6 7
7
4
9
6
3
4
1
9
0
0
0
6
5
6
4
4
0
4
0
1
9
1
7
7
2
1
0
66
82
3
6
9
1
6
4
7
0
7
9
1
9
5
4
4
0 6 8 5
2
5
2
5
6
0
2
4
1
2
3
4
0
9
2
5
6
6
3
6
1
3
5
6
6
5
2 3
6
7
8
6
8
7
4
4
1
2
3
2
0
2
2
7
0
3
4
4
0
5
3
7
9
1
4
5
7
0
1
8
1
1
3
7
6
9
2
1
1
0
4
9 9
4
8
0
9
8
5
2
2
8
0
5
5
0
2
8
7
2
1
0
3
4
5
4
5
3
4
1
5 5
2
6
8
8
1 1
6
8
2 2
9
5
8
4
1
7
9
6
6
1
0
2
6
1
4
73
8
6
8
0
6
4
3
1
1
4
7
0
8
2
4
8
8
Data after PCA
Figure 2: Data plotted in the space of two principal components. Only the label of 200 datapoints are shown.
– Give all your plots in your report.
You are not allowed to use built-in function directly implements SVD.
Submission Policy
• Prepare the report and code. Only electronic submissions through Ninova will be accepted no later than May 3, 10pm • You may discuss the problems at an abstract level with your classmates, but you should not share or copy code from your classmates or from the Internet. You should submit your own, individual homework. • Academic dishonesty, including cheating, plagiarism, and direct copying, is unacceptable. • Note that your codes and reports will be checked with the plagiarism tools including previous years submissions! • If a question is not clear, please let the teaching assistants know by email kivrakh@itu.edu.tr.
Bonus marks (10pts)
• Clarity and nicely described report • Using Latex template for the report Deductions (-10pts)
• Spelling errors. • Messiness
Page 2 of 3
BLG 456E Learning From Data Homework #3
0 500 1000 1500 2000 2500
0 200 400 600 800 1000 1200 1400
Original
0 500 1000 1500 2000 2500
0 200 400 600 800 1000 1200 1400
Using the 1 term
0 500 1000 1500 2000 2500
0 200 400 600 800 1000 1200 1400
Original
0 500 1000 1500 2000 2500
0 200 400 600 800 1000 1200 1400
Using the 5 term
0 500 1000 1500 2000 2500
0 200 400 600 800 1000 1200 1400
Original
0 500 1000 1500 2000 2500
0 200 400 600 800 1000 1200 1400
Using the 20 term
0 500 1000 1500 2000 2500
0 200 400 600 800 1000 1200 1400
Original
0 500 1000 1500 2000 2500
0 200 400 600 800 1000 1200 1400
Using the 50 term
Figure 3: The original image and its the compressed results are displayed.
