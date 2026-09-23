# CSPC - Computer Science for Physics and Chemistry

My coursework repository. Each practical is under PW<n>/Lab <X>/.
## PW1 - Lab A: Reproducible Foundations

**What I built:**
- I created a reproducible Python environment for the radioactive decay simulation.
- I used Git for version control and tested the NumPy and pure-Python implementations.

**Speed comparison (loop vs NumPy):**
- loop: 1.9473 s
- numpy: 0.0002 s
- speed-up: 8380.72 x faster

**Tests:** all passing? yes

**Conclusion:**
- All three tests passed successfully. The NumPy implementation was much faster than the pure-Python loop, showing the advantage of vectorised operations.

## PW1 - Lab B: Data, Plotting, and Automation

**What the data showed:**
- The observed atom count decreased over time.

**Comparison with the analytical law:**
- The observed data followed the same general decay trend as the analytical law.

**Snakemake pipeline:**
- Snakemake automatically generates figure.png from decay_observed.csv by running plot.py.
- If the output is already up to date, Snakemake does not run the job again.