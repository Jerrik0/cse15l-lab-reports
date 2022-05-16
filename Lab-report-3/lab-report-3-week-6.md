# Lab Report 3
_Jerry Ko_

## Streamlining ssh Configuration

* In the following screenshot, I edited the config file in the `.ssh` directory and successfully logged into the server in a easier way.

![image1](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-3/ssh%20ieng6.png?raw=true)
![image2](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-3/ssh%20ieng6(2).png?raw=true)

## Setup Github Access from ieng6
* Below is the keys in github that I stored and location of the private key for my laptop. 

![image3](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-3/ssh%20key.png?raw=true)
![image4](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-3/private%20key%20spot.png?raw=true)
* Having those keys, I could access `git` commands in both the server and my personal laptop. Using `git add`, `git commit`, and `git push` commands, I successfully added a file called `NEWFILE.md` into the github repository.
> [Link of commit](https://github.com/Jerrik0/cse15l-lab-reports/commit/bb9ebc563bb03b65264cb9997f54c92b4001af58)

![image5](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-3/cloned.png?raw=true)
![image6](https://github.com/Jerrik0/cse15l-lab-reports/blob/main/Lab-report-3/cloned-2.png?raw=true)

## Copy whole directories with `scp -r`
* 