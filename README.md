# Proof of Concept demonstrating the CI Cache Poison critical vulnerability

You can check https://github.com/kolya5544/PoC_CI_Poison/tree/demonstration branch to see how it's done. You're currently looking at master, where the commit history has been rewritten to obscure the cache poison.

This is a benign commit that does not actually introduce any malware. However, the artifact produced in this run will contain attacker-controlled executable binary.
