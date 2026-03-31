Design a scalable log processing architecture for DNS logs with the following constraints:

- Baseline: 5,000 logs/sec
- Spike: 100,000 logs/sec for 10 minutes daily
- Budget: $800/month

Requirements:
- No data loss during spikes
- Real-time ingestion
- Buffering layer required
- Searchable storage
- Daily reporting

Constraints:
- Prefer open-source or low-cost AWS services
- Avoid over-engineered expensive solutions

Output:
- Architecture diagram (text)
- Component list with justification
- Data flow explanation
