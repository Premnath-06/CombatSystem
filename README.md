# Combat System — Smart Enemy AI (UE5)

An ongoing Unreal Engine 5 learning project focused on building intelligent enemy AI and combat mechanics, following Ali Elzoheiry's **Smart Enemy AI** course.

I'm using this project to learn and experiment with enemy behavior, AI logic, combat interactions, and character systems in Unreal Engine 5.

## 📌 Project Status

**In Development — Currently Following Part 7 of the Course**

This project is still under development. Features and systems are being implemented and tested as I progress through the course.

## 🎯 Project Goals

- Learn and implement smart enemy AI behavior in Unreal Engine 5.
- Develop enemy combat and player interaction systems.
- Understand AI behavior, decision-making, and character logic.
- Improve character death and physics-based ragdoll behavior.
- Practice debugging and documenting issues during development.

## 📂 Project Structure

The project is organized to separate the main gameplay implementation from supporting assets.

### ⭐ `madebyme/` — Main Project Implementation

**This is the main folder to explore when looking for the core gameplay implementation.**

It contains the main gameplay elements, including:

- Player characters and related gameplay logic.
- Enemy characters and AI behavior.
- Enemy AI systems and gameplay logic.
- Other main gameplay components and systems used in the project.

If you want to understand how the player, enemies, and AI work together, start by exploring the `madebyme/` folder.

### 📦 Other Folders — Supporting Assets

The other folders primarily contain supporting assets and resources used by the main project, such as:

- Character models and meshes.
- Animations.
- Textures and materials.
- Other assets required by the gameplay systems.

These resources support the main implementation in `madebyme/`.

**Note:** This describes the intended organization of the project. Individual folders may contain additional resources or configuration files.

## 🛠️ Built With

- **Unreal Engine 5** — Game development.
- **Blueprints and/or C++** — Gameplay and AI implementation, depending on the systems used.
- **Git and GitHub** — Version control and issue tracking.
- **Git LFS** — Version control for large Unreal Engine assets.

## 📚 Learning Resource

This project follows Ali Elzoheiry's **Smart Enemy AI** course.

- **Course instructor:** Ali Elzoheiry
- **Current progress:** Part 7
- **Learning approach:** Implementing course concepts, testing gameplay behavior, and debugging issues as development progresses.

This repository documents my learning and implementation progress while following the course.

## 🐛 Known Issues

### Players and Enemies Do Not Ragdoll on Death

**Status:** Investigating

**Expected Behavior**
- The player should enter a physics-driven ragdoll state when dying.
- Enemies should enter a physics-driven ragdoll state when dying.
- Character meshes should respond to physics and gravity to produce a natural collapse.

**Actual Behavior**
- Players and enemies do not ragdoll as expected when they die.

**Possible Investigation Areas**
- Death events and ragdoll logic.
- Skeletal mesh physics simulation.
- Physics Asset configuration.
- Animation or character movement interfering with physics.
- Differences between player and enemy death implementations.

See the [GitHub Issues](../../issues) page for updates and troubleshooting.

## 🚧 Development Roadmap

- [x] Create the Unreal Engine project repository.
- [x] Begin following the Smart Enemy AI course.
- [ ] Continue implementing features beyond Part 7.
- [ ] Investigate and fix player ragdoll behavior.
- [ ] Investigate and fix enemy ragdoll behavior.
- [ ] Document additional features, fixes, and progress.

## 📸 Screenshots and Videos

Screenshots and gameplay recordings will be added as the project develops.

## ⚠️ Project Status Disclaimer

This is a work in progress, not a finished game. Some features may be incomplete or may not behave as expected.

## 📄 Credits and Acknowledgments

- **Course instructor:** Ali Elzoheiry
- **Project developer:** Premnath Rajule

This project is being developed for learning and experimentation while following the Smart Enemy AI course.

Course materials, third-party assets, and other included resources remain the property of their respective owners and are subject to their applicable licenses.
