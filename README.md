# Avaj Launcher

An introductory Java project at 42 exploring Object-Oriented Design (OOD). This program is an aircraft simulation tracking various flight types moving through dynamically changing coordinates and weather conditions, built entirely using Java without external tools.

---

## 🛠️ Features
* **Design Patterns:** Implements **Observer**, **Singleton**, and **Factory** design patterns.
* **Dynamic Weather Simulation:** Generates weather (`RAIN`, `FOG`, `SUN`, `SNOW`) mapping directly to 3D coordinates.
* **Aircraft Dynamics:** Tracks distinct altitude and coordinate updates for `JetPlane`, `Helicopter`, and `Baloon` types based on changing weather conditions.

---

### Prerequisites
Make sure you have `java` and `javac` installed in your terminal environment.

### Compilation
Compile the project from the root folder using the standard Java compiler syntax (avoiding build tools):

```bash
find -name "*.java" > sources.txt
javac @sources.txt
