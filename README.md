# Dmoney-api-jmx

## Technology and Tool Used
- Apache JMeter
- Java

## Requests
1. Login to user
2. Create a new agent
3. Give balance to the newly created agent from system
4. Create a customer
5. Search the newly created user by phone number
6. Deposit balance to the customer from the agent
7. Withdraw some money from the agent
8. Delete the user

## How to run this project
- clone this project
- copy the Dmoney-Load-Test.jmx file into bin folder of installed location of Jmeter
- open the Dmoney-Load-Test.jmx file with jemeter & run the project
- to Generate report on the command prompt, delete the already copied .csv file and Report folder from the project
- hit the following command:
- $ jmeter -n -t Dmoney-API-Test.jmx -l dmoneyapi-Test.csv -e -o Reports

## Prerequisite
- Jmeter and Java must be installed

## Generated Html Report
![1](https://user-images.githubusercontent.com/96409251/216774099-42f57f1d-1433-449b-9910-1718f72a47bb.png)
![2](https://user-images.githubusercontent.com/96409251/216774150-f179f329-a036-4b87-9278-486114e35096.png)

## Requests Screenshot:
![4](https://user-images.githubusercontent.com/96409251/216774189-92a7dc21-2633-4fdd-972c-f026f572bfd2.png)

## Summary Report
![3](https://user-images.githubusercontent.com/96409251/216774222-002c2503-c696-48d4-bb63-b95eda2a4f7b.png)
