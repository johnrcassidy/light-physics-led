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

Light intensity diminishes according to the inverse square law.

**Establishing the Reference (Baseline)**:
The reference distance is the distance from the LED to the nearest shelf - this is your baseline measurement (100%). All other intensities are calculated relative to this baseline.

- **At reference distance (LED to nearest shelf)**: 100% intensity (baseline)
- **At 2× reference distance**: 25% of baseline intensity
- **At 3× reference distance**: 11% of baseline intensity
- **At 4× reference distance**: 6.25% of baseline intensity

**Why?** Light spreads out in all directions from a point source. When you double the distance from your baseline, the same light energy covers 4× the area, resulting in ¼ the intensity.

---

## What Happens with Natural Sunlight?

### The Rule: Distance Doesn't Matter (Practically)

Natural PAR from the sun works differently:

- **At 1 metre height**: Full sunlight
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

**Solution**: Keep LEDs as close to the canopy as practical to maximise efficiency. Halving the distance quadruples the light intensity.

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
- At 1 metre: paint covers 1 square metre (thick coverage)
- At 2 metres: paint covers 4 square metres (thin coverage - 1/4 as thick)
- Same amount of paint, but spread thinner

### Why Natural Sunlight Doesn't Change

**The Physics**:
- The sun is **150,000,000,000 meters** away
- Moving plants a few meters closer = essentially 0% change
- The distance is so huge that tiny movements make **zero practical difference**

**Simple Analogy**:
- You're 1 kilometre from a mountain
- Moving 1 metre closer doesn't change how big the mountain looks
- The distance is already so large that 1 metre is nothing

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

## Glasshouse Vertical Growing Environments

Vertical growing in glasshouses introduces complex light dynamics that demand careful analysis. Unlike open-field agriculture, controlled environment agriculture (CEA) must account for structural shading, seasonal solar progression, multi-level canopy management, and plant physiological responses to suboptimal light.

### Solar Progression: Equinoxes and Solstices

The sun's position changes dramatically throughout the year, fundamentally altering light distribution within a glasshouse.

**Solar Elevation Angles (UK latitudes, ~52°N)**:

| Date | Event | Solar Elevation (noon) | Day Length |
|------|-------|------------------------|------------|
| June 21 | Summer Solstice | ~62° | ~16.5 hours |
| March 21 / Sept 21 | Equinoxes | ~38° | ~12 hours |
| December 21 | Winter Solstice | ~15° | ~7.5 hours |

**Implications for Glasshouse Design**:

```
SIDE VIEW (cross-section, looking from east or west):

Summer Solstice (62°):           Winter Solstice (15°):
         ☀️                              ☀️
          │                                \
          │ (steep angle)                   \ (shallow angle)
          ▼                                  \
    ┌──────────┐                        ┌──────────┐
    │ Glasshouse│                       │ Glasshouse│
    │  roof    │                        │  roof    │
    └──────────┘                        └──────────┘
         │                                    │
    Light penetrates                   Light enters
    from above                         from the side
    ══════════════                     ══════════════
        Floor                              Floor
```

**Seasonal Light Behaviour**:
- **Summer**: High sun angle means light enters predominantly through the roof. Upper shelves receive direct light; lower shelves are shaded by upper structures.
- **Winter**: Low sun angle means light enters through side walls. Orientation becomes critical - south-facing walls receive most light.
- **Equinoxes**: Transitional periods where both roof and wall transmission contribute significantly.

### Photoperiod Dynamics

Photoperiod (day length) affects plant development independently of light intensity:

**Photoperiod-Sensitive Responses**:
- **Long-day plants** (lettuce, spinach): Flower when days exceed ~14 hours
- **Short-day plants** (chrysanthemums, poinsettias): Flower when days fall below ~12 hours
- **Day-neutral plants** (tomatoes, peppers): Flower based on maturity, not day length

**Glasshouse Considerations**:
- Natural photoperiod varies from 7.5 hours (winter) to 16.5 hours (summer) at UK latitudes
- Supplemental lighting extends photoperiod but must be managed to avoid triggering unwanted flowering
- Blackout systems may be required for short-day crop production in summer

