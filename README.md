(Leveled) Homomorphic C++ implementation of DGHV scheme using Pari C library.
The implementation supports addition and multiplication gates on integers.

For the parameters taken in the implementation, the SwHE scheme supports integer addition upto 32 bits and integer multilpication upto 3 bits.

I've used rand(), seeded with system time to generate random numbers, which is cryptographically insecure.
But, this is not an industrial grade implementation.
