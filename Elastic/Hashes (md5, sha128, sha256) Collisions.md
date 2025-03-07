# Hashes (md5, sha128, sha256) and Collisions

## Introduction to Hashes

- **Hashes** are digital fingerprints of data. They are generated using algorithms that take input data of any size and produce a fixed-size string of characters, known as a hash value or digest.
    
- Hashes are used for data integrity, authenticity, and security.
    

## Common Hash Algorithms

1. **MD5 (Message-Digest Algorithm 5)**
    
    - **Output Size**: 128 bits (32 hexadecimal digits).
        
    - **Security**: Considered insecure due to vulnerabilities like collisions (different inputs producing the same hash).
        
    - **Use Cases**: Still used for non-security purposes like file integrity checks.
        
2. **SHA-1 (Secure Hash Algorithm 1)**
    
    - **Output Size**: 160 bits (40 hexadecimal digits).
        
    - **Security**: Also considered insecure due to vulnerabilities similar to MD5.
        
    - **Use Cases**: Not recommended for security applications.
        
3. **SHA-256 (Secure Hash Algorithm 256)**
    
    - **Output Size**: 256 bits (64 hexadecimal digits).
        
    - **Security**: More secure than MD5 and SHA-1, resistant to collisions and brute-force attacks.
        
    - **Use Cases**: Recommended for security applications, such as password storage and data integrity checks.
        

## Key Differences

- **Output Size**: MD5 (128 bits), SHA-1 (160 bits), SHA-256 (256 bits).
    
- **Security**: SHA-256 is more secure than MD5 and SHA-1.
    
- **Performance**: SHA-256 is slower to compute than MD5 and SHA-1.
    

## Notes for Remembering

- **MD5** is fast but insecure.
    
- **SHA-1** is slightly more secure than MD5 but still insecure.
    
- **SHA-256** is the most secure and recommended for security applications.
    

## Example Use Cases

- **File Integrity**: Use MD5 or SHA-256 to verify that a downloaded file has not been corrupted.
    
- **Password Storage**: Use SHA-256 or other secure algorithms for storing passwords securely.
***
# What is a Collision?

A **collision** occurs when two different input values produce the same output hash value using a hash function. This means that the hash function maps different data to the same fixed-size string of characters, known as a hash value or digest.

## Types of Collisions

1. **Classical Collision Attack**: This involves finding two distinct messages that produce the same hash value.
    
2. **Chosen-Prefix Collision Attack**: Given two different prefixes, find suffixes such that the concatenation of each prefix with its respective suffix produces the same hash value.
    
## Impact of Collisions

- **Security Risks**: Collisions can compromise data integrity and authenticity. For example, if two different files have the same hash, it might indicate tampering or unauthorized modifications.
    
- **Vulnerabilities**: Collisions can be exploited to create fake digital signatures or manipulate data without detection.
    

## Examples

- **MD5 Collisions**: MD5 is known to be vulnerable to collisions. In 2005, researchers demonstrated creating two X.509 certificates with different public keys but the same MD5 hash.
    
- **SHA-1 Collisions**: SHA-1 has also been shown to be vulnerable to collisions, though it is less severe than MD5.
    

## Mitigation

- **Use Secure Hash Algorithms**: SHA-256 and other members of the SHA-2 family are considered more secure and resistant to collisions.
    
- **Regularly Update Algorithms**: As vulnerabilities are discovered, it's crucial to update hash functions to more secure versions.
