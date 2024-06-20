
Simulated a 5 stage scalar pipleined processor model in C++.

The stages include 
1. Fetch
2. Decode
3. Execute
4. Memory access
5. Write back

Features:
- The code handles RAW (Read After Write) data dependency by stalling instructions.
- Control hazrds during branch instructions are handled by stalls.

Further Scope:
- Implement Discrete State Branch Prediction Unit
- Hnadling cache misses
