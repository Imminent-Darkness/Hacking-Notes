# Hashcat

*********************************************************************************
Items inside [SQUARE-BRACKETS] indicate changeable (fill in the blank) fields.  
Note: Bracket characters themselves [ ] require removal. See examples.
*********************************************************************************

## Basic Dictionary Attack
```
hashcat -m [HASH-TYPE-CODE] -a 0 [HASH-FILE] [WORDLIST]
```
Example:
```
hashcat -m 1800 -a 0 hashes.txt wordlists/rockyou.txt
```