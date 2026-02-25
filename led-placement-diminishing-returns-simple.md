# LED Lighting: A Simple Guide to Distance

**Source**: Archipelagos Labs  
**Author**: John Cassidy  
**Year**: 2026

---

## Quick Summary

**The main idea**: LED lights work best when they're close to your plants. The further away they are, the less light your plants get.

**The simple rule**: If you double the distance, you get only one-quarter of the light.

---

## What You Need to Know

### LED Lights

**The Problem**: 
- LED lights are like flashlights - they shine in one direction
- The further away they are, the more the light spreads out
- Spread out light = weaker light for your plants

**How Light Diminishes** (Inverse Square Law):
- **At 1 meter**: Reference intensity (call this 100%)
- **At 2 meters**: 25% of the 1-meter value
- **At 3 meters**: 11% of the 1-meter value
- **At 4 meters**: 6.25% of the 1-meter value

**The Rule**: Every time you double the distance, you get only **one-quarter** of the light.

**What This Means**:
- If your LEDs are too high, your plants won't get enough light
- You'll waste electricity and money
- Your plants won't grow as well

**The Solution**:
- Keep LEDs as close to your plants as practical
- Don't hang them too high
- Move the lights closer, not the plants further away

### Natural Sunlight

**The Good News**:
- Natural sunlight from the sun works completely differently
- The sun is so far away (150 million kilometers!) that moving your plants a few meters makes no difference at all
- Whether your plants are 1 meter or 4 meters from the ground, they get the same sunlight

**What This Means**:
- You don't need to worry about plant height affecting natural sunlight
- The sun is already so far away that small changes don't matter

---

## Visual Examples

### LED Light (Inverse Square Law)
```
LED Light
   │
   │ 1m → 100% (reference)
   │
   │ 2m → 25%
   │
   │ 3m → 11%
   │
   │ 4m → 6.25%
   ▼
```

### Natural Sunlight
```
Sun (150 million km away)
   │
   │ Distance doesn't change
   │
   ▼
Plants ← Full sunlight (height doesn't matter)
```

---

## Practical Tips

