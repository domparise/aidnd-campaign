# Reference System
Documentation for the UUID-based reference system used to track campaign elements.

## UUID Structure
- **Character UUIDs**
  * Unique per character
  * Used in development logs
  * Referenced in interactions

- **Thread UUIDs**
  * One per thread
  * Tracks continuity
  * Links related content

- **Interaction UUIDs**
  * Generated per session
  * Documents key developments
  * References character UUIDs

## Implementation
1. **UUID Generation**
- Use provided UUID generator
- Store in references directory
- Document in relevant files

2. **Reference Format**
- Use `ref:[UUID]` syntax
- Include in development logs
- Reference in character files

3. **Tracking System**
- Log all interactions
- Maintain reference consistency
- Update documentation regularly