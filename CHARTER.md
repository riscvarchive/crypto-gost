# GOST-R Crypto Extension Task Group Charter

RISC-V International is committed to helping members succeed in specialized and regional markets 
where the flexibility of the RISC-V ISA offers a unique advantage in relation to cryptographic 
algorithm support and performance.

The focus of the GOST-R Crypto Extension TG (GOST-TG) is to investigate, evaluate, and specify 
ISA extensions for the implementation of Russian defined-symmetric cryptography. The main 
algorithms in scope are defined in GOST R 34.12-2015 ("Kuznyechik" and "Magma" block ciphers) 
and GOST R 34.11-2012 ("Streebog" cryptographic hash function). The goal of the extension is to 
both improve performance and also to reduce the risk of security vulnerabilities such as timing 
attacks in RISC-V cryptographic stacks. Quantitative analysis (e.g. modes of operation) is 
primarily based on use cases in IETF, ETSI, and 3GPP/5G security protocols and required platform 
security features. The TG may propose both stand-alone extensions and ones that work in conjunction 
with other extensions (such as vector, scalar cryptography, and bit manipulation).

NOTE: The initial algorithm selection rationale is from GOST / TLS 1.2 
(https://www.ietf.org/id/draft-smyshlyaev-tls12-gost-suites-18.html) and GOST / TLS 1.3 
(https://www.ietf.org/id/draft-smyshlyaev-tls13-gost-suites-05.html) which themselves correspond 
to ratified standard protocol specifications R 1323565.1.020-2020 and R 1323565.1.030-2020.
