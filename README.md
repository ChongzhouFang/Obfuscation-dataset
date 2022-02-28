# Obfuscation-dataset<br />
Directory Structure:<br />

<!-- EncryptedBenches: Stores all benchmark circuits after encryption. <br />
&nbsp;|<br />
&nbsp;|---[Benchmarks]: Stores encrypted circuits of a single benchmark<br />
&nbsp;|&nbsp;&nbsp;|<br />
&nbsp;|&nbsp;&nbsp;|---[Encoding schemes]: Stores encrypted circuits under a specific encoding scheme.<br />
&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|<br />
&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|---[Iteration numbers]: number of iteration applied<br />
&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|<br />
&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|---[Encrypted benchmarks]: named after the percentage of circuits being obfuscated or<br />
&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|	key lengths, e.g. 10_per.bench means 10% of the circuit is being obfuscated,<br />
&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|    10_key.bench means the key length is 10.<br />
&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|&nbsp;&nbsp;|	<br />
&nbsp;...<br /> -->
```bash 
|
├── EncryptedBenches: Stores all benchmark circuits after encryption.
│   └── [Benchmarks]: Stores encrypted circuits of a single benchmark
│       └── [Encoding schemes]: Stores encrypted circuits under a specific encoding scheme.
│           └── [Iteration numbers]: number of iteration applied
│               ├── [Encrypted benchmarks]: named after the percentage of circuits being obfuscated or
│               ├── key lengths, e.g. 10_per.bench means 10% of the circuit is being obfuscated,
│               ├── 10_key.bench means the key length is 10.
|               ├──...
|               └──...
├── decryption_time.csv
└── encryption_time.csv
```
In encryption_time.csv and decryption_time.csv, we provide benchmark names, gate numbers, FF numbers, encryption scheme, keylength, obfuscation fraction, number of iterations and time spent on encrypting/decrypting.

