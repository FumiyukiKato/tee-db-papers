# tee-db-papers

Trusted Execution Environment(SGX) database system or query system papers. Please help me with your PR.

- [KVS](#kvs)
- [RDB](#rdb-sql)
- [Uncategorized](#uncategorized)
- [Security](#security)
- [Other materials](#other-materials)

## Papers and Notes
### KVS
- 2019
  - (USENIX '19) **SPEICHER: Securing LSM-based Key-Value Stores using Shielded Execution** [[link]](https://www.usenix.org/system/files/fast19-bailleu.pdf) [[web]](https://www.usenix.org/conference/fast19/presentation/bailleu)
  - (International Middleware Conference '19) **EnclaveCache: A Secure and Scalable Key-value Cache in Multi-tenant Clouds using Intel SGX** [[link]](https://dl.acm.org/doi/abs/10.1145/3361525.3361533)
  - (EuroSys '19) **ShieldStore: Shielded In-memory Key-value Storage with SGX** [[link]](https://dl.acm.org/doi/pdf/10.1145/3302424.3303951) [[source code]](https://github.com/cocoppang/ShieldStore)
    - in memory key-value store
  - (preprint arXiv '19) **Authenticated Key-Value Stores with Hardware Enclaves** [[link]](https://arxiv.org/abs/1904.12068)
- 2018
  - (IACR '18) **VeritasDB: High Throughput Key-Value Store with Integrity using SGX** [[link]](https://eprint.iacr.org/2018/251) [[source code]](https://github.com/apache/incubator-teaclave-sgx-sdk/tree/master/samplecode/db-proxy)
  - (Symposium on Cloud Computing '18) **Secure In-memory Key-Value Storage with SGX** [[link]](https://dl.acm.org/doi/pdf/10.1145/3267809.3275449)
    - poster like
    

### RDB SQL
- 2019
  - **StealthDB: a Scalable Encrypted Database with Full SQL Query Support** [[link]](https://arxiv.org/pdf/1711.02279.pdf) [[source code]](https://github.com/cryptograph/stealthdb)
    - SQL support
  - (preprint arXiv '19)**Enjoy the Untrusted Cloud: A Secure, Scalable and Efficient SQL-like Query Framework for Outsourcing Data** [[link]](https://arxiv.org/abs/1912.08454)
- 2018
  - (SP '18) **EnclaveDB: A Secure Database using SGX** [[link]](https://www.microsoft.com/en-us/research/uploads/prod/2018/02/enclavedb.pdf)
    - overview [[blog]](https://blog.acolyer.org/2018/07/05/enclavedb-a-secure-database-using-sgx/)
  - (IC2E '18) **STANlite – A Database Engine for Secure Data Processing at Rack-Scale Level** [[link]](https://ieeexplore.ieee.org/abstract/document/8360309)
- 2017
  - (NaNA '17) **CryptSQLite: Protecting data confidentiality of SQLite with Intel SGX** [[link]](https://ieeexplore.ieee.org/abstract/document/8247155/)
  

### Indexing
- 2019
  - (Access '19) **SGX-Based Secure Indexing System** [[link]](https://ieeexplore.ieee.org/abstract/document/8731986)
- 2017
  - (SP '17) **HardIDX: Practical and secure index with SGX** [[link]](https://arxiv.org/pdf/1703.04583.pdf)  
  

### Uncategorized
- 2019
  - **Inout Secure DB: Maximizing Security for Data INside and OUTside the Database** [[link]](https://periodicos.ufmg.br/index.php/jidm/article/view/12172)
    - network coding
- 2018
  - (SmartCloud '18) **Secure and Scalable Key Value Storage for Managing Big Data in Smart Cities Using Intel SGX** [[link]](https://ieeexplore.ieee.org/abstract/document/8513718)
  - (CloudCom '18) **SGX-FS: Hardening a File System in User-Space with Intel SGX**[[link]](https://ieeexplore.ieee.org/abstract/document/8590996) [[source code]](https://github.com/dburihabwa/sgx-fs)
     - a user-space in-enclave file system
     
### Security
- 2020
  - (preprint arXiv '20) **Secure Cloud Storage with Client-Side Encryption Using a Trusted Execution Environment** [[link]](https://arxiv.org/abs/2003.04163)
    - client side encryption
  - (CODASPY '20) **MOSE: Practical Multi-User Oblivious Storage via Secure Enclaves** [[link]](https://dl.acm.org/doi/abs/10.1145/3374664.3375749)
- 2019
  - **Pbsx: A practical private boolean search using Intel SGX** [[link]](https://www.sciencedirect.com/science/article/pii/S0020025520301079)
    - obliviousness, boolean search
  - (DSN '19) **NeXUS: Practical and Secure Access Control on Untrusted Storage Platforms using Client-Side SGX** [[link]](https://ieeexplore.ieee.org/document/8809505)
- 2018
  - (NDSS '18) **OBLIVIATE: A Data Oblivious Filesystem for Intel SGX** [[link]](https://pdfs.semanticscholar.org/1e41/72ab6fb7568c6235ba05d401dcace32f88a7.pdf)
    - obliviousness, file system of sgx
    
### Other Materials
- Recent Trends of TEE implementaion(RISC-V, ARM, etc) [[slide]](https://seminar-materials.iijlab.net/iijlab-seminar/iijlab-seminar-20181120.pdf)

