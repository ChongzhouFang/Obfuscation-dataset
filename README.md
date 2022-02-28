# Obfuscation-dataset<br />
Directory Structure:<br />

EncryptedBenches: Stores all benchmark circuits after encryption. <br />
    |<br />
    |---[Benchmarks]: Stores encrypted circuits of a single benchmark<br />
    |       |<br />
    |       |---[Encoding schemes]: Stores encrypted circuits under a specific encoding scheme.<br />
    |       |       |<br />
    |       |       |---[Iteration numbers]: number of iteration applied<br />
    |       |       |       |<br />
    |       |       |       |---[Encrypted benchmarks]: named after the percentage of circuits being obfuscated or<br />	|       |       |       |	key lengths, e.g. 10_per.bench means 10% of the circuit is being obfuscated,<br />
    |       |       |       |    10_key.bench means the key length is 10.<br />
    |       |       |       |	<br />
    ...<br />
         
