# linkedin-post-generator
linkedin-post-generator

## Architectural Overview

### Phase 1: Preprocessing

Raw Posts -> Preprocessing (using llama-3.3-70b-versatile) -> Enriched Posts (Topic, Language, Length)

### Phase 2: Generation

Enriched Posts (Topic, Language, Length) -> Generate Prompt -> Generate Post (using llama-3.3-70b-versatile)

