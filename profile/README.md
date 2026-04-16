# Forming Worlds Lab

Code hub of the [Forming Worlds Lab](https://www.formingworlds.space), an interdisciplinary and multi-national team of researchers investigating the formation and evolution of rocky exoplanets and terrestrial worlds of the Solar System. All codes here are open source, under active research development, and executable stand-alone.

> [!NOTE]
> If you see changes pushed to one of the repositories that are not yet linked to a journal publication and you want to make use of them, please contact the authors first.

**Questions or suggestions?** Open a [Discussion](https://github.com/orgs/FormingWorlds/discussions), an `Issue` on the relevant repository, or email contact@formingworlds.space.

## PROTEUS, coupled framework

[**PROTEUS**](https://github.com/FormingWorlds/PROTEUS) · [Development Roadmap](https://github.com/orgs/FormingWorlds/projects/7)

Coupled atmosphere-interior framework to simulate the temporal evolution of rocky planets. The modules below plug into PROTEUS and also run stand-alone.

### Atmosphere
| Code | Purpose |
|---|---|
| [AGNI](https://github.com/nichollsh/AGNI) | Atmospheric radiative-convective solver |
| [JANUS](https://github.com/FormingWorlds/JANUS) | Parameterised convective model of planetary atmospheres |
| [SOCRATES](https://github.com/FormingWorlds/SOCRATES) | Atmospheric radiative transfer code |
| [VULCAN](https://github.com/FormingWorlds/VULCAN) | Photochemical kinetics model for exoplanetary atmospheres |

### Interior
| Code | Purpose |
|---|---|
| [SPIDER](https://github.com/FormingWorlds/SPIDER) | Parameterised interior dynamics for rocky planets with molten and/or solid interiors |
| [Aragog](https://github.com/FormingWorlds/aragog) | Interior dynamics of solid, liquid, and mixed phase rocky mantles |
| [Zalmoxis](https://github.com/FormingWorlds/Zalmoxis) | Internal structure of rocky planets and exoplanets |
| [PALEOS](https://github.com/maraattia/PALEOS) | Equation-of-state tables for Fe, MgSiO₃, H₂O |

### Volatiles, escape, stellar, tidal
| Code | Purpose |
|---|---|
| [CALLIOPE](https://github.com/FormingWorlds/CALLIOPE) | Volatile equilibrium outgassing from magma oceans |
| [ZEPHYRUS](https://github.com/FormingWorlds/ZEPHYRUS) | Atmospheric escape on magma ocean planets |
| [MORS](https://github.com/FormingWorlds/MORS) | Rotation and flux evolution of stars |
| [Obliqua](https://github.com/FormingWorlds/Obliqua) | Poro-visco-elastic solid-liquid tidal heating model |

## Related planetary modelling

| Code | Purpose |
|---|---|
| [i2elvis_planet](https://github.com/FormingWorlds/i2elvis_planet) | Fluid mechanics and thermochemistry of planetesimal and protoplanet interiors |
| [Erebus.jl](https://github.com/FormingWorlds/Erebus.jl) | Hydro-thermo-mechanical-chemical geodynamic code with two-phase thermodynamic reactions |
| [THOTH](https://github.com/FormingWorlds/THOTH) | Thermal emission and reflection properties of rocky exoplanet surfaces |
