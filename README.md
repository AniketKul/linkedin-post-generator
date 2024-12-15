# linkedin-post-generator
linkedin-post-generator

## Architectural Overview

### Phase 1: Preprocessing

Raw Posts -> Preprocessing (using Llama3.2) -> Enriched Posts (Topic, Language, Length)

### Phase 2: Generation

Enriched Posts (Topic, Language, Length) -> Generate Prompt -> Generate Post (using Llama3.2)

