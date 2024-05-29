# Server Management

This project is to find if specific servers are up/down

## Features

- User can add a server to the list
- User can view the status of a server (up / down)
- User can ping the server to see if a specific server is up
- User can remove the server info from the list
- User can export the list of servers as .xls file

## Tech Stack

![Static Badge](https://img.shields.io/badge/SpringBoot-blue)
![Static Badge](https://img.shields.io/badge/SpringWeb-blue)
![Static Badge](https://img.shields.io/badge/SpringDataJPA-blue)
![Static Badge](https://img.shields.io/badge/Gradle-blue)
![Static Badge](https://img.shields.io/badge/MySQL-blue)
![Static Badge](https://img.shields.io/badge/Angular-blue)

## Screenshots

- Form to add a server info to list
  ![form](images/form.png)
- Main page to see a list of all servers
  ![all](images/all.png)
- Main page to see a sorted list of servers
  ![sort](images/sort.png)
- exported file for list of servers
  ![excel](images/excel.png)

## Lessons Learned

- To ping the server, we can get help from InetAddress, which is from java.net package
- InetAddress determines the IP address of a host by a hostname using getByName method, and can test whether the address is reachable
- XLSX library helps create .xls files
- XLSX catches table by looking for table tag, picks up all data, creates a workbook, creates a sheet in the workbook, and puts in all the table data into the sheet