### A-Frame and Structural Shading

A 4-metre A-frame structure (common in glasshouse construction) creates predictable shadow patterns based on solar geometry.

**Shadow Length Calculation**:

```
Shadow Length = Structure Height / tan(Solar Elevation Angle)

For a 4m structure:
- Summer (62°): 4 / tan(62°) = 4 / 1.88 = 2.1m shadow
- Equinox (38°): 4 / tan(38°) = 4 / 0.78 = 5.1m shadow  
- Winter (15°): 4 / tan(15°) = 4 / 0.27 = 14.9m shadow
```

**Shadow Impact Table**:

| Season | Solar Elevation | 4m Structure Shadow | Impact |
|--------|-----------------|---------------------|--------|
| Summer | 62° | 2.1m | Minimal - shadow stays close to structure |
| Equinox | 38° | 5.1m | Moderate - adjacent rows affected |
| Winter | 15° | 14.9m | Severe - shadows extend across multiple bays |

**Practical Implications**:
- Row orientation (N-S vs E-W) significantly affects shadow distribution
- N-S orientation: shadows move across rows throughout the day (more even distribution)
- E-W orientation: shadows fall consistently on north side (permanent shading of some areas)

### Multi-Level Shelf Light Distribution

In vertical farming systems, each shelf level receives fundamentally different light. A typical configuration comprises 4 shelf levels: **Shelves 1 and 2 are single aspect**, while **Shelves 3 and 4 are double aspect with east and west facing sides**.

```
SIDE VIEW (cross-section, looking from the south):

Glasshouse Cross-Section (4-Shelf Configuration):
                    ┌─────────────────────────────────┐
                    │            Roof glazing          │
                    └─────────────────────────────────┘
                                    │
                              Natural light
                                    ▼
┌─────────────────────────────────────────────────────────────────┐
│ Shelf 4 (Double) │ EAST aspect │ WEST aspect │ 100% available  │
│     (Top)        │   morning   │  afternoon  │ Direct + diffuse│
├─────────────────────────────────────────────────────────────────┤
│ Shelf 3 (Double) │ EAST aspect │ WEST aspect │ 60-80%          │
│                  │   morning   │  afternoon  │ Shaded by Shelf 4│
├─────────────────────────────────────────────────────────────────┤
│ Shelf 2 (Single) │      Centre aspect        │ 30-50%          │
│                  │                           │ Cumulative shade │
├─────────────────────────────────────────────────────────────────┤
│ Shelf 1 (Single) │      Centre aspect        │ 10-25%          │
│    (Bottom)      │                           │ Severe limitation│
└─────────────────────────────────────────────────────────────────┘
    ════════════════════════════════════════════════════════════
                               Floor
```

**Shelf Configuration Summary**:

| Shelf | Type | Aspects | Typical Light | Notes |
|-------|------|---------|---------------|-------|
| 4 | Double | East + West | 100% | Top level, maximum exposure |
| 3 | Double | East + West | 60-80% | Good light, some shading from above |
| 2 | Single | Centre | 30-50% | Moderate light, cumulative shading |
| 1 | Single | Centre | 10-25% | Lowest light, requires supplementation |

**East vs West Aspect Dynamics**:

The double shelves (3 and 4) present different light environments on each side:

| Time Period | East Aspect | West Aspect |
|-------------|-------------|-------------|
| Morning (6am-12pm) | Direct sun exposure | Shaded/diffuse only |
| Solar noon (12pm) | Transitioning | Transitioning |
| Afternoon (12pm-6pm) | Shaded/diffuse only | Direct sun exposure |

**Implications for Crop Placement**:
- **East aspects**: Better for crops sensitive to afternoon heat stress
- **West aspects**: Better for crops requiring maximum light accumulation
- **Single shelves (1 & 2)**: Require careful crop selection or supplemental LED lighting

