1. Triangle

Graph

![image](https://user-images.githubusercontent.com/20588061/108458684-75277080-72b8-11eb-94d9-90f8a89d284b.png)

Histogram output from QASM

![image](https://user-images.githubusercontent.com/20588061/108458618-5d4fec80-72b8-11eb-8693-7cc416ecb8ef.png)

The most probable output sequence is [010 001 100], meaning 0th node must be placed at the 1st position in the graph, 1st node going to the 2nd position, and the 2nd node going to the 0th position in the graph. Thus, our quantum circuit simulated by QASM produces the correct result.


2. Rectangle

Graph

![image](https://user-images.githubusercontent.com/20588061/108459409-eddafc80-72b9-11eb-9f1c-265ca6098da3.png)

Histogram output from QASM

![image](https://user-images.githubusercontent.com/20588061/108459411-f16e8380-72b9-11eb-9a77-d3375dc36e00.png)

Output sequence is [0010 0100 0001 1000], meaning 0th node must be placed at the 2nd position in the graph, 1st node going to the 1st position, the 2nd node going to the 3rd position, and the 3rd node going to the 0th position in the graph. Thus, our quantum circuit simulated by QASM produces the correct result.
