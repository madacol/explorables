# Agents

## Parameters

- ? bias_spectrum: multidimensional vector

- Sharing
  - liar: %
  - ? fact_mutation_rate: % / dimension?
  - confidence_to_share: %
- Consuming
  - verify_prob: %
  - verify_delay: int
  - recency_preference: %
  - bias_preference: %
  - behavior: enum()

## Strategies

### Axis
- bias to follow sources
- build reputation ({
      sharing_accuracy: %
    })
- sharing threshold

<!-- ### consuming
- random sources
- biased following sources

### reputation
- no
- build reputation

### sharing
- get random source, no reputation
- get random source, build reputation by verifying
- follow with bias, and build reputation by verifying
- keep track and build reputation of sources -->

# Facts

Expertise can be modeled as having more resolution bits in a subject knowledge (axis)

When producing information, we are sharing specific bits

- verifiability: %