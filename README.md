# Chat Application using interprocess communication

A command line utility chat application which allows multiple users to chat with the server simultaneously. It uses Interprocess communication - Shared Memory concept. The users can also view their message history.

## Getting Started

This application is especially for Linux systems.

### Prerequisites

1. Linux System
2. g++ compiler

### Installing

1. Download the programs (server.cpp & client.cpp)
2. Run server.cpp

```
>> g++ server.cpp
>> ./a.out
```
3. Run client.cpp in a different terminal

```
>> g++ client.cpp
>> ./a.out 1
```
4. Run client.cpp once again in a different terminal

```
>> g++ client.cpp
>> ./a.out 2
```

5. Do same to rum more clients (Max client limit = 5)

## Built With

* [C++ 11](https://en.cppreference.com/w/cpp) - Programming Language

## Authors

* **Rachit Rahul Mishra  - 17JE003017** 
* **Samyak Singh - 17JE003024** 
* **Vipul Bandi - 17JE003026** 
* **Sandesh Sinha - 17JE003038** 
* **Sandeep Sheela - 17JE0048** 
* **Avi Sahney - 17JE003050** 
* **Navya Srivastava - 17JE0052** 
* **Vipin Prakash - 17JE003061** 
* **Thakur Ashutosh Suman - 17JE003067** 

