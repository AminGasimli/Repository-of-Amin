## PW1 --- Lab A: Radioactive Decay Simulation

### Speed Comparison Results
- **Pure-Python loop time:** 2.7887 seconds *
- **NumPy vectorised time:** 0.0003 seconds *
- **Speed-up factor:** ~9176.89x faster

### Test Status
- `pytest -v` output: **3 passed** in 0.12s

### Conclusion
Using NumPy's vectorised operations significantly outperforms pure-Python loops for simulating radioactive decay, reducing execution time drastically while maintaining accurate stochastic results.