**Light Attenuation Factors**:
1. **Structural shading**: Shelf frames, supports, irrigation systems
2. **Canopy shading**: Upper-level plants block light to lower levels
3. **Glazing transmission**: Glass/polycarbonate typically transmits 85-90% of light
4. **Cumulative losses**: Each level compounds the reduction
5. **Aspect orientation**: East/west aspects receive asymmetric light throughout the day

### Shade Avoidance Syndrome (SAS)

Plants have evolved sophisticated mechanisms to detect and respond to shading. This **shade avoidance syndrome** is triggered by changes in light quality, specifically the red:far-red (R:FR) ratio.

**Detection Mechanism**:
- Chlorophyll absorbs red light (660nm) but transmits far-red (730nm)
- Under canopy shade, R:FR ratio drops from ~1.2 (full sun) to ~0.2 (deep shade)
- Phytochrome photoreceptors detect this shift and trigger responses

**Shade Avoidance Responses**:

| Response | Description | Agricultural Impact |
|----------|-------------|---------------------|
| Stem elongation | Rapid internode extension | Weak, leggy plants; lodging risk |
| Leaf hyponasty | Leaves angle upward | Reduced light capture efficiency |
| Reduced branching | Apical dominance increases | Lower yield potential |
| Accelerated flowering | Early reproduction trigger | Premature bolting; reduced vegetative growth |
| Reduced chlorophyll | Pale, thin leaves | Lower photosynthetic capacity |
| Resource reallocation | Energy diverted to height growth | Reduced root development; lower fruit set |

**Management Strategies**:
- Maintain adequate spacing to prevent mutual shading
- Use supplemental lighting to improve R:FR ratios on lower shelves
- Select shade-tolerant varieties for lower positions
- Monitor for early signs: elongated internodes, pale leaves, upward leaf angles

### ePAR: Extended Photosynthetically Active Radiation

**Definition**: ePAR encompasses the wavelengths of light that drive photosynthesis in plants, defined as **400-750nm**. This extends beyond traditional PAR (400-700nm) to include far-red wavelengths that influence photomorphogenesis and the Emerson enhancement effect.

**Measurement**:
- Unit: **µmol/m²/s** (micromoles of photons per square metre per second)
- Instrument: Apogee ePAR quantum sensor
- Integration: Daily Light Integral (DLI) = µmol/m²/s × hours × 0.0036 = mol/m²/day

**ePAR Requirements by Crop Category**:

| Category | Examples | Min ePAR | Optimal ePAR | Max ePAR | Min DLI |
|----------|----------|----------|--------------|----------|---------|
| Low-light | Lettuce, spinach, microgreens | 150 | 200-400 | 600 | 12-17 |
| Medium-light | Herbs, strawberries, peppers | 300 | 400-600 | 800 | 17-25 |
| High-light | Tomatoes, cucumbers, cannabis | 400 | 600-1000 | 1500 | 25-40 |
| Very high-light | Roses, cut flowers | 500 | 800-1200 | 2000 | 30-50 |

**Consequences of Incorrect ePAR**:

| Condition | Symptoms | Outcome |
|-----------|----------|---------|
| Below minimum | Etiolation, pale leaves, slow growth | Crop failure; unmarketable produce |
| Below optimal | Reduced yield, extended crop cycle | Economic losses; inefficiency |
| At optimal | Healthy growth, maximum yield | Target condition |
| Above optimal | Wasted energy, no additional benefit | Unnecessary electricity costs |
| Above maximum | Leaf bleaching, heat stress, photoinhibition | Crop damage; reduced quality |

### The Critical Role of ePAR Sensors

**Why Measurement is Non-Negotiable**:

Human perception of light (lux, lumens) does not correlate with plant-usable radiation. A space that appears "bright" to humans may be severely light-limited for plants, and vice versa.

**Recommended Equipment**: Apogee ePAR sensors are the industry standard for horticultural light measurement. Apogee sensors provide accurate, calibrated measurements across the full extended photosynthetically active spectrum (400-750nm) with excellent cosine correction for oblique-angle readings.

**Data-Driven Decision Making**:

| Without Sensors | With Sensors |
|-----------------|--------------|
| Guessing LED runtime | Precise on/off scheduling |
| Uniform lighting across all levels | Targeted supplementation where needed |
| Seasonal surprises | Predictive adjustments |
| Over-lighting (waste) or under-lighting (poor yield) | Optimised energy use and plant performance |
| Reactive problem-solving | Proactive management |

**Sensor Selection Criteria** (Apogee ePAR sensors meet all criteria):
- **Spectral range**: Must cover 400-750nm (ePAR range)
- **Cosine correction**: Essential for accurate readings at oblique angles
- **Calibration**: NIST-traceable calibration recommended
- **Data logging**: Continuous recording enables DLI calculation and trend analysis
- **Connectivity**: IoT-enabled sensors allow remote monitoring and automated control

### Misting, Fogging, and Secondary Radiation Effects

Misting and fogging systems, while essential for humidity control and evaporative cooling, introduce significant but often overlooked impacts on light transmission and plant photosynthesis.

#### The Physics of Light Scattering by Water Droplets

When light encounters water droplets, several phenomena occur:

**Mie Scattering**: Droplets comparable in size to light wavelengths (0.4-0.7µm for PAR) scatter light in all directions. This is the dominant effect in horticultural misting systems where droplet sizes typically range from 10-100µm.

```
Incident Light Interaction with Water Droplet:
                    
        Reflected ↗   
                  \   
    Incoming → → → ●  → → → Transmitted (reduced)
    light         /|\        
                 / | \       
        Scattered in multiple directions
```

**Effects on PAR Transmission**:

| Droplet Size | Scattering Behaviour | PAR Reduction |
|--------------|---------------------|---------------|
| Fine fog (<20µm) | High scattering, long suspension time | 15-30% |
| Medium mist (20-50µm) | Moderate scattering, settles faster | 10-20% |
| Coarse spray (>50µm) | Lower scattering, rapid settling | 5-15% |

#### Blocking of Secondary (Diffuse) Radiation

In glasshouse environments, plants receive light from two sources:
1. **Direct radiation**: Sunlight travelling in straight lines from the sun
2. **Diffuse radiation**: Light scattered by atmosphere, clouds, and reflected from surfaces

**Critical Insight**: Misting disproportionately affects diffuse radiation because:
- Diffuse light arrives from all angles (hemisphere above canopy)
- Each path through the mist zone encounters scattering
- Lower shelves rely more heavily on diffuse light (direct light blocked by upper shelves)

```
Without Misting:                    With Misting:
                                    
   Direct ↓   Diffuse ↘ ↙ ↓        Direct ↓   Diffuse (scattered)
           \    │    /                    \    ░░░░░░
            \   │   /                      \   ░░░░░░
             \  │  /                        \  ░▓▒░░░
    ┌─────────────────┐            ┌─────────────────┐
    │   Top Shelf     │            │   Top Shelf     │
    │ (receives both) │            │ (reduced both)  │
    ├─────────────────┤            ├─────────────────┤
    │  Lower Shelf    │            │  Lower Shelf    │
    │ (diffuse only)  │            │ (severely reduced)│
    └─────────────────┘            └─────────────────┘
```

#### Quantifying Misting Impact on DLI

**Measurement Protocol**:
1. Record baseline PAR at each shelf level (no misting)
2. Activate misting system at normal operational settings
3. Record PAR at same positions during misting
4. Calculate percentage reduction
5. Multiply by daily misting duration to estimate DLI impact

**Example Calculation**:
```
Baseline PAR (no mist): 450 µmol/m²/s
PAR during misting: 360 µmol/m²/s
Reduction: (450-360)/450 = 20%

If misting operates 4 hours/day during peak light:
  - Peak light contribution: 4h × 450 = 1800 µmol/m² equivalent
  - With misting: 4h × 360 = 1440 µmol/m² equivalent
  - DLI loss: 360 µmol/m² equivalent = ~1.3 mol/m²/day
```

#### Thermal Radiation and Infrared Effects

Misting also affects thermal (infrared) radiation:

**Cooling Effect**: 
- Evaporative cooling reduces leaf temperature
- Lower leaf temperature can improve photosynthetic efficiency in heat stress conditions
- Trade-off: PAR reduction vs. thermal benefit

**Infrared Blocking**:
- Water droplets absorb and scatter infrared radiation
- Reduces radiative heat load on plants
- May reduce thermal stress during summer months

#### Management Strategies for Misting

**Timing Optimisation**:

| Time Period | Light Availability | Misting Recommendation |
|-------------|-------------------|------------------------|
| Early morning (6-9am) | Low-moderate | Safe to mist |
| Mid-morning (9-11am) | Increasing | Reduce misting frequency |
| Solar noon (11am-2pm) | Peak | Avoid misting if possible |
| Afternoon (2-5pm) | Decreasing | Resume misting |
| Evening (5pm+) | Low | Safe to mist |

**Sensor-Driven Control**:
- Link misting to Apogee ePAR sensors: suppress misting when PAR exceeds threshold
- Implement humidity-based triggers rather than time-based schedules
- Use VPD (Vapour Pressure Deficit) control for optimal balance

**Infrastructure Considerations**:
- Position misting nozzles to minimise light path interference
- Use larger droplet sizes where humidity requirements allow
- Consider ultrasonic foggers (finer control) vs high-pressure misting (coarser droplets)
- Ensure adequate air movement to disperse mist quickly

### Integration: Bringing It All Together

**The Glasshouse Light Management Framework**:

1. **Baseline Assessment**
   - Install Apogee ePAR sensors at all growing positions
   - Record ePAR readings hourly for minimum 2 weeks
   - Map light distribution across all levels and seasons

2. **Gap Analysis**
   - Compare measured ePAR to crop requirements
   - Identify positions below minimum thresholds
   - Quantify supplemental lighting needs

3. **Strategic LED Deployment**
   - Position LEDs based on measured deficits, not assumptions
   - Apply inverse square law to determine mounting heights
   - Calculate energy costs vs. yield improvements

4. **Dynamic Control**
   - Use sensor feedback to trigger LED operation
   - Implement photoperiod management for day-length-sensitive crops
   - Adjust seasonally as natural light contribution changes

5. **Continuous Optimisation**
   - Monitor shade avoidance symptoms
   - Track DLI against yield data
   - Refine LED schedules based on performance

---

## Technical Appendix: Algorithms and Implementations

### The Algorithm (Simple Form)

**Step-by-Step Calculation for LEDs:**

1. **Establish reference distance**: Measure from LED to nearest shelf (this is your baseline = 100%)
2. **Measure new distance** (e.g., if baseline is 0.5m, new distance might be 1m)
3. **Calculate ratio**: Reference Distance ÷ New Distance
   - Example: 1 ÷ 2 = 0.5
4. **Square the ratio**: (Ratio)²
   - Example: 0.5² = 0.25
5. **This gives you the fraction of original intensity**
   - Example: I × 0.25 = **25% of reference intensity**

**Result**: At 2m, you get 25% of the light intensity you had at 1m.

### Quick Reference Table (Relative to Baseline)

The reference distance (baseline) is the distance from LED to nearest shelf.

| Distance Multiple | Intensity | Calculation |
|-------------------|-----------|-------------|
| 1× baseline (nearest shelf) | 100% (reference) | 1/(1)² = 1 |
| 2× baseline | 25% | 1/(2)² = 0.25 |
| 3× baseline | 11% | 1/(3)² = 0.11 |
| 4× baseline | 6.25% | 1/(4)² = 0.0625 |

### Inverse Square Law Formula

```
I₂ = I₁ × (d₁ / d₂)²

Where:
  I₁ = Light intensity at distance d₁ (reference)
  I₂ = Light intensity at distance d₂
  d₁ = Reference distance (e.g., 1m)
  d₂ = New distance (e.g., 2m)

Using the distance to the nearest shelf as 100% reference (baseline) shows how intensity diminishes with distance.
```

### Implementation (Pseudocode)

