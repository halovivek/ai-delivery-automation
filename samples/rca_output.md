## Incident Summary
Payment API experienced intermittent failures due to latency spikes.

## Root Cause
Database connection pool exhaustion caused request timeouts.

## Impact
- Failed transactions
- Customer dissatisfaction

## Fix Implemented
- Increased connection pool size
- Optimized query performance

## Preventive Actions
- Add monitoring alerts
- Implement auto-scaling
