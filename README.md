# jmeter-test-file

## Prerequisites:
- install jdk 1.8
- set JMeter home in env variables

## Run the script:

- Open the folder with git bash or powershell or cmd
- Then type following command to perform load test and generate report.

======report generate after load test======
```sh 
jmeter -n -t ./customer_api.jmx -l ./result.xml -e -o ./Customer_Test_API/Reports
```
======report generate from existing log======
```sh 
jmeter -g ./result.jtl -o ./Reports 
```