```
FUNCTION calculateLightIntensity(referenceDistance, newDistance, referenceIntensity):
    ratio = referenceDistance / newDistance
    newIntensity = referenceIntensity × (ratio × ratio)
    percentageLoss = (1 - (ratio × ratio)) × 100
    
    RETURN {
        intensity: newIntensity,
        percentage: (ratio × ratio) × 100,
        loss: percentageLoss
    }
END FUNCTION

// Example: calculateLightIntensity(1.0, 2.0, 100) → { intensity: 25, percentage: 25%, loss: 75% }
```

### JavaScript Implementation

```javascript
function calculateLEDLightIntensity(referenceDistance, newDistance, referenceIntensity) {
    var ratio = referenceDistance / newDistance;
    var newIntensity = referenceIntensity * (ratio * ratio);
    var percentage = (ratio * ratio) * 100;
    var loss = (1 - (ratio * ratio)) * 100;
    
    return {
        intensity: parseFloat(newIntensity.toFixed(2)),
        percentage: parseFloat(percentage.toFixed(2)),
        loss: parseFloat(loss.toFixed(2)),
        ratio: parseFloat(ratio.toFixed(3))
    };
}

// Example: calculateLEDLightIntensity(1.0, 2.0, 100) → { intensity: 25, percentage: 25, loss: 75, ratio: 0.5 }
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
    ratio = reference_distance / new_distance
    new_intensity = reference_intensity * (ratio ** 2)
    percentage = (ratio ** 2) * 100
    loss = (1 - (ratio ** 2)) * 100
    
    return {
        'intensity': round(new_intensity, 2),
        'percentage': round(percentage, 2),
        'loss': round(loss, 2),
        'ratio': round(ratio, 3)
    }

# Example: calculate_led_light_intensity(1.0, 2.0, 100) → {'intensity': 25.0, 'percentage': 25.0, 'loss': 75.0, 'ratio': 0.5}
```

### Shadow Length Calculator

```python
import math

def calculate_shadow_length(structure_height, solar_elevation_degrees):
    """
    Calculate shadow length from a structure based on solar elevation.
    
    Args:
        structure_height: Height of structure in meters
        solar_elevation_degrees: Solar elevation angle in degrees
    
    Returns:
        Shadow length in meters
    """
    solar_elevation_radians = math.radians(solar_elevation_degrees)
    shadow_length = structure_height / math.tan(solar_elevation_radians)
    return round(shadow_length, 1)

# Examples:
# Summer (62°): calculate_shadow_length(4, 62) → 2.1m
# Equinox (38°): calculate_shadow_length(4, 38) → 5.1m
# Winter (15°): calculate_shadow_length(4, 15) → 14.9m
```

---

## Key Takeaways

### LED Physics
1. ✅ **Reference = LED to nearest shelf** - this baseline distance is your 100%
2. ✅ **Double the distance = quarter the light** (inverse square law)
3. ✅ **Halve the distance = quadruple the light** (works both ways)

### Natural Sunlight
4. ✅ **Distance to sun is irrelevant** - but angle and structures are everything
5. ✅ **Solar elevation changes seasonally** - 15° (winter) to 62° (summer) at UK latitudes
6. ✅ **A 4m structure casts a 15m shadow in winter** - plan accordingly

### Glasshouse Vertical Growing
7. ✅ **Each shelf level receives different light** - top may get 100%, bottom only 10-20%
8. ✅ **Shade avoidance syndrome is real** - plants stretch, weaken, and underperform in low light
9. ✅ **ePAR measurement is non-negotiable** - human perception of brightness is irrelevant to plants
10. ✅ **Apogee ePAR sensors enable data-driven decisions** - guessing is not a strategy

### Misting and Environmental Control
11. ✅ **Misting reduces PAR by 10-30%** - water droplets scatter and reflect incoming light
12. ✅ **Lower shelves suffer most from misting** - they rely on diffuse light which is disproportionately affected
13. ✅ **Time misting to avoid peak light hours** - schedule for early morning or late afternoon
14. ✅ **Factor misting into DLI calculations** - cumulative daily impact can be significant