### ✅ Do This:
- Keep LED lights as close to your plants as practical
- Check your light height regularly
- Adjust LED height as plants grow
- Use natural sunlight when possible (it's free!)

### ❌ Don't Do This:
- Hang LEDs too high (you'll waste light and money)
- Think moving plants will fix LED distance problems
- Assume all light works the same way

---

## Why This Happens

**Simple Explanation**:
- Light spreads out in all directions (like a balloon getting bigger)
- When you double the distance, the light has to cover 4 times the area
- Same amount of light spread over 4 times the area = 1/4 the strength

**Real-World Comparison**:
- Think of spraying paint from a can
- Close up: thick paint on a small area
- Far away: thin paint spread over a big area
- Same amount of paint, but much thinner when spread out

---

## Quick Reference

| Distance | Relative to 1m | Calculation |
|----------|----------------|-------------|
| 1m       | 100% (reference) | 1/(1)² = 1 |
| 2m       | 25%            | 1/(2)² = 0.25 |
| 3m       | 11%            | 1/(3)² = 0.11 |
| 4m       | 6.25%          | 1/(4)² = 0.0625 |

**The Formula**: Intensity ∝ 1/distance²

**Key Insight**: Halving the distance gives you 4× the light; doubling the distance gives you only ¼ the light.

---

## Glasshouse Vertical Growing: What You Need to Know

In a glasshouse with vertical shelving, light becomes complicated. Unlike open fields, you're dealing with structures, seasons, and multiple growing levels.

### The Sun Moves - Your Light Changes

**Throughout the Year**:
- **Summer solstice** (June 21): Sun is highest in the sky (~62° at UK latitudes)
- **Winter solstice** (December 21): Sun is lowest (~15° at UK latitudes)
- **Equinoxes** (March 21, September 21): Sun at middle height (~38°)

**What This Means**:
- In summer, light comes from almost directly overhead
- In winter, light comes in at a low angle through the sides
- Your shelves receive very different light depending on the season

### The A-Frame Shading Problem

A typical 4-metre A-frame structure creates shadows:

```
Summer (high sun):              Winter (low sun):
      ☀️ (62°)                        ☀️ (15°)
        \                               \
         \                               \
    ┌─────┐                         ┌─────┐
    │  A  │                         │  A  │
    │frame│ ← Short shadow          │frame│ ← Long shadow
    └─────┘                         └─────┘
      ▓▓                              ▓▓▓▓▓▓▓▓▓▓▓▓
```

**Shadow length from a 4m structure**:
- Summer (62° sun): ~2m shadow
- Equinox (38° sun): ~5m shadow
- Winter (15° sun): ~15m shadow

### Multi-Level Shelving: Each Level is Different

```
┌─────────────────────────────┐
│ Top shelf    │ Most light   │ ← Best for high-light crops
├─────────────────────────────┤
│ Middle shelf │ Partial shade│ ← Moderate-light crops
├─────────────────────────────┤
│ Bottom shelf │ Heavy shade  │ ← Low-light crops only
└─────────────────────────────┘
```

**The Reality**:
- Top shelves may get 100% available light
- Middle shelves may get 40-60%
- Bottom shelves may get only 10-20%

### Shade Avoidance Response

Plants know when they're being shaded. They respond by:
- **Stretching** towards light (etiolation)
- **Thinner leaves** to capture more light
- **Reduced flowering** and fruiting
- **Pale, weak growth**

This is called the **shade avoidance response** - plants waste energy trying to outgrow their neighbours instead of producing fruit.

### ePAR: The Light Plants Actually Use

**What is ePAR?**
- ePAR = Extended Photosynthetically Active Radiation
- The wavelengths plants use: **400-700nm** (visible light)
- Measured in **µmol/m²/s** (micromoles per square metre per second)

**Target ePAR Ranges**:

| Crop Type | ePAR Range (µmol/m²/s) |
|-----------|------------------------|
| Leafy greens | 200-400 |
| Herbs | 300-500 |
| Tomatoes, peppers | 400-600 |
| High-light crops | 600-1000+ |

**Below minimum ePAR**: Poor growth, weak plants, low yields
**Above maximum ePAR**: Wasted energy, potential light stress

### Why PAR Sensors Are Critical

**You cannot guess light levels.** You must measure them.

**Without sensors, you're guessing**:
- How much light reaches each shelf?
- How does it change through the day?
- How does it change through the seasons?
- Are your LEDs actually helping?

**With sensors, you know**:
- Exact ePAR at each growing position
- When natural light is sufficient
- When to turn LEDs on/off
- Which shelves need supplemental lighting

### Misting and Fogging: The Hidden Light Blocker

Misting systems are essential for humidity and cooling, but they affect light in ways growers often overlook.

**What Happens When You Mist**:
```
Without mist:               With mist:
     ☀️                          ☀️
      │                           │
      │ (direct light)           ░░░ ← Water droplets
      │                          ░░░   scatter light
      ▼                           │
   Plants                        ▼
   (100% light)               Plants
                              (reduced light)
```

**How Mist Reduces Light**:
- Water droplets **scatter** incoming light in all directions
- Some light is **reflected** back upward, never reaching plants
- Fine mist creates a "fog" that blocks direct radiation
- Effect is worse with fine droplets (more surface area)

**The Impact**:
- Heavy misting can reduce PAR by **10-30%**
- Effect is temporary but cumulative over day
- Lower shelves affected more (light passes through multiple mist zones)

**Practical Advice**:
- Time misting for early morning or late afternoon when light is less critical
- Avoid misting during peak sunlight hours (10am-2pm)
- Use coarser droplets where possible (less scattering)
- Monitor PAR during misting cycles to understand actual impact
- Factor misting losses into your DLI calculations

### Simple Glasshouse Checklist

✅ **Measure first**: Install PAR sensors before making decisions
✅ **Map your light**: Record ePAR at each shelf level, multiple times per day
✅ **Track seasons**: Light in July ≠ light in December
✅ **Match crops to light**: Put high-light crops on top shelves
✅ **Supplement strategically**: Use LEDs only where and when needed
✅ **Watch for shade avoidance**: Stretchy, pale plants = not enough light
✅ **Time your misting**: Avoid misting during peak light hours

---

## Bottom Line

**For LED Lights**:
- Distance matters a lot
- Closer = better light = better growth
- Double the distance = quarter the light (inverse square law)

**For Natural Sunlight**:
- Distance doesn't matter for intensity
- But angle, season, and structures change everything in a glasshouse

**For Glasshouse Vertical Growing**:
- Every shelf level is different - measure, don't assume
- Winter light ≠ summer light
- PAR sensors are essential, not optional
- Match crops to available light at each position

**For Misting Systems**:
- Misting can reduce light by 10-30%
- Lower shelves are hit hardest (they rely on diffuse light)
- Time misting for early morning or late afternoon, not peak sunlight

**Key Takeaway**: 
You cannot manage what you do not measure. Install PAR sensors, map your light environment, and make data-driven decisions.

---

## Need Help?

If you're not sure about your LED placement:
1. Measure the distance from your LEDs to your plants
2. Use the reference table to see relative intensity at that distance
3. Remember: halving the distance quadruples the light intensity

---

## Attribution

**Source**: Archipelagos Labs  
**Author**: John Cassidy  
**Year**: 2026

This guide is based on the inverse square law, a principle discovered in 1729 by Pierre Bouguer. We've simplified it to make it easy to understand and apply to your growing setup.

---

© 2026 Archipelagos Labs. All rights reserved.
