# LED Lighting Placement: Why Distance Matters

**Source**: Archipelagos Labs  
**Author**: John Cassidy  
**Year**: 2026

---

## Historical Context

The **Inverse Square Law** for light intensity was formally established in **1729** by French physicist **Pierre Bouguer** in his work on photometry. The law states that light intensity from a point source decreases proportionally to the square of the distance from the source.

**Formula**: `I ∝ 1/d²` (Intensity is inversely proportional to distance squared)

This document applies the inverse square law to LED lighting placement in agricultural and horticultural applications.

---

## The Simple Truth

**LED lights lose power quickly as you move away from them. Natural sunlight doesn't.**

---

## What Happens with LEDs?

### The Rule: Double the Distance = Quarter the Light

Light intensity diminishes according to the inverse square law:

- **At 1 meter**: Reference intensity - call this 100%
- **At 2 meters**: 25% of the 1-meter intensity
- **At 3 meters**: 11% of the 1-meter intensity
- **At 4 meters**: 6.25% of the 1-meter intensity

**Why?** Light spreads out in all directions from a point source. When you double the distance, the same light energy covers 4× the area, resulting in ¼ the intensity.

---

## What Happens with Natural Sunlight?

### The Rule: Distance Doesn't Matter (Practically)

Natural PAR from the sun works differently:

- **At 1 meter height**: Full sunlight
- **At 4 meters height**: Still full sunlight (no practical difference)

**Why?** The sun is 150 million kilometers away. Moving your plants a few meters closer or further makes zero difference. The distance to the sun is essentially the same.

---

## Visual Example

```
LED Light - Inverse Square Law:
┌─────────┐
│   LED   │
└─────────┘
    │
    │ 1m → 100% (reference)
    │
    │ 2m → 25%
    │
    │ 3m → 11%
    │
    │ 4m → 6.25%
    ▼


Natural Sun (Far):
        ☀️ ← 150,000,000 km away
        │
        │ Distance doesn't change
        │
        ▼
┌─────────┐
│ Plants  │ ← Full sunlight (height doesn't matter)
└─────────┘
```

---

## Real-World Impact

### LED Placement Strategy

**Problem**: If you double the distance from your LEDs to the canopy:
- You lose **75% of your LED light** (inverse square law: 1/2² = 1/4)
- Your plants get only **25% of what you're paying for**
- You waste electricity and money

**Solution**: Keep LEDs as close to the canopy as practical to maximize efficiency. Halving the distance quadruples the light intensity.

### Natural Light Strategy

**Reality**: Canopy height doesn't affect natural sunlight. Whether your plants are 1m or 4m from the ground, they get the same natural PAR from the sun.

---

## The Physics (Simple Explanation)

### Why LEDs Lose Power with Distance

**The Problem**: Light spreads out in all directions from a point source (like an LED).

**The Physics**: 
- Light energy spreads over a **sphere** (like a balloon inflating)
- The surface area of a sphere = 4 × π × radius²
- When distance doubles, the sphere's surface area becomes **4 times bigger**
- Same amount of light energy spread over 4x the area = **1/4 the intensity**

**Simple Analogy**: 
- Imagine spraying paint from a can
- At 1 meter: paint covers 1 square meter (thick coverage)
- At 2 meters: paint covers 4 square meters (thin coverage - 1/4 as thick)
- Same amount of paint, but spread thinner

### Why Natural Sunlight Doesn't Change

**The Physics**:
- The sun is **150,000,000,000 meters** away
- Moving plants a few meters closer = essentially 0% change
- The distance is so huge that tiny movements make **zero practical difference**

**Simple Analogy**:
- You're 1 kilometer from a mountain
- Moving 1 meter closer doesn't change how big the mountain looks
- The distance is already so large that 1 meter is nothing

---

## The Math (Simplified)

### LEDs: Inverse Square Law

- **Distance doubles** → **Light becomes 4× weaker** (1/2² = 1/4)
- **Distance halves** → **Light becomes 4× stronger** (1/0.5² = 4)
- Formula: I₂ = I₁ × (d₁/d₂)²

**Examples using 1m as reference**:
- 1m → 2m: I × (1/2)² = I × 0.25 = **25% of original**
- 1m → 0.5m: I × (1/0.5)² = I × 4 = **400% of original**

### Natural Sun: No Practical Change

- **Distance to sun**: 150,000,000,000 meters
- **Moving plants**: a few meters
- **Change**: essentially 0% (negligible)

---

## The Algorithm (Simple Form)

### Step-by-Step Calculation

**For LEDs:**

1. **Choose a reference distance** (e.g., 1m = reference intensity I)
2. **Measure new distance** (e.g., 2m)
3. **Calculate ratio**: Reference Distance ÷ New Distance
   - Example: 1 ÷ 2 = 0.5
4. **Square the ratio**: (Ratio)²
   - Example: 0.5² = 0.25
5. **This gives you the fraction of original intensity**
   - Example: I × 0.25 = **25% of reference intensity**

**Result**: At 2m, you get 25% of the light intensity you had at 1m.

### Quick Reference Table (Relative to 1m Reference)

| Distance | Intensity | Calculation |
|----------|-----------|-------------|
| 1m       | 100% (reference) | 1/(1)² = 1 |
| 2m       | 25%       | 1/(2)² = 0.25 |
| 3m       | 11%       | 1/(3)² = 0.11 |
| 4m       | 6.25%     | 1/(4)² = 0.0625 |

---

## The Algorithm (Mathematical Form)

### Inverse Square Law Formula

```
I₂ = I₁ × (d₁ / d₂)²

Where:
  I₁ = Light intensity at distance d₁ (reference)
  I₂ = Light intensity at distance d₂
  d₁ = Reference distance (e.g., 1m)
  d₂ = New distance (e.g., 2m)

Using 1m as 100% reference shows how intensity diminishes with distance.
```

### Implementation (Pseudocode)

```
FUNCTION calculateLightIntensity(referenceDistance, newDistance, referenceIntensity):
    // Calculate distance ratio
    ratio = referenceDistance / newDistance
    
    // Apply inverse square law
    newIntensity = referenceIntensity × (ratio × ratio)
    
    // Calculate percentage loss
    percentageLoss = (1 - (ratio × ratio)) × 100
    
    RETURN {
        intensity: newIntensity,
        percentage: (ratio × ratio) × 100,
        loss: percentageLoss
    }
END FUNCTION

// Example usage (using 1m as reference):
result = calculateLightIntensity(1.0, 2.0, 100)
// Returns: { intensity: 25, percentage: 25%, loss: 75% }
```

### JavaScript Implementation

```javascript
function calculateLEDLightIntensity(referenceDistance, newDistance, referenceIntensity) {
    // Calculate distance ratio
    var ratio = referenceDistance / newDistance;
    
    // Apply inverse square law: I₂ = I₁ × (d₁/d₂)²
    var newIntensity = referenceIntensity * (ratio * ratio);
    
    // Calculate percentage and loss
    var percentage = (ratio * ratio) * 100;
    var loss = (1 - (ratio * ratio)) * 100;
    
    return {
        intensity: parseFloat(newIntensity.toFixed(2)),
        percentage: parseFloat(percentage.toFixed(2)),
        loss: parseFloat(loss.toFixed(2)),
        ratio: parseFloat(ratio.toFixed(3))
    };
}

// Example: Calculate light at 2.0m when reference is 1.0m at 100%
var result = calculateLEDLightIntensity(1.0, 2.0, 100);
// Result: { intensity: 25, percentage: 25, loss: 75, ratio: 0.5 }
```

### Python Implementation

```python
def calculate_led_light_intensity(reference_distance, new_distance, reference_intensity):
    """
    Calculate light intensity using inverse square law.
    
    Args:
        reference_distance: Distance where reference intensity is measured (meters)
        new_distance: New distance to calculate intensity for (meters)
        reference_intensity: Light intensity at reference distance (percentage or absolute)
    
    Returns:
        Dictionary with intensity, percentage, loss, and ratio
    """
    # Calculate distance ratio
    ratio = reference_distance / new_distance
    
    # Apply inverse square law: I₂ = I₁ × (d₁/d₂)²
    new_intensity = reference_intensity * (ratio ** 2)
    
    # Calculate percentage and loss
    percentage = (ratio ** 2) * 100
    loss = (1 - (ratio ** 2)) * 100
    
    return {
        'intensity': round(new_intensity, 2),
        'percentage': round(percentage, 2),
        'loss': round(loss, 2),
        'ratio': round(ratio, 3)
    }

# Example: Calculate light at 2.0m when reference is 1.0m at 100%
result = calculate_led_light_intensity(1.0, 2.0, 100)
# Result: {'intensity': 25.0, 'percentage': 25.0, 'loss': 75.0, 'ratio': 0.5}
```

### Natural Sunlight Calculation

```javascript
function calculateNaturalSunlightChange(plantHeightChange) {
    var sunDistance = 150000000000; // 150 million km in meters
    var originalDistance = sunDistance;
    var newDistance = sunDistance - plantHeightChange; // Moving closer
    
    // Calculate change using inverse square law
    var ratio = originalDistance / newDistance;
    var change = ((ratio * ratio) - 1) * 100;
    
    return {
        originalDistance: sunDistance,
        newDistance: newDistance,
        change: parseFloat(change.toFixed(10)),
        practicalChange: "Essentially zero"
    };
}

// Example: Moving plants 1.5m closer to sun
var result = calculateNaturalSunlightChange(1.5);
// Result: { change: 0.000000001%, practicalChange: "Essentially zero" }
```

---

## Key Takeaways

1. ✅ **Use 1m as reference (100%)** - compare all other distances to this
2. ✅ **Double the distance = quarter the light** (inverse square law)
3. ✅ **Halve the distance = quadruple the light** (works both ways)
4. ✅ **Natural sunlight** is unaffected by canopy height
5. ✅ **LED placement matters** - natural light placement doesn't

---

## Bottom Line

**LEDs**: Distance = Everything. Keep them close.

**Natural Sun**: Distance = Nothing. It doesn't matter.

You can't fix LED placement by moving plants. You can only fix it by moving the LEDs closer.

---

## Attribution

**Document Source**: Archipelagos Labs  
**Document Author**: John Cassidy  
**Document Year**: 2026

**Inverse Square Law**:  
- **Published**: 1729  
- **Author**: Pierre Bouguer  
- **Work**: "Essai d'optique sur la gradation de la lumière" (Essay on Optics on the Gradation of Light)

**Application**: This document applies the inverse square law (1729) to LED lighting placement in agricultural and horticultural applications.

---

© 2026 Archipelagos Labs. All rights reserved.
