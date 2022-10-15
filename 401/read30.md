# **Hashtables**

Hash is the what you get when you convert a string into a number. It can be used to find the index of an array. A bucket is a container of each index of the array. For example if array [1, 2, 3] 1 is a bucket that can contain multiple key/value pairs if a collisioin occurs. A collision is when two or more keys get hashed in the same location.

Hashtables are created from an array. There are a few steps to creating a hash:

1. Add or multiply all the ASCII values together.
2. Multiply it by a prime number such as 599.
3. Use modulo to get the remainder of the result, when divided by the total size of the array.
4. Insert into the array at that index.

### Recources

- [Hashtables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
