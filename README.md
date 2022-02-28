# Obfuscation-dataset
Directory Structure:

EncryptedBenches: Stores all benchmark circuits after encryption. 
    |
    |___<Benchmarks>: Stores encrypted circuits of a single benchmark
    |       |
    |       |___<Encoding schemes>: Stores encrypted circuits under a specific encoding scheme.
    |       |       |
    |       |       |__<Iteration numbers>: number of iteration applied
    |       |       |       |
    |       |       |       |__<Encrypted benchmarks>: named after the percentage of circuits being obfuscated or key lengths, e.g. 10_per.bench means 10% of the circuit is being obfuscated,
    |       |       |       |                           10_key.bench means the key length is 10.
    |       |       |       |
    ...
         