---

## The Sensor Head: Foundation of All Light Measurement

Every value discussed in this document—ePAR, PPFD, DLI, and all derived metrics—is fundamentally dependent on one critical component: **the sensor head**. Understanding how sensor heads work, and why quality matters, is essential for any data-driven approach to controlled environment agriculture.

### The Measurement Chain: Sensor Head to Decision

```
┌─────────────┐    ┌──────────────┐    ┌─────────────┐    ┌──────────────┐
│ Sensor Head │ → │ Raw PAR Data │ → │ Derived     │ → │ Management   │
│ (primary)   │    │ (µmol/m²/s)  │    │ Metrics     │    │ Decisions    │
└─────────────┘    └──────────────┘    └─────────────┘    └──────────────┘
       │                  │                  │                   │
   If wrong,          If wrong,          If wrong,           If wrong,
   everything         DLI wrong,         LED timing          yield and
   is wrong           PPFD wrong         wrong               costs wrong
```

**The sensor head is the primary measurement point.** All subsequent calculations, analyses, and decisions inherit any errors introduced at this stage.

### The Lux-to-PPFD Problem: Why Cheap Sensors Fail

Many devices marketed as "PAR meters" or "PPFD sensors" do not directly measure photosynthetically active radiation. Instead, they:

1. **Measure illuminance (lux)** using a cheap silicon photodiode optimised for human vision
2. **Apply a mathematical conversion factor** to estimate PPFD
3. **Present the result as if it were true PPFD**

**Why this is problematic**:

| Measurement | What It Measures | Spectral Weighting |
|-------------|------------------|-------------------|
| **Lux** | Light as humans perceive it | Weighted to 555nm (green-yellow, peak human sensitivity) |
| **PPFD** | Photons plants use for photosynthesis | Equal weighting across 400-700nm |
| **ePAR** | Extended range including far-red | Equal weighting across 400-750nm |

The spectral composition of light varies significantly between sources:
- **Sunlight**: Broad spectrum, relatively even distribution
- **LEDs**: Narrow peaks at specific wavelengths (often 450nm blue, 660nm red)
- **HPS lamps**: Strong yellow-orange emission

A lux-to-PPFD conversion factor calibrated for sunlight will give incorrect results under LEDs, and vice versa. **The larger the reading, the greater the potential error**, because the conversion factor accumulates error proportionally.

### What True ePAR Sensors Measure

A genuine quantum sensor (such as Apogee ePAR sensors) directly counts photons in the photosynthetically active range using:

- **Filtered photodiodes** with spectral response matched to the ePAR range (400-750nm)
- **Calibration against NIST-traceable standards**
- **Cosine correction** for accurate readings at oblique angles of incidence

There is no conversion from lux. The sensor directly measures what plants use.

### Derived Metrics: All Dependent on Primary Measurement

Every derived metric inherits the accuracy (or inaccuracy) of the primary sensor measurement:

| Metric | Definition | Dependence on Sensor |
|--------|------------|---------------------|
| **PPFD** | Photosynthetic Photon Flux Density (µmol/m²/s) | Direct measurement from sensor head |
| **DLI** | Daily Light Integral (mol/m²/day) | PPFD integrated over 24 hours |
| **PFD** | Photon Flux Density | Similar to PPFD with slight spectral range differences |
| **Supplemental light requirement** | Gap between measured DLI and crop requirement | Calculated from DLI |
| **LED runtime** | Hours of supplemental lighting needed | Calculated from PPFD deficit |

**A 10% error in the sensor head propagates to a 10% error in DLI, supplemental lighting calculations, and ultimately yield predictions and energy costs.**

### Data Alignment: Comparing Measurements Across Sources

When integrating data from multiple measurement systems (e.g., handheld meters, fixed sensors, camera-based systems), rigorous attention to data alignment is required.

**For each data source, confirm**:

1. **Sensor head model and manufacturer**
   - What specific sensor head is used?
   - Is it a true quantum sensor or a lux-based transform?

