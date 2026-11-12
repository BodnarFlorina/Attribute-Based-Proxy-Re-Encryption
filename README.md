# Attribute-Based Proxy Re-Encryption

## Summary

This master's dissertation explores **Attribute-Based Proxy Re-Encryption (AB-PRE)**, focusing on cryptographic mechanisms for secure data sharing and fine-grained access control.

In cloud environments, data owners cannot rely solely on storage providers to enforce confidentiality. Attribute-Based Encryption (ABE) enables access policies to be enforced cryptographically, while Proxy Re-Encryption (PRE) allows decryption rights to be delegated without requiring the data owner to decrypt and re-encrypt the information.

Their combination, AB-PRE, joins the expressive access policies of ABE with the flexible delegation of PRE.

## 🔬 Main Contribution

The dissertation investigates a structural relationship between **Key-Policy Attribute-Based Encryption (KP-ABE)** and **Ciphertext-Policy Attribute-Based Encryption (CP-ABE)**.

Although these approaches are commonly described as dual architectures, the research examines whether this relationship can be expressed explicitly through their underlying algebraic constructions.

The main contributions include:

- Defining **a structural transformation S** that derives the analyzed CP-ABE construction from a KP-ABE construction, examining the Setup, Encrypt, KeyGen, and Decrypt algorithms.

- Identifying three elementary structural operations underlying the transformation and distinguishing the components that follow from it from those requiring independent construction.

- Demonstrating that the transformation transfers **correctness, but not automatically security guarantees**, due to differences in the underlying security models and assumptions.

- Exploring the relationship between this transformation and proxy re-encryption, including its relevance to ReKeyGen and the structural connections between KP-ABPRE and CP-ABPRE.

## 📚 Contents

| Chapter | Topic |
|---|---|
| 1 | Introduction: context, motivation, objectives, and contributions |
| 2 | Cryptographic foundations: bilinear maps, security assumptions, secret-sharing schemes, and security models |
| 3 | Attribute-Based Encryption: from IBE and Fuzzy IBE to KP-ABE and CP-ABE |
| 4 | Proxy Re-Encryption and CP-ABPRE: architecture, security properties, and comparison of existing schemes |
| 5 | **Original contribution:** structural transformation from KP-ABE to CP-ABE, correctness and security analysis, and implications for proxy re-encryption |
| 6 | Conclusions and future research directions |

## Keywords

`cryptography` · `attribute-based-encryption` · `proxy-re-encryption` · `CP-ABE` · `KP-ABE` · `access-control` · `secret-sharing` · `cloud-security` · `bilinear-pairings`

