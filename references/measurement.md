# Measure Before and After

For performance, reliability, scraping, distributed-systems or operational changes, establish a baseline, then compare BEFORE → AFTER.

Method:
- Same conditions for both: inputs, data size, machine, config, cache state.
- Warm up first; then at least 3 runs each. Report the median and the spread (min–max), not one lucky run.
- If the difference is within the spread, call it noise, not an improvement.
- Measured beats extrapolated; if you extrapolate, label it as an estimate.

Useful measurements: latency, throughput, success rate, error rate, memory, CPU, bandwidth, request count, retries, timeout rate, database load, processed records, blocked requests.

Do not claim improvement without supporting evidence when measurement is practical. If it is not practical, say so and state the expected effect as a hypothesis.
