# Huckel Solver
A general Huckel solver for linear, cyclic and selected 3D polyenes

## Input format
The first line should contain an integer specifying the type of the molecule. This should be 0, 1 or 2 for linear, cyclic or 3D polyenes respectively.

The second line contains an integer *N*. This gives an *N* by *N* Huckel matrix. Do note that for 3D polyenes, the only acceptable values of *N* are 4, 6, 8, 12, 20 and 60.

## Example inputs

Linear polyene of length 4
0
4

Cyclic polyene of size 6
1
6

Buckminsterfullerene
2
60
