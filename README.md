# CODTECH-TASK3

# task 3 : Pipelined Processor

Pipeline Processor
It consists of a sequence of m data-processing circuits, called stages or segments, which collectively perform a single operation on a stream of data operands passing through them. Some processing takes place in each stage, but a final result is obtained only after an operand set has passed through the entire pipeline. As shown in figure, a stage S(i) contains a multiword input register or latch R(i) , and a datapath circuit C(i), that is usually combinational. The R(i)‘s hold partially processed results as they move through the pipeline; they also serve as buffers that prevent neighbouring stages from interfering with one another. A common clock signal causes the R(i)‘s to change state synchronously. Each R(i)‘s to change state synchronously. Each R(i) receives a new set of input data D(i-1) from the preceding stage S(i-1) except for R(1) whose data is supplied from an external source. D(i-1) represents the results computed by C(i-1) during the preceding clock period. Once D(i-1) has been loaded into R(i) , C(i) proceeds to D(i-1)
to computer a new data set D(i) . Thus in each clock period, every stage transfers its previous results to the next stage and computers a new set of results.

Principle of Pipelining

pipeline is technique where multiple instructions are executed to overlapping fashion. Pipeline is divided into stages and their stages are connected to each other is cascade from to look like pipe like structure. In a pipeline system, each stage/segment consists of an input register followed by a combinational circuit. The register is used to hold data and combinational circuit perform operation on it.

Here stages are pure combinational circuits performing arithmetic of logic operations. Over the data stream following through the pipe latches are high speed register for holding intermediate. Registers between the stages information flows between adjacent stages are under control of a common clock applied to all the latches simultaneously.

Performance evolution factor for pipelined computer:

1.clock period
2.Speedup
3.Efficiency
4.Throughput

![image](https://github.com/user-attachments/assets/0673e380-c718-403a-b2fd-375e8dd47ccb)



