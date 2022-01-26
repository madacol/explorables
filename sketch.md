# Agents

## Parameters

- ? bias_spectrum: multidimensional vector

- Sharing
  - liar: %
  - ? fact_mutation_rate: % / dimension?
  - confidence_to_share: %
- Consuming
  - ? sources: [{
      id,
      sharing_accuracy: %
    }]
        ↑ Maybe only related to specific behaviors?
  - verify_prob: %
  - verify_delay: int
  - recency_preference: %
  - bias_preference: %
  - behavior: enum()

## Strategies

- keep track and build reputation of sources
- random sources

# Facts

- verifiability: %