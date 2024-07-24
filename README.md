# scipy-2024
Open github repo with PQB  poster, slide deck, and code example for scipy-2024.   

# Code example: A QAOA approach to solving a combinatorial optimization problem
This work demonstrates the representation of a combinatorial optimization problem using a Quantum approximate optimization algorithm (QAOA) approach 

## What is the interlocking bricks problem?
Checkout the poster or slides for details!

## How to run the solver?

### Install docker
- Install docker:
  - https://docs.docker.com/install/
- Install docker-compose:
  - https://docs.docker.com/compose/install/

### Prepare repo
- Clone the repo and change into it

### Add your IBM token
- find the cell that has the line ibmqx_token="xxxx" and replace xxxx with your ibmq token
- apply for an IBM token here: https://quantum.ibm.com/

### Build the container
```
sudo sh build_gpu.sh
```

### Start the notebook
```
sudo sh start_gpu.sh
```
- in your browser navigate to: http://127.0.0.1:8885 
- open the 'bricks_example' folder and start the notebook

