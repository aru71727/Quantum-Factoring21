# Quantum-Factoring21
Shor’s algorithm is a quantum algorithm for factoring a number N in O((log N)3) time and O(log N) space, named after Peter Shor.

The algorithm is significant because it implies that public key cryptography might be easily broken, given a sufficiently large quantum computer. RSA, for example, uses a public key N which is the product of two large prime numbers. One way to crack RSA encryption is by factoring N, but with classical algorithms, factoring becomes increasingly time-consuming as N grows large; more specifically, no classical algorithm is known that can factor in time O((log N)k) for any k. By contrast, Shor’s algorithm can crack RSA in polynomial time. It has also been extended to attack many other public key cryptosystems.

The problem we are trying to solve is that, given an integer N, we try to find another integer p between 1 and N that divides N.
Shor’s algorithm consists of two parts:
1. A reduction of the factoring problem to the problem of order-finding, which can be done on a classical computer.
2. A quantum algorithm to solve the order-finding problem.

For detailed explanantion

visit Blog : https://medium.com/@kush.aradhana007/shors-factoring-algorithm-cd70802e0544
