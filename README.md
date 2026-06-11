# avaj-launcher

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

### Running the simulation
```
java ro.academyplus.avaj.simulator.Simulator scenario.txt
```

### Scenario.txt exmaple
```
25
Baloon B1 2 3 20
Baloon B2 1 8 66
JetPlane J1 23 44 32
Helicopter H1 654 33 20
Helicopter H2 22 33 44
Helicopter H3 98 68 99
Baloon B3 102 22 34
JetPlane J2 11 99 768
Helicopter H4 223 23 54
```
