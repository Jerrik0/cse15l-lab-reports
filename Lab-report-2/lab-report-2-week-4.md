# Lab Report 2
_Jerry Ko_

## Eliminated Empty Link
In the following code changes, I checked if the link has 0 length to determine add it or not.

![failure1](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-2/Test_failure1.png?raw=true)
>Test failed as shown above
* This error occurs because the code did not check for the length between the two brackets.

![image](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-2/Lab2_1.png?raw=true)
> [Link to the test used](https://github.com/Jerrik0/markdown-parser/blob/main/testcase3-jerry.md)

> [Link to the change](https://github.com/Jerrik0/markdown-parser/commit/d6bc84d70d651550ccec961e2c66ce6852365952)

## Not to add image links
Finishing eliminating the empty ones, images are the one undesired, so the code changes below shows if statements I added to the code to exclude image links.

![failure2](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-2/Test-Failed2.png?raw=true)
>Test failed as shown above
* This bug occurs because it did not check for the "!" before the parantheses.


![image2](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-2/Lab2_2.png?raw=true)
![image3](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-2/Lab2_3.png?raw=true)

>_[Link to the test](https://github.com/Jerrik0/markdown-parser/blob/main/testcase3-jerry.md)_


>_[Link to the slight change](https://github.com/Jerrik0/markdown-parser/commit/62a78816452fc213bd8fee12c4a05a3572c55288)_

