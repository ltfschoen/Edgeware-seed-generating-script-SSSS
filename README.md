# Edgeware-seed-generating-script-SSSS
A set of short scripts that will create a main mnemonic phrase from which it derives 3 keys for validator registration during the lockdrop period without exposing the seed on screen. The resulting output are the three public keys and addresses. Two keys are generated by sr25519 and last one by Ed25519 encryption. The second script uses Shamirs Secret Sharing Scheme to divide the mnemonic into 5 set of hashes from which a minimum of 3 are needed to reconstruct the mnemonic phrase. The only output of the first script are the three public keys and addresses. The second one will output 5 shares of the scheme.
