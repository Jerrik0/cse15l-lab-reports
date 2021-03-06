# Lab Report 4
_Jerry Ko_

To start the testing process, below are the three snippets that will be tested in preview.
## Snippet 1
![image1](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_snippet1.png?raw=true)

## Snippet 2
![image2](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_snippet2.png?raw=true)

## Snippet 3
![image3](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_snippet3.png?raw=true)

## My Own Implementation
_[This is a link to the code of my implementation](https://github.com/Jerrik0/markdown-parser)_

* Below are the screenshots for test of Snippet1 and the result, in which it failed.
![image4](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_myTestcode1.png?raw=true)
![image5](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_myTest1.png?raw=true)

* Then are the code and failed test result for Snippet2.
![image7](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_myTestcode2.png?raw=true)
![image8](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_myTest2.png?raw=true)

* Below is the test for Snippet3. It did not pass the test or did not even finish the test, it probably went into an infinite loop that it wouldn't get out of. There will be more code than 10 lines to fix this problem approximately.
![image9](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_myTestcode3.png?raw=true)


## Code I Reviewed
_[This is a link to the code I reviewed]( https://github.com/aHewig/markdown-parser)_

* Below are the screenshots of the three test results.
![image10](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_reviewedTest1.png?raw=true)
![image11](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_reviewedTest2.png?raw=true)
![image12](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-4/Screenshot_reviewedTest3.png?raw=true)

## Code Fixing
* For the first test, it is easily fixed by checking if there is any backticks ahead of the bracket and eliminate the link that would be added. The added code is well within 10 lines.

* For Snippet2, I think there will be a bit more code than 10 lines to check a link within a already existing brackets.

*  It did not pass the test or did not even finish the test, it probably went into an infinite loop that it wouldn't get out of. There will be more code than 10 lines to fix this problem approximately.(For my own code) But for the one I reviewed, I think there will be more than 10 lines to check if the brackets or parentheses are within certain range of the link.