# KAPTUE TALOM LAËL ELISÉE

**Self-taught programmer | Software architecture is power | Student at the National Superior Polytechnic School of Yaounde | Low-Level dev enthusiats | Too hard ? We care ? | Just enjoying programming**

* [gesee37@gmail.com](https://www.google.com/search?q=mailto%3Agesee37%40gmail.com)
 
* [github.com/Gesee-y](https://www.google.com/search?q=https://github.com/Gesee-y)


*Yaoundé, Cameroon | Open to International Relocation & Remote Internships*

## About me

I'm a self-taught programmer with a passion for low-level development. I'm currently a student at the National School of Engineering Yaounde, where I'm learning softs skills as I wanted to have a broader understanding of the current software industry. That's why I'm actually in the Digital Humanity course.

## Skills

- **Programming Languages**: Julia, Nim, Rust, Python, JavaScript 
- **Software architecture**: Able to design and implement architecture that best suits a project requirement, believer that clean abstraction is power.
- **Tools**: Git, Godot 4, Gamemaker, etc.

## Achievements

**Cruise (Nim): A Game Engine Kernel**

*[Main Repository](https://github.com/Gesee-y/Cruise) | [ECS Engine](https://www.google.com/search?q=https://github.com/Gesee-y/Cruise/tree/main/src/ecs) | [Plugin System](https://github.com/Gesee-y/Cruise/tree/main/src/plugins) | [GPGPU Backend](https://github.com/Gesee-y/Cruise/tree/main/src/gpuarrays)*


This project is a game engine kernel written in Nim. Made to be what I conceptualized as a perfect game engine. It offers building blocks to build a game engine without going to the hell of low-level magic.
The architecture was designed to be able to host other architecture without restricting them.
I wrote more about it [here](https://github.com/Gesee-y/Cruise/tree/main/docs/A-perfect-game-engine.md)

The engine features:

- **Dual-DAG Architecture** were game systems are modelled as vertices and dependency/resources access as edges. Through *runtime borrow checking*, safe access is guaranteed even in a wild and interrupted multithreaded environment.
- **Shader VM**: A VM running on GPU, interpreting shader converted to a bytecode. This allows for dynamic shader compilation and execution without the need for a separate shader compiler, resolving shader compilation overhead (stuttering, loading screens, etc)
- **ECS**: A fragment vector based ECS storage allowing to mimick archetypes and sparse sets behaviors through storage organization, flexibility is achieved through abstract queries, inspired from relational database (views and more). This is a high performance data oriented ECS powered by Nim metaprogramming to allows the best performances. 


**Low-Level & Runtime Optimization Ecosystem (Julia)**

*[Arceus.jl](https://github.com/Gesee-y/Arceus.jl) | [Outdoors.jl](https://github.com/Gesee-y/Outdoors.jl) | [WavesFlow.jl](https://github.com/Gesee-y/WavesFlow.jl) | [EventNotifiers.jl](https://github.com/Gesee-y/EventNotifiers.jl) | [FunctionPooling.jl](https://github.com/Gesee-y/FunctionPooling.jl)*


- **JIT Memory Pooling:** Resolved severe JIT runtime memory allocation overhead by constructing a method-overriding recycling engine (`FunctionPooling`), shrinking dynamic function memory footprint from **55.5 MB down to 9.9 MB** for 1,000 tasks.
- **Arceus Hardware Traits ($O(1)$):** Implemented a trait-matching and decision engine utilizing **Magic Bitboards** and processor-native bit extraction instructions (`PEXT`/`BMI2`), speeding up structural lookup speeds.
- **Audio & Windowing Core:** Authored `WavesFlow.jl`, a zero-latency multi-threaded audio engine using lock-free circular buffers and a producer-consumer cycle. And `Outdoors.jl`, an OS-agnostic windowing/input microkernel interface used to allow users to add switch backends without important modification to their code.
- **2D Animation system**: Based on a layered architecture where smaller pieces (keyframes, animation frames) compose into higher level structure (animation player, blend tree, etc.) allowing peak extensibility while being easy to understand (just understand what you use)

**xxxxtale Engine (Godot / GDScript)**

*[xxxxtale Project](https://github.com/Gesee-y/xxxxtale-engine)*

* **Data-Driven Framework (xxxxtale):** Architected an engine framework separating engine logic from game assets using pure composition and fully serialized resources (CSV parsers), which successfully powered 3 published standalone community games.
* **Custom Custom DSL & Physics:** Designed a custom Domain Specific Language (DSL) parser for script-triggered text events and rolled out a specialized, custom 2D collision system to bypass default engine which suffered from excessive tunneling when bullets of the arena where moving too fast (nothing fancy, just me optimizing my engine with the knowledge of a 15 y/o and high-school maths).


## EDUCATION & ACADEMIC ACHIEVEMENTS

**National Superior School Engineering of Yaounde (ENSPY), Cameroon**

*Master of Engineering (5-Year Program)* | Expected Graduation: 2030

* **Current Core Focus:** Computer Architecture, Mathematical Statistics, Linear Algebra, Marketing, General Economics, Applied Law.

**International Mathematical Modeling Challenge (IMMC)**

*Cameroon National Team Representative | [Our work](https://github.com/Gesee-y/IMMC2025.jl)*

* Competed globally in applied mathematics. Was about the scheduling of a global sport competition. Not quite happy with our result but yeah.

---

### HOBBIES & INTERESTS

* Competitive Basketball, Game Music Composition, Horror Narrative Framework Design.
