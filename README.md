# OOP Instruments Project (Kotlin)

## Project Overview
We have an **abstract class** called `Instrument`, which is the parent of all instruments.  
It cannot be instantiated directly, because in this project an instrument must either be a `Drum` or a `BassGuitar`.

### Class Hierarchy
- `Instrument` (abstract)  
  - `Drum`  
    - `VDrum`  
    - `KitDrum` (abstract)  
      - `FullKitDrum`  
      - `PartialKitDrum`  
  - `BassGuitar` (abstract)  
    - `BatteryBassGuitar`  
    - `NonBatteryBassGuitar`  

This structure ensures that only valid, **concrete instruments** can be created, while shared fields and behaviors are defined in abstract classes.

---

## OOP Concepts Demonstrated
This project demonstrates almost all of the core object-oriented programming concepts, including:

- **Abstraction** (abstract classes, interfaces)  
- **Encapsulation** (`private`, `protected`, …)  
- **Inheritance**  
- **Polymorphism** (`override`, `overload`)  
- **Class and object**  
- **Primary constructor and secondary constructor**  
- **Getters and setters**  
- **Enum class**  

---

## Language and Tools
- **Kotlin**  
- **OOP principles**  
- Example-based, educational approach  
