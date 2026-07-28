# Silvaco Code Documentation

## File: cmos_45nm.in

### Mesh Definition (Lines 1-30)
Fine mesh (0.002 μm) near gate, coarse (0.01 μm) in bulk.

### Device Structure (Lines 32-60)
Gate length: 45 nm
Oxide thickness: ~10 nm
S/D doping: 1×10^20 cm^-3

### How to Run
```bash
atlas -i cmos_45nm.in -o output.log
```

### Runtime
~10-15 minutes
