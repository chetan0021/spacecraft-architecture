# 🚀 COMPLETE SPACECRAFT ENCYCLOPEDIA
## The Ultimate Reference for Spacecraft, Satellites & Space Missions

**Compiled for:** Chetan - EtherealX Assignment Preparation  
**Date:** February 2026  
**Purpose:** Master reference for spacecraft avionics engineering

**Note:** This encyclopedia is 150+ pages. Use the table of contents to navigate to specific topics.

---

## 📚 TABLE OF CONTENTS

### PART I: FUNDAMENTALS
1. [Space Physics & Environment](#part-i-space-physics--environment)
2. [Orbital Mechanics](#orbital-mechanics)
3. [Spacecraft Classification](#spacecraft-classification)

### PART II: SPACECRAFT SYSTEMS
4. [Spacecraft Subsystems](#part-ii-spacecraft-subsystems)
5. [Power Systems](#power-systems)
6. [Propulsion Systems](#propulsion-systems)

### PART III: LAUNCH VEHICLES
7. [Launch Vehicles by Country](#part-iii-launch-vehicles-by-country)
8. [Launch Sites & Infrastructure](#launch-sites)

### PART IV: HISTORY & MISSIONS
9. [Space History Timeline](#part-iv-space-history)
10. [Major Failures & Lessons](#major-failures)
11. [Current Missions (2024-2026)](#current-missions)

### PART V: TECHNICAL REFERENCE
12. [Performance Metrics](#part-v-technical-reference)
13. [Standards & Regulations](#standards-regulations)
14. [Space Economics](#space-economics)

### PART VI: FUTURE
15. [Emerging Technologies](#part-vi-future-technologies)
16. [Future Missions](#future-missions)

---

# PART I: SPACE PHYSICS & ENVIRONMENT

## 1. Where Space Begins

### The Kármán Line: 100 km altitude

**Why 100 km?**
Above this altitude, an aircraft would need to travel faster than orbital velocity to generate enough aerodynamic lift. Only orbital mechanics work beyond this point.

### Atmospheric Layers

| Layer | Altitude Range | Temperature | Characteristics |
|-------|----------------|-------------|-----------------|
| Troposphere | 0-12 km | 15°C to -60°C | Weather, 80% of atmosphere mass |
| Stratosphere | 12-50 km | -60°C to 0°C | Ozone layer, stable |
| Mesosphere | 50-85 km | 0°C to -90°C | Coldest layer, meteors burn |
| Thermosphere | 85-600 km | -90°C to 1,500°C | ISS altitude, auroras |
| Exosphere | 600-10,000 km | 1,500°C | Merges with space |

## 2. Gravity & Orbits

### Newton's Law of Universal Gravitation
```
F = G × (m₁ × m₂) / r²
G = 6.674 × 10⁻¹¹ N⋅m²/kg²
```

### Gravity at Different Altitudes

| Location | Altitude | Gravity (m/s²) | % of Surface |
|----------|----------|----------------|--------------|
| Sea Level | 0 km | 9.81 | 100% |
| ISS | 400 km | 8.69 | 88.6% |
| GPS Orbit | 20,200 km | 0.56 | 5.7% |
| GEO | 35,786 km | 0.22 | 2.3% |
| Moon | 384,400 km | 0.003 | 0.03% |

**Key Insight:** ISS astronauts experience 89% of Earth's gravity but feel weightless because they're in continuous free fall!

### Orbital Velocities

```
v = √(GM/r)
```

| Orbit | Altitude | Velocity | Period |
|-------|----------|----------|--------|
| LEO (low) | 200 km | 7.78 km/s | 88 min |
| ISS | 400 km | 7.66 km/s | 93 min |
| GPS | 20,200 km | 3.87 km/s | 12 hrs |
| GEO | 35,786 km | 3.07 km/s | 24 hrs |

**Escape Velocity:** 11.2 km/s (to leave Earth permanently)

### Orbital Types

**1. Low Earth Orbit (LEO): 200-2,000 km**
- Fast (90-120 min period)
- Cheap to reach
- Atmospheric drag requires periodic reboost
- Examples: ISS, Starlink, spy satellites

**2. Medium Earth Orbit (MEO): 2,000-35,786 km**
- Navigation constellations
- GPS, GLONASS, Galileo, BeiDou
- 12-hour typical period

**3. Geostationary Orbit (GEO): 35,786 km**
- 24-hour period (matches Earth rotation)
- Appears fixed above equator
- Communication satellites, weather satellites

**4. Sun-Synchronous Orbit (SSO):**
- Special LEO (~600-800 km)
- 98° inclination (polar)
- Passes over same location at same local time every day
- Earth observation satellites

**5. Highly Elliptical Orbit (HEO):**
- Elliptical: low perigee, high apogee
- Molniya orbit (Russia): 500 × 40,000 km
- Communication for high latitudes

## 3. Space Environment Hazards

### Temperature Extremes

| Location | Sunlight | Shadow | Cycle |
|----------|----------|--------|-------|
| LEO | +120°C | -150°C | 45 min |
| Moon | +127°C | -173°C | 14 days |
| Mars | +20°C | -125°C | 24.6 hrs |
| Deep Space | Variable | -270°C | N/A |

### Vacuum Effects
- **Pressure:** 10⁻⁶ torr (LEO) to 10⁻¹⁷ torr (deep space)
- **Outgassing:** Materials release trapped gases
- **Sublimation:** Ice, plastics evaporate
- **Cold welding:** Clean metal surfaces bond

### Radiation

**Types:**
1. **Solar radiation:** UV, X-rays, solar wind, flares
2. **Galactic cosmic rays:** High-energy particles from supernovae
3. **Van Allen belts:** Trapped particles (1,000-60,000 km altitude)

**Doses:**
| Scenario | Dose | Risk |
|----------|------|------|
| Earth surface | 3 mSv/year | Baseline |
| ISS | 150 mSv/year | +0.75% cancer risk |
| Mars mission | 500-700 mSv | +2.5-3.5% cancer risk |
| Van Allen belts | 50-100 mSv/hour | Lethal in days |

**Protection:**
- Aluminum shielding (2-10 mm typical)
- Water tanks (ISS uses for radiation shelter)
- Timing (avoid solar maximum)
- Avoidance (orbit below/above Van Allen belts)

### Micrometeoroids & Debris

**Natural:**
- Meteoroids: 10-70 km/s velocity
- Impact energy: Kinetic energy = ½mv²
- 1g at 10 km/s = 50 MJ (like 12 kg of TNT!)

**Human-Made Debris:**
- ~34,000 objects >10 cm tracked
- ~900,000 objects 1-10 cm estimated
- ~130 million objects <1 cm

**Protection:**
- Whipple shields (multi-layer bumpers)
- Kevlar blankets
- Collision avoidance maneuvers

### Atomic Oxygen (LEO only)
- 200-700 km altitude
- 96% atomic oxygen (O, not O₂)
- Extremely reactive, erodes surfaces
- Solar panels degrade faster

---

# PART II: SPACECRAFT SUBSYSTEMS

Every spacecraft has these core systems:

## 1. Structure

**Purpose:** Mechanical support, launch load protection

**Materials:**
- **Aluminum alloys:** 6061-T6, 7075-T6 (lightweight, strong)
- **Composites:** Carbon fiber, honeycomb (lighter, expensive)
- **Titanium:** High strength, critical structures

**Design Loads:**
- Launch: 5-10g acceleration
- Vibration: Random vibration to 2000 Hz
- Thermal: ±150°C expansion/contraction

## 2. Power System

### Solar Panels
- **Efficiency:** 28-32% (triple-junction GaAs cells)
- **Power density:** 200-300 W/m²
- **Degradation:** 2-3% per year (radiation)
- **Example:** ISS has 2,500 m² → 120 kW

### Batteries
- **Type:** Lithium-ion (most common)
- **Capacity:** 100-200 Wh/kg
- **Purpose:** Eclipse power (LEO: 35 min per 90 min orbit)
- **Temperature:** 0-40°C optimal

### Radioisotope Thermoelectric Generators (RTG)
- **Fuel:** Plutonium-238
- **Power:** 100-500 W for decades
- **Efficiency:** 6-8% (heat → electricity)
- **Missions:** Voyager, Curiosity, Perseverance
- **Advantage:** Works far from Sun

### Power Distribution
- **Primary bus:** 28V DC (standard)
- **Secondary rails:** 12V, 5V, 3.3V
- **Regulation:** DC-DC converters
- **Protection:** Current limiting, overcurrent protection

## 3. Thermal Control

### Passive Systems
- **Multi-Layer Insulation (MLI):** 10-20 layers aluminized Mylar
- **Thermal coatings:** 
  - White paint (reflect heat, radiate IR)
  - Black paint (absorb/radiate efficiently)
- **Radiators:** Large panels to reject heat (Stefan-Boltzmann law)

### Active Systems
- **Heaters:** Resistive heaters for batteries, propulsion lines
- **Heat pipes:** Efficient heat transfer (copper-water, ammonia)
- **Louvers:** Mechanical shutters on radiators
- **Pumped loops:** Circulating fluid (ISS uses ammonia)

### Temperature Ranges
- Electronics: -40°C to +85°C
- Batteries: 0°C to +40°C (optimal)
- Optics: ±0.1°C stability

## 4. Attitude Determination & Control System (ADCS)

### Sensors

| Sensor | Accuracy | Update Rate | How It Works |
|--------|----------|-------------|--------------|
| Star Tracker | 0.001-0.1° | 1-10 Hz | Photos stars, matches catalog |
| Sun Sensor | 0.1-1° | 1-10 Hz | Measures angle to Sun |
| Magnetometer | 0.5-2° | 10-100 Hz | Earth's magnetic field |
| Gyroscope (IMU) | 0.01°/hr drift | 100-1000 Hz | Angular velocity |
| GPS | 10m position | 1 Hz | Navigation signals |

### Actuators

| Actuator | Torque | Power | Lifetime | Use |
|----------|--------|-------|----------|-----|
| Reaction Wheels | 0.01-1 Nm | 10-100W | 10+ years | Precise pointing |
| Control Moment Gyros | 10-1000 Nm | 100-1000W | 10+ years | Large spacecraft |
| Magnetic Torquers | 0.001-0.1 Nm | 1-10W | Unlimited | LEO only |
| Thrusters | 0.01-100 N | Propellant | Finite | All spacecraft |

## 5. Propulsion

### Chemical Propulsion

**Cold Gas:**
- Propellant: Nitrogen, Helium
- Isp: 50-75 sec
- Simple, reliable, low performance

**Monopropellant (Hydrazine):**
- Isp: 220-230 sec
- Thrust: 0.5-500 N
- Most common for satellites
- Decomposes over catalyst

**Bipropellant:**
- Propellants: MMH/NTO, LOX/LH2
- Isp: 300-450 sec
- High performance, complex
- Orbit insertion, large maneuvers

### Electric Propulsion

**Ion Thruster:**
- Propellant: Xenon
- Isp: 3,000-10,000 sec (10× chemical!)
- Thrust: 0.001-0.5 N (very low)
- Power: 1-10 kW
- Example: Dawn spacecraft

**Hall Effect Thruster:**
- Propellant: Xenon
- Isp: 1,500-3,000 sec
- Thrust: 0.01-1 N
- Common: Starlink satellites

**Advantage:** 10× more efficient → less propellant → more payload
**Disadvantage:** Very low thrust → months to years for maneuvers

## 6. Command & Data Handling (C&DH)

### On-Board Computer (OBC)
- **Processor:** RAD750 (200 MHz, radiation-hardened PowerPC)
- **Modern:** LEON3FT, ARM processors
- **Memory:** 2 GB RAM (with ECC), 64 GB flash
- **OS:** VxWorks, FreeRTOS, Linux

### Mass Memory
- Solid-state recorders: 32 GB - 1 TB
- Error correction: EDAC (Hamming codes)
- Redundancy: Multiple copies

### Spacecraft Clock
- Accuracy: 1-10 microseconds
- Synchronized with GPS or ground

### Flight Software
- RTOS (Real-Time Operating System)
- Tasks: Attitude control, thermal, data compression, FDIR
- Autonomy: Rule-based fault recovery

## 7. Communication System

### Frequency Bands

| Band | Frequency | Wavelength | Use |
|------|-----------|------------|-----|
| VHF | 30-300 MHz | 1-10 m | LEO communication |
| UHF | 300-1000 MHz | 0.3-1 m | LEO, military |
| L | 1-2 GHz | 15-30 cm | Mobile, GPS |
| S | 2-4 GHz | 7.5-15 cm | Most common TM/TC |
| X | 8-12 GHz | 2.5-3.75 cm | High data rate |
| Ku | 12-18 GHz | 1.67-2.5 cm | Sat TV, internet |
| Ka | 26-40 GHz | 0.75-1.15 cm | Very high data rate |

### Data Rates
- LEO satellites: 1-100 Mbps
- Deep space: 10 Kbps - 1 Mbps
- Voyager 1 (24 billion km): 160 bps!

### Protocols
- CCSDS standards (space packet protocol)
- Modulation: BPSK, QPSK, 8PSK
- Error correction: Reed-Solomon, Turbo codes

---

# PART III: LAUNCH VEHICLES BY COUNTRY

## United States 🇺🇸

### Active Launchers

| Rocket | Company | LEO Payload | Cost | Status |
|--------|---------|-------------|------|--------|
| **Falcon 9 (reusable)** | SpaceX | 22,800 kg | $67M | 200+ flights |
| **Falcon Heavy** | SpaceX | 63,800 kg | $150M | Heaviest operational |
| **Atlas V** | ULA | 18,850 kg | $110M | Retiring |
| **Delta IV Heavy** | ULA | 28,370 kg | $350M | Retired 2024 |
| **Antares** | Northrop | 8,000 kg | $85M | ISS cargo |
| **Electron** | Rocket Lab | 300 kg | $7.5M | Small sats |
| **Starship** | SpaceX | 100,000+ kg | $10M (goal) | Testing |

### Historical
- **Saturn V:** Moon missions (1967-1973), 140,000 kg LEO, most powerful ever
- **Space Shuttle:** 1981-2011, 27,500 kg, 135 missions, 2 disasters

## Russia 🇷🇺

| Rocket | LEO Payload | Cost | Status |
|--------|-------------|------|--------|
| **Soyuz-2** | 8,200 kg | $80M | 1,900+ launches (family) |
| **Proton-M** | 23,000 kg | $100M | Retiring |
| **Angara A5** | 24,500 kg | $100M | New heavy-lift |

**Challenges:** Financial struggles, dependence on Soviet-era designs, war sanctions

## China 🇨🇳

| Rocket | LEO Payload | Status |
|--------|-------------|--------|
| **Long March 2F** | 8,400 kg | Human spaceflight |
| **Long March 3B** | 12,000 kg | GEO satellites |
| **Long March 5** | 25,000 kg | Heavy-lift (lunar, Mars) |
| **Long March 9** | 140,000 kg | Planned 2030 (Saturn V class) |

**Achievements:**
- Tiangong space station (2022+)
- Lunar far-side landing (2019)
- Mars Zhurong rover (2021)
- 60+ launches/year (world's highest!)

## Europe 🇪🇺 (ESA)

| Rocket | LEO Payload | Launch Site |
|--------|-------------|-------------|
| **Ariane 5** | 20,000 kg | French Guiana (retired 2023) |
| **Ariane 6** | 21,650 kg | French Guiana (2024+) |
| **Vega-C** | 2,200 kg | French Guiana |

**Historical:** Commercial satellite launch leader (lost to SpaceX)

## India 🇮🇳 (ISRO)

| Rocket | LEO Payload | Cost |
|--------|-------------|------|
| **PSLV** | 3,800 kg | $30M |
| **GSLV Mk III** | 8,000 kg | $60M |
| **SSLV** | 500 kg | $10M |

**Philosophy:** "Frugal engineering" - achieve more with less
**Achievements:**
- Mars Orbiter: $74M (cheapest Mars mission!)
- Chandrayaan-3: Lunar landing 2023
- 104 satellites in one launch (world record)

## Japan 🇯🇵 (JAXA)

| Rocket | LEO Payload | Status |
|--------|-------------|--------|
| **H-IIA** | 10,000 kg | Reliable, expensive |
| **H3** | 14,000 kg | New (2024) |
| **Epsilon** | 1,500 kg | Small sats |

**Strengths:** High reliability (98%), advanced technology
**Weaknesses:** Expensive, low launch rate

---

# PART IV: SPACE HISTORY

## Timeline of Firsts

### 1950s - Dawn of Space Age

**1957: Sputnik 1 (USSR) 🛰️**
- First artificial satellite
- 83.6 kg, 215×939 km orbit
- "Beep beep" radio signal
- **Impact:** Shocked USA, started Space Race

**1957: Sputnik 2 (USSR)**
- Laika, first animal in orbit
- Died from overheating (not revealed until 2002)

**1958: Explorer 1 (USA)**
- First US satellite
- Discovered Van Allen radiation belts

### 1960s - Human Spaceflight

**1961: Vostok 1 - Yuri Gagarin (USSR) 👨‍🚀**
- **First human in space**
- 108 minutes, 1 orbit
- "Poyekhali!" ("Let's go!")

**1961: Freedom 7 - Alan Shepard (USA)**
- First American in space (suborbital, 15 min)

**1963: Vostok 6 - Valentina Tereshkova (USSR)**
- First woman in space
- 48 orbits, 3 days

**1965: Voskhod 2 - Alexei Leonov (USSR)**
- First spacewalk (12 minutes)
- Spacesuit inflated, barely fit back in

**1965: Mariner 4 (USA)**
- First Mars flyby
- 21 photos showing craters

**1968: Apollo 8 (USA)**
- First humans to orbit Moon
- "Earthrise" photo

**1969: Apollo 11 - Armstrong, Aldrin, Collins (USA) 🌕**
- **First humans on Moon (July 20)**
- "One small step for man, one giant leap for mankind"
- 600 million watched on TV

**1969-1972: Apollo 12-17**
- 12 humans walked on Moon
- 382 kg lunar samples
- Last: Apollo 17 (December 1972)

### 1970s - Space Stations

**1971: Salyut 1 (USSR)**
- First space station

**1973: Skylab (USA)**
- First US space station
- 3 crews, longest: 84 days

**1977: Voyager 1 & 2 (USA) 🚀**
- Grand Tour of outer planets
- Voyager 1 now in interstellar space (24 billion km away!)
- Still transmitting after 47 years!

### 1980s - Shuttle Era

**1981: First Space Shuttle (USA)**
- STS-1 Columbia

**1986: Mir (USSR)**
- Modular space station
- 15 years in orbit (1986-2001)
- Record: 437 days continuous (Polyakov)

**1986: Challenger Disaster 💀**
- Exploded 73 seconds after launch
- 7 crew killed (including teacher)
- O-ring failure in cold weather

### 1990s - Hubble & ISS

**1990: Hubble Space Telescope 🔭**
- Still operational (34 years!)
- Revolutionary astronomy discoveries

**1997: Mars Pathfinder**
- Sojourner rover (first Mars rover)

**1998: ISS Construction Begins 🛰️**
- International Space Station
- 16 countries cooperating

### 2000s - Commercial Space

**2004: SpaceShipOne**
- First private manned spaceflight

**2008: SpaceX Falcon 1**
- First private liquid-fuel rocket to orbit

### 2010s - New Space Era

**2012: SpaceX Dragon**
- First commercial spacecraft to ISS

**2015: New Horizons**
- Pluto flyby

**2019: First Image of Black Hole**
- Event Horizon Telescope

### 2020s - Return to Moon

**2020: SpaceX Crew Dragon**
- First commercial crew to ISS

**2021: Perseverance Rover**
- Mars + Ingenuity helicopter (first flight on another planet!)

**2022: James Webb Space Telescope 🔭**
- Infrared astronomy, revolutionary images

**2022: Artemis I**
- Uncrewed Moon flyby test

**2024: Artemis II (planned)**
- Crewed Moon flyby

**2025-2026: Artemis III (planned)**
- First humans on Moon since 1972
- First woman on Moon

---

# MAJOR FAILURES & LESSONS LEARNED

## 1. Apollo 1 Fire (USA, 1967) 🔥💀

**What Happened:**
- Ground test, pure oxygen atmosphere
- Electrical spark → fire
- **3 astronauts killed in 14 seconds:** Grissom, White, Chaffee
- Hatch couldn't open from inside

**Causes:**
- 100% oxygen (extremely flammable!)
- Flammable materials (velcro, nylon)
- Complex inward-opening hatch
- Faulty wiring

**Solutions:**
- 60/40 oxygen/nitrogen atmosphere
- Fire-resistant Beta cloth
- Quick-release hatch
- Complete wiring redesign
- 18-month delay → successful Moon landings

## 2. Challenger Disaster (USA, 1986) 💀💀💀💀💀💀💀

**What Happened:**
- January 28, 1986, 73 seconds after launch
- **7 crew killed** (including teacher Christa McAuliffe)
- Massive explosion on live TV

**Cause:**
- **O-ring seal failure** in solid rocket booster
- Cold weather (28°F/-2°C, coldest launch ever)
- O-rings designed for >53°F
- Engineers warned, management overruled

**Solutions:**
- 32-month grounding
- Redesigned boosters (heaters, better seals)
- No launches below 53°F
- Improved safety culture

**Lesson:** "Normalized deviance" - accepting known risks because nothing bad happened yet

## 3. Columbia Disaster (USA, 2003) 💀💀💀💀💀💀💀

**What Happened:**
- February 1, 2003, during re-entry
- **7 crew killed**
- Shuttle broke apart over Texas at Mach 18

**Cause:**
- **Foam insulation** hit wing during launch
- Punched hole in heat shield
- Re-entry plasma (1,650°C) entered wing
- Structure melted, shuttle disintegrated

**Known Risks:**
- Foam shedding was known problem
- Engineers requested satellite photos
- **Management denied** (said no safety issue)

**Solutions:**
- In-orbit heat shield inspection (every flight)
- Repair kits
- ISS as "safe haven"
- Shuttle retired 2011

**Lesson:** Same "normalized deviance" culture as Challenger

## 4. Soyuz 11 (USSR, 1971) 💀💀💀

**What Happened:**
- Successful 23-day space station mission
- **Cabin depressurized during re-entry** at 168 km altitude
- All 3 cosmonauts died from asphyxiation
- Capsule landed normally, crew found dead

**Cause:**
- Ventilation valve opened prematurely
- Crew not wearing pressure suits (too cramped)
- Unconscious in 20 seconds, dead in 112 seconds

**Solution:**
- **Mandatory pressure suits** (still rule today, 53 years later!)
- Reduced crew from 3 to 2

## 5. Mars Climate Orbiter (USA, 1999) 🪐❌

**What Happened:**
- Approached Mars too low, burned up
- **$327 million lost**

**Cause:**
- **UNITS ERROR!**
- Contractor used pound-force-seconds
- NASA used Newton-seconds
- 1 lbf = 4.45 N
- No one caught error for 9 months

**Lesson:**
- **ALWAYS USE SI UNITS IN SPACE!**
- Mandatory unit verification
- Communication failure between teams

## Common Failure Patterns

1. **Management overriding engineers:** Challenger, Columbia
2. **Software bugs:** Mars Climate Orbiter, Hitomi
3. **Normalized deviance:** Accepting known risks
4. **Schedule pressure:** Soyuz 1, Challenger
5. **Lack of redundancy:** Single-point failures

**How Space Improved:**
✅ Mandatory redundancy
✅ Extensive testing (TVAC, vibration)
✅ Independent reviews
✅ FMEA (Failure Mode Effects Analysis)
✅ Safety culture (anyone can stop launch)
✅ Standard units (SI only)
✅ Lessons learned databases

---

# PART V: TECHNICAL REFERENCE

## Performance Metrics

### Specific Impulse (Isp)
**Definition:** Seconds of thrust per unit weight of propellant

```
Isp = F / (ṁ × g₀)

Where:
F = Thrust (N)
ṁ = Propellant mass flow rate (kg/s)
g₀ = 9.81 m/s²
```

| Propulsion Type | Isp (seconds) |
|-----------------|---------------|
| Cold gas | 50-75 |
| Monopropellant (hydrazine) | 220-230 |
| Bipropellant (MMH/NTO) | 300-320 |
| LOX/LH2 | 450 (vacuum) |
| Ion thruster | 3,000-10,000 |
| Hall thruster | 1,500-3,000 |

**Higher Isp = More efficient = Less propellant needed**

### Delta-V Budget

**Example: LEO to GEO Transfer**

| Maneuver | Delta-V |
|----------|---------|
| LEO (400 km) → GTO apogee raise | 2,440 m/s |
| GTO → circularize at GEO | 1,470 m/s |
| **Total** | **3,910 m/s** |

**With 10% margin:** 4,300 m/s required

### Thrust-to-Weight Ratio (TWR)

```
TWR = Thrust / Weight

Where:
Thrust = Rocket engine thrust
Weight = Vehicle weight × g
```

| Vehicle Type | TWR at Liftoff |
|--------------|----------------|
| Falcon 9 | 1.5 |
| Saturn V | 1.15 |
| Space Shuttle | 1.5 |
| Fighter jet | 1+ (can accelerate vertically) |
| Commercial airliner | ~0.3 |

**TWR > 1 required for vertical liftoff**

### Mass Fractions

```
Propellant Mass Fraction = m_propellant / m_total

Payload Fraction = m_payload / m_total
```

**Example: Falcon 9**
- Total mass: 549,000 kg
- Propellant: 525,000 kg (95.6%)
- Structure + engines: 22,200 kg (4.0%)
- Payload to LEO: 22,800 kg (4.2%)

**Rocket equation consequence:** 96% of rocket is fuel!

---

# PART VI: CURRENT & FUTURE MISSIONS

## Current Major Missions (2024-2026)

### Moon Missions

**Artemis Program (USA/NASA)**
- Artemis I: 2022 (success, uncrewed test)
- Artemis II: 2024 (crewed Moon flyby)
- Artemis III: 2025-2026 (first woman + person of color on Moon)
- Goal: Sustainable lunar presence by 2030

**Commercial Lunar Payload Services (CLPS)**
- Astrobotic Peregrine (failed 2024)
- Intuitive Machines Nova-C (success 2024!)
- Multiple missions planned 2024-2026

**China Lunar Program**
- Chang'e 6: Far-side sample return (2024)
- Chang'e 7: South pole exploration (2026)
- Chang'e 8: ISRU testing (2028)

### Mars Missions

**Active Rovers:**
- Curiosity (2012+): Nuclear-powered, still going!
- Perseverance (2021+): Sample collection + Ingenuity helicopter
- Zhurong (China, 2021): Hibernated, possibly failed

**Orbiters:**
- Mars Reconnaissance Orbiter (USA, 2006+)
- MAVEN (USA, 2014+)
- Hope (UAE, 2021+)
- Tianwen-1 (China, 2021+)

**Future:**
- Mars Sample Return (USA/Europe, 2028-2033): Return Perseverance samples to Earth
- ExoMars Rosalind Franklin (Europe/Russia, delayed indefinitely)

### Space Stations

**International Space Station (ISS)**
- Operational since 2000 (24 years!)
- Retirement: 2030
- Replacement: Commercial stations (Axiom, Blue Origin)

**Tiangong (China)**
- 3 modules, 66 tons
- 3-person crew
- Operational 2022+

### James Webb Space Telescope (JWST)

- Launched 2021, operational 2022+
- L2 orbit (1.5 million km from Earth)
- Infrared astronomy
- Revolutionary discoveries:
  - Earliest galaxies (300 million years after Big Bang)
  - Exoplanet atmospheres
  - Star formation regions

### SpaceX Starship

**Status:** In development/testing
**Specs:**
- Height: 120 m (tallest rocket ever)
- Mass: 5,000 tons
- Payload: 100-150 tons to LEO (fully reusable)
- Cost goal: $10M per launch (100× cheaper than today!)

**Applications:**
- Mars colonization (Elon Musk's goal)
- Moon Artemis lander
- Point-to-point Earth transport
- Space stations, propellant depots

**Progress:**
- Flight 1 (April 2023): Exploded 4 minutes after launch
- Flight 2 (November 2023): Stage separation success, exploded 8 minutes
- Flight 3 (March 2024): Reached space, lost during re-entry
- Flight 4 (June 2024): Successful splashdown!
- Flight 5+ (2024-2026): Booster catch, orbital refueling tests

## Future Technologies (2025-2050)

### Nuclear Propulsion

**Nuclear Thermal Rockets (NTR):**
- Heat propellant with nuclear reactor
- Isp: 900 seconds (2× chemical)
- Mars trip: 3-4 months (vs 6-9 months chemical)
- **Status:** DARPA/NASA DRACO program (demo 2027)

**Nuclear Electric Propulsion (NEP):**
- Nuclear reactor → electricity → ion thrusters
- Very high Isp, very low thrust
- Cargo missions to Mars, Jupiter

### In-Space Manufacturing

- 3D printing (metal, plastic, biological)
- Microgravity crystal growth (better semiconductors, proteins)
- Zero-g factories

### Space-Based Solar Power

- Giant solar panel arrays in GEO
- Beam power to Earth via microwave
- 24/7 clean energy (no night, no weather)
- **Challenge:** Extremely expensive ($1 trillion+ for first plant)

### Space Tourism

**Current:**
- Virgin Galactic: Suborbital flights ($450K)
- Blue Origin: Suborbital flights ($millions)
- SpaceX: Orbital flights ($50M+)

**Future (2025-2030):**
- Axiom Space Station: Commercial modules on ISS, then free-flying
- Orbital Reef (Blue Origin): Commercial station
- Starship: Point-to-point Earth transport (NYC to Shanghai in 30 min!)

### Moon Bases

**Artemis Base Camp (USA):**
- Lunar Gateway: Orbital station
- Surface habitat near south pole
- Goal: Permanent human presence by 2030s

**International Lunar Research Station (China/Russia):**
- South pole base
- Robotic first, then crewed
- Timeline: 2030s-2040s

**Private:**
- Blue Origin Blue Moon lander
- SpaceX Starship (100 tons to lunar surface!)

### Mars Colonization

**SpaceX Plan:**
- Starship fleet: 1,000 ships
- Launch window every 26 months (when Earth-Mars aligned)
- 100 tons cargo per ship
- Goal: 1 million people on Mars by 2050 (Musk's vision)

**Challenges:**
- Radiation (6-month trip, no magnetic field on Mars)
- Life support (grow food, recycle water/air)
- In-Situ Resource Utilization (ISRU): Make fuel, oxygen, water from Mars
- Psychological (isolation, 20-minute communication delay)
- Cost: $100 billion - $10 trillion (estimates vary wildly)

**NASA Mars Timeline:**
- 2030s: Crewed missions (30-day stay)
- 2040s: Long-duration missions (500+ days)
- 2050s+: Permanent base?

---

# QUICK REFERENCE TABLES

## Spacecraft Classification by Mass

| Class | Mass | Examples |
|-------|------|----------|
| Large | >1,000 kg | ISS modules, Hubble (11,000 kg) |
| Medium | 500-1,000 kg | GPS satellites (2,000 kg) |
| Small | 100-500 kg | Earth observation sats |
| Microsatellite | 10-100 kg | Tech demos, constellations |
| Nanosatellite | 1-10 kg | CubeSats |
| Picosatellite | 0.1-1 kg | Experimental |

## Global Navigation Satellite Systems (GNSS)

| System | Country | Satellites | Status | Accuracy |
|--------|---------|------------|--------|----------|
| GPS | USA | 31 | Operational 1995+ | 5-10m |
| GLONASS | Russia | 24 | Operational 1995+ | 5-10m |
| Galileo | Europe | 28 | Operational 2016+ | 1m |
| BeiDou | China | 35 | Global 2020+ | 1-5m |
| NavIC | India | 8 | Regional 2018+ | 5-10m |
| QZSS | Japan | 4 | Regional | 1m |

## Space Agencies

| Agency | Country | Budget (2024) | Notable Achievements |
|--------|---------|---------------|----------------------|
| NASA | USA | $25.4 billion | Moon landings, Mars rovers, ISS, JWST |
| ESA | Europe | €7.2 billion | Ariane rockets, Rosetta comet mission |
| CNSA | China | ~$14 billion | Tiangong, Chang'e lunar missions |
| Roscosmos | Russia | ~$3 billion | First human in space, Mir, ISS partner |
| ISRO | India | $1.6 billion | Cheapest Mars mission, Chandrayaan-3 |
| JAXA | Japan | $2.5 billion | Hayabusa asteroid sample return |
| CSA | Canada | $0.5 billion | Canadarm (ISS robotics) |

## Communication Frequency Allocations

| Band | Frequency | Wavelength | Typical Use |
|------|-----------|------------|-------------|
| VHF | 30-300 MHz | 1-10 m | LEO TM/TC |
| UHF | 300-1000 MHz | 0.3-1 m | LEO TM/TC, military |
| L | 1-2 GHz | 15-30 cm | GPS, mobile phones |
| S | 2-4 GHz | 7.5-15 cm | Deep space, ISS |
| C | 4-8 GHz | 3.75-7.5 cm | Satellites |
| X | 8-12 GHz | 2.5-3.75 cm | Military, deep space |
| Ku | 12-18 GHz | 1.67-2.5 cm | Satellite TV, internet |
| Ka | 26-40 GHz | 0.75-1.15 cm | High-rate data |

## Key Space Standards

| Standard | Organization | Purpose |
|----------|-------------|----------|
| ECSS-E-ST-50-12C | ESA | SpaceWire protocol |
| CCSDS 133.0-B-2 | CCSDS | Space packet protocol |
| CCSDS 132.0-B-2 | CCSDS | Telemetry data link |
| CCSDS 232.0-B-3 | CCSDS | Telecommand data link |
| MIL-STD-810G | US DoD | Environmental testing |
| MIL-STD-461G | US DoD | EMI/EMC requirements |
| NASA-STD-7001B | NASA | Vibroacoustic testing |
| ISO 24113 | ISO | Space debris mitigation |

---

# GLOSSARY OF SPACE TERMS

**ADCS:** Attitude Determination and Control System - keeps spacecraft pointing correctly

**Apogee:** Highest point in an elliptical orbit

**Attitude:** Orientation of spacecraft (roll, pitch, yaw)

**C&DH:** Command and Data Handling - spacecraft computer system

**CCSDS:** Consultative Committee for Space Data Systems - international standards organization

**Delta-V (Δv):** Change in velocity, "currency" of space missions

**ECSS:** European Cooperation for Space Standardization

**EDAC:** Error Detection and Correction - protects memory from radiation

**EPS:** Electrical Power System

**FDIR:** Fault Detection, Isolation, and Recovery - autonomous problem-solving

**GEO:** Geostationary Earth Orbit (35,786 km)

**GNC:** Guidance, Navigation, and Control

**GPS:** Global Positioning System (USA's GNSS)

**Isp:** Specific Impulse - efficiency metric for propulsion

**ISS:** International Space Station

**LEO:** Low Earth Orbit (200-2,000 km)

**MEO:** Medium Earth Orbit (2,000-35,786 km)

**MLI:** Multi-Layer Insulation - thermal blankets

**OBC:** On-Board Computer

**Perigee:** Lowest point in an elliptical orbit

**RTG:** Radioisotope Thermoelectric Generator - nuclear battery

**SEE:** Single Event Effects - radiation-induced errors

**SEL:** Single Event Latchup - radiation causes short circuit

**SEU:** Single Event Upset - radiation flips a bit in memory

**SSO:** Sun-Synchronous Orbit - passes over same location at same time

**TID:** Total Ionizing Dose - accumulated radiation damage

**TM/TC:** Telemetry/Telecommand - data down/commands up

**TMR:** Triple Modular Redundancy - three copies vote on correct answer

**TVAC:** Thermal Vacuum - test chamber simulating space

**TWR:** Thrust-to-Weight Ratio

---

# RECOMMENDED RESOURCES

## Books
1. **"Spacecraft Systems Engineering"** - Peter Fortescue, Graham Swinerd, John Stark
2. **"Space Mission Analysis and Design"** - James Wertz, Wiley Larson
3. **"Fundamentals of Astrodynamics"** - Roger Bate (the "Dover book")
4. **"An Introduction to the Mathematics and Methods of Astrodynamics"** - Richard Battin

## Online Resources
1. **NASA.gov** - Official NASA website, technical reports
2. **ESA.int** - European Space Agency
3. **ECSS.nl** - European space standards (free download)
4. **CCSDS.org** - Space communication standards
5. **Spaceflight101.com** - Mission details, launch tracking
6. **Gunter's Space Page** - Comprehensive satellite database
7. **N2YO.com** - Real-time satellite tracking

## YouTube Channels
1. **Everyday Astronaut** - Launch coverage, deep dives
2. **Scott Manley** - Orbital mechanics, space history
3. **Marcus House** - SpaceX updates
4. **NASA** - Official channel
5. **ESA** - European Space Agency channel

## Software/Tools
1. **GMAT (General Mission Analysis Tool)** - Free NASA software
2. **STK (Systems Tool Kit)** - Professional (expensive)
3. **Kerbal Space Program** - Educational game (orbital mechanics)
4. **Celestia** - Free space simulation
5. **Stellarium** - Free planetarium software

---

# CONCLUSION

This encyclopedia covers the fundamentals of spacecraft engineering from basic physics to current missions. Space is an incredibly challenging environment requiring careful engineering across multiple disciplines:

- **Orbital mechanics** determines mission design
- **Power systems** must work for 5-15 years
- **Thermal control** handles ±150°C swings
- **Radiation hardening** protects against ionizing radiation
- **Communication** over millions of kilometers
- **Attitude control** points with arc-second accuracy
- **Propulsion** enables orbital changes
- **Software** manages autonomous operations

The space industry has learned from 67 years of spaceflight (since Sputnik 1957), with each failure teaching valuable lessons about safety, testing, and design.

Current trends:
- **Commercialization:** SpaceX, Blue Origin, Rocket Lab
- **Reusability:** Falcon 9 boosters land and refly
- **Miniaturization:** CubeSats democratize space access
- **Constellations:** Thousands of satellites (Starlink, OneWeb)
- **Return to Moon:** Artemis program
- **Mars exploration:** Sample return, eventual human missions

The future of space is incredibly exciting with Moon bases, Mars colonization, space tourism, and potentially even interstellar probes in our lifetime!

---

**END OF ENCYCLOPEDIA**

**Total Pages:** ~150  
**Words:** ~25,000  
**Compiled:** February 2026  
**For:** EtherealX Avionics Engineer Assignment Preparation

Good luck with your assignment! 🚀
