# Forming Worlds Lab

Code hub of the [Forming Worlds Lab](https://www.formingworlds.space), an interdisciplinary and multi-national team of researchers investigating the formation and evolution of rocky exoplanets and terrestrial worlds of the Solar System. All codes here are open source, under active research development, and executable stand-alone.

> [!NOTE]
> If you see changes pushed to one of the repositories that are not yet linked to a journal publication and you want to make use of them, please contact the authors first.

**Questions or suggestions?** Open a [Discussion](https://github.com/orgs/FormingWorlds/discussions), an `Issue` on the relevant repository, or email contact@formingworlds.space.

## PROTEUS, coupled framework

[**PROTEUS**](https://github.com/FormingWorlds/PROTEUS) · [Documentation](https://proteus-framework.org) · [Development Roadmap](https://github.com/orgs/FormingWorlds/projects/7)

Coupled atmosphere-interior framework to simulate the temporal evolution of rocky planets. The modules below plug into PROTEUS and also run stand-alone.

### Atmosphere
| Code | Purpose <img width="1200" height="0"> | Docs |
|---|---|---|
| [AGNI](https://github.com/nichollsh/AGNI) | Atmospheric radiative-convective solver | [link](http://www.h-nicholls.space/AGNI/) |
| [JANUS](https://github.com/FormingWorlds/JANUS) | Parameterised convective model of planetary atmospheres | [link](https://proteus-framework.org/JANUS) |
| [SOCRATES](https://github.com/FormingWorlds/SOCRATES) | Atmospheric radiative transfer code | [link](https://proteus-framework.org/SOCRATES/) |
| [VULCAN](https://github.com/FormingWorlds/VULCAN) | Photochemical kinetics model for exoplanetary atmospheres | [link](https://proteus-framework.org/VULCAN/) |

### Interior
| Code | Purpose <img width="1200" height="0"> | Docs |
|---|---|---|
| [SPIDER](https://github.com/FormingWorlds/SPIDER) | Parameterised interior dynamics for rocky planets with molten and/or solid interiors | [link](https://proteus-framework.org/SPIDER/) |
| [Aragog](https://github.com/FormingWorlds/aragog) | Interior dynamics of solid, liquid, and mixed phase rocky mantles | [link](https://proteus-framework.org/aragog/) |
| [Zalmoxis](https://github.com/FormingWorlds/Zalmoxis) | Internal structure of rocky planets and exoplanets | [link](https://proteus-framework.org/Zalmoxis) |
| [PALEOS](https://github.com/maraattia/PALEOS) | Equation-of-state tables for Fe, MgSiO₃, H₂O | — |

### Volatiles, escape, stellar, tidal
| Code | Purpose <img width="1200" height="0"> | Docs |
|---|---|---|
| [CALLIOPE](https://github.com/FormingWorlds/CALLIOPE) | Volatile equilibrium outgassing from magma oceans | [link](https://proteus-framework.org/CALLIOPE/) |
| [atmodeller](https://github.com/FormingWorlds/atmodeller) | Volatile partitioning between planetary reservoirs with solubility, non-ideality, and condensation | [link](https://proteus-framework.org/atmodeller/) |
| [ZEPHYRUS](https://github.com/FormingWorlds/ZEPHYRUS) | Atmospheric escape on magma ocean planets | [link](https://proteus-framework.org/ZEPHYRUS/) |
| [MORS](https://github.com/FormingWorlds/MORS) | Rotation and flux evolution of stars | [link](https://proteus-framework.org/MORS) |
| [Obliqua](https://github.com/FormingWorlds/Obliqua) | Poro-visco-elastic solid-liquid tidal heating model | [link](https://proteus-framework.org/Obliqua) |

## Related planetary modelling

| Code | Purpose <img width="1200" height="0"> | Docs |
|---|---|---|
| [i2elvis_planet](https://github.com/FormingWorlds/i2elvis_planet) | Fluid mechanics and thermochemistry of planetesimal and protoplanet interiors | — |
| [Erebus.jl](https://github.com/FormingWorlds/Erebus.jl) | Hydro-thermo-mechanical-chemical geodynamic code with two-phase thermodynamic reactions | [link](https://proteus-framework.org/Erebus.jl/) |
| [THOTH](https://github.com/FormingWorlds/THOTH) | Thermal emission and reflection properties of rocky exoplanet surfaces | — |
