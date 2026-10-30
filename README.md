# Bandit Description

Bandit Description is the open-source robot model for Bandit, a community-driven humanoid robotics platform.

Start with a complete robot description, bring it into your preferred robotics environment or URDF editor, experiment with new capabilities, and share what you build.

Whether you're developing controllers, exploring robot kinematics, designing new hardware, or building a simulation playground, Bandit is yours to extend.

## What's Included

- **Robot URDF** — The initial Bandit 24-DoF kinematic structure.
- **3D meshes** — The custom Bandit exterior and robot geometry.
- **Materials and textures** — Bandit's distinctive raccoon-inspired appearance.
- **Physical definitions** — Joint limits, collision geometry and inertial properties for simulation development.

The initial Bandit model builds on the open-source RoboParty RP1 robot architecture.

## Get Started

Clone the repository:

```bash
git clone https://github.com/banditteam/bandit-description.git
```

The current model is provided as `bandit_final_v2.urdf`, alongside the required `meshes/` directory.

Keep the URDF and its referenced assets together when importing the model into a simulator.

## Make Bandit Your Own

This repository is designed to be extended.

You can:

- Import Bandit into your own compatible simulation environment.
- Experiment with custom motion and control systems.
- Add new joints, actuators and sensors.
- Replace or redesign its exterior meshes.
- Develop new robot variants.
- Share compatible improvements with the community.

**Bandit is a starting point, not a finished design.**

## Contributing

We welcome contributions involving robot geometry, joint definitions, new hardware configurations, improved simulation compatibility and documentation.

For major structural changes, consider introducing a versioned robot variant to preserve compatibility with the existing model.

Open an Issue to discuss your proposal, then submit a Pull Request with your implementation.

## Related Repositories

**[Bandit Robotics](https://github.com/banditteam/bandit-robotics)** — Simulation, expressive control and robotics development.

**[Bandit Design](https://github.com/banditteam/bandit-design)** — Editable Blender sources and mechanical customization.

**[Bandit Simarena Integration](https://github.com/banditteam/bandit-simarena-integration)** — Advanced physics and locomotion simulation in SimArena.

## Current Status

Reusable controllers, autonomous locomotion and additional hardware variants are rolling out gradually.

**Build it. Move it. Make it yours.**
