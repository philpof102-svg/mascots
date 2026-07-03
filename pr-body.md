## Summary

Open sources the **mascots** project — animated mascots for developer tools. Toshi is the first mascot, ready for community use.

### What is Mascots?

A collection of animated mascots that can be integrated into developer tools and IDEs. Think of it like Zero's assistant panel that appears on the right side of your screen while coding — but with personality!

### Toshi Mascot

Toshi is a friendly robot mascot with:
- **15 viseme codes** for lip-sync animation
- **Multiple states**: idle, look_around, pointing, hand_wave, dancing, celebration
- **Expressive eyes** with random blinking/cycling
- **Runtime file**: toshi.riv (~2.1MB) for Rive runtime
- **Source file**: toshi.rev (~4.9MB) for Rive editor

### Changes

- Updated Toshi metadata with community-focused description
- Changed status from `draft` to `ready`
- Tags updated: `draft` → `community`, added `ready`
- Rebuilt manifest (dist/mascots.json)

### Validation

- ✅ `test:manifest` - Validated manifest with 2 mascots
- ✅ `test:schema` - Validated against schema
- ✅ `test:state-engine` - State engine validation passes

### Files

```
mascots/toshi/mascot.json    # Updated metadata
dist/mascots.json            # Rebuilt manifest
```

---

This PR marks the beginning of open sourcing our mascot assets for the community. Future mascots will follow the same pattern.
