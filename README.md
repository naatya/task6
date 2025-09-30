**Research on Common Password Attacks**

Understanding the threats is crucial for creating defensive passwords. The two most common forms of password attacks are:

**Brute Force Attack:**

        Mechanism: An attacker attempts every possible character combination until the correct password is found.

        Defense: This attack is countered primarily by password length. A longer password exponentially increases the required time for the attack to succeed.

**Dictionary Attack:**

        Mechanism: An attacker uses a pre-compiled list of common words, phrases, names, and previously leaked passwords (a "dictionary") to quickly test against a target account.

        Defense: This attack is countered by complexity and uniqueness—avoiding common words, using symbols, and adding irregular capitalization.
        
**Summary: How Complexity Affects Security**

Password complexity directly translates to entropy (randomness) and thus, security.

    Increased Character Set: Using uppercase, lowercase, numbers, and symbols increases the number of available characters (the 'keyspace'), making each position in the password harder to guess. The search space for an attacker grows multiplicatively.

    Increased Length: Adding more characters increases the number of positions an attacker must guess. The total number of possibilities grows exponentially with length. For example, moving from an 8-character password to a 14-character password, even with the same character set, can increase the cracking time from seconds to millions of years.

Conclusion: Strong security requires passwords that combine maximum length (to defeat brute force) and high complexity (to defeat dictionary attacks and pattern recognition).
