# matlab_programming
introduction to matlab programming

I confirmed the following examples with GNU Octave

# Matlab operation (1)

octave:1> 1+sin(1)

ans = 1.8415

octave:2> a=[1 2 3 4 5 6 7 8]

a =

   1   2   3   4   5   6   7   8

octave:3> a'

ans =


   1
   
   2
   
   3
   
   4
   
   5
   
   6
   
   7
   
   8

octave:4> b=sin(a)

b =

   0.8415   0.9093   0.1411  -0.7568  -0.9589  -0.2794   0.6570   0.9894

octave:5> plot(a,b)

<img width="560" alt="octave-plot-2023-08-12" src="https://github.com/chibaf/matlab_programming/assets/1296728/b4f897f0-cfa0-4715-8470-25b3ec7aae5e">

# Matlab operation (2)：Sovin a liear equation

We solve a liear equation A x = b by Matlab

octave:1> A=[1 2 3;0 1 2;0 0 1]
A =

   1   2   3
   
   0   1   2
   
   0   0   1

octave:2> det(A)

ans = 1

octave:3>  b=[1;2;3]

b =

   1
   
   2
   
   3

octave:4> A\b

ans =

   0
   
  -4
  
   3

octave:5> x=A\b

x =

   0
   
  -4
  
   3

octave:6> A*x

ans =

   1
   
   2
   
   3




