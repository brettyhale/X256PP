# X256PP
A simple, portable [**xoshiro256++**](https://prng.di.unimi.it) PRNG for C++20, satisfying: [std::uniform_random_bit_generator](https://en.cppreference.com/w/cpp/numeric/random/uniform_random_bit_generator)

This header-only **`X256PP`** class can functionally replace any `std` [PRNG](https://en.cppreference.com/w/cpp/numeric/random). It exhibits excellent statistical qualities, can be efficiently forked to provide multiple streams, and solves a long-standing deficiency with `std` generators: it can correctly initialize the full 256-bit state IV from a [`std::random_device`](https://en.cppreference.com/w/cpp/numeric/random/random_device).
