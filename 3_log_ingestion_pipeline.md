Design log ingestion pipeline for DNS logs:

Requirements:
- Handle 100K logs/sec spike
- No data loss
- Backpressure handling

Use:
- Kafka as ingestion buffer
- Fluent Bit for log shipping

Output:
- Kafka topic configuration
- Partition strategy
- Producer configuration
- Retention policy
