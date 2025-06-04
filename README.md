# Sorting-System-SCL-CODESYS

## Project Description:
 This project aims to build an automatic bottle sorting system using a weight-based method.
 Products (bottles) pass through a sensor, and based on their weight, they are classified and directed through one of three gates (A, B, or C). Each gate represents a product category, and a counter tracks the number of bottles that pass through each gate.

 ## System Components:
 - Start Signal: A digital input to trigger the start of the process.
 - Sensor: Detects the presence of a bottle on the conveyor.
 - Weight Input: A signal (analog) read from a weight sensor.
 - Classification Gates (A, B, C): Open to allow a bottle to pass based on its type.
 - Timers: Used to keep the gates open for a fixed time.
 - Counters: Count how many bottles of each type have passed.
