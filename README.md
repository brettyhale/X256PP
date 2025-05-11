# X256PP
A simple, portable **xoshiro256++** PRNG for C++20, satisfying: [std::uniform_random_bit_generator](https://en.cppreference.com/w/cpp/numeric/random/uniform_random_bit_generator)

This header-only **`X256PP`** class can, therefore, replace any `std` PRNG. It exhibits excellent statistical qualities, can be efficiently forked to provide multiple streams, and solves a long-standing deficiency with `std` generators: it correctly initializes the full 256-bit state IV from a `std::random_device`.
