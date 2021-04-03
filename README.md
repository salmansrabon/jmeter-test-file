# jmeter-test-file

## Prerequisites:
- install jdk 1.8
- set JMeter home in env variables

## Run the script:
- ======report generate after load test======
- ``` jmeter -n -t ./Customer_Test_API/customer_api.jmx -l ./Customer_Test_API/result.xml -e -o ./Customer_Test_API/Reports```
- ======report generate from existing log======
- ``` jmeter -g ./Customer_Test_API/result.jtl -o ./Customer_Test_API/Reports```