2. **Technical specifications** (from datasheet, not marketing materials)
   - Accuracy (typically ±5% for quality sensors)
   - Range (e.g., 0-4000 µmol/m²/s)
   - Resolution (e.g., 0.1 µmol/m²/s)
   - Spectral range (400-700nm for PAR, 400-750nm for ePAR)

3. **Conversion methods**
   - Is raw PAR measured directly?
   - If transformed from lux, what conversion factor is used?
   - Under what light source was the conversion factor calibrated?

4. **Timestamp synchronisation**
   - Some systems have data transmission delays (e.g., 24-hour delays)
   - Timestamps must be aligned before comparing datasets
   - Time zone handling must be consistent

**Without this information, comparing readings from different sources is not scientifically valid.** You may be comparing a direct measurement to a transformed estimate, or comparing data from different time periods due to transmission delays.

### Apogee Instruments: The Scientific Standard

Apogee Instruments (Logan, Utah, USA) are world-class developers and manufacturers of sensing equipment for agricultural and environmental research. Their sensors are:

- **Designed by scientists** with expertise in photobiology and radiometry
- **Used by research institutions** worldwide for peer-reviewed studies
- **NIST-traceable calibration** ensuring measurements can be compared across instruments and institutions
- **Fully documented** with technical datasheets specifying accuracy, range, resolution, and spectral response

**Apogee ePAR Sensors**: [https://www.apogeeinstruments.com/epar-sensors/](https://www.apogeeinstruments.com/epar-sensors/)

The ePAR sensors extend measurement to 750nm, capturing far-red wavelengths increasingly recognised as important for photomorphogenesis and the Emerson enhancement effect.

### Sun vs LED: Different Measurement Challenges

Measuring PAR from natural sunlight and from LED fixtures presents different technical challenges, both of which relate to **where the light source is relative to the target crop**.

**Natural Sunlight**:

| Factor | Challenge | Sensor Requirement |
|--------|-----------|-------------------|
| Angle of incidence | Sun angle changes continuously throughout day and year | Excellent cosine correction |
| Diffuse component | Significant portion of light is scattered by atmosphere | Hemispherical response |
| Spectral stability | Relatively consistent spectrum | Standard ePAR spectral response |
| Distance to source | Effectively infinite (150 million km) | Not a factor |

**LED Fixtures**:

| Factor | Challenge | Sensor Requirement |
|--------|-----------|-------------------|
| Point source behaviour | Intensity follows inverse square law | Precise distance measurement |
| Narrow spectral peaks | LEDs emit at specific wavelengths, not broad spectrum | Correct spectral weighting across ePAR range |
| Fixture geometry | Light distribution varies with fixture design | Multiple measurement points |
| Distance sensitivity | Small changes in height significantly affect PPFD | Reference height must be defined (LED to nearest shelf) |

**The common denominator**: Accurate measurement depends on understanding the geometric relationship between light source and sensor, and selecting a sensor head appropriate for the light source being measured.

### Practical Checklist: Before Trusting Any Light Data

Before using light measurements for management decisions, verify:

- [ ] **Sensor head identified**: Model number and manufacturer known
- [ ] **Technical datasheet obtained**: Not marketing materials—actual specifications
- [ ] **Measurement type confirmed**: Direct quantum measurement or lux transform?
- [ ] **Accuracy stated**: What is the manufacturer-stated accuracy (e.g., ±5%)?
- [ ] **Spectral range confirmed**: PAR (400-700nm) or ePAR (400-750nm)?
- [ ] **Calibration status**: When was the sensor last calibrated? Is calibration traceable?
- [ ] **Conversion factors documented**: If any transforms are applied, what are they?
- [ ] **Timestamps aligned**: Are all data sources synchronised to the same time reference?
- [ ] **Light source considered**: Is the sensor appropriate for the light source (sun/LED/HPS)?

**The sensor head is the foundation of all measurement. Everything else—DLI calculations, supplemental lighting schedules, yield predictions, energy optimisation—stands or falls on this foundation.**

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
