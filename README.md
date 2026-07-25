🔬 Open Molecular Printing Platform & Applied Ionic Technologies

📌 Executive Summary

The Open Molecular Printing project is a pioneering Open Source Hardware (OSHW) initiative dedicated to democratizing and expanding the frontiers of Applied Molecular Printing and the additive manufacturing of electrochemically active materials.

Our fundamental goal is to transition from traditional geometric 3D printing to the functional construction of devices at the molecular and structural levels. We are developing a complete ecosystem—from the engineering of 3D printers with controlled-atmosphere chambers to the chemical formulations of ionic and polymeric printing inks—enabling on-demand fabrication of energy systems and functional devices directly on the desktop.

To validate the potential of this revolutionary technology, we begin with practical "start" applications: the replacement of traditional energy sources, such as everyday alkaline batteries, and the evolution toward advanced systems, such as Magnesium-Manganese Dioxide ($Mg-MnO_2$) structural batteries, culminating in monolithically printed high-performance drone airframes.

⚠️ Safety Disclaimer

THIS IS AN ADVANCED RESEARCH PROJECT IN MATERIALS CHEMISTRY AND MANUFACTURING.
The replication and experiments documented in this repository involve the handling of highly reactive metallic powders, organic solvents, radiation-curable resins, and inert gas environments.

Ink mixing and extrusion must be conducted strictly in ventilated areas or under an exhaust hood.

Personal Protective Equipment (PPE), including nitrile/butyl gloves, safety goggles, and respiratory protection for particulates, is mandatory.

The maintainers of this ecosystem disclaim all liability for incidents resulting from the incorrect replication of the chemical and physical processes described herein.

🏗️ Repository Architecture

The project is structured in a modular fashion to encourage specialized contributions across different technological fronts:

📁 /Chemistry & Inks: Open formulations of functional inks, including cathodic compounds ($MnO_2$ + conductive carbon additives), activated polymeric binders, and solid/gel electrolytes.

📁 /Printer & Atmosphere: Mechanical, electronic, and firmware designs for printers adapted for high-viscosity fluid extrusion (Direct Ink Writing - DIW), integrated UV curing modules, and sealed controlled-atmosphere chambers to prevent unwanted oxidation.

📁 /Applications (Start & Scale):

/Micro_Power: Parametric models and CAD files for printing compact energy cells (fully open and customizable alternatives to traditional alkaline batteries for IoT and portable devices).

/Structural_LFSD: Advanced cellular architectures (honeycomb and Voronoi) for structural batteries applied to unmanned aerial vehicle airframes.

📁 /Software: Trajectory control scripts, parametric G-code generation adapted for non-Newtonian fluids, and automation for the controlled environment.

🚀 Technological Roadmap

Our development journey scales from molecular foundations to decentralized industrial applications:

[ ] Phase 1: Ink Formulation & Rheology - Optimization of $MnO_2$ and carbon mixtures to ensure ideal thixotropic behavior for extrusion.

[ ] Phase 2: The Open Source Toolhead - Development and release of high-precision extrusion toolhead designs for accessible 3D printers.

[ ] Phase 3: "Start" Applications (Open Cells) - Successful printing of small-scale primary energy cells with custom geometries, proving commercial viability against conventional alkaline batteries.

[ ] Phase 4: Controlled Atmosphere & Scalability - Implementation of low-cost inert gas cabinets to allow the safe handling of reactive metallic anodes (such as pure Magnesium).

[ ] Phase 5: High-Performance Structural Integration - Completion of the LFSD project (energy-generating drone airframe) and consolidation of a global open molecular printing platform.

🤝 How to Contribute

The evolution of open molecular manufacturing requires multidisciplinary collaboration. We invite materials scientists, mechanical engineers, software developers, and open hardware enthusiasts to join forces.

Please consult our CONTRIBUTING.md and CODE_OF_CONDUCT.md to begin your interactions and submissions.

💡 Funding and Transparency

This project operates under the principles of total openness and transparency. We are seeking fiscal hosting through the Open Source Collective (OSC) to ensure integrity and community-managed governance of all obtained resources.

Funds collected are applied exclusively to:

Acquisition of analytical-grade chemical reagents and laboratory supplies.

Machining and prototyping of mechanical components and controlled-atmosphere chambers.

Computational infrastructure for molecular modeling and AI-assisted simulations.

📄 Licensing

This ecosystem is governed by rigorous open licenses:

Hardware, Mechanics, and CAD: CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S)

Firmware, Scripts, and Code: MIT License

Documentation, Manuals, and Texts: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)
