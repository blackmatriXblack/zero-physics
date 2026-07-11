# zero-physics / 零物之理

> **167 Interactive Physics Simulations / 167个交互式物理模拟实验**
>
> A comprehensive collection of physics simulations covering Classical Mechanics, Electromagnetism, Thermodynamics, Waves & Optics, Quantum Mechanics, Relativity, Fluid Dynamics, Chaos & Nonlinear Systems, Condensed Matter, Nuclear & Particle Physics, Astrophysics, Computational Physics, and Circuits.
>
> 涵盖经典力学、电磁学、热力学、波与光学、量子力学、相对论、流体动力学、混沌与非线性系统、凝聚态物理、核物理与粒子物理、天体物理、计算物理和电路分析的综合性物理模拟合集。
>
> **[Explore / 探索](https://blackmatrixblack.github.io/zero-physics/)**

## Table of Contents / 目录

1. [Classical Mechanics / 经典力学](#1-classical-mechanics--经典力学)
2. [Electromagnetism / 电磁学](#2-electromagnetism--电磁学)
3. [Thermodynamics / 热力学](#3-thermodynamics--热力学)
4. [Waves & Optics / 波与光学](#4-waves--optics--波与光学)
5. [Quantum Mechanics / 量子力学](#5-quantum-mechanics--量子力学)
6. [Relativity / 相对论](#6-relativity--相对论)
7. [Fluid Dynamics / 流体动力学](#7-fluid-dynamics--流体动力学)
8. [Chaos & Nonlinear / 混沌与非线性](#8-chaos--nonlinear--混沌与非线性)
9. [Condensed Matter / 凝聚态物理](#9-condensed-matter--凝聚态物理)
10. [Nuclear & Particle / 核物理与粒子物理](#10-nuclear--particle--核物理与粒子物理)
11. [Astrophysics / 天体物理](#11-astrophysics--天体物理)
12. [Computational / 计算物理](#12-computational--计算物理)
13. [Circuits / 电路](#13-circuits--电路)

---

# 1. Classical Mechanics / 经典力学

### 1. [AC Circuit / 交流电路](https://blackmatrixblack.github.io/zero-physics/ac-circuit/)
- **EN:** This simulation demystifies alternating current circuits by providing an interactive oscilloscope view of voltage and current waveforms. Learners can adjust the driving frequency and observe how the phase relationship between voltage and current evolves across resistors, capacitors, and inductors. The key equation demonstrated is V(t) = V₀sin(ωt) for the source voltage and I(t) = I₀sin(ωt + φ) where φ is the phase angle determined by the circuit impedance Z = √(R² + (X_L − X_C)²). Reactances X_L = ωL and X_C = 1/(ωC) are visualized dynamically as sliders change. The simulation plots both time-domain waveforms and a phasor diagram showing the rotational vector representation of AC quantities. Educational value includes understanding resonance at ω₀ = 1/√(LC), where impedance minimizes and current peaks. By toggling component values, one can see how capacitive and inductive reactance oppose each other.
- **CN:** 该模拟通过交互式示波器视图展示交流电路中的电压和电流波形，揭示交流电的内在规律。学习者可以调节驱动频率，观察电阻、电容和电感上电压与电流之间相位关系的实时变化。核心方程为电源电压 V(t) = V₀sin(ωt) 和电流 I(t) = I₀sin(ωt + φ)，其中相位角 φ 由电路阻抗 Z = √(R² + (X_L − X_C)²) 决定。感抗 X_L = ωL 和容抗 X_C = 1/(ωC) 随着滑块调整而动态变化。模拟同时绘制时域波形图和相量图（旋转矢量表示法），直观展示交流量的矢量叠加。教育价值在于理解 ω₀ = 1/√(LC) 处的谐振现象——此时阻抗最小、电流达到峰值。通过切换元件参数，可以观察电容性和电感性电抗如何相互抵消。

### 2. [Acoustic Resonance / 声学共振](https://blackmatrixblack.github.io/zero-physics/acoustic-resonance/)
- **EN:** This simulation explores acoustic resonance in air columns, demonstrating how standing sound waves form at specific frequencies inside tubes. The fundamental physics follows the wave equation ∂²y/∂t² = v²∂²y/∂x² with boundary conditions determining the resonant modes. For an open tube, resonance occurs at fₙ = nv/(2L) where n = 1,2,3..., and for a closed tube at fₙ = (2n−1)v/(4L). Users can switch between open and closed boundary configurations and adjust the driving frequency to watch pressure nodes and antinodes form. The simulation color-codes air pressure variations, with red representing compression and blue representing rarefaction. A frequency spectrum display shows the harmonic series, helping learners identify overtones and their relative amplitudes. Educational value extends to understanding timbre — how different instruments produce distinct sounds via their unique harmonic profiles.
- **CN:** 该模拟探索空气柱中的声学共振现象，展示特定频率下管内形成的驻波模式。核心物理基于波动方程 ∂²y/∂t² = v²∂²y/∂x²，边界条件决定共振模式。开端管的共振频率为 fₙ = nv/(2L)（n = 1,2,3...），闭端管为 fₙ = (2n−1)v/(4L)。用户可以切换开端和闭端两种边界配置，调节驱动频率观察压力波节和波腹的形成过程。模拟用颜色编码表示气压变化——红色代表压缩区，蓝色代表稀疏区。频谱图显示谐波系列，帮助学习者识别泛音及其相对振幅。教育意义在于理解音色本质——不同乐器如何通过独特的谐波谱产生各异的声音。

### 3. [Angular Momentum / 角动量](https://blackmatrixblack.github.io/zero-physics/angular-momentum/)
- **EN:** This interactive simulation visualizes the vector nature of angular momentum L = r × p = Iω in three-dimensional space. Users can rotate a spinning object and adjust its mass distribution (moment of inertia I = Σmr²) to see how angular velocity ω responds to conserve angular momentum. The simulation clearly demonstrates the right-hand rule for the cross product, showing L⃗ perpendicular to the plane of r⃗ and p⃗. A key interactive feature allows changing the rotational axis and observing precession effects when an external torque τ = dL/dt is applied. Conservation of angular momentum is shown in real-time: when a spinning figure pulls arms inward (reducing I), angular velocity increases proportionally. Educational value includes understanding gyroscopic stability, the relationship between torque and angular momentum change, and the rotational analog of Newton's laws.
- **CN:** 该交互式模拟在三维空间中可视化角动量的矢量特性 L = r × p = Iω。用户可以旋转一个旋转物体并调节其质量分布（转动惯量 I = Σmr²），观察角速度 ω 如何在角动量守恒条件下相应变化。模拟清晰展示了叉积的右手定则，显示 L⃗ 垂直于 r⃗ 和 p⃗ 构成的平面。关键的交互功能是改变旋转轴，当施加外力矩 τ = dL/dt 时观察进动效应。角动量守恒得到实时呈现：当旋转体收回手臂时（转动惯量减小），角速度成比例增加。教育价值在于理解陀螺稳定性、力矩与角动量变化之间的关系以及牛顿定律的转动类比。

### 4. [Atwood Machine / 阿特伍德机](https://blackmatrixblack.github.io/zero-physics/atwood-machine/)
- **EN:** This simulation recreates the classic Atwood machine experiment: two masses connected by a string over a frictionless pulley. The core physics is described by Newton's second law applied to the system: a = (m₁ − m₂)g/(m₁ + m₂) and tension T = 2m₁m₂g/(m₁ + m₂). Users can adjust both masses independently via sliders and watch the resulting motion in real-time. The simulation displays force diagrams showing gravitational forces and tension vectors acting on each mass. Velocity and acceleration graphs are plotted against time, allowing learners to see constant acceleration motion confirmed. The simulation also includes an option to add pulley mass and friction for more realistic scenarios, extending to Iα = τ for rotational inertia effects. Educational value includes understanding the relationship between net force, mass, and acceleration.
- **CN:** 该模拟重现了经典的阿特伍德机实验：两个质量通过绳子连接于无摩擦定滑轮两侧。核心物理由牛顿第二定律描述：加速度 a = (m₁ − m₂)g/(m₁ + m₂)，张力 T = 2m₁m₂g/(m₁ + m₂)。用户可通过滑块独立调节两个质量，实时观察运动变化。模拟显示每个质量的受力分析图——重力矢量和张力矢量清晰可见。速度-时间和加速度-时间图同步绘制，确认匀加速运动。模拟还提供添加滑轮质量和摩擦力的选项，引入 Iα = τ 的转动惯量效应。教育价值在于理解净力、质量和加速度之间的关系。

### 5. [Ballistic Pendulum / 弹道摆](https://blackmatrixblack.github.io/zero-physics/ballistic-pendulum/)
- **EN:** This simulation demonstrates the classic ballistic pendulum experiment, which combines projectile motion with inelastic collisions and pendulum mechanics. A projectile of mass m embeds into a pendulum bob of mass M, and the system swings upward to height h. Conservation of momentum applies during the collision: mv = (m+M)V, followed by conservation of mechanical energy: ½(m+M)V² = (m+M)gh. Users can adjust the projectile mass, velocity, and pendulum length to observe how these parameters affect the swing height. The simulation visualizes the trajectory before impact and the pendulum arc after collision, with velocity vectors shown at each stage. The calculated initial velocity is displayed, showing how ballistic pendulums were historically used to measure bullet speeds. Educational value includes understanding the distinction between elastic and inelastic collisions.
- **CN:** 该模拟展示了经典的弹道摆实验，将抛体运动、非弹性碰撞和摆运动结合于一体。质量为 m 的弹丸射入质量为 M 的摆锤并嵌入其中，系统摆升至高度 h。碰撞过程动量守恒：mv = (m+M)V，随后机械能守恒：½(m+M)V² = (m+M)gh。用户可以调节弹丸质量、速度和摆长，观察这些参数如何影响摆升高度。模拟可视化碰撞前的弹道轨迹和碰撞后的摆弧运动。弹丸初速度的计算结果显示于界面，说明弹道摆历史上如何用于测量子弹速度。教育价值在于理解弹性碰撞与非弹性碰撞的区别。

### 6. [Billiard Simulation / 台球模拟](https://blackmatrixblack.github.io/zero-physics/billiard-simulation/)
- **EN:** This simulation models elastic collisions between multiple circular objects on a frictionless table. Each collision is governed by conservation of momentum m₁v₁i + m₂v₂i = m₁v₁f + m₂v₂f and conservation of kinetic energy ½m₁v₁i² + ½m₂v₂i² = ½m₁v₁f² + ½m₂v₂f² for perfectly elastic impacts. The simulation calculates post-collision velocities using the formula for 2D elastic collisions, resolving normal and tangential components. Users can place balls at arbitrary positions, set initial velocities, and observe the resulting chain reactions. Users can adjust coefficients of restitution between 0 (perfectly inelastic) and 1 (perfectly elastic) to explore intermediate scenarios. Educational value includes understanding conservation laws in multi-body systems and the difference between head-on and oblique collisions.
- **CN:** 该模拟在无摩擦台面上模拟多个圆形物体之间的弹性碰撞。每次碰撞遵循动量守恒 m₁v₁i + m₂v₂i = m₁v₁f + m₂v₂f 和动能守恒 ½m₁v₁i² + ½m₂v₂i² = ½m₁v₁f² + ½m₂v₂f²。模拟通过分解法向和切向分量计算二维弹性碰撞后的速度。用户可在任意位置放置球体，设定初速度，观察连锁反应。用户可在 0（完全非弹性）到 1（完全弹性）之间调节恢复系数。教育价值在于理解多体系统中的守恒定律以及正碰与斜碰的区别。

### 7. [Bouncing Ball / 弹跳球](https://blackmatrixblack.github.io/zero-physics/bouncing-ball/)
- **EN:** This simulation illustrates the physics of a bouncing ball under gravity, demonstrating energy loss through successive impacts. The ball's motion follows the kinematic equations y(t) = y₀ + v₀t − ½gt² during free flight, with velocity reversal at each bounce reduced by the coefficient of restitution e = √(h₁/h₀). Users can adjust gravity, initial height, and restitution coefficient to see how these parameters affect bounce height and frequency. The simulation displays energy bar charts showing the conversion between kinetic energy KE = ½mv², gravitational potential energy PE = mgh, and energy lost as heat or sound on each bounce. Educational value includes understanding energy dissipation, the concept of inelastic collisions with a fixed surface, and the geometric series governing bounce heights (hₙ = h₀e²ⁿ).
- **CN:** 该模拟演示重力作用下弹跳球的物理过程，展示连续碰撞中的能量损失。球的运动遵循自由飞行阶段的运动学方程 y(t) = y₀ + v₀t − ½gt²，每次碰撞时速度反转并由恢复系数 e = √(h₁/h₀) 减小。用户可以调节重力加速度、初始高度和恢复系数，观察这些参数如何影响弹跳高度和频率。模拟显示能量条形图，展示动能 KE = ½mv²、重力势能 PE = mgh 和能量损失之间的转换。教育价值在于理解能量耗散、与固定表面非弹性碰撞的概念以及弹跳高度的几何级数规律（hₙ = h₀e²ⁿ）。

### 8. [Center of Mass / 质心](https://blackmatrixblack.github.io/zero-physics/center-of-mass/)
- **EN:** This simulation visualizes the concept of center of mass for multi-particle systems and extended rigid bodies. The center of mass is calculated as R_cm = (Σmᵢrᵢ)/(Σmᵢ) for discrete systems, or R_cm = (1/M)∫r dm for continuous bodies. Users can arrange multiple point masses on a 2D plane, adjusting each mass value and position while the simulation shows the resulting center of mass location as a highlighted marker. Velocity vectors show how individual masses move around the center of mass in a system with no external forces, demonstrating that the center of mass moves with constant velocity as predicted by ΣF_ext = M·a_cm. Educational value includes understanding the stability of objects, the relationship between center of mass and center of gravity, and why tall objects tip over.
- **CN:** 该模拟可视化多粒子系统和扩展刚体的质心概念。质心计算公式为 R_cm = (Σmᵢrᵢ)/(Σmᵢ)（离散系统）或 R_cm = (1/M)∫r dm（连续体）。用户可在二维平面上排列多个质点，调节各点的质量和位置，模拟将以高亮标记显示质心位置。速度矢量展示无外力系统中各质点如何围绕质心运动，证实 ΣF_ext = M·a_cm 所描述的质心匀速运动规律。教育价值在于理解物体稳定性、质心与重心之间的关系，以及高大物体为何容易倾倒。

### 9. [Central Force / 中心力](https://blackmatrixblack.github.io/zero-physics/central-force/)
- **EN:** This simulation explores motion under central forces, where the force magnitude depends only on distance from a fixed point and always points radially. The general central force F(r) = −k/r² corresponds to gravitational and electrostatic cases, while F(r) = −kr represents the harmonic oscillator. Users can select different force laws (inverse-square, linear, cubic) and adjust parameters to observe dramatically different orbital patterns. The simulation numerically integrates equations of motion and displays the trajectory. Kepler's laws emerge naturally for inverse-square forces: elliptical orbits with the center at one focus, equal areas swept in equal times (dA/dt = L/2m = constant), and T² ∝ a³. Educational value includes understanding orbital mechanics and effective potential U_eff(r) = U(r) + L²/(2mr²).
- **CN:** 该模拟探索中心力作用下的运动——力的大小仅取决于到固定点的距离且方向始终沿径向。一般中心力形式 F(r) = −k/r² 对应引力和静电情况，F(r) = −kr 代表谐振子。用户可选择不同的力的定律（平方反比、线性、立方）并调节参数，观察截然不同的轨道图案。模拟通过数值积分运动方程显示轨迹。平方反比力自然展现开普勒定律：椭圆轨道、等面积定律（dA/dt = L/2m = 常数）和 T² ∝ a³。教育价值在于理解轨道力学和有效势 U_eff(r) = U(r) + L²/(2mr²)。

### 10. [Circular Motion / 圆周运动](https://blackmatrixblack.github.io/zero-physics/circular-motion/)
- **EN:** This simulation provides a comprehensive visualization of uniform and non-uniform circular motion. The fundamental relationship v = ωr connects tangential velocity to angular velocity, with centripetal acceleration a_c = v²/r = ω²r directed toward the center. Users can adjust angular velocity, radius, and tangential acceleration to observe how these parameters affect the motion. The simulation displays position, velocity, and acceleration vectors in real-time as the object traces a circular path. A key feature is the simultaneous display of linear (s, v, a) and angular (θ, ω, α) kinematic quantities side by side. Educational value includes understanding the vector nature of rotational motion and the relationship between period T = 2π/ω and frequency f = 1/T.
- **CN:** 该模拟全面可视化匀速和非匀速圆周运动。基本关系 v = ωr 将切向速度与角速度相连，向心加速度 a_c = v²/r = ω²r 指向圆心。用户可以调节角速度、半径和切向加速度，观察这些参数如何影响运动。模拟实时显示位置、速度和加速度矢量，物体沿圆形路径运动。关键功能是同时展示线量（s、v、a）和角量（θ、ω、α）的运动学参数。教育价值在于理解转动运动的矢量性质以及周期 T = 2π/ω 与频率 f = 1/T 之间的关系。

### 11. [Elastic Collision 1D / 一维弹性碰撞](https://blackmatrixblack.github.io/zero-physics/elastic-collision-1d/)
- **EN:** This simulation models perfectly elastic collisions between two masses in one dimension, governed by simultaneous conservation of momentum m₁v₁i + m₂v₂i = m₁v₁f + m₂v₂f and kinetic energy ½m₁v₁i² + ½m₂v₂i² = ½m₁v₁f² + ½m₂v₂f². The final velocities are calculated using v₁f = (m₁−m₂)v₁i/(m₁+m₂) + 2m₂v₂i/(m₁+m₂) and v₂f = 2m₁v₁i/(m₁+m₂) + (m₂−m₁)v₂i/(m₁+m₂). Users can independently adjust both masses and their initial velocities, then observe the collision in slow motion or real-time. Special cases are highlighted: equal masses exchange velocities, a light mass striking a heavy one bounces back. Educational value includes understanding why conservation laws are independent yet must be satisfied simultaneously.
- **CN:** 该模拟模拟一维空间中两个质量之间的完全弹性碰撞，受动量守恒 m₁v₁i + m₂v₂i = m₁v₁f + m₂v₂f 和动能守恒 ½m₁v₁i² + ½m₂v₂i² = ½m₁v₁f² + ½m₂v₂f² 共同支配。最终速度计算公式为 v₁f = (m₁−m₂)v₁i/(m₁+m₂) + 2m₂v₂i/(m₁+m₂) 和 v₂f = 2m₁v₁i/(m₁+m₂) + (m₂−m₁)v₂i/(m₁+m₂)。用户可独立调节两个质量及其初速度，以慢动作或实时观察碰撞过程。特殊情况高亮显示：等质量交换速度、轻质量撞击重质量反弹。教育价值在于理解为什么守恒定律相互独立却必须同时满足。

### 12. [Elastic Collision 2D / 二维弹性碰撞](https://blackmatrixblack.github.io/zero-physics/elastic-collision-2d/)
- **EN:** This simulation extends elastic collision analysis to two dimensions, where the vector nature of momentum becomes essential. The conservation laws are expressed as m₁v⃗₁i + m₂v⃗₂i = m₁v⃗₁f + m₂v⃗₂f and ½m₁v₁i² + ½m₂v₂i² = ½m₁v₁f² + ½m₂v₂f², now requiring vector decomposition. The simulation solves the collision by rotating to the frame where the impact direction defines the normal axis, applying the 1D elastic formulas in that direction while preserving tangential velocity components. Users can drag balls to set initial positions and velocities, aim the collision angle, and watch the realistic post-collision trajectories. Educational value includes understanding that in 2D elastic collisions, the angle between outgoing velocities depends on mass ratio and impact parameter.
- **CN:** 该模拟将弹性碰撞分析扩展至二维空间，动量的矢量性质在此变得至关重要。守恒定律表达为 m₁v⃗₁i + m₂v⃗₂i = m₁v⃗₁f + m₂v⃗₂f 和 ½m₁v₁i² + ½m₂v₂i² = ½m₁v₁f² + ½m₂v₂f²，现需进行矢量分解。模拟通过旋转至碰撞方向定义法轴的参考系来求解，在该方向应用一维弹性碰撞公式，同时保持切向速度分量不变。用户可拖拽球体设置初始位置和速度，瞄准碰撞角度，观察逼真的碰撞后轨迹。教育价值在于理解二维弹性碰撞中，出射速度间的夹角取决于质量比和碰撞参数。

### 13. [Friction Simulation / 摩擦力模拟](https://blackmatrixblack.github.io/zero-physics/friction-simulation/)
- **EN:** This simulation models both static and kinetic friction forces between surfaces. Static friction obeys f_s ≤ μ_sN where it matches applied force up to a maximum, while kinetic friction follows f_k = μ_kN with μ_k < μ_s typically. Users can push an object on a surface by applying variable horizontal force, observing the transition from static to kinetic friction at the threshold F = μ_smg. The simulation displays force diagrams with all four forces (weight, normal, applied, friction) as vectors. Educational value includes understanding why it is harder to start moving an object than to keep it moving, the distinction between static and kinetic coefficients, and how normal force N = mg depends on mass and gravity.
- **CN:** 该模拟模拟表面之间的静摩擦力和动摩擦力。静摩擦力满足 f_s ≤ μ_sN（等于施加力直至达到最大值），动摩擦力遵循 f_k = μ_kN（通常 μ_k < μ_s）。用户对物体施加可变的水平推力，观察在阈值 F = μ_smg 处从静摩擦到动摩擦的转变。模拟以比例长度矢量显示所有四个力（重力、支持力、施加力、摩擦力）。教育价值在于理解为什么使物体开始运动比维持运动更难、静摩擦和动摩擦系数的区别，以及法向力 N = mg 如何取决于质量和重力。

### 14. [Gyroscope / 陀螺仪](https://blackmatrixblack.github.io/zero-physics/gyroscope/)
- **EN:** This simulation visualizes the fascinating precession and nutation of a spinning gyroscope under gravity. The core physics involves the torque τ = r × mg applied to a rotating object with angular momentum L = Iω, causing precession at angular velocity Ω_p = mgr/L = mgr/(Iω). Users can adjust the spin rate, mass, and distance from pivot to see how precession frequency responds. The simulation renders a 3D gyroscope with torque, angular momentum, and precession velocity vectors clearly displayed. A distinguishing feature is the nutation (wobbling) visualization that occurs when the gyroscope is released at an angle. Educational value includes understanding the vector cross product relationship τ = dL/dt and the principle of gyroscopic stability.
- **CN:** 该模拟可视化旋转陀螺在重力作用下的进动和章动现象。核心物理涉及力矩 τ = r × mg 作用于具有角动量 L = Iω 的旋转物体，导致进动角速度为 Ω_p = mgr/L = mgr/(Iω)。用户可以调节自旋速率、质量和支点距离，观察进动频率如何变化。模拟以 3D 方式渲染陀螺，清晰显示力矩、角动量和进动速度矢量。突出特点是以角度释放时出现的章动（摇摆）可视化。教育价值在于理解矢量叉积关系 τ = dL/dt 和陀螺稳定性原理。

### 15. [Harmonic Oscillator / 谐振子](https://blackmatrixblack.github.io/zero-physics/harmonic-oscillator/)
- **EN:** This simulation explores the simple harmonic oscillator, governed by Hooke's law F = −kx and the differential equation d²x/dt² + ω₀²x = 0 where ω₀ = √(k/m). Users can adjust mass, spring constant, initial displacement, and damping coefficient b to observe the transition from underdamped (b < 2√(mk)) through critically damped (b = 2√(mk)) to overdamped (b > 2√(mk)) regimes. The simulation displays position, velocity, and acceleration graphs alongside the moving mass, with energy bar charts showing KE = ½mv², PE = ½kx². Educational value includes understanding resonance, phase space plots (x vs. v), and the Q factor Q = ω₀m/b.
- **CN:** 该模拟探索简谐振子，遵循胡克定律 F = −kx 和微分方程 d²x/dt² + ω₀²x = 0，其中 ω₀ = √(k/m)。用户可以调节质量、弹簧常数、初始位移和阻尼系数 b，观察从欠阻尼 (b < 2√(mk)) 到临界阻尼 (b = 2√(mk)) 再到过阻尼 (b > 2√(mk)) 的转变。模拟显示位置、速度和加速度图以及移动质量，能量条形图展示 KE = ½mv²、PE = ½kx²。教育价值在于理解共振、相空间图（x 对 v）和品质因数 Q = ω₀m/b。

### 16. [Inclined Plane / 斜面](https://blackmatrixblack.github.io/zero-physics/inclined-plane/)
- **EN:** This simulation analyzes the motion of an object sliding down an inclined plane under gravity. The component of gravity along the incline is mg sinθ, while the normal component is mg cosθ. The acceleration down a frictionless incline is a = g sinθ, and with kinetic friction it becomes a = g(sinθ − μ_k cosθ). Users can adjust the incline angle θ, mass, and coefficient of friction to observe how these parameters affect acceleration. The simulation displays the decomposition of gravitational force into parallel and perpendicular components. A key feature is the critical angle demonstration: the object begins sliding when tanθ > μ_s.
- **CN:** 该模拟分析物体在重力作用下沿斜面下滑的运动。重力沿斜面分量为 mg sinθ，法向分量为 mg cosθ。无摩擦斜面加速度为 a = g sinθ，有动摩擦时为 a = g(sinθ − μ_k cosθ)。用户可以调节斜面角度 θ、质量和摩擦系数，观察这些参数如何影响加速度。模拟展示重力分解为平行和垂直分量。关键功能是临界角演示：当 tanθ > μ_s 时物体开始滑动。

### 17. [Ladder Sliding / 梯子滑动](https://blackmatrixblack.github.io/zero-physics/ladder-sliding/)
- **EN:** This simulation models a ladder leaning against a wall, analyzing the static equilibrium conditions and the point at which it begins to slide. The physics involves balancing forces: horizontal wall normal force N_w equals floor friction f_f, while vertical floor normal force N_f equals ladder weight mg plus any added load. Torque equilibrium about any point gives N_w·Lsinθ = mg·(L/2)cosθ for a uniform ladder. The critical condition for slipping is μ_sN_f > N_w, meaning the ladder slips when tanθ < 1/(2μ_s). Users can adjust the ladder angle, coefficient of friction, ladder length, and add a person climbing.
- **CN:** 该模拟模拟靠墙放置的梯子，分析静力平衡条件和开始滑动的临界点。物理涉及力的平衡：水平方向墙壁法向力 N_w 等于地面摩擦力 f_f，垂直方向地面法向力 N_f 等于梯子重量 mg 加额外负载。绕任一点的力矩平衡给出均匀梯子的 N_w·Lsinθ = mg·(L/2)cosθ。滑动的临界条件是 μ_sN_f > N_w，即对于无额外负载的均匀梯子，当 tanθ < 1/(2μ_s) 时滑动发生。

### 18. [Mass Spring Array / 质量弹簧阵列](https://blackmatrixblack.github.io/zero-physics/mass-spring-array/)
- **EN:** This simulation extends the simple harmonic oscillator to a coupled system of masses connected by springs in an array. Each mass obeys m·d²xᵢ/dt² = −k(2xᵢ − xᵢ₋₁ − xᵢ₊₁), leading to normal mode solutions where all masses oscillate at a common frequency. Users can excite individual masses, adjust the number of masses, spring constants, and mass values. A frequency spectrum analysis reveals the normal mode frequencies ωₙ = 2√(k/m)·sin(nπ/(2(N+1))) for N masses. Educational value includes understanding how discrete systems approximate continuous wave media, the concept of dispersion relations, and how coupling leads to collective behavior.
- **CN:** 该模拟将简谐振子扩展到弹簧连接的质量阵列耦合系统。每个质量遵循 m·d²xᵢ/dt² = −k(2xᵢ − xᵢ₋₁ − xᵢ₊₁)，产生所有质量以共同频率振荡的简正模解。用户可以激发单个质量，调节质量数量、弹簧常数和质量值。频谱分析揭示简正模频率 ωₙ = 2√(k/m)·sin(nπ/(2(N+1)))（N 个质量）。教育价值在于理解离散系统如何近似连续波动介质、色散关系的概念，以及耦合如何导致集体行为。

### 19. [Pendulum Wave / 摆波](https://blackmatrixblack.github.io/zero-physics/pendulum-wave/)
- **EN:** This visually stunning simulation displays an array of pendulums with carefully tuned lengths to create wave-like patterns. Each pendulum has length Lₙ = g/(2πfₙ)² where frequencies fₙ form an arithmetic progression, so they start in phase and progressively dephase, then return to phase alignment at specific times (revival time T_revival = 1/Δf). Users can adjust the number of pendulums, frequency range, and initial conditions. The simulation renders all pendulums simultaneously with color-coded bobs showing phase relative to the first pendulum. Educational value includes understanding the relationship between pendulum length and period (T = 2π√(L/g)), phase coherence/decoherence, and how small frequency differences produce beats.
- **CN:** 这个视觉震撼的模拟展示了精心调谐长度的摆阵列，以产生波浪状图案。每个摆的长度为 Lₙ = g/(2πfₙ)²，其中频率 fₙ 形成等差数列，因此它们从同相开始，逐渐失相，然后在特定时间（恢复时间 T_revival = 1/Δf）重新对齐。用户可以调节摆的数量、频率范围和初始条件。模拟同时渲染所有摆，摆锤颜色编码显示相对于第一个摆的相位。教育价值在于理解摆长与周期之间的关系 (T = 2π√(L/g))、相位相干和退相干的概念。

### 20. [Projectile Motion / 抛体运动](https://blackmatrixblack.github.io/zero-physics/projectile-motion/)
- **EN:** This simulation models the classic projectile motion problem, where an object launched at angle θ with initial velocity v₀ follows a parabolic trajectory under uniform gravity. The horizontal and vertical components are described by x(t) = v₀cosθ·t and y(t) = v₀sinθ·t − ½gt², with range R = v₀²sin(2θ)/g. Users can adjust launch angle, initial speed, launch height, and toggle air resistance (drag force F_d = −½ρC_dAv²). The simulation draws the complete parabolic trajectory with velocity vectors at regular intervals. A key feature is the range-angle plot, demonstrating that complementary angles produce the same range, with maximum at 45°.
- **CN:** 该模拟模拟经典抛体运动问题：以角度 θ、初速度 v₀ 发射的物体在均匀重力下沿抛物线轨迹运动。水平和垂直分量由 x(t) = v₀cosθ·t 和 y(t) = v₀sinθ·t − ½gt² 描述，射程 R = v₀²sin(2θ)/g。用户可以调节发射角度、初速度、发射高度，并可切换空气阻力。模拟绘制完整抛物线轨迹，等间隔显示速度矢量。关键功能是射程-角度图，证明互补角度产生相同射程，最大射程角为 45°。

### 21. [Pulley System / 滑轮系统](https://blackmatrixblack.github.io/zero-physics/pulley-system/)
- **EN:** This simulation models compound pulley systems that provide mechanical advantage, allowing a small input force to lift a heavy load. The mechanical advantage MA = F_load/F_input equals the number of supporting rope segments. For a system with N movable pulleys, the tension relationship is T = mg/2^N. Users can configure pulley systems with different numbers of fixed and movable pulleys, adjust masses, and add pulley mass and friction. The work-energy principle W_input = W_output (ideal) is verified, with efficiency η = AMA/IMA × 100%. Educational value includes understanding how force amplification trades off with displacement and the conservation of energy in simple machines.
- **CN:** 该模拟模拟提供机械优势的复合滑轮系统——较小的输入力可以提起较重的负载。机械优势 MA = F_负载/F_输入 等于支撑绳段的数量。对于有 N 个动滑轮的体系，张力关系为 T = mg/2^N。用户可以配置不同数量的定滑轮和动滑轮，调节质量，添加滑轮质量和摩擦力。功能原理 W_输入 = W_输出（理想情况下）得到验证，效率 η = AMA/IMA × 100%。教育价值在于理解力放大如何与位移权衡以及简单机械中的能量守恒。

### 22. [Rocket Motion / 火箭运动](https://blackmatrixblack.github.io/zero-physics/rocket-motion/)
- **EN:** This simulation models the motion of a rocket under thrust, governed by the Tsiolkovsky rocket equation Δv = v_ex·ln(m₀/m_f), where v_ex is the exhaust velocity, m₀ the initial mass, and m_f the final mass. The thrust force is F_thrust = v_ex·(dm/dt). Users can adjust the exhaust velocity, fuel mass, burn rate, and rocket dry mass. The simulation displays velocity, altitude, and acceleration graphs over time. A key visualization shows the impulse-momentum relationship: the backward momentum of exhaust gases equals the forward momentum gained by the rocket. The simulation demonstrates the multi-stage rocket concept, showing why staging improves efficiency.
- **CN:** 该模拟模拟火箭在推力下的运动，由齐奥尔科夫斯基火箭方程 Δv = v_ex·ln(m₀/m_f) 支配，其中 v_ex 为排气速度，m₀ 为初始质量，m_f 为最终质量。推力 F_thrust = v_ex·(dm/dt)。用户可以调节排气速度、燃料质量、燃烧速率和火箭干质量。模拟随时间显示速度、高度和加速度图。关键可视化展示了冲量-动量关系：排气的向后动量等于火箭获得的向前动量。模拟演示了多级火箭概念，展示分级为何提高效率。

### 23. [Roller Coaster / 过山车](https://blackmatrixblack.github.io/zero-physics/roller-coaster/)
- **EN:** This simulation models a roller coaster car moving along a track, demonstrating conservation of mechanical energy in the presence of gravitational potential and kinetic energy. The total energy E = KE + PE = ½mv² + mgh remains constant (ideal) as the car traverses hills and loops. The minimum speed required to complete a vertical loop is v_min = √(gR) at the top. Users can design custom track shapes by placing control points, adjust initial height, car mass, and add friction. The simulation displays energy bar charts showing the continuous trade-off between KE and PE. Real-time G-force readings show the apparent weight experienced by riders.
- **CN:** 该模拟模拟过山车沿轨道运动，演示重力势能和动能之间的机械能守恒。总能量 E = KE + PE = ½mv² + mgh 在过山车经过山坡和回环时保持恒定（理想情况下）。完成垂直回环所需的最小速度为 v_min = √(gR)（顶部）。用户可通过放置控制点设计自定义轨道形状，调节初始高度、车质量和摩擦力。模拟显示能量条形图，展示 KE 和 PE 之间的持续转换。实时 G 力读数显示骑手承受的表现重量。

### 24. [Simple Pendulum / 单摆](https://blackmatrixblack.github.io/zero-physics/simple-pendulum/)
- **EN:** This simulation models a simple pendulum consisting of a mass suspended from a fixed point by a massless string. For small angles, the motion is simple harmonic with period T = 2π√(L/g), independent of mass. The governing differential equation d²θ/dt² + (g/L)sinθ = 0 is solved numerically, showing how the small-angle approximation sinθ ≈ θ breaks down at large amplitudes. Users can adjust pendulum length, mass, initial angle, and gravity. Energy bar charts show the conversion between gravitational potential energy PE = mgL(1−cosθ) and kinetic energy KE = ½mL²ω².
- **CN:** 该模拟模拟由无质量细绳悬挂于固定点的单摆。小角度下运动为简谐运动，周期 T = 2π√(L/g)，与质量无关。控制微分方程 d²θ/dt² + (g/L)sinθ = 0 通过数值求解，展示小角度近似 sinθ ≈ θ 在大振幅下失效。用户可以调节摆长、质量、初始角度和重力加速度。能量条形图展示重力势能 PE = mgL(1−cosθ) 与动能 KE = ½mL²ω² 之间的转换。

### 25. [Spring Pendulum / 弹簧摆](https://blackmatrixblack.github.io/zero-physics/spring-pendulum/)
- **EN:** This simulation combines a simple pendulum with a spring, creating a system with two coupled degrees of freedom: the angular displacement θ and the radial extension r of the spring. The Lagrangian for this system is L = ½m(ṙ² + (L₀+r)²θ̇²) − ½kr² + mg(L₀+r)cosθ, leading to coupled equations of motion. The system exhibits rich dynamics including energy transfer between the swinging and springing modes, producing beating patterns. Users can adjust spring constant k, natural length L₀, mass, damping, and initial conditions. Educational value includes understanding coupled oscillations, normal modes, and parametric resonance.
- **CN:** 该模拟将单摆与弹簧结合，创建具有两个耦合自由度的系统：角度位移 θ 和弹簧的径向伸长 r。该系统的拉格朗日量为 L = ½m(ṙ² + (L₀+r)²θ̇²) − ½kr² + mg(L₀+r)cosθ，导出耦合运动方程。系统展现丰富动力学，包括摆动和伸缩模式之间的能量传递，产生拍频图案。用户可以调节弹簧常数 k、原长 L₀、质量、阻尼和初始条件。教育价值在于理解耦合振荡、简正模和参数共振。

---

# 2. Electromagnetism / 电磁学

### 26. [Biot-Savart Law / 毕奥-萨伐尔定律](https://blackmatrixblack.github.io/zero-physics/biot-savart/)
- **EN:** This simulation visualizes the Biot-Savart law, which describes the magnetic field generated by a steady electric current. The law states dB⃗ = (μ₀/4π)·(Idℓ⃗ × r̂)/r² for a current element Idℓ⃗, with the total field obtained by integration B⃗ = ∫ dB⃗. Users can choose between different current configurations: straight wire, circular loop, and solenoid, observing the resulting magnetic field lines in 3D. For a straight wire, B = μ₀I/(2πr) is confirmed. Users can adjust current, wire geometry, and add multiple current elements. The simulation includes a field strength color map. Educational value includes understanding the vector cross-product nature of magnetic fields and how superposition applies.
- **CN:** 该模拟可视化描述稳恒电流产生磁场的毕奥-萨伐尔定律。定律表述为 dB⃗ = (μ₀/4π)·(Idℓ⃗ × r̂)/r²（电流元 Idℓ⃗），总磁场通过积分 B⃗ = ∫ dB⃗ 获得。用户可在不同电流配置间选择：直导线、圆形线圈和螺线管，以 3D 方式观察产生的磁感线。直导线情况验证 B = μ₀I/(2πr)。模拟包含场强彩色图。教育价值在于理解磁场的矢量叉积性质以及叠加原理的应用。

### 27. [Charged Particle in B-Field / 带电粒子在磁场中运动](https://blackmatrixblack.github.io/zero-physics/charged-particle-b-field/)
- **EN:** This simulation tracks a charged particle moving through a uniform magnetic field, experiencing the Lorentz force F⃗ = q(v⃗ × B⃗). The magnetic force causes circular motion with radius r = mv/(qB) (cyclotron radius) and angular frequency ω_c = qB/m (cyclotron frequency). Users can adjust the charge, mass, initial velocity, and magnetic field strength and direction. The simulation renders the particle's trajectory in 3D, showing helical paths when velocity has both parallel and perpendicular components. Users can add an electric field to see the E⃗ × B⃗ drift (v_drift = E⃗ × B⃗/B²). Educational value includes understanding why magnetic fields do no work.
- **CN:** 该模拟追踪带电粒子在均匀磁场中的运动，受洛伦兹力 F⃗ = q(v⃗ × B⃗) 作用。磁力导致圆周运动，半径 r = mv/(qB)（回旋半径），角频率 ω_c = qB/m（回旋频率）。用户可以调节电荷、质量、初速度以及磁场强度和方向。模拟以 3D 方式渲染粒子轨迹，当速度有平行和垂直分量时显示螺旋路径。用户可添加电场观察 E⃗ × B⃗ 漂移。教育价值在于理解磁场不做功的原因。

### 28. [Coulomb's Law / 库仑定律](https://blackmatrixblack.github.io/zero-physics/coulombs-law/)
- **EN:** This simulation visualizes Coulomb's law describing the electrostatic force between charged particles: F = k·|q₁q₂|/r², where k = 1/(4πε₀) = 8.99×10⁹ N·m²/C². Like charges repel, opposite charges attract, and the force follows an inverse-square relationship with distance. Users can place multiple point charges on a 2D plane, adjust their charge values (positive or negative), and observe the resulting force vectors on each charge. A force probe tool allows measuring the electric field at any point: E⃗ = F⃗/q₀. Educational value includes understanding the inverse-square law's geometric origin and the principle of superposition.
- **CN:** 该模拟可视化描述带电粒子间静电力的库仑定律：F = k·|q₁q₂|/r²，其中 k = 1/(4πε₀) = 8.99×10⁹ N·m²/C²。同号电荷相斥，异号电荷相吸，力与距离的平方成反比。用户可在二维平面上放置多个点电荷，调节电荷值，观察每个电荷所受的力矢量。力探针工具可测量任意点的电场：E⃗ = F⃗/q₀。教育价值在于理解平方反比律的几何起源和叠加原理。

### 29. [Dipole Antenna / 偶极天线](https://blackmatrixblack.github.io/zero-physics/dipole-antenna/)
- **EN:** This simulation models the electromagnetic radiation from a half-wave dipole antenna, demonstrating the generation and propagation of radio waves. The current distribution I(z,t) = I₀cos(ωt)cos(πz/L) for a half-wave dipole produces the radiated electric field pattern. Users can adjust the driving frequency, antenna length, and input power. The simulation visualizes the electric field lines detaching from the antenna and propagating outward at the speed of light. A polar radiation pattern diagram shows the directional dependence of radiated power. Educational value includes understanding how accelerating charges produce electromagnetic waves and the relationship between antenna length and wavelength.
- **CN:** 该模拟模拟半波偶极天线的电磁辐射，演示无线电波的产生和传播。半波偶极子的电流分布为 I(z,t) = I₀cos(ωt)cos(πz/L)。用户可以调节驱动频率、天线长度和输入功率。模拟可视化电场线从天线上脱离并以光速向外传播。极坐标辐射图显示辐射功率的方向依赖性。教育价值在于理解加速电荷如何产生电磁波以及天线长度与波长的关系。

### 30. [Electric Field 2D / 二维电场](https://blackmatrixblack.github.io/zero-physics/electric-field-2d/)
- **EN:** This simulation provides an interactive 2D visualization of electric fields generated by arbitrary charge configurations. The electric field at any point is E⃗ = kΣ(qᵢ/rᵢ²)·r̂ᵢ (superposition principle), and the electric potential is V = kΣ(qᵢ/rᵢ). Users can place positive and negative charges freely on the canvas, adjust their magnitudes, and watch the field vectors update in real-time. The simulation offers multiple visualization modes: field vectors, field lines, equipotential contours, and a color map of field strength. Educational value includes understanding Gauss's law ∮E⃗·dA⃗ = Q_enc/ε₀ intuitively through field line counting.
- **CN:** 该模拟提供任意电荷配置产生的电场的交互式二维可视化。任意点的电场为 E⃗ = kΣ(qᵢ/rᵢ²)·r̂ᵢ（叠加原理），电势为 V = kΣ(qᵢ/rᵢ)。用户可在画布上自由放置正负电荷，调节电荷量，实时观察场矢量更新。模拟提供多种可视化模式：场矢量、电场线、等势线和场强彩色图。教育价值在于通过场线计数直观理解高斯定律 ∮E⃗·dA⃗ = Q_enc/ε₀。

### 31. [Electric Field Lines / 电场线](https://blackmatrixblack.github.io/zero-physics/electric-field-lines/)
- **EN:** This simulation focuses specifically on the visualization of electric field lines generated by various charge distributions. Field lines satisfy dℓ⃗/ds = E⃗/|E⃗|, and the simulation traces these curves using numerical integration. Users can select from preset configurations (single charge, dipole, quadrupole, parallel plate capacitor) or create custom arrangements. Equipotential lines are superimposed, demonstrating their perpendicular relationship to field lines (E⃗ = −∇V, so E⃗ ⟂ equipotential surfaces). Educational value includes understanding the relationship between field lines and potential gradients.
- **CN:** 该模拟专注于各种电荷分布产生的电场线的可视化。电场线满足 dℓ⃗/ds = E⃗/|E⃗|，模拟通过对场方向进行数值积分来追踪这些曲线。用户可从预设配置中选择（单电荷、电偶极子、四极子、平行板电容器）或创建自定义布置。等势线以对比色叠加，展示与电场线垂直的关系（E⃗ = −∇V）。教育价值在于理解电场线与电势梯度之间的关系。

### 32. [Electric Motor / 电动机](https://blackmatrixblack.github.io/zero-physics/electric-motor/)
- **EN:** This simulation demonstrates the operating principles of a simple DC electric motor. The motor consists of a current-carrying coil in a magnetic field, experiencing torque τ = NIABsinθ where N is the number of turns, I the current, A the coil area, B the magnetic field, and θ the angle between the field and coil normal. Users can adjust magnetic field strength, current, number of coil turns, and add a load torque. The simulation shows the coil rotating with force vectors on each side of the loop (F = IL × B) and the back EMF generated. Educational value includes understanding the Lorentz force on current-carrying wires and Faraday's law.
- **CN:** 该模拟演示简单直流电动机的工作原理。电动机由磁场中的载流线圈组成，受力矩 τ = NIABsinθ 作用，其中 N 为匝数，I 为电流，A 为线圈面积，B 为磁场，θ 为场与线圈法线夹角。用户可以调节磁场强度、电流、线圈匝数，并添加负载力矩。模拟显示线圈旋转时每侧导体的力矢量（F = IL × B）以及产生的反电动势。教育价值在于理解载流导线上的洛伦兹力和法拉第定律。

### 33. [Electric Potential / 电势](https://blackmatrixblack.github.io/zero-physics/electric-potential/)
- **EN:** This simulation visualizes the electric potential V(r) = kQ/r (or superposition Σkqᵢ/rᵢ) and its relationship to the electric field E⃗ = −∇V. Users place charges on a 2D grid and see the potential landscape rendered as a 3D surface, where height represents potential value. The electric field vectors are shown as perpendicular to the equipotential contours. The simulation computes the potential energy U = qV for a test charge. Educational value includes understanding that potential is a scalar quantity, the arbitrary zero-point of potential, and the concept of voltage as potential difference.
- **CN:** 该模拟可视化电势 V(r) = kQ/r（或叠加 Σkqᵢ/rᵢ）及其与电场 E⃗ = −∇V 的关系。用户在二维网格上放置电荷，电势景观渲染为三维曲面，高度代表电势值。电场矢量显示为垂直于等势线轮廓。模拟计算检验电荷的电势能 U = qV。教育价值在于理解电势是标量、电势零点的任意性，以及电压作为电势差的概念。

### 34. [Faraday's Law / 法拉第定律](https://blackmatrixblack.github.io/zero-physics/faraday-law/)
- **EN:** This simulation demonstrates Faraday's law of electromagnetic induction: ε = −dΦ_B/dt, where the induced EMF equals the negative rate of change of magnetic flux. The negative sign embodies Lenz's law. Users can move a magnet toward or away from a coil, adjust the number of coil turns, magnet strength, and speed of motion. The simulation displays the magnetic flux Φ_B = B·A = BAcosθ through the coil, the induced EMF, and the resulting induced current I = ε/R. Users can also explore the case of a rotating coil in a uniform field (generator principle) where ε = NBAωsinωt.
- **CN:** 该模拟演示法拉第电磁感应定律：ε = −dΦ_B/dt——闭合回路中的感应电动势等于通过回路的磁通量变化率的负值。负号体现楞次定律。用户可将磁铁移近或远离线圈，调节线圈匝数、磁铁强度和运动速度。模拟显示通过线圈的磁通量 Φ_B = B·A = BAcosθ、感应电动势和感应电流 I = ε/R。用户还可探索均匀场中旋转线圈的情况（发电机原理），ε = NBAωsinωt。

### 35. [Hall Effect / 霍尔效应](https://blackmatrixblack.github.io/zero-physics/hall-effect/)
- **EN:** This simulation demonstrates the Hall effect, where a current-carrying conductor in a perpendicular magnetic field develops a transverse voltage. The Lorentz force F = q(v × B) pushes charge carriers to one side, creating an electric field E_H that balances the magnetic force: qE_H = qvB, giving Hall voltage V_H = IB/(nq·d). Users can adjust current, magnetic field, material properties, and sample dimensions. The sign of V_H indicates whether charge carriers are positive (holes) or negative (electrons). Educational value includes understanding the experimental determination of carrier type, density, and mobility.
- **CN:** 该模拟演示霍尔效应——垂直于磁场的载流导体产生横向电压。洛伦兹力 F = q(v × B) 将载流子推向一侧，产生电场 E_H 平衡磁力：qE_H = qvB，得到霍尔电压 V_H = IB/(nq·d)。用户可以调节电流、磁场、材料属性和样品尺寸。V_H 的符号指示载流子是正（空穴）还是负（电子）。教育价值在于理解通过实验确定载流子类型、密度和迁移率。

### 36. [Kirchhoff's Law / 基尔霍夫定律](https://blackmatrixblack.github.io/zero-physics/kirchhoff-law/)
- **EN:** This simulation teaches circuit analysis using Kirchhoff's Current Law (KCL) and Kirchhoff's Voltage Law (KVL). KCL states ΣI_in = ΣI_out at any node (conservation of charge), while KVL states ΣV = 0 around any closed loop (conservation of energy). Users can build circuits with resistors, voltage sources, and current sources on a breadboard-like interface. The simulation automatically computes node voltages and branch currents. Educational value includes understanding the fundamental conservation laws underlying circuit theory and the systematic approach to solving complex circuits.
- **CN:** 该模拟利用基尔霍夫电流定律 (KCL) 和基尔霍夫电压定律 (KVL) 教授电路分析。KCL 指出任意节点的 ΣI_入 = ΣI_出（电荷守恒），KVL 指出任意闭合回路的 ΣV = 0（能量守恒）。用户可以在类似面包板的界面上搭建包含电阻、电压源和电流源的电路。模拟自动计算节点电压和支路电流。教育价值在于理解电路理论背后的基本守恒定律和解决复杂电路的系统方法。

### 37. [Lorentz Force / 洛伦兹力](https://blackmatrixblack.github.io/zero-physics/lorentz-force/)
- **EN:** This simulation visualizes the complete Lorentz force F⃗ = q(E⃗ + v⃗ × B⃗) acting on a charged particle in combined electric and magnetic fields. Users can independently control E⃗ and B⃗ fields, particle charge, mass, and initial velocity. The simulation renders the 3D trajectory with color coding for speed. A velocity selector configuration is demonstrated: particles with v = E/B pass undeflected. The simulation also demonstrates the principle of the mass spectrometer. Educational value includes understanding the complete electromagnetic force law and practical applications in particle accelerators.
- **CN:** 该模拟可视化带电粒子在复合电磁场中的完整洛伦兹力 F⃗ = q(E⃗ + v⃗ × B⃗)。用户可独立控制 E⃗ 和 B⃗ 场、粒子电荷、质量和初速度。模拟以 3D 方式渲染轨迹，颜色编码表示速度。演示速度选择器配置：v = E/B 的粒子无偏转通过。模拟还演示质谱仪原理。教育价值在于理解完整的电磁力定律以及在粒子加速器中的实际应用。

### 38. [Magnetic Dipole / 磁偶极子](https://blackmatrixblack.github.io/zero-physics/magnetic-dipole/)
- **EN:** This simulation visualizes the magnetic field of a magnetic dipole, such as a bar magnet or current loop. The far-field magnetic dipole field is B⃗(r) = (μ₀/4π)[(3(m⃗·r̂)r̂ − m⃗)/r³]. Users can rotate the dipole, adjust its strength, and place compass needles around it to measure field direction. The torque on a second dipole placed in the field is shown, governed by τ = m⃗ × B⃗. Users can also observe the potential energy U = −m⃗·B⃗. Educational value includes understanding the similarities and differences between electric and magnetic dipoles.
- **CN:** 该模拟可视化磁偶极子的磁场，如条形磁铁或电流回路。远场磁偶极子场为 B⃗(r) = (μ₀/4π)[(3(m⃗·r̂)r̂ − m⃗)/r³]。用户可以旋转偶极子、调节其强度，并在周围放置指南针测量场方向。展示置于场中第二个偶极子所受的力矩 τ = m⃗ × B⃗。用户可观察势能 U = −m⃗·B⃗。教育价值在于理解电偶极子和磁偶极子的异同。

### 39. [Ohm's Law / 欧姆定律](https://blackmatrixblack.github.io/zero-physics/ohms-law/)
- **EN:** This simulation demonstrates Ohm's law V = IR, the fundamental relationship between voltage, current, and resistance in electrical circuits. Users can build simple circuits with a voltage source and resistor, adjusting both V and R while observing the resulting current I = V/R measured by an ammeter. Multiple resistors can be combined in series (R_eq = R₁ + R₂ + ...) and parallel (1/R_eq = 1/R₁ + 1/R₂ + ...). Power dissipation P = IV = I²R = V²/R is displayed as heat energy. Educational value includes understanding the linear regime of conduction and the design of voltage dividers.
- **CN:** 该模拟演示欧姆定律 V = IR——电压、电流和电阻之间的基本关系。用户可以搭建含电压源和电阻的简单电路，调节 V 和 R 的同时观察电流表测量的 I = V/R。多个电阻可以串联（R_eq = R₁ + R₂ + ...）和并联（1/R_eq = 1/R₁ + 1/R₂ + ...）。功率耗散 P = IV = I²R = V²/R 显示为热能。教育价值在于理解导通的线性区域和分压器的设计。

### 40. [Parallel Plate Capacitor / 平行板电容器](https://blackmatrixblack.github.io/zero-physics/parallel-plate-capacitor/)
- **EN:** This simulation models a parallel plate capacitor, storing electrical energy in an electric field between two conducting plates. The capacitance is C = ε₀ε_r·A/d, where A is plate area, d the separation, and ε_r the relative permittivity. The stored energy is U = ½CV² = ½QV = Q²/(2C). Users can adjust plate area, separation, applied voltage, and dielectric material. The simulation visualizes the uniform electric field E = V/d between the plates. Educational value includes understanding the relationship between geometry and capacitance and the role of dielectrics.
- **CN:** 该模拟模拟在两块导电板之间的电场中存储电能的平行板电容器。电容为 C = ε₀ε_r·A/d，其中 A 为板面积，d 为间距，ε_r 为介质的相对介电常数。存储能量为 U = ½CV² = ½QV = Q²/(2C)。用户可以调节板面积、间距、外加电压和介电材料。模拟可视化板间的均匀电场 E = V/d。教育价值在于理解几何形状与电容的关系以及电介质的作用。

### 41. [Polarization / 偏振](https://blackmatrixblack.github.io/zero-physics/polarization/)
- **EN:** This simulation visualizes the polarization of electromagnetic waves. Unpolarized light contains electric field oscillations in all directions perpendicular to propagation. After passing through a linear polarizer at angle θ, the transmitted intensity follows Malus's law: I = I₀cos²θ. Users can rotate polarizing filters, add multiple filters, and introduce wave plates to manipulate polarization state. The simulation displays linear, circular, and elliptical polarization states. A Poincaré sphere visualization maps polarization states. Educational value includes understanding the transverse nature of light and the mathematics of polarization.
- **CN:** 该模拟可视化电磁波的偏振。非偏振光包含垂直于传播方向所有方向的电场振荡。通过角度 θ 的线偏振片后，透射强度遵循马吕斯定律：I = I₀cos²θ。用户可以旋转偏振滤光片，添加多个滤光片，引入波片来操控偏振态。模拟显示线偏振、圆偏振和椭圆偏振态。庞加莱球可视化映射偏振态。教育价值在于理解光的横波性质和偏振的数学描述。

### 42. [Transformer / 变压器](https://blackmatrixblack.github.io/zero-physics/transformer/)
- **EN:** This simulation models an ideal and non-ideal transformer, demonstrating electromagnetic induction for voltage conversion. The ideal transformer relationship is V_s/V_p = N_s/N_p = I_p/I_s. Users can adjust the number of turns on primary and secondary coils, input voltage, and add a load resistor. Efficiency η = P_out/P_in is computed, with losses identified: copper losses (I²R), hysteresis losses, and eddy current losses. Educational value includes understanding how transformers enable efficient power distribution and why they only work with AC.
- **CN:** 该模拟模拟理想和非理想变压器，演示利用电磁感应进行电压转换。理想变压器关系为 V_s/V_p = N_s/N_p = I_p/I_s。用户可以调节初级和次级线圈的匝数、输入电压，并添加负载电阻。计算效率 η = P_out/P_in，识别损耗：铜损（I²R）、磁滞损耗和涡流损耗。教育价值在于理解变压器如何实现高效电力分配以及为什么只能在交流电下工作。

### 43. [Wheatstone Bridge / 惠斯通电桥](https://blackmatrixblack.github.io/zero-physics/wheatstone-bridge/)
- **EN:** This simulation models the Wheatstone bridge, a precision circuit for measuring unknown resistance. The bridge is balanced when R₁/R₂ = R₃/R₄ (or R_x = R₃·R₂/R₁ for unknown R_x), at which point no current flows through the galvanometer (V_G = 0). Users can adjust all four resistor values and observe the galvanometer deflection. The simulation computes the Thevenin equivalent circuit between the bridge midpoints. Educational value includes understanding the power of null measurement techniques for high accuracy and the concept of ratiometric measurement.
- **CN:** 该模拟模拟惠斯通电桥——用于精确测量未知电阻的精密电路。电桥平衡条件为 R₁/R₂ = R₃/R₄（或未知电阻 R_x = R₃·R₂/R₁），此时检流计无电流通过（V_G = 0）。用户可以调节所有四个电阻值，观察检流计偏转。模拟计算电桥中点之间的戴维南等效电路。教育价值在于理解零值测量技术实现高精度的优势和比例测量的概念。

---

# 3. Thermodynamics / 热力学

### 44. [Blackbody Radiation / 黑体辐射](https://blackmatrixblack.github.io/zero-physics/blackbody-radiation/)
- **EN:** This simulation visualizes the blackbody radiation spectrum, the electromagnetic radiation emitted by an idealized opaque object at thermal equilibrium. The spectral radiance follows Planck's law: B(λ,T) = (2hc²/λ⁵)·1/(e^(hc/λkT)−1). Users can adjust temperature from near absolute zero to thousands of Kelvin. Wien's displacement law λ_maxT = 2.898×10⁻³ m·K and the Stefan-Boltzmann law P = σAT⁴ are demonstrated. The simulation overlays the Rayleigh-Jeans law for comparison, showing the ultraviolet catastrophe. Educational value includes understanding why the ultraviolet catastrophe necessitated Planck's quantum hypothesis E = hf.
- **CN:** 该模拟可视化黑体辐射光谱——理想化不透明热平衡物体发射的电磁辐射。光谱辐亮度遵循普朗克定律：B(λ,T) = (2hc²/λ⁵)·1/(e^(hc/λkT)−1)。用户可以调节从接近绝对零度到数千开尔文的温度。维恩位移定律 λ_maxT = 2.898×10⁻³ m·K 和斯特藩-玻尔兹曼定律 P = σAT⁴ 被演示。模拟叠加瑞利-金斯定律作为对比，展示紫外灾难。教育价值在于理解紫外灾难为何需要普朗克量子假说 E = hf。

### 45. [Carnot Cycle / 卡诺循环](https://blackmatrixblack.github.io/zero-physics/carnot-cycle/)
- **EN:** This simulation demonstrates the Carnot cycle, the most efficient thermodynamic cycle possible between two heat reservoirs. The cycle consists of four reversible processes: isothermal expansion (T_H), adiabatic expansion, isothermal compression (T_C), and adiabatic compression. The efficiency is η_Carnot = 1 − T_C/T_H. Users can adjust the hot and cold reservoir temperatures and observe the PV diagram rendered in real-time. The entropy change ΔS = Q/T is shown for each process, with ΔS_total = 0 for the reversible cycle. Educational value includes understanding the fundamental limit on heat engine efficiency.
- **CN:** 该模拟演示卡诺循环——两个热源之间可能达到的最有效率的热力学循环。循环由四个可逆过程组成：等温膨胀 (T_H)、绝热膨胀、等温压缩 (T_C) 和绝热压缩。效率为 η_Carnot = 1 − T_C/T_H。用户可以调节高温和低温热源温度，观察 PV 图实时渲染。每个过程的熵变 ΔS = Q/T 被展示，可逆循环总熵变 ΔS_total = 0。教育价值在于理解热机效率的基本极限。

### 46. [Convection / 对流](https://blackmatrixblack.github.io/zero-physics/convection/)
- **EN:** This simulation visualizes thermal convection, the transfer of heat by bulk fluid movement due to density differences from temperature gradients. The governing equations are the Navier-Stokes equations coupled with the heat equation using the Boussinesq approximation. Users can heat a fluid from below, adjusting the temperature gradient, fluid viscosity, and thermal expansion coefficient. The simulation renders streamlines and temperature color maps, showing Rayleigh-Bénard convection cells when the Rayleigh number Ra = gβΔTL³/(να) exceeds ≈ 1708. Educational value includes understanding the Nusselt number Nu and the role of buoyancy in atmospheric circulation.
- **CN:** 该模拟可视化热对流——由于温度梯度导致密度差异而引起的流体宏观运动所传递的热量。控制方程为纳维-斯托克斯方程与热方程的耦合（布西内斯克近似）。用户可以从下方加热流体，调节温度梯度、流体黏度和热膨胀系数。模拟渲染流线和温度彩图，展示当瑞利数 Ra = gβΔTL³/(να) 超过 ≈ 1708 时形成的瑞利-贝纳德对流胞。教育价值在于理解努塞尔数 Nu 和浮力在大气环流中的作用。

### 47. [Entropy / 熵](https://blackmatrixblack.github.io/zero-physics/entropy/)
- **EN:** This simulation provides an intuitive visualization of entropy as a measure of disorder. The thermodynamic definition is dS = dQ_rev/T (Clausius), while the statistical definition is S = k·lnΩ (Boltzmann). Users can observe a system of particles evolving from ordered to disordered states, with the entropy calculation shown numerically. The simulation demonstrates the second law: ΔS_total ≥ 0 for any spontaneous process. Interactive features include mixing colored particles and allowing gas expansion into vacuum. Educational value includes understanding why some processes are irreversible and the statistical meaning of entropy.
- **CN:** 该模拟直观地展示熵作为无序度量的概念。热力学定义为 dS = dQ_rev/T（克劳修斯），统计力学定义为 S = k·lnΩ（玻尔兹曼）。用户可以观察粒子系统从有序向无序演化的过程，熵的数值实时显示。模拟演示热力学第二定律：任何自发过程的 ΔS_total ≥ 0。交互功能包括混合有色粒子和允许气体向真空膨胀。教育价值在于理解为什么某些过程不可逆以及熵的统计含义。

### 48. [Entropy Simulation / 熵模拟](https://blackmatrixblack.github.io/zero-physics/entropy-simulation/)
- **EN:** This simulation expands on entropy through a particle-based statistical mechanics model. It tracks particle positions and velocities, computing Boltzmann entropy S = k_B·lnΩ. Users can create low-entropy initial states and watch the system evolve toward higher entropy. The Maxwell's demon thought experiment is simulated, highlighting the energy cost of gaining information. The simulation shows velocity histograms evolving toward the Maxwell-Boltzmann distribution. Educational value includes understanding the microscopic foundation of thermodynamics, Loschmidt's paradox, and the information-theoretic interpretation of entropy.
- **CN:** 该模拟通过基于粒子的统计力学模型扩展熵的概念。追踪每个粒子的位置和速度，计算玻尔兹曼熵 S = k_B·lnΩ。用户可以创建低熵初始状态，观察系统向更高熵演化。麦克斯韦妖思想实验被模拟，强调获取信息的能量成本。模拟显示速度直方图向麦克斯韦-玻尔兹曼分布演化。教育价值在于理解热力学的微观基础、洛施密特悖论以及熵的信息论解释。

### 49. [Equipartition / 能量均分](https://blackmatrixblack.github.io/zero-physics/equipartition/)
- **EN:** This simulation demonstrates the equipartition theorem: each quadratic degree of freedom in thermal equilibrium receives (½)k_BT of energy on average. For a monatomic gas (3 translational DOF), average energy is (3/2)k_BT; for diatomic gases, (5/2)k_BT; with vibrational modes, (7/2)k_BT. Users can select different gas molecules and adjust temperature. The heat capacity C_V = (f/2)R per mole is computed. The freezing out of rotational and vibrational modes at low temperatures is demonstrated. Educational value includes understanding why different gases have different heat capacities.
- **CN:** 该模拟演示能量均分定理——热平衡系统每个二次自由度平均获得 (½)k_BT 的能量。单原子气体（3 个平动自由度）平均能量为 (3/2)k_BT；双原子气体为 (5/2)k_BT；包含振动模式时为 (7/2)k_BT。用户可选择不同气体分子，调节温度。摩尔热容 C_V = (f/2)R 被计算。低温下转动和振动模式的冻结被演示。教育价值在于理解为什么不同气体具有不同热容。

### 50. [Fermi-Bose Distributions / 费米-玻色分布](https://blackmatrixblack.github.io/zero-physics/fermi-bose-distributions/)
- **EN:** This simulation visualizes quantum statistical distributions: Fermi-Dirac f_FD(E) = 1/(e^((E−μ)/(k_BT)) + 1) for fermions and Bose-Einstein f_BE(E) = 1/(e^((E−μ)/(k_BT)) − 1) for bosons. The Maxwell-Boltzmann distribution is shown for comparison. Users can adjust temperature T and chemical potential μ. For fermions, f_FD ≤ 1 (Pauli principle); for bosons, f_BE can exceed 1, signaling Bose-Einstein condensation. Educational value includes understanding why electrons follow Fermi-Dirac statistics and photons follow Bose-Einstein statistics.
- **CN:** 该模拟可视化量子统计分布：费米子的费米-狄拉克分布 f_FD(E) = 1/(e^((E−μ)/(k_BT)) + 1) 和玻色子的玻色-爱因斯坦分布 f_BE(E) = 1/(e^((E−μ)/(k_BT)) − 1)。麦克斯韦-玻尔兹曼分布作为经典极限显示以供比较。用户可以调节温度 T 和化学势 μ。费米子 f_FD ≤ 1（泡利原理），玻色子 f_BE 可超过 1，标志玻色-爱因斯坦凝聚。教育价值在于理解为什么电子遵循费米-狄拉克统计而光子遵循玻色-爱因斯坦统计。

### 51. [Heat Conduction / 热传导](https://blackmatrixblack.github.io/zero-physics/heat-conduction/)
- **EN:** This simulation models one-dimensional heat conduction governed by the heat equation ∂T/∂t = α·∂²T/∂x², where α = k/(ρc_p) is the thermal diffusivity. Users can set initial temperature distributions, adjust boundary conditions, and material properties. The simulation renders the temperature profile as a function of position and time. Fourier's law q = −k·dT/dx is demonstrated locally. Educational value includes understanding why metals conduct heat well and the role of boundary conditions in determining steady-state solutions.
- **CN:** 该模拟模拟由热方程 ∂T/∂t = α·∂²T/∂x² 控制的一维热传导，其中 α = k/(ρc_p) 为热扩散系数。用户可以设置初始温度分布，调节边界条件和材料属性。模拟渲染温度随位置和时间变化的曲线图。局部演示傅里叶定律 q = −k·dT/dx。教育价值在于理解为什么金属导热好以及边界条件在确定稳态解中的作用。

### 52. [Heat Conduction 1D / 一维热传导](https://blackmatrixblack.github.io/zero-physics/heat-conduction-1d/)
- **EN:** This simulation provides a focused visualization of heat conduction along a 1D rod using the finite difference method. The explicit forward-time central-space scheme Tᵢⁿ⁺¹ = Tᵢⁿ + r(Tᵢ₊₁ⁿ − 2Tᵢⁿ + Tᵢ₋₁ⁿ) requires r = αΔt/(Δx)² ≤ 0.5 for stability (CFL condition). Users can define initial temperature profiles and boundary conditions (Dirichlet, Neumann, Robin). Educational value includes understanding the CFL stability condition and the difference between explicit and implicit numerical schemes.
- **CN:** 该模拟专注于一维杆中的热传导可视化，使用有限差分法求解。显式前向时间中心空间格式 Tᵢⁿ⁺¹ = Tᵢⁿ + r(Tᵢ₊₁ⁿ − 2Tᵢⁿ + Tᵢ₋₁ⁿ) 要求 r = αΔt/(Δx)² ≤ 0.5 以保证稳定性（CFL 条件）。用户可定义初始温度分布和边界条件（狄利克雷、诺伊曼、罗宾）。教育价值在于理解 CFL 稳定性条件以及显式与隐式数值格式的区别。

### 53. [Heat Engine / 热机](https://blackmatrixblack.github.io/zero-physics/heat-engine/)
- **EN:** This simulation models a thermodynamic heat engine that converts heat into mechanical work. The net work output is W = Q_H − Q_C, and efficiency η = W/Q_H = 1 − Q_C/Q_H. Users can select different cycles: Carnot, Otto (η_Otto = 1 − 1/r^(γ−1)), Diesel, and Stirling. The simulation animates the piston motion synchronized with the PV diagram. Educational value includes understanding the first and second laws in practical engine contexts and why higher compression ratios improve efficiency.
- **CN:** 该模拟模拟热机——将热转化为机械功的热力学循环。净功输出为 W = Q_H − Q_C，效率 η = W/Q_H = 1 − Q_C/Q_H。用户可选择不同循环：卡诺、奥托（η_Otto = 1 − 1/r^(γ−1)）、狄塞尔和斯特林。模拟动画显示活塞运动与 PV 图同步。教育价值在于理解实用发动机背景下的第一和第二定律以及为什么更高的压缩比提高效率。

### 54. [Heat Equation / 热方程](https://blackmatrixblack.github.io/zero-physics/heat-equation/)
- **EN:** This simulation provides a 2D visualization of the heat equation ∂T/∂t = α(∂²T/∂x² + ∂²T/∂y²) with interactive heat sources and sinks. Users can paint hot and cold regions directly onto the canvas. The simulation uses the alternating direction implicit (ADI) method for computation. The steady-state solution satisfies Laplace's equation ∇²T = 0. Users can observe how heat spreads isotropically from point sources, following σ² = 2αt. Educational value includes understanding partial differential equations through visual simulation.
- **CN:** 该模拟提供热方程 ∂T/∂t = α(∂²T/∂x² + ∂²T/∂y²) 的二维可视化，包含交互式热源和热汇。用户可直接在画布上绘制冷区和热区。模拟使用交替方向隐式 (ADI) 方法计算。稳态解满足拉普拉斯方程 ∇²T = 0。用户可以观察热如何从点源各向同性扩散，遵循 σ² = 2αt。教育价值在于通过视觉模拟理解偏微分方程。

### 55. [Ideal Gas Law / 理想气体定律](https://blackmatrixblack.github.io/zero-physics/ideal-gas-law/)
- **EN:** This simulation demonstrates the ideal gas law PV = nRT (or PV = Nk_BT). Users control a piston to change volume, a heater to adjust temperature, and can add/remove gas particles. The pressure is computed from molecular collisions: P = (1/3)(N/V)m⟨v²⟩. Graphs display PV, PT, and VT relationships, allowing verification of Boyle's law, Charles's law, and Gay-Lussac's law. Educational value includes understanding the kinetic theory derivation of the ideal gas law and the concept of absolute zero.
- **CN:** 该模拟演示理想气体定律 PV = nRT（或 PV = Nk_BT）。用户控制活塞改变体积，调节加热器改变温度，并可添加/移除气体粒子。压力由分子碰撞计算：P = (1/3)(N/V)m⟨v²⟩。图表显示 PV、PT 和 VT 关系，允许验证玻意耳定律、查理定律和盖-吕萨克定律。教育价值在于理解理想气体定律的动理论推导和绝对零度的概念。

### 56. [Joule Expansion / 焦耳膨胀](https://blackmatrixblack.github.io/zero-physics/joule-expansion/)
- **EN:** This simulation models Joule (free) expansion, where a gas expands into a vacuum without doing work or exchanging heat. For an ideal gas, ΔU = 0 and ΔT = 0. The entropy change for free expansion from V₁ to V₂ is ΔS = nR·ln(V₂/V₁) > 0. A real gas option using van der Waals interactions shows a slight temperature change. Educational value includes understanding irreversible processes and why free expansion increases entropy.
- **CN:** 该模拟模拟焦耳（自由）膨胀——气体向真空中膨胀，不做功也不交换热量。对于理想气体，ΔU = 0 且 ΔT = 0。从 V₁ 自由膨胀至 V₂ 的熵变为 ΔS = nR·ln(V₂/V₁) > 0。使用范德瓦尔斯相互作用的真实气体选项显示微小温度变化。教育价值在于理解不可逆过程以及为什么自由膨胀增加熵。

### 57. [Joule-Thomson / 焦耳-汤姆逊效应](https://blackmatrixblack.github.io/zero-physics/joule-thomson/)
- **EN:** This simulation models the Joule-Thomson effect, where a real gas experiences temperature change when forced through a throttle under adiabatic conditions (constant enthalpy). The Joule-Thomson coefficient μ_JT = (∂T/∂P)_H determines whether the gas cools (μ_JT > 0) or heats (μ_JT < 0). Users can select different gases and adjust inlet pressure, temperature, and pressure drop. The Linde-Hampson liquefaction process is demonstrated. Educational value includes understanding gas liquefaction principles.
- **CN:** 该模拟模拟焦耳-汤姆逊效应——真实气体在绝热条件下被迫通过节流阀时的温度变化（等焓过程）。焦耳-汤姆逊系数 μ_JT = (∂T/∂P)_H 决定气体冷却还是加热。用户可选择不同气体，调节进口压力、温度和压降。林德-汉普森液化过程被演示。教育价值在于理解气体液化原理。

### 58. [Kinetic Theory of Gas / 气体动理论](https://blackmatrixblack.github.io/zero-physics/kinetic-theory-gas/)
- **EN:** This simulation provides a particle-level view of gas behavior. The simulation tracks hundreds of particles, computing macroscopic quantities from microscopic averages. Pressure: P = (N/3V)m⟨v²⟩; Temperature: T = (2/(3k_B))⟨KE⟩. The Maxwell-Boltzmann speed distribution is fitted in real-time. Users can adjust temperature, volume, and particle number. Educational value includes understanding the statistical origin of thermodynamic laws and the derivation of transport phenomena.
- **CN:** 该模拟根据气体动理论提供气体行为的粒子级视图。模拟追踪数百个粒子，从微观平均值计算宏观量。压力 P = (N/3V)m⟨v²⟩；温度 T = (2/(3k_B))⟨KE⟩。麦克斯韦-玻尔兹曼速率分布实时拟合。用户可以调节温度、体积和粒子数。教育价值在于理解热力学定律的统计起源和输运现象的推导。

### 59. [Latent Heat / 潜热](https://blackmatrixblack.github.io/zero-physics/latent-heat/)
- **EN:** This simulation demonstrates phase changes and latent heat: Q = mL_f (fusion) and Q = mL_v (vaporization). Users can heat a substance from solid through melting to liquid, then through vaporization to gas. The T-Q graph shows characteristic plateaus during phase transitions. The molecular view shows bond breaking. Specific heat capacity determines the slope: Q = mcΔT. Educational value includes understanding the energy cost of phase transitions and why steam burns are more severe.
- **CN:** 该模拟演示相变和潜热：Q = mL_f（熔化潜热）和 Q = mL_v（汽化潜热）。用户可以加热物质从固体经历熔化至液体，再经历汽化至气体。T-Q 图展示相变期间的特征性平台期。分子视图展示键的断裂。比热容决定斜率：Q = mcΔT。教育价值在于理解相变的能量代价以及为什么蒸汽烫伤比沸水烫伤更严重。

### 60. [Maxwell-Boltzmann / 麦克斯韦-玻尔兹曼分布](https://blackmatrixblack.github.io/zero-physics/maxwell-boltzmann/)
- **EN:** This simulation focuses on the Maxwell-Boltzmann speed distribution: f(v) = 4π(m/(2πk_BT))^(3/2) v² exp(−mv²/(2k_BT)). Key speeds are: most probable v_mp = √(2k_BT/m), mean ⟨v⟩ = √(8k_BT/(πm)), and RMS v_rms = √(3k_BT/m). Users can adjust temperature and molecular mass. The simulation displays the distribution curve with characteristic speeds marked. Educational value includes understanding why lighter molecules move faster on average and applications in effusion (Graham's law).
- **CN:** 该模拟聚焦于麦克斯韦-玻尔兹曼速率分布：f(v) = 4π(m/(2πk_BT))^(3/2) v² exp(−mv²/(2k_BT))。特征速率：最概然速率 v_mp = √(2k_BT/m)、平均速率 ⟨v⟩ = √(8k_BT/(πm)) 和均方根速率 v_rms = √(3k_BT/m)。用户可以调节温度和分子质量。模拟显示分布曲线并标记特征速率。教育价值在于理解为什么较轻分子平均运动更快以及在瀉流中的应用。

### 61. [Maxwell Distribution / 麦克斯韦分布](https://blackmatrixblack.github.io/zero-physics/maxwell-distribution/)
- **EN:** This simulation provides an additional perspective on the Maxwell-Boltzmann distribution, emphasizing velocity components. The distribution for v_x is: f(v_x) = √(m/(2πk_BT))·exp(−mv_x²/(2k_BT)), a Gaussian with σ = √(k_BT/m). Users can toggle between 1D, 2D, and 3D distributions. The simulation includes an energy distribution view: f(E) = (2/√π)(E/(k_BT))^(3/2)·(1/E)·exp(−E/(k_BT)). Educational value includes understanding why velocity components follow a Gaussian while speed follows a Maxwellian.
- **CN:** 该模拟提供麦克斯韦-玻尔兹曼分布的补充视角，强调速度分量的分布。v_x 的分布为：f(v_x) = √(m/(2πk_BT))·exp(−mv_x²/(2k_BT))，是 σ = √(k_BT/m) 的高斯分布。用户可在一维、二维和三维分布间切换。模拟包含能量分布视图：f(E) = (2/√π)(E/(k_BT))^(3/2)·(1/E)·exp(−E/(k_BT))。教育价值在于理解为什么速度分量服从高斯分布而速率服从麦克斯韦分布。

### 62. [Monte Carlo Gas / 蒙特卡洛气体](https://blackmatrixblack.github.io/zero-physics/monte-carlo-gas/)
- **EN:** This simulation uses the Monte Carlo method to model a gas system using the Metropolis-Hastings algorithm. Microstates are generated according to Boltzmann distribution P(E) ∝ exp(−E/k_BT). The acceptance probability = min(1, exp(−ΔE/k_BT)). The simulation computes ensemble averages of pressure, energy, and heat capacity. The Ising model on a 2D lattice shows the phase transition at critical temperature. Educational value includes understanding importance sampling and the ergodic hypothesis.
- **CN:** 该模拟使用蒙特卡洛方法模拟气体系统，采用梅特罗波利斯-黑斯廷斯算法。微观态根据玻尔兹曼分布 P(E) ∝ exp(−E/k_BT) 生成。接受概率 = min(1, exp(−ΔE/k_BT))。模拟计算压力、能量和热容的系综平均。二维晶格上的伊辛模型展示临界温度下的相变。教育价值在于理解重要性采样和遍历假说。

### 63. [Phase Transition / 相变](https://blackmatrixblack.github.io/zero-physics/phase-transition/)
- **EN:** This simulation visualizes phase transitions between solid, liquid, and gas on a pressure-temperature phase diagram. Phase boundaries follow the Clausius-Clapeyron equation dP/dT = L/(TΔV). The triple point and critical point are highlighted. Users can adjust temperature and pressure. The molecular view shows changes in molecular arrangement. For water, the anomalous negative slope of the solid-liquid boundary (ice melts under pressure) is shown. Educational value includes understanding first-order phase transitions and critical phenomena.
- **CN:** 该模拟可视化压力-温度相图中固态、液态和气态之间的相变。相边界遵循克劳修斯-克拉佩龙方程 dP/dT = L/(TΔV)。三相点和临界点被高亮显示。用户可以调节温度和压力。分子视图展示分子排列的变化。对于水，固-液边界的异常负斜率（冰在压力下融化）被展示。教育价值在于理解一级相变和临界现象。

### 64. [Planck Blackbody / 普朗克黑体辐射](https://blackmatrixblack.github.io/zero-physics/planck-blackbody/)
- **EN:** This simulation provides detailed visualization of Planck's law: B(ν,T) = (2hν³/c²)·1/(e^(hν/k_BT)−1) and B(λ,T) = (2hc²/λ⁵)·1/(e^(hc/λk_BT)−1). The simulation overlays Rayleigh-Jeans and Wien approximations. Total radiated power P = σT⁴ (Stefan-Boltzmann). Peak frequency ν_max = 5.88×10¹⁰ T Hz. A color bar shows the perceived color. Educational value includes understanding how Planck's formula resolved the ultraviolet catastrophe and applications in astrophysics.
- **CN:** 该模拟提供普朗克定律的详细可视化：B(ν,T) = (2hν³/c²)·1/(e^(hν/k_BT)−1) 和 B(λ,T) = (2hc²/λ⁵)·1/(e^(hc/λk_BT)−1)。模拟叠加瑞利-金斯和维恩近似。辐射总功率 P = σT⁴（斯特藩-玻尔兹曼）。峰值频率 ν_max = 5.88×10¹⁰ T Hz。色条显示感知颜色。教育价值在于理解普朗克公式如何解决紫外灾难以及在天体物理中的应用。

### 65. [Refrigeration / 制冷循环](https://blackmatrixblack.github.io/zero-physics/refrigeration/)
- **EN:** This simulation models a vapor-compression refrigeration cycle: compression, condensation, expansion, and evaporation. COP_R = Q_C/W for refrigeration, COP_HP = Q_H/W for heat pumps, with Carnot limit COP_R ≤ T_C/(T_H−T_C). Users can adjust working fluid, temperatures, and compressor efficiency. The P-h diagram traces the cycle. Educational value includes understanding how refrigerators pump heat uphill and why COP decreases with larger temperature differences.
- **CN:** 该模拟模拟蒸汽压缩制冷循环：压缩、冷凝、膨胀和蒸发。制冷 COP_R = Q_C/W，热泵 COP_HP = Q_H/W，卡诺极限 COP_R ≤ T_C/(T_H−T_C)。用户可以调节工作流体、温度和压缩机效率。P-h 图描迹循环。教育价值在于理解冰箱如何将热量从冷处泵到热处以及为什么 COP 随温度差增大而减小。

### 66. [Stefan-Boltzmann / 斯特藩-玻尔兹曼定律](https://blackmatrixblack.github.io/zero-physics/stefan-boltzmann/)
- **EN:** This simulation demonstrates the Stefan-Boltzmann law: j = σT⁴, σ = 5.67×10⁻⁸ W·m⁻²·K⁻⁴. Users can adjust temperature and compare blackbody, gray body (ε < 1), and selective emitter. The solar constant S = 1361 W/m² can be derived from the Sun's temperature. Educational value includes understanding why small temperature increases cause dramatic increases in radiated power and applications in climate science.
- **CN:** 该模拟演示斯特藩-玻尔兹曼定律：j = σT⁴，σ = 5.67×10⁻⁸ W·m⁻²·K⁻⁴。用户可以调节温度，比较黑体、灰体（ε < 1）和选择性发射体。太阳常数 S = 1361 W/m² 可从太阳温度推导。教育价值在于理解为什么较小的温度增量导致辐射功率急剧增加以及在气候科学中的应用。

### 67. [Stirling Cycle / 斯特林循环](https://blackmatrixblack.github.io/zero-physics/stirling-cycle/)
- **EN:** This simulation models the Stirling cycle with regeneration: isothermal compression, isochoric heating, isothermal expansion, isochoric cooling. Net work W = nR(T_H − T_C)ln(V_max/V_min), efficiency η = 1 − T_C/T_H (same as Carnot) with ideal regeneration. Users can adjust temperatures, compression ratio, and working fluid (helium/hydrogen). Educational value includes understanding why the Stirling cycle can achieve Carnot efficiency and why Stirling engines can use any heat source.
- **CN:** 该模拟模拟具有回热的斯特林循环：等温压缩、等容加热、等温膨胀、等容冷却。净功 W = nR(T_H − T_C)ln(V_max/V_min)，理想回热时效率 η = 1 − T_C/T_H（与卡诺相同）。用户可以调节温度、压缩比和工作流体（氦气/氢气）。教育价值在于理解斯特林循环为何能达到卡诺效率以及为何能使用任何热源。

### 68. [Thermal Radiation / 热辐射](https://blackmatrixblack.github.io/zero-physics/thermal-radiation/)
- **EN:** This simulation explores thermal radiation from objects due to their temperature. Planck's law governs the emitted spectrum. Users can adjust temperature and compare materials with varying emissivity ε (0 to 1). A thermographic camera view simulates thermal imaging. Kirchhoff's law of thermal radiation (good absorbers are also good emitters) is demonstrated. Educational value includes understanding infrared thermography, astronomy, and low-e coatings.
- **CN:** 该模拟探索物体因温度产生的热辐射。普朗克定律支配发射光谱。用户可以调节温度，比较不同发射率 ε（0 到 1）的材料。热像仪视图模拟热成像。基尔霍夫热辐射定律（好的吸收体也是好的发射体）被演示。教育价值在于理解红外热成像、天文学和低辐射涂层。

### 69. [Van der Waals / 范德瓦尔斯方程](https://blackmatrixblack.github.io/zero-physics/van-der-waals/)
- **EN:** This simulation models real gas behavior using the van der Waals equation: (P + a·n²/V²)(V − nb) = nRT. The parameters a (intermolecular attraction) and b (molecular volume) are adjustable. Below the critical temperature T_c = 8a/(27Rb), P-V isotherms develop a sigmoidal shape. The critical point and Maxwell's equal area construction are shown. Educational value includes understanding why real gases deviate from ideality and the origin of the critical point.
- **CN:** 该模拟使用范德瓦尔斯方程模拟真实气体行为：(P + a·n²/V²)(V − nb) = nRT。参数 a（分子间吸引力）和 b（分子体积）可调。在临界温度 T_c = 8a/(27Rb) 以下，P-V 等温线出现 S 形。临界点和麦克斯韦等面积法则被展示。教育价值在于理解真实气体为何偏离理想性以及临界点的起源。

---

# 4. Waves & Optics / 波与光学

### 70. [Bragg Diffraction / 布拉格衍射](https://blackmatrixblack.github.io/zero-physics/bragg-diffraction/)
- **EN:** This simulation visualizes Bragg diffraction from crystal lattice planes: nλ = 2d·sinθ. Users can adjust incident angle, wavelength, and lattice spacing d, observing constructive interference at specific angles. The simulation renders the crystal lattice with incident and reflected wavefronts. Reciprocal space and the Ewald sphere construction are introduced. Educational value includes understanding X-ray crystallography principles and how crystal structures are determined from diffraction patterns.
- **CN:** 该模拟可视化晶格平面的布拉格衍射：nλ = 2d·sinθ。用户可以调节入射角、波长和晶格间距 d，观察特定角度下的相长干涉。模拟渲染晶格以及入射和反射波前。引入倒易空间和埃瓦尔德球构造。教育价值在于理解 X 射线晶体学原理以及如何从衍射图样确定晶体结构。

### 71. [Doppler Effect / 多普勒效应](https://blackmatrixblack.github.io/zero-physics/doppler-effect/)
- **EN:** This simulation demonstrates the Doppler effect: f' = f·(v ± v_o)/(v ∓ v_s) for sound, and f' = f·√((1 ± β)/(1 ∓ β)) for light (β = v/c). Users can move a source toward/away from an observer. Wavefronts are visualized as concentric circles that bunch up ahead of a moving source. When v_s > v, a Mach cone forms with angle sinα = v/v_s. Educational value includes understanding applications in radar, medical ultrasound, astronomy (redshift), and the sonic boom.
- **CN:** 该模拟演示多普勒效应：声波 f' = f·(v ± v_o)/(v ∓ v_s)，光波 f' = f·√((1 ± β)/(1 ∓ β))（β = v/c）。用户可移动波源靠近/远离观察者。波前可视化为同心圆，波源前方密集。当 v_s > v 时形成马赫锥，角度 sinα = v/v_s。教育价值在于理解在雷达、医学超声、天文学（红移）和音爆中的应用。

### 72. [Double Slit / 双缝干涉](https://blackmatrixblack.github.io/zero-physics/double-slit/)
- **EN:** This simulation models Young's double-slit experiment. Constructive interference: d·sinθ = mλ; destructive: d·sinθ = (m + ½)λ. The intensity pattern I(θ) = I₀·cos²(πd·sinθ/λ)·sinc²(πa·sinθ/λ). Users can adjust slit separation d, slit width a, wavelength λ, and screen distance. Fringe spacing Δy = λL/d. Educational value includes understanding the wave nature of light, coherence requirements, and applications in spectroscopy.
- **CN:** 该模拟模拟杨氏双缝干涉实验。相长干涉：d·sinθ = mλ；相消干涉：d·sinθ = (m + ½)λ。强度图案 I(θ) = I₀·cos²(πd·sinθ/λ)·sinc²(πa·sinθ/λ)。用户可以调节缝间距 d、缝宽 a、波长 λ 和屏幕距离。条纹间距 Δy = λL/d。教育价值在于理解光的波动性质、相干性条件以及在光谱学中的应用。

### 73. [Double Slit Fluid / 双缝流体波动](https://blackmatrixblack.github.io/zero-physics/double-slit-fluid/)
- **EN:** This simulation provides a fluid dynamics analog of the double-slit experiment using water waves. The wave equation ∂²h/∂t² = c²∇²h governs surface height. Circular wavefronts emerge from each slit and interfere beyond. Users can adjust wave frequency, slit width and separation. Educational value includes understanding the universal nature of wave phenomena and the analogy between mechanical and electromagnetic waves.
- **CN:** 该模拟使用水波提供双缝实验的流体动力学类比。波动方程 ∂²h/∂t² = c²∇²h 控制表面高度。每个缝发出圆形波前并在后方干涉。用户可以调节波频、缝宽和缝间距。教育价值在于理解波动现象的普遍性以及机械波与电磁波之间的类比。

### 74. [Fourier Series / 傅里叶级数](https://blackmatrixblack.github.io/zero-physics/fourier-series/)
- **EN:** This simulation visualizes Fourier series decomposition: f(t) = a₀/2 + Σ[aₙ·cos(nω₀t) + bₙ·sin(nω₀t)]. Users can select preset functions (square, sawtooth, triangle) or draw custom waveforms. The Gibbs phenomenon (overshoot near discontinuities) is visible. The amplitude spectrum shows harmonic content. Educational value includes understanding the frequency domain versus time domain and applications in signal processing and audio compression.
- **CN:** 该模拟可视化傅里叶级数分解：f(t) = a₀/2 + Σ[aₙ·cos(nω₀t) + bₙ·sin(nω₀t)]。用户可选择预设函数（方波、锯齿波、三角波）或绘制自定义波形。吉布斯现象（不连续点附近的过冲）可见。幅度频谱展示谐波含量。教育价值在于理解频域与时域以及在信号处理和音频压缩中的应用。

### 75. [Fresnel Diffraction / 菲涅尔衍射](https://blackmatrixblack.github.io/zero-physics/fresnel-diffraction/)
- **EN:** This simulation models Fresnel (near-field) diffraction using the Fresnel-Kirchhoff integral. The Fresnel number F = a²/(λL) determines the regime (F > 1: Fresnel, F < 1: Fraunhofer). Users can select apertures (circular, rectangular, single slit, straight edge) and adjust parameters. Educational value includes understanding the difference between near-field and far-field diffraction and the importance of the Fresnel number.
- **CN:** 该模拟使用菲涅尔-基尔霍夫积分模拟菲涅尔（近场）衍射。菲涅尔数 F = a²/(λL) 决定区域（F > 1：菲涅尔，F < 1：夫琅禾费）。用户可选择孔径（圆形、矩形、单缝、直边）并调节参数。教育价值在于理解近场与远场衍射的区别以及菲涅尔数的重要性。

### 76. [Michelson Interferometer / 迈克尔逊干涉仪](https://blackmatrixblack.github.io/zero-physics/michelson-interferometer/)
- **EN:** This simulation models the Michelson interferometer. Intensity at detector: I = I₀[1 + cos(2π·ΔL/λ)]. Moving a mirror by λ/2 changes path difference by λ, shifting interference. Users can adjust mirror positions with nanometer precision. Key demonstrations include measuring wavelength and the historic Michelson-Morley experiment that disproved the luminiferous aether. Educational value includes understanding interferometric precision measurement.
- **CN:** 该模拟模拟迈克尔逊干涉仪。探测器处强度：I = I₀[1 + cos(2π·ΔL/λ)]。移动镜子 λ/2 改变 λ 光程差，干涉条纹移位。用户可以纳米精度调节镜子位置。关键演示包括波长测量和历史上否定发光以太的迈克尔逊-莫雷实验。教育价值在于理解干涉精密测量原理。

### 77. [Newton's Rings / 牛顿环](https://blackmatrixblack.github.io/zero-physics/newtons-rings/)
- **EN:** This simulation visualizes Newton's rings from the air gap between a convex lens and flat plate. Ring radii: bright rₘ = √(mλR), dark rₘ = √((m+½)λR). Users can adjust lens curvature radius R, wavelength, and gap medium. The characteristic circular fringe pattern has a dark center. Educational value includes understanding thin-film interference with variable-thickness gap and applications in optical testing.
- **CN:** 该模拟可视化凸透镜和平板之间空气间隙产生的牛顿环。环半径：亮环 rₘ = √(mλR)，暗环 rₘ = √((m+½)λR)。用户可以调节透镜曲率半径 R、波长和间隙介质。特征性圆形条纹图样中心为暗斑。教育价值在于理解变厚度间隙的薄膜干涉以及在光学检测中的应用。

### 78. [Single Slit Diffraction / 单缝衍射](https://blackmatrixblack.github.io/zero-physics/single-slit-diffraction/)
- **EN:** This simulation models Fraunhofer diffraction from a single slit: I(θ) = I₀·sinc²(πa·sinθ/λ). Minima occur at a·sinθ = mλ. The Rayleigh criterion for resolution is demonstrated: Δθ = 1.22λ/D for circular aperture. Educational value includes understanding the uncertainty principle analog in diffraction and applications in optical resolution limits of microscopes and telescopes.
- **CN:** 该模拟模拟单缝的夫琅禾费衍射：I(θ) = I₀·sinc²(πa·sinθ/λ)。极小值出现在 a·sinθ = mλ。演示瑞利分辨判据：圆形孔径 Δθ = 1.22λ/D。教育价值在于理解衍射中的不确定性原理类比以及在显微镜和望远镜光学分辨率极限中的应用。

### 79. [Snell's Law / 斯涅尔定律](https://blackmatrixblack.github.io/zero-physics/snells-law/)
- **EN:** This simulation demonstrates Snell's law: n₁sinθ₁ = n₂sinθ₂. Total internal reflection occurs beyond θ_c = arcsin(n₂/n₁). Dispersion splits white light into a spectrum. The Fresnel equations show reflectance dependence on polarization (Brewster's angle θ_B = arctan(n₂/n₁)). Educational value includes understanding fiber optic light guiding via total internal reflection and atmospheric refraction phenomena.
- **CN:** 该模拟演示斯涅尔定律：n₁sinθ₁ = n₂sinθ₂。超过临界角 θ_c = arcsin(n₂/n₁) 发生全内反射。色散将白光分解为光谱。菲涅尔方程展示反射率对偏振的依赖（布儒斯特角 θ_B = arctan(n₂/n₁)）。教育价值在于理解通过全内反射的光纤导光和大气折射现象。

### 80. [Soliton / 孤子](https://blackmatrixblack.github.io/zero-physics/soliton/)
- **EN:** This simulation visualizes solitons from the KdV equation: ∂u/∂t + 6u·∂u/∂x + ∂³u/∂x³ = 0. Single-soliton solution: u(x,t) = (c/2)·sech²(√c/2·(x − ct)). When two solitons collide, they emerge unchanged (only phase shift). Educational value includes understanding nonlinear wave phenomena, balance between nonlinearity and dispersion, and applications in optical fiber communications.
- **CN:** 该模拟可视化 KdV 方程的孤子解：∂u/∂t + 6u·∂u/∂x + ∂³u/∂x³ = 0。单孤子解：u(x,t) = (c/2)·sech²(√c/2·(x − ct))。两孤子碰撞后形状不变（仅有相移）。教育价值在于理解非线性波动现象、非线性与色散的平衡，以及在光纤通信中的应用。

### 81. [Sound Waves / 声波](https://blackmatrixblack.github.io/zero-physics/sound-waves/)
- **EN:** This simulation visualizes longitudinal sound waves. Speed v = √(γRT/M). The wave equation ∂²p/∂t² = v²∇²p governs pressure. Users can adjust frequency, amplitude, and waveform. The simulation shows particle oscillation along propagation with compression/rarefaction regions. The decibel scale: β(dB) = 10·log₁₀(I/I₀). Educational value includes understanding longitudinal vs. transverse waves and applications in architectural acoustics.
- **CN:** 该模拟可视化纵波——声波。速度 v = √(γRT/M)。波动方程 ∂²p/∂t² = v²∇²p 控制压力。用户可以调节频率、振幅和波形。模拟显示粒子沿传播方向的振荡以及压缩/稀疏区域。分贝标度：β(dB) = 10·log₁₀(I/I₀)。教育价值在于理解纵波与横波的区别以及在建筑声学中的应用。

### 82. [Standing Waves / 驻波](https://blackmatrixblack.github.io/zero-physics/standing-waves/)
- **EN:** This simulation demonstrates standing waves: y(x,t) = 2A·sin(kx)·cos(ωt). Nodes at x = nλ/2, antinodes at x = (2n+1)λ/4. For a fixed-fixed string, fₙ = nv/(2L) = (n/2L)√(T/μ). Users can adjust frequency, tension, and boundary conditions. Educational value includes understanding boundary conditions determine allowed modes, the difference between traveling and standing waves, and relationship to musical instruments.
- **CN:** 该模拟演示驻波：y(x,t) = 2A·sin(kx)·cos(ωt)。波节位于 x = nλ/2，波腹位于 x = (2n+1)λ/4。固定-固定弦 fₙ = nv/(2L) = (n/2L)√(T/μ)。用户可以调节频率、张力和边界条件。教育价值在于理解边界条件决定允许的模式、行波与驻波的区别以及与乐器的关系。

### 83. [Thin Film Interference / 薄膜干涉](https://blackmatrixblack.github.io/zero-physics/thin-film-interference/)
- **EN:** This simulation models thin-film interference (soap bubbles, oil slicks). Constructive: 2nt = (m + ½)λ (with π phase shift). Users can adjust thickness, refractive index, incident angle, and wavelength. White light illumination produces vivid colors. Educational value includes understanding why thin films produce colors, the role of π phase shift, and applications in anti-reflection coatings.
- **CN:** 该模拟模拟薄膜干涉（肥皂泡、油膜）。相长干涉条件：2nt = (m + ½)λ（有 π 相位变化）。用户可以调节厚度、折射率、入射角和波长。白光照明产生鲜艳颜色。教育价值在于理解为什么薄膜产生颜色、π 相位变化的作用，以及在增透膜中的应用。

### 84. [Thin Lens / 薄透镜](https://blackmatrixblack.github.io/zero-physics/thin-lens/)
- **EN:** This simulation models thin lens image formation: 1/f = 1/u + 1/v, magnification M = −v/u. Users can select converging/diverging lenses and adjust focal length, object distance, and size. Ray diagrams show three principal rays. The lensmaker's equation 1/f = (n−1)(1/R₁ − 1/R₂) relates focal length to geometry. Educational value includes understanding real vs. virtual images and applications in cameras and telescopes.
- **CN:** 该模拟模拟薄透镜成像：1/f = 1/u + 1/v，放大率 M = −v/u。用户可选择会聚/发散透镜，调节焦距、物距和物体尺寸。光线图显示三条主光线。透镜制造者方程 1/f = (n−1)(1/R₁ − 1/R₂) 将焦距与几何关联。教育价值在于理解实像与虚像的区别以及在相机和望远镜中的应用。

### 85. [Wave 1D / 一维波](https://blackmatrixblack.github.io/zero-physics/wave-1d/)
- **EN:** This simulation visualizes 1D wave propagation on a string: ∂²y/∂t² = c²∂²y/∂x², c = √(T/μ). d'Alembert's solution y(x,t) = f(x − ct) + g(x + ct) shows shape preservation. Users can create arbitrary initial shapes. Boundary conditions can be fixed, free, or absorbing. Reflection at boundaries: fixed ends invert the pulse. Educational value includes understanding the wave equation and superposition principle.
- **CN:** 该模拟可视化一维波在弦上的传播：∂²y/∂t² = c²∂²y/∂x²，c = √(T/μ)。达朗贝尔解 y(x,t) = f(x − ct) + g(x + ct) 展示形状保持。用户可创建任意初始形状。边界条件可为固定、自由或吸收。边界反射：固定端反转脉冲。教育价值在于理解波动方程和叠加原理。

### 86. [Wave Beats / 拍频](https://blackmatrixblack.github.io/zero-physics/wave-beats/)
- **EN:** This simulation visualizes beats from two waves of slightly different frequencies: y(t) = 2A·cos(2π·Δf/2·t)·cos(2π·f_avg·t). The envelope oscillates at Δf/2, perceived intensity beats at Δf. Users can adjust the two frequencies independently. A spectrogram shows the frequency components. Educational value includes understanding amplitude modulation and applications in musical instrument tuning and AM radio.
- **CN:** 该模拟可视化两个频率略有差异的波产生的拍频：y(t) = 2A·cos(2π·Δf/2·t)·cos(2π·f_avg·t)。包络以 Δf/2 振荡，感知拍频为 Δf。用户可以独立调节两个频率。频谱图显示频率分量。教育价值在于理解振幅调制以及在乐器调音和调幅广播中的应用。

### 87. [Wave Equation 2D / 二维波动方程](https://blackmatrixblack.github.io/zero-physics/wave-equation-2d/)
- **EN:** This simulation provides 2D wave propagation on a membrane: ∂²u/∂t² = c²(∂²u/∂x² + ∂²u/∂y²). Normal modes: for rectangle f_mn = (c/2)√((m/L_x)² + (n/L_y)²). Users can create disturbances and observe circular ripples. Fixed, free, and absorbing boundaries are available. Educational value includes understanding 2D normal modes, Chladni figures, and applications in drum design and earthquake waves.
- **CN:** 该模拟提供二维膜上的波动传播：∂²u/∂t² = c²(∂²u/∂x² + ∂²u/∂y²)。简正模：矩形 f_mn = (c/2)√((m/L_x)² + (n/L_y)²)。用户可产生扰动并观察圆形涟漪。固定、自由和吸收边界可用。教育价值在于理解二维简正模、克拉尼图形以及在鼓设计和地震波中的应用。

### 88. [Wave Packet Dispersion / 波包色散](https://blackmatrixblack.github.io/zero-physics/wave-packet-dispersion/)
- **EN:** This simulation visualizes dispersive wave propagation where phase velocity v_ph = ω/k depends on frequency. Group velocity v_g = dω/dk. Users can select dispersion relations: water waves (ω² = gk + σk³/ρ), deep water (ω² = gk), and massive particles (ω = ℏk²/(2m)). An initial Gaussian wave packet spreads when v_g ≠ v_ph. Educational value includes understanding the distinction between phase and group velocity.
- **CN:** 该模拟可视化色散波传播——相速度 v_ph = ω/k 依赖于频率。群速度 v_g = dω/dk。用户可选择色散关系：水波 (ω² = gk + σk³/ρ)、深水波 (ω² = gk) 和实物粒子 (ω = ℏk²/(2m))。当 v_g ≠ v_ph 时高斯波包展宽。教育价值在于理解相速度与群速度的区别。

### 89. [Wave Reflection / 波反射](https://blackmatrixblack.github.io/zero-physics/wave-reflection/)
- **EN:** This simulation focuses on wave reflection/transmission at boundaries. Reflection coefficient R = (Z₁ − Z₂)/(Z₁ + Z₂), transmission T = 2Z₁/(Z₁ + Z₂), where Z = √(Tμ) is impedance. When Z₁ = Z₂ (matched), no reflection occurs. Standing wave ratio SWR = (1 + |R|)/(1 − |R|) shows mismatch. Educational value includes understanding impedance matching in transmission lines, acoustics, and optics.
- **CN:** 该模拟聚焦于边界上的波反射/透射。反射系数 R = (Z₁ − Z₂)/(Z₁ + Z₂)，透射系数 T = 2Z₁/(Z₁ + Z₂)，其中 Z = √(Tμ) 为阻抗。Z₁ = Z₂（匹配）时无反射。驻波比 SWR = (1 + |R|)/(1 − |R|) 显示失配程度。教育价值在于理解传输线、声学和光学中的阻抗匹配。

### 90. [Waveguide / 波导](https://blackmatrixblack.github.io/zero-physics/waveguide/)
- **EN:** This simulation models wave propagation in a rectangular waveguide. Cutoff frequency for TE_mn/TM_mn modes: f_c_mn = (c/2π)√((mπ/a)² + (nπ/b)²). Below cutoff, waves are evanescent. The dominant TE₁₀ mode is visualized. Phase constant β = √(k² − k_c²) and group velocity v_g = c·√(1 − (f_c/f)²) are displayed. Educational value includes understanding waveguide high-pass response and applications in radar and microwave communications.
- **CN:** 该模拟模拟矩形波导中的波传播。TE_mn/TM_mn 模式的截止频率：f_c_mn = (c/2π)√((mπ/a)² + (nπ/b)²)。低于截止频率时波呈逝散。主模 TE₁₀ 被可视化。相位常数 β = √(k² − k_c²) 和群速度 v_g = c·√(1 − (f_c/f)²) 被显示。教育价值在于理解波导的高通响应以及在雷达和微波通信中的应用。

---

# 5. Quantum Mechanics / 量子力学

### 91. [BB84 / BB84量子密钥分发](https://blackmatrixblack.github.io/zero-physics/bb84/)
- **EN:** This simulation implements the BB84 quantum key distribution protocol. Alice sends qubits in one of two bases (rectilinear: |0⟩, |1⟩; diagonal: |+⟩, |−⟩). Bob randomly chooses measurement bases. After transmission, they compare bases publicly and keep only matching bits. Any eavesdropping (Eve) introduces detectable errors due to the no-cloning theorem. Users can observe the quantum state transmission, basis reconciliation, and quantum bit error rate (QBER). Educational value includes understanding the no-cloning theorem and how quantum mechanics enables secure communication.
- **CN:** 该模拟实现 BB84 量子密钥分发协议。Alice 在两种基矢（直线基：|0⟩、|1⟩；对角基：|+⟩、|−⟩）中编码量子比特。Bob 随机选择测量基矢。传输后他们公开比较基矢，仅保留匹配的比特。任何窃听 (Eve) 因不可克隆定理而引入可检测误差。用户可以观察量子态传输、基矢比对和量子比特误码率。教育价值在于理解不可克隆定理以及量子力学如何实现安全通信。

### 92. [Bell Inequality / 贝尔不等式](https://blackmatrixblack.github.io/zero-physics/bell-inequality/)
- **EN:** This simulation demonstrates Bell's inequality violation by quantum mechanics. The CHSH form: S = |E(a,b) + E(a,b') + E(a',b) − E(a',b')| ≤ 2 for local realism. Quantum mechanics predicts S = 2√2 ≈ 2.828 for maximally entangled states. Users simulate EPR experiments, choosing measurement angles. The correlation coefficient E(θ₁,θ₂) = cos(2(θ₁ − θ₂)) for quantum mechanics. Educational value includes understanding entanglement and the experimental refutation of local realism.
- **CN:** 该模拟演示贝尔不等式被量子力学违反。CHSH 形式：S = |E(a,b) + E(a,b') + E(a',b) − E(a',b')| ≤ 2（局域实在论）。量子力学预测最大纠缠态的 S = 2√2 ≈ 2.828。用户模拟 EPR 实验，选择测量角度。量子力学相关系数 E(θ₁,θ₂) = cos(2(θ₁ − θ₂))。教育价值在于理解纠缠以及对局域实在论的实验反驳。

### 93. [Bloch Oscillations / 布洛赫振荡](https://blackmatrixblack.github.io/zero-physics/bloch-oscillations/)
- **EN:** This simulation visualizes Bloch oscillations in a periodic potential under a constant electric field. Crystal momentum evolves as ℏ·dk/dt = −eE. Electrons oscillate with Bloch frequency ω_B = eEa/ℏ, bouncing from the Brillouin zone boundary. The Wannier-Stark ladder E_n = E₀ + n·ℏω_B is displayed. Educational value includes understanding band theory, the Brillouin zone, and negative differential resistance for high-frequency oscillators.
- **CN:** 该模拟可视化恒定电场下周期势中的布洛赫振荡。晶体动量演化为 ℏ·dk/dt = −eE。电子以布洛赫频率 ω_B = eEa/ℏ 振荡，从布里渊区边界反弹。Wannier-Stark 阶梯 E_n = E₀ + n·ℏω_B 被显示。教育价值在于理解能带理论、布里渊区以及用于高频振荡器的负微分电阻。

### 94. [Bloch Sphere / 布洛赫球](https://blackmatrixblack.github.io/zero-physics/bloch-sphere/)
- **EN:** This simulation visualizes the Bloch sphere for a qubit: |ψ⟩ = cos(θ/2)|0⟩ + e^(iφ)sin(θ/2)|1⟩. Users can manipulate the state by dragging on the sphere or applying quantum gates (X, Y, Z, H, S, T). Pauli operator expectation values ⟨X⟩, ⟨Y⟩, ⟨Z⟩ correspond to sphere coordinates. Educational value includes understanding quantum state representation, superposition vs. mixed states, and the geometric interpretation of single-qubit gates for quantum computing.
- **CN:** 该模拟可视化量子比特的布洛赫球：|ψ⟩ = cos(θ/2)|0⟩ + e^(iφ)sin(θ/2)|1⟩。用户可通过拖拽球面或应用量子门（X、Y、Z、H、S、T）操控状态。泡利算符期望值 ⟨X⟩、⟨Y⟩、⟨Z⟩ 对应球坐标。教育价值在于理解量子态表示、叠加态与混合态的区别，以及量子计算中单量子比特门的几何解释。

### 95. [Bose-Einstein Condensate / 玻色-爱因斯坦凝聚](https://blackmatrixblack.github.io/zero-physics/bose-einstein-condensate/)
- **EN:** This simulation visualizes Bose-Einstein condensation (BEC). Critical temperature T_c = (2πℏ²/mk_B)·(n/ζ(3/2))^(2/3). Condensate fraction N₀/N = 1 − (T/T_c)^(3/2). Users can adjust temperature, particle number, and trap potential. The Gross-Pitaevskii equation governs BEC dynamics. Vortices with quantized circulation ∮v·dr = 2πℏ/m × integer are shown. Educational value includes understanding macroscopic quantum coherence and atom lasers.
- **CN:** 该模拟可视化玻色-爱因斯坦凝聚 (BEC)。临界温度 T_c = (2πℏ²/mk_B)·(n/ζ(3/2))^(2/3)。凝聚体分数 N₀/N = 1 − (T/T_c)^(3/2)。用户可调节温度、粒子数和囚禁势。格罗斯-皮塔耶夫斯基方程支配 BEC 动力学。展示具有量子化环量 ∮v·dr = 2πℏ/m × 整数的涡旋。教育价值在于理解宏观量子相干和原子激光。

### 96. [Compton Scattering / 康普顿散射](https://blackmatrixblack.github.io/zero-physics/compton-scattering/)
- **EN:** This simulation models Compton scattering: λ' − λ = (h/(m_e c))·(1 − cosθ) = λ_C·(1 − cosθ). The scattered photon has longer wavelength. Users can adjust incident photon energy and scattering angle θ. Scattered photon energy: E' = E/[1 + (E/(m_e c²))(1 − cosθ)]. Educational value includes understanding the particle nature of light (p = h/λ) and conservation of energy/momentum in photon-electron collisions.
- **CN:** 该模拟模拟康普顿散射：λ' − λ = (h/(m_e c))·(1 − cosθ) = λ_C·(1 − cosθ)。散射光子具有更长波长。用户可调节入射光子能量和散射角 θ。散射光子能量：E' = E/[1 + (E/(m_e c²))(1 − cosθ)]。教育价值在于理解光的粒子性 (p = h/λ) 以及光子-电子碰撞中的能量/动量守恒。

### 97. [Density Matrix / 密度矩阵](https://blackmatrixblack.github.io/zero-physics/density-matrix/)
- **EN:** This simulation visualizes the density matrix ρ = Σpᵢ|ψᵢ⟩⟨ψᵢ| for pure and mixed states. For a qubit: ρ = (I + r⃗·σ⃗)/2 where |r⃗| = 1 for pure, |r⃗| < 1 for mixed. Users can apply quantum channels (depolarizing, dephasing, amplitude damping) via Kraus operators. Educational value includes understanding the difference between pure and mixed states, expectation values ⟨A⟩ = Tr(ρA), and open quantum systems.
- **CN:** 该模拟可视化纯态和混合态的密度矩阵 ρ = Σpᵢ|ψᵢ⟩⟨ψᵢ|。对于量子比特：ρ = (I + r⃗·σ⃗)/2，|r⃗| = 1 为纯态，|r⃗| < 1 为混合态。用户可通过克劳斯算符应用量子信道（退极化、退相位、振幅阻尼）。教育价值在于理解纯态与混合态的区别、期望值 ⟨A⟩ = Tr(ρA) 以及开放量子系统。

### 98. [Entanglement / 纠缠](https://blackmatrixblack.github.io/zero-physics/entanglement/)
- **EN:** This simulation visualizes quantum entanglement. Bell state |Φ⁺⟩ = (|00⟩ + |11⟩)/√2 cannot be written as |ψ⟩ ≠ |a⟩⊗|b⟩. Measuring one particle instantly determines the other's state. Reduced density matrix ρ_A = Tr_B(ρ_AB) = I/2 is maximally mixed. Users can measure entanglement via concurrence C or von Neumann entropy S(ρ_A). Educational value includes understanding entanglement as a uniquely quantum resource for teleportation and superdense coding.
- **CN:** 该模拟可视化量子纠缠。贝尔态 |Φ⁺⟩ = (|00⟩ + |11⟩)/√2 不能写为 |ψ⟩ ≠ |a⟩⊗|b⟩。测量一个粒子即时确定另一个的状态。约化密度矩阵 ρ_A = Tr_B(ρ_AB) = I/2 是最大混合态。用户可通过 concurrence C 或冯·诺伊曼熵 S(ρ_A) 测量纠缠。教育价值在于理解纠缠作为量子隐形传态和超密编码的独特量子资源。

### 99. [Finite Well / 有限深势阱](https://blackmatrixblack.github.io/zero-physics/finite-well/)
- **EN:** This simulation solves the Schrödinger equation for a finite square well. The wavefunction penetrates into classically forbidden regions with decay e^(−κx), κ = √(2m(V₀ − E))/ℏ. Bound state energies solve: k·tan(kL/2) = κ (even), k·cot(kL/2) = −κ (odd). Users can adjust well depth V₀ and width L. Educational value includes understanding quantum tunneling into forbidden regions and the number of bound states vs. well depth.
- **CN:** 该模拟求解有限深方势阱的薛定谔方程。波函数以 e^(−κx) 穿透经典禁戒区域，κ = √(2m(V₀ − E))/ℏ。束缚态能级求解：k·tan(kL/2) = κ（偶宇称），k·cot(kL/2) = −κ（奇宇称）。用户可调节势阱深度 V₀ 和宽度 L。教育价值在于理解量子隧穿进入禁戒区域以及束缚态数量与阱深的关系。

### 100. [Heisenberg Uncertainty / 海森堡不确定性原理](https://blackmatrixblack.github.io/zero-physics/heisenberg-uncertainty/)
- **EN:** This simulation demonstrates Δx·Δp ≥ ℏ/2. For a Gaussian wave packet, the minimum uncertainty product is ℏ/2. Users can vary the wave packet width and observe the corresponding momentum spread. The simulation displays ψ(x) and φ(p) (Fourier transform) with calculated Δx and Δp. Single-slit diffraction shows confinement (Δx small) → momentum spread (Δp large). Educational value includes understanding inherent uncertainty and the Fourier relationship between position and momentum.
- **CN:** 该模拟演示 Δx·Δp ≥ ℏ/2。高斯波包的最小不确定度乘积为 ℏ/2。用户可变化波包宽度，观察对应的动量扩展。模拟显示 ψ(x) 和 φ(p)（傅里叶变换）以及计算的 Δx 和 Δp。单缝衍射展示约束 (Δx 小) → 动量扩展 (Δp 大)。教育价值在于理解固有不确定性和位置与动量之间的傅里叶关系。

### 101. [Hydrogen Atom / 氢原子](https://blackmatrixblack.github.io/zero-physics/hydrogen-atom/)
- **EN:** This simulation visualizes the hydrogen atom quantum solution. Wavefunctions ψ_nlm(r,θ,φ) = R_nl(r)·Y_l^m(θ,φ). Energy E_n = −13.6 eV / n². Users can select quantum states (n, l, m) and observe |ψ|² in 3D. Radial distribution P(r) = r²|R_nl(r)|² and angular distribution |Y_l^m|² are shown. All states with n ≤ 5 are available. Educational value includes understanding quantum numbers (n, l, m), orbital shapes, and the periodic table explained by quantum mechanics.
- **CN:** 该模拟可视化氢原子的量子力学解。波函数 ψ_nlm(r,θ,φ) = R_nl(r)·Y_l^m(θ,φ)。能量 E_n = −13.6 eV / n²。用户可选量子态 (n, l, m)，以 3D 观察 |ψ|²。径向分布 P(r) = r²|R_nl(r)|² 和角度分布 |Y_l^m|² 被展示。n ≤ 5 的所有态可用。教育价值在于理解量子数 (n, l, m)、轨道形状以及用量子力学解释元素周期表。

### 102. [Infinite Square Well / 无限深方势阱](https://blackmatrixblack.github.io/zero-physics/infinite-square-well/)
- **EN:** This simulation solves the 1D infinite square well: ψₙ(x) = √(2/L)·sin(nπx/L), Eₙ = n²π²ℏ²/(2mL²). Users can adjust well width L and select n. Time evolution of superpositions Ψ(x,t) = Σcₙψₙ(x)·e^(−iEₙt/ℏ) shows quantum revival at T_rev = 2πmL²/πℏ. Educational value includes understanding energy quantization from boundary conditions and the particle-in-a-box model for conjugated molecules.
- **CN:** 该模拟求解一维无限深方势阱：ψₙ(x) = √(2/L)·sin(nπx/L)，Eₙ = n²π²ℏ²/(2mL²)。用户可调节宽度 L 并选择 n。叠加态的时间演化 Ψ(x,t) = Σcₙψₙ(x)·e^(−iEₙt/ℏ) 展示量子恢复 T_rev = 2πmL²/πℏ。教育价值在于理解边界条件导致的能量量子化以及用于共轭分子的箱中粒子模型。

### 103. [Landau Levels / 朗道能级](https://blackmatrixblack.github.io/zero-physics/landau-levels/)
- **EN:** This simulation visualizes Landau quantization: Eₙ = (n + ½)ℏω_c, ω_c = qB/m. Degeneracy D = BA/(h/q). Magnetic length l_B = √(ℏ/(qB)). Hall conductivity plateaus at σ_xy = ν·e²/h (integer quantum Hall effect). Educational value includes understanding how magnetic fields quantize electron motion and the integer quantum Hall effect explaining resistance standards.
- **CN:** 该模拟可视化朗道量子化：Eₙ = (n + ½)ℏω_c，ω_c = qB/m。简并度 D = BA/(h/q)。磁长度 l_B = √(ℏ/(qB))。霍尔电导在 σ_xy = ν·e²/h 处形成平台（整数量子霍尔效应）。教育价值在于理解磁场如何将电子运动量子化以及整数量子霍尔效应对电阻标准的解释。

### 104. [Pauli Exclusion / 泡利不相容原理](https://blackmatrixblack.github.io/zero-physics/pauli-exclusion/)
- **EN:** This simulation demonstrates the Pauli exclusion principle: no two identical fermions can occupy the same quantum state. Users build atoms by adding electrons following Hund's rules. Electron configurations (e.g., Fe: [Ar]3d⁶4s²) are displayed. Fermi energy E_F = ℏ²/(2m)(3π²n)^(2/3) produces degeneracy pressure supporting white dwarfs. Educational value includes understanding the periodic table structure, chemical bonding, and stellar stability.
- **CN:** 该模拟演示泡利不相容原理：两个全同费米子不能占据同一量子态。用户通过遵循洪德规则添加电子来构建原子。电子排布（如 Fe：[Ar]3d⁶4s²）被显示。费米能量 E_F = ℏ²/(2m)(3π²n)^(2/3) 产生支撑白矮星的简并压力。教育价值在于理解周期表结构、化学键和恒星稳定性。

### 105. [Photoelectric Effect / 光电效应](https://blackmatrixblack.github.io/zero-physics/photoelectric-effect/)
- **EN:** This simulation models the photoelectric effect: KE_max = hf − W = eV_stop. KE_max depends on frequency, not intensity — contradicting classical theory. Users can adjust frequency, intensity, and select metal cathodes with different work functions. A graph plots KE_max vs. frequency, slope = h (Planck's constant), intercept = −W. Below threshold f₀ = W/h, no electrons are emitted. Educational value includes understanding the photon concept E = hf and applications in solar cells.
- **CN:** 该模拟模拟光电效应：KE_max = hf − W = eV_截止。KE_max 取决于频率而非强度——与经典理论矛盾。用户可调节频率、强度并选择不同逸出功的金属阴极。KE_max vs. 频率图斜率为 h（普朗克常数），截距为 −W。低于阈值 f₀ = W/h 时不发射电子。教育价值在于理解光子概念 E = hf 以及在太阳能电池中的应用。

### 106. [QFT 1D / 一维量子场论](https://blackmatrixblack.github.io/zero-physics/qft-1d/)
- **EN:** This simulation visualizes 1D quantum field theory. The field operator φ̂(x) = ∫(dk/√(2π·2ω_k))·(â_k·e^(ikx) + â_k†·e^(−ikx)). Particles are excitations of the field. Users can add particle quanta, observe propagation, and see pair creation/annihilation. Vacuum fluctuations and Feynman diagrams for 2→2 scattering are shown. Educational value includes understanding that particles are field quanta, vacuum fluctuations, and the foundations of the Standard Model.
- **CN:** 该模拟可视化一维量子场论。场算符 φ̂(x) = ∫(dk/√(2π·2ω_k))·(â_k·e^(ikx) + â_k†·e^(−ikx))。粒子是场的激发态。用户可添加粒子量子，观察传播和粒子对产生/湮灭。真空涨落和 2→2 散射的费曼图被展示。教育价值在于理解粒子是场量子、真空涨落以及标准模型的基础。

### 107. [Quantum Dot / 量子点](https://blackmatrixblack.github.io/zero-physics/quantum-dot/)
- **EN:** This simulation models a quantum dot with discrete energy levels E_nl = ℏ²α_nl²/(2m*R²). Band gap increases as R decreases: E_gap(R) = E_g_bulk + ℏ²π²/(2m*R²). Users can adjust dot size and material (CdSe, InAs, PbS). Larger dots emit red light, smaller dots emit blue (size-tunable fluorescence). Educational value includes understanding quantum confinement effects and applications in QLED displays and biological imaging.
- **CN:** 该模拟模拟具有离散能级 E_nl = ℏ²α_nl²/(2m*R²) 的量子点。带隙随 R 减小而增大：E_带隙(R) = E_带隙_体 + ℏ²π²/(2m*R²)。用户可调节量子点尺寸和材料（CdSe、InAs、PbS）。大量子点发红光，小量子点发蓝光（尺寸可调荧光）。教育价值在于理解量子约束效应以及在 QLED 显示和生物成像中的应用。

### 108. [Quantum Double Slit / 量子双缝](https://blackmatrixblack.github.io/zero-physics/quantum-double-slit/)
- **EN:** This simulation models the quantum double-slit experiment. Probability density |ψ(x)|² = |ψ₁(x) + ψ₂(x)|². Single particles interfere with themselves. A which-path detector destroys interference (complementarity). Users can adjust detector sensitivity to show continuous transition from interference to no interference. Educational value includes understanding wave-particle duality, the role of measurement, and the Copenhagen interpretation.
- **CN:** 该模拟模拟量子双缝实验。概率密度 |ψ(x)|² = |ψ₁(x) + ψ₂(x)|²。单个粒子与自身干涉。路径探测器破坏干涉（互补性）。用户可调节探测器灵敏度展示从干涉到无干涉的连续过渡。教育价值在于理解波粒二象性、测量的作用以及哥本哈根解释。

### 109. [Quantum Eraser / 量子擦除器](https://blackmatrixblack.github.io/zero-physics/quantum-eraser/)
- **EN:** This simulation demonstrates the quantum eraser experiment. Which-path information is encoded in entangled photons. Erasing this information restores interference — even retroactively (delayed-choice). Users can choose to measure or erase which-path information. The simulation shows coincidence counts between detectors. Educational value includes understanding the role of information in quantum mechanics and why the quantum eraser does not allow faster-than-light communication.
- **CN:** 该模拟演示量子擦除器实验。路径信息编码在纠缠光子中。擦除信息恢复干涉——甚至追溯性地（延迟选择）。用户可选择测量或擦除路径信息。模拟显示探测器间的符合计数。教育价值在于理解信息在量子力学中的作用以及为什么量子擦除器不允许超光速通信。

### 110. [Quantum Harmonic Oscillator / 量子谐振子](https://blackmatrixblack.github.io/zero-physics/quantum-harmonic-oscillator/)
- **EN:** This simulation solves the quantum harmonic oscillator: Eₙ = (n + ½)ℏω. Wavefunctions ψₙ(x) = (1/√(2ⁿn!))·(mω/(πℏ))^(1/4)·Hₙ(√(mω/ℏ)·x)·e^(−mωx²/(2ℏ)) with Hermite polynomials Hₙ. Users can select n, adjust ω and m. Coherent states (minimum uncertainty) and squeezed states are shown. Ladder operators â and â† are demonstrated. Educational value includes understanding zero-point energy and the correspondence principle.
- **CN:** 该模拟求解量子谐振子：Eₙ = (n + ½)ℏω。波函数 ψₙ(x) = (1/√(2ⁿn!))·(mω/(πℏ))^(1/4)·Hₙ(√(mω/ℏ)·x)·e^(−mωx²/(2ℏ))（厄米多项式 Hₙ）。用户可选择 n，调节 ω 和 m。相干态（最小不确定态）和压缩态被展示。阶梯算符 â 和 â† 被演示。教育价值在于理解零点能和对应原理。

### 111. [Quantum Spin / 量子自旋](https://blackmatrixblack.github.io/zero-physics/quantum-spin/)
- **EN:** This simulation visualizes quantum spin. For spin-½, S_i = (ℏ/2)σ_i. Users can set the spin state on the Bloch sphere and measure components along arbitrary directions. P(↑) = cos²(θ/2), P(↓) = sin²(θ/2). Consecutive non-commuting measurements yield random results (Stern-Gerlach sequence). Commutation relations [S_i, S_j] = iℏε_ijkS_k are illustrated. Educational value includes understanding purely quantum angular momentum and applications in MRI and quantum computing.
- **CN:** 该模拟可视化量子自旋。对于自旋 ½，S_i = (ℏ/2)σ_i。用户可在布洛赫球上设置自旋态并沿任意方向测量分量。P(↑) = cos²(θ/2)，P(↓) = sin²(θ/2)。连续非对易测量给出随机结果（斯特恩-盖拉赫序列）。对易关系 [S_i, S_j] = iℏε_ijkS_k 被说明。教育价值在于理解纯量子角动量以及在磁共振成像和量子计算中的应用。

### 112. [Quantum Tunneling / 量子隧穿](https://blackmatrixblack.github.io/zero-physics/quantum-tunneling/)
- **EN:** This simulation visualizes quantum tunneling through a barrier. Transmission probability T ≈ 16E(V₀−E)/V₀²·e^(−2κa) for E < V₀, κ = √(2m(V₀−E))/ℏ. Users can adjust barrier height, width, and particle energy. The wavefunction inside the barrier decays exponentially. Resonant tunneling through double barriers produces perfect transmission at specific energies. Educational value includes understanding applications in STM, flash memory, and alpha decay.
- **CN:** 该模拟可视化量子隧穿。透射概率 T ≈ 16E(V₀−E)/V₀²·e^(−2κa)（E < V₀），κ = √(2m(V₀−E))/ℏ。用户可调节势垒高度、宽度和粒子能量。势垒内部波函数指数衰减。双势垒的共振隧穿在特定能量下产生完美透射。教育价值在于理解在扫描隧道显微镜、闪存和 α 衰变中的应用。

### 113. [Quantum Wavepacket / 量子波包](https://blackmatrixblack.github.io/zero-physics/quantum-wavepacket/)
- **EN:** This simulation visualizes quantum wave packet dynamics solving the time-dependent Schrödinger equation iℏ∂ψ/∂t = −(ℏ²/2m)∂²ψ/∂x² + V(x)ψ. Users can set initial wave packets (Gaussian) and watch evolution under various potentials. Spreading, reflection, and interference are shown. Expectation values ⟨x⟩ and ⟨p⟩ are computed. Educational value includes understanding wave packet spreading, Ehrenfest's theorem, and the classical limit of quantum mechanics.
- **CN:** 该模拟通过求解含时薛定谔方程 iℏ∂ψ/∂t = −(ℏ²/2m)∂²ψ/∂x² + V(x)ψ 可视化量子波包动力学。用户可设置初始波包（高斯）并观察在各种势下的演化。展宽、反射和干涉被展示。期望值 ⟨x⟩ 和 ⟨p⟩ 被计算。教育价值在于理解波包展宽、埃伦费斯特定理和量子力学的经典极限。

### 114. [Quantum Zeno / 量子芝诺效应](https://blackmatrixblack.github.io/zero-physics/quantum-zeno/)
- **EN:** This simulation demonstrates the quantum Zeno effect: frequent measurement can inhibit quantum evolution. A two-level system undergoes Rabi oscillation between |0⟩ and |1⟩. When measured frequently, the system remains in the initial state — \"a watched pot never boils.\" Users can adjust measurement frequency and observe the freezing of dynamics. Educational value includes understanding the role of measurement in quantum mechanics and the projection postulate.
- **CN:** 该模拟演示量子芝诺效应：频繁测量可以抑制量子演化。两能级系统在 |0⟩ 和 |1⟩ 之间进行拉比振荡。当频繁测量时，系统保持在初始态——\"看着的水壶永远不会开\"。用户可调节测量频率并观察动力学的冻结。教育价值在于理解测量在量子力学中的作用和投影假设。

### 115. [Rabi Oscillation / 拉比振荡](https://blackmatrixblack.github.io/zero-physics/rabi-oscillation/)
- **EN:** This simulation visualizes Rabi oscillation, the periodic population transfer between two quantum states driven by an external field. The probability P₁(t) = (Ω_R²/Ω²)·sin²(Ωt/2) where Ω_R is the Rabi frequency and Ω = √(Ω_R² + Δ²) with detuning Δ. Users can adjust the driving field strength and detuning. π-pulse (complete transfer) and 2π-pulse (return) are demonstrated. Educational value includes understanding coherent control of quantum systems and applications in NMR and quantum computing.
- **CN:** 该模拟可视化拉比振荡——外场驱动下两个量子态之间的周期性布居转移。概率 P₁(t) = (Ω_R²/Ω²)·sin²(Ωt/2)，其中 Ω_R 为拉比频率，Ω = √(Ω_R² + Δ²)，Δ 为失谐量。用户可调节驱动场强度和失谐量。π 脉冲（完全转移）和 2π 脉冲（返回）被演示。教育价值在于理解量子系统的相干控制在核磁共振和量子计算中的应用。

### 116. [Schrödinger 1D / 一维薛定谔方程](https://blackmatrixblack.github.io/zero-physics/schrodinger-1d/)
- **EN:** This simulation solves the 1D time-dependent Schrödinger equation numerically. Users can draw arbitrary potential V(x) and set initial wavefunctions (Gaussian, plane wave, eigenstates). The simulation shows |ψ(x,t)|² evolution, with probability conservation verified. Stationary states and scattering problems can be explored. Educational value includes understanding wave mechanics, probability density interpretation, and numerical solutions to PDEs.
- **CN:** 该模拟数值求解一维含时薛定谔方程。用户可绘制任意势 V(x) 并设置初始波函数（高斯、平面波、本征态）。模拟显示 |ψ(x,t)|² 演化，概率守恒被验证。可探索定态和散射问题。教育价值在于理解波动力学、概率密度解释以及偏微分方程的数值解。

### 117. [Spherical Harmonics / 球谐函数](https://blackmatrixblack.github.io/zero-physics/spherical-harmonics/)
- **EN:** This simulation visualizes spherical harmonics Y_l^m(θ,φ), the angular part of quantum mechanical wavefunctions in central potentials. Users can select quantum numbers l (0,1,2,3...) and m (−l,...,+l). The real and imaginary parts, magnitude |Y_l^m|², and phase are shown as 3D surfaces. Nodal structures (l nodal planes) are visible. Educational value includes understanding angular momentum quantization, orbital shapes (s, p, d, f), and multipole expansions.
- **CN:** 该模拟可视化球谐函数 Y_l^m(θ,φ)——中心势中量子力学波函数的角度部分。用户可选择量子数 l (0,1,2,3...) 和 m (−l,...,+l)。实部、虚部、模 |Y_l^m|² 和相位以 3D 曲面显示。节面结构（l 个节面）可见。教育价值在于理解角动量量子化、轨道形状（s、p、d、f）和多极展开。

### 118. [Spin 1/2 / 自旋1/2](https://blackmatrixblack.github.io/zero-physics/spin-12/)
- **EN:** This simulation focuses on spin-½ systems. The state is represented on the Bloch sphere. Users can apply rotations (magnetic field pulses) and measurements. The Stern-Gerlach experiment is simulated: a beam of spin-½ particles splits into two discrete spots. Sequential SG experiments demonstrate the non-commutativity of spin measurements. Educational value includes understanding the two-state quantum system, measurement postulate, and quantum randomness.
- **CN:** 该模拟专注于自旋 ½ 系统。状态在布洛赫球上表示。用户可施加旋转（磁场脉冲）和测量。斯特恩-盖拉赫实验被模拟：自旋 ½ 粒子束分裂为两个离散斑点。连续 SG 实验展示自旋测量的非对易性。教育价值在于理解两态量子系统、测量假设和量子随机性。

### 119. [Stark Effect / 斯塔克效应](https://blackmatrixblack.github.io/zero-physics/stark-effect/)
- **EN:** This simulation visualizes the Stark effect — the splitting of spectral lines due to an external electric field. For hydrogen, the linear Stark effect shows splitting proportional to field strength E_field for degenerate states (n ≥ 2). The quadratic Stark effect (non-degenerate states) shows shifts ∝ E_field². Users can adjust the electric field and observe energy level shifts and wavefunction deformation. Educational value includes understanding perturbation theory and symmetry breaking in quantum systems.
- **CN:** 该模拟可视化斯塔克效应——外电场导致的光谱线分裂。对于氢原子，线性斯塔克效应对简并态（n ≥ 2）的分裂与场强 E_场 成正比。二次斯塔克效应（非简并态）的偏移 ∝ E_场²。用户可调节电场，观察能级移动和波函数变形。教育价值在于理解微扰理论和量子系统中的对称性破缺。

### 120. [Stern-Gerlach / 斯特恩-盖拉赫实验](https://blackmatrixblack.github.io/zero-physics/stern-gerlach/)
- **EN:** This simulation reproduces the historic Stern-Gerlach experiment, which demonstrated spatial quantization of angular momentum. Silver atoms pass through an inhomogeneous magnetic field and split into two discrete beams. Users can adjust field gradient, atom velocity, and orientation of the magnet. Sequential arrangements (SGx then SGz) show the quantization and non-commutativity of spin components. Educational value includes understanding the discovery of electron spin and the foundations of quantum measurement.
- **CN:** 该模拟重现历史上的斯特恩-盖拉赫实验——证明了角动量的空间量子化。银原子通过非均匀磁场后分裂为两束离散束流。用户可调节磁场梯度、原子速度和磁体方向。连续排列（SGx 然后 SGz）展示自旋分量的量子化和非对易性。教育价值在于理解电子自旋的发现和量子测量的基础。

### 121. [Zeeman Effect / 塞曼效应](https://blackmatrixblack.github.io/zero-physics/zeeman-effect/)
- **EN:** This simulation visualizes the Zeeman effect — splitting of spectral lines in a magnetic field. The normal Zeeman effect (singlet states) shows splitting into three lines with energy shift ΔE = m_l·μ_B·B. The anomalous Zeeman effect includes spin-orbit coupling, following ΔE = g_J·m_J·μ_B·B with Landé g-factor g_J = 1 + [j(j+1) + s(s+1) − l(l+1)]/[2j(j+1)]. Users can adjust B-field and view polarization of emitted light. Educational value includes understanding atomic structure and magnetic fields in astrophysics.
- **CN:** 该模拟可视化塞曼效应——磁场中光谱线的分裂。正常塞曼效应（单重态）分裂为三条线，能量偏移 ΔE = m_l·μ_B·B。反常塞曼效应包含自旋-轨道耦合，ΔE = g_J·m_J·μ_B·B，朗德 g 因子 g_J = 1 + [j(j+1) + s(s+1) − l(l+1)]/[2j(j+1)]。用户可调节 B 场并观察发射光的偏振。教育价值在于理解原子结构和天体物理中的磁场。

---

# 6. Relativity / 相对论

### 122. [Length Contraction / 长度收缩](https://blackmatrixblack.github.io/zero-physics/length-contraction/)
- **EN:** This simulation demonstrates relativistic length contraction: L = L₀/γ = L₀√(1 − v²/c²). A moving object appears contracted along its direction of motion. Users can adjust the relative velocity v/c and observe how a measuring rod or spacecraft shrinks. Both the moving observer's perspective (who sees no contraction of their own frame) and the stationary observer's view are shown simultaneously. Educational value includes understanding the relativity of simultaneity and the Lorentz-FitzGerald contraction hypothesis.
- **CN:** 该模拟演示相对论性长度收缩：L = L₀/γ = L₀√(1 − v²/c²)。运动物体沿运动方向收缩。用户可以调节相对速度 v/c，观察测量杆或飞船如何收缩。运动观察者视角（自己参考系无收缩）和静止观察者视角同时展示。教育价值在于理解同时性的相对性和洛伦兹-菲茨杰拉德收缩假说。

### 123. [Lorentz Transformation / 洛伦兹变换](https://blackmatrixblack.github.io/zero-physics/lorentz-transformation/)
- **EN:** This simulation visualizes Lorentz transformations between inertial frames. The transformation equations: x' = γ(x − vt), t' = γ(t − vx/c²), γ = 1/√(1 − v²/c²). Users can boost between frames and observe how spacetime coordinates transform. Worldlines of light cones (x = ±ct) are invariant. The simulation demonstrates the mixing of space and time coordinates and the invariant interval Δs² = c²Δt² − Δx². Educational value includes understanding the geometric structure of Minkowski spacetime.
- **CN:** 该模拟可视化惯性系之间的洛伦兹变换。变换方程：x' = γ(x − vt)，t' = γ(t − vx/c²)，γ = 1/√(1 − v²/c²)。用户在参考系之间加速并观察时空坐标如何变换。光锥世界线 (x = ±ct) 不变。模拟演示空间和时间坐标的混合以及不变间隔 Δs² = c²Δt² − Δx²。教育价值在于理解闵可夫斯基时空的几何结构。

### 124. [Minkowski Diagram / 闵可夫斯基图](https://blackmatrixblack.github.io/zero-physics/minkowski-diagram/)
- **EN:** This simulation provides interactive Minkowski (spacetime) diagrams. Events, worldlines, and light cones are plotted in 2D spacetime (x vs. ct). Users can apply Lorentz boosts and observe how the axes tilt. Timelike (Δs² > 0), spacelike (Δs² < 0), and lightlike (Δs² = 0) intervals are distinguished. Causality is visualized: events inside the light cone can be causally connected. Educational value includes understanding spacetime geometry, proper time, and the causal structure of relativity.
- **CN:** 该模拟提供交互式闵可夫斯基（时空）图。事件、世界线和光锥在二维时空中绘制（x vs. ct）。用户可应用洛伦兹加速并观察轴如何倾斜。类时间隔 (Δs² > 0)、类空间隔 (Δs² < 0) 和类光间隔 (Δs² = 0) 被区分。因果性可视化：光锥内的事件可以有因果联系。教育价值在于理解时空几何、固有时和相对论的因果结构。

### 125. [Relativistic Doppler / 相对论多普勒效应](https://blackmatrixblack.github.io/zero-physics/relativistic-doppler/)
- **EN:** This simulation demonstrates the relativistic Doppler effect: f_obs = f_src·√((1 − β)/(1 + β)) for recession, f_obs = f_src·√((1 + β)/(1 − β)) for approach, β = v/c. The transverse Doppler effect (time dilation) is also shown: f_obs = f_src/γ. Users can adjust relative velocity and observe redshift/blueshift. The simulation distinguishes between the classical Doppler effect and the relativistic correction. Educational value includes understanding how redshift is used to measure cosmic expansion and stellar velocities.
- **CN:** 该模拟演示相对论多普勒效应：退行时 f_obs = f_src·√((1 − β)/(1 + β))，接近时 f_obs = f_src·√((1 + β)/(1 − β))，β = v/c。横向多普勒效应（时间膨胀）也被展示：f_obs = f_src/γ。用户可调节相对速度并观察红移/蓝移。模拟区分经典多普勒效应和相对论修正。教育价值在于理解红移如何用于测量宇宙膨胀和恒星速度。

### 126. [Schwarzschild Geodesic / 史瓦西测地线](https://blackmatrixblack.github.io/zero-physics/schwarzschild-geodesic/)
- **EN:** This simulation visualizes particle and light trajectories in Schwarzschild spacetime (non-rotating black hole). The geodesic equation is derived from the Schwarzschild metric: ds² = (1−r_s/r)c²dt² − (1−r_s/r)⁻¹dr² − r²(dθ² + sin²θ dφ²), where r_s = 2GM/c². Users can launch particles or photons and observe orbits, gravitational deflection, and the innermost stable circular orbit (ISCO at r = 3r_s). Below the photon sphere (r = 1.5r_s), light is captured. Educational value includes understanding black hole physics and general relativity.
- **CN:** 该模拟可视化史瓦西时空（非旋转黑洞）中的粒子和光线轨迹。测地线方程从史瓦西度规推导：ds² = (1−r_s/r)c²dt² − (1−r_s/r)⁻¹dr² − r²(dθ² + sin²θ dφ²)，其中 r_s = 2GM/c²。用户可以发射粒子或光子，观察轨道、引力偏转和最内稳定圆轨道（r = 3r_s 处的 ISCO）。在光子球 (r = 1.5r_s) 以下，光被捕获。教育价值在于理解黑洞物理和广义相对论。

### 127. [Time Dilation / 时间膨胀](https://blackmatrixblack.github.io/zero-physics/time-dilation/)
- **EN:** This simulation demonstrates relativistic time dilation: Δt = γΔt₀, where Δt₀ is proper time and γ = 1/√(1 − v²/c²). A moving clock ticks slower relative to a stationary observer. Users can adjust velocity and compare clock rates. The light clock thought experiment is visualized: a light pulse bouncing between mirrors appears to take a longer path (hence longer time) when the clock moves. Educational value includes understanding the twin paradox resolution and experimental verification (muon decay, GPS).
- **CN:** 该模拟演示相对论性时间膨胀：Δt = γΔt₀，其中 Δt₀ 为固有时，γ = 1/√(1 − v²/c²)。运动的时钟相对于静止观察者走得更慢。用户可以调节速度并比较时钟速率。光钟思想实验被可视化：镜子间反射的光脉冲在运动时钟中路径更长（因此时间更长）。教育价值在于理解双生子悖论的解决以及实验验证（μ子衰变、GPS）。

### 128. [Twin Paradox Detailed / 双生子悖论详解](https://blackmatrixblack.github.io/zero-physics/twin-paradox-detailed/)
- **EN:** This simulation provides a detailed analysis of the twin paradox. One twin travels at relativistic speed to a distant star and returns, while the other stays on Earth. The traveling twin ages less. The simulation includes spacetime diagrams showing the worldlines of both twins, proper time calculations along each path, and the resolution: acceleration breaks the symmetry. The Doppler shift communication between twins is shown. Educational value includes resolving the apparent paradox and understanding proper time as the clock reading along a worldline.
- **CN:** 该模拟提供双生子悖论的详细分析。一个双胞胎以相对论速度前往遥远恒星并返回，另一个留在地球。旅行者衰老更少。模拟包括显示两个双胞胎世界线的时空图、每条路径的固有时计算以及分辨——加速度打破对称性。双胞胎之间的多普勒频移通信被展示。教育价值在于解决表观悖论以及理解固有时作为沿世界线的时钟读数。

---

# 7. Fluid Dynamics / 流体动力学

### 129. [Bernoulli Principle / 伯努利原理](https://blackmatrixblack.github.io/zero-physics/bernoulli-principle/)
- **EN:** This simulation demonstrates Bernoulli's principle: P + ½ρv² + ρgh = constant along a streamline. Users can adjust pipe cross-section, fluid velocity, and height. Venturi effect (pressure drop at constriction) is visualized with manometers. Applications include airplane wing lift (airfoil), atomizers, and Pitot tubes. The simulation shows streamlines with velocity vectors and pressure color maps. Educational value includes understanding the conservation of energy in fluid flow and lift generation.
- **CN:** 该模拟演示伯努利原理：P + ½ρv² + ρgh = 常数（沿流线）。用户可调节管道截面、流速和高度。文丘里效应（收缩处压力下降）用压力计可视化。应用包括机翼升力、雾化器和皮托管。模拟显示带速度矢量的流线和压力彩色图。教育价值在于理解流动中的能量守恒和升力产生。

### 130. [Karman Vortex / 卡门涡街](https://blackmatrixblack.github.io/zero-physics/karman-vortex/)
- **EN:** This simulation visualizes the Kármán vortex street — alternating vortices shed from a bluff body in a fluid flow. The Strouhal number St = fD/v ≈ 0.2 relates vortex shedding frequency f to flow velocity v and body diameter D. Users can adjust flow velocity and body shape/size. The Reynolds number Re = ρvD/μ determines the flow regime. Educational value includes understanding vortex-induced vibration, drag reduction, and applications in bridge design (Tacoma Narrows) and flow metering.
- **CN:** 该模拟可视化卡门涡街——流体中钝体交替脱落的涡旋。斯特劳哈尔数 St = fD/v ≈ 0.2 关联涡脱频率 f 与流速 v 和物体直径 D。用户可调节流速和物体形状/尺寸。雷诺数 Re = ρvD/μ 决定流动状态。教育价值在于理解涡激振动、减阻以及在桥梁设计（塔科马海峡）和流量计量中的应用。

### 131. [Navier-Stokes LBM / 纳维-斯托克斯LBM](https://blackmatrixblack.github.io/zero-physics/navier-stokes-lbm/)
- **EN:** This simulation solves fluid flow using the Lattice Boltzmann Method (LBM), an alternative to directly solving the Navier-Stokes equations. The discrete Boltzmann equation fᵢ(x + cᵢΔt, t + Δt) = fᵢ(x,t) − [fᵢ(x,t) − fᵢ^(eq)(x,t)]/τ governs particle distribution evolution. Users can set boundary conditions (wall, inlet, outlet) and obstacles. The simulation visualizes velocity fields, pressure contours, and streamlines. Educational value includes understanding computational fluid dynamics, the LBM algorithm, and its advantages for parallel computing.
- **CN:** 该模拟使用格子玻尔兹曼方法 (LBM) 求解流体流动——直接求解纳维-斯托克斯方程的替代方法。离散玻尔兹曼方程 fᵢ(x + cᵢΔt, t + Δt) = fᵢ(x,t) − [fᵢ(x,t) − fᵢ^(eq)(x,t)]/τ 控制粒子分布演化。用户可设置边界条件（壁面、入口、出口）和障碍物。模拟可视化速度场、压力云图和流线。教育价值在于理解计算流体动力学、LBM 算法及其在并行计算中的优势。

### 132. [Shock Waves / 激波](https://blackmatrixblack.github.io/zero-physics/shock-waves/)
- **EN:** This simulation visualizes shock wave formation when an object moves faster than the speed of sound. The Rankine-Hugoniot conditions relate properties across the shock: ρ₁v₁ = ρ₂v₂, P₁ + ρ₁v₁² = P₂ + ρ₂v₂². Users can adjust the Mach number M = v/c and observe the shock cone angle μ = arcsin(1/M). The simulation shows pressure, density, and temperature jumps. Educational value includes understanding supersonic flow, sonic booms, and scramjet design.
- **CN:** 该模拟可视化物体超音速运动时的激波形成。兰金-于戈尼奥条件关联激波前后属性：ρ₁v₁ = ρ₂v₂，P₁ + ρ₁v₁² = P₂ + ρ₂v₂²。用户可调节马赫数 M = v/c，观察激波锥角 μ = arcsin(1/M)。模拟显示压力、密度和温度的跃变。教育价值在于理解超音速流、音爆和超燃冲压发动机设计。

### 133. [Vortex Dynamics / 涡旋动力学](https://blackmatrixblack.github.io/zero-physics/vortex-dynamics/)
- **EN:** This simulation models vortex dynamics in 2D inviscid flow. Vortices are point singularities with circulation Γ = ∮v·dℓ. The velocity field from a point vortex is v_θ = Γ/(2πr). Multiple vortices interact via Biot-Savart-like laws. Users can place vortices with adjustable strength and observe their motion. Vortex pairing, merging, and the formation of vortex dipoles are shown. Educational value includes understanding vorticity ω = ∇ × v, Kelvin's circulation theorem, and applications in aerodynamics and weather systems.
- **CN:** 该模拟模拟二维无黏流中的涡旋动力学。涡旋是具有环量 Γ = ∮v·dℓ 的点奇点。点涡的速度场为 v_θ = Γ/(2πr)。多个涡旋通过类毕奥-萨伐尔定律相互作用。用户可放置具有可调强度的涡旋并观察其运动。涡旋配对、合并和涡偶极子的形成被展示。教育价值在于理解涡量 ω = ∇ × v、开尔文环量定理以及在空气动力学和天气系统中的应用。

---

# 8. Chaos & Nonlinear / 混沌与非线性

### 134. [Chaotic Pendulum / 混沌摆](https://blackmatrixblack.github.io/zero-physics/chaotic-pendulum/)
- **EN:** This simulation demonstrates a parametrically driven chaotic pendulum. The equation of motion: θ̈ + γθ̇ + (ω₀² + f·cos(ω_d·t))sinθ = 0. Small changes in initial conditions lead to exponentially diverging trajectories — sensitive dependence on initial conditions (butterfly effect). Users can adjust drive amplitude and frequency. The Poincaré section and Lyapunov exponent are computed. Educational value includes understanding chaos theory, strange attractors, and the transition from regular to chaotic motion.
- **CN:** 该模拟演示参数驱动的混沌摆。运动方程：θ̈ + γθ̇ + (ω₀² + f·cos(ω_d·t))sinθ = 0。初始条件的微小变化导致轨迹指数发散——对初始条件的敏感依赖性（蝴蝶效应）。用户可调节驱动振幅和频率。庞加莱截面和李雅普诺夫指数被计算。教育价值在于理解混沌理论、奇怪吸引子以及从规则到混沌运动的转变。

### 135. [Coupled Oscillators / 耦合振子](https://blackmatrixblack.github.io/zero-physics/coupled-oscillators/)
- **EN:** This simulation models coupled harmonic oscillators. Two masses connected by springs exhibit normal modes: in-phase (ω₁ = √(k/m)) and out-of-phase (ω₂ = √((k+2K)/m)) where K is the coupling spring constant. Energy beats between oscillators are shown. Users can adjust masses, spring constants, and coupling strength. With many oscillators, wave propagation and dispersion emerge. Educational value includes understanding mode splitting, avoided crossings, and synchronization phenomena in nature.
- **CN:** 该模拟模拟耦合谐振子。弹簧连接的两个质量展现简正模：同相 (ω₁ = √(k/m)) 和反相 (ω₂ = √((k+2K)/m))，K 为耦合弹簧常数。振子间的能量拍频被展示。用户可调节质量、弹簧常数和耦合强度。多个振子时出现波传播和色散。教育价值在于理解模式分裂、避免交叉以及自然界中的同步现象。

### 136. [Damped Driven Oscillator / 阻尼受迫振子](https://blackmatrixblack.github.io/zero-physics/damped-driven-oscillator/)
- **EN:** This simulation models a damped, driven harmonic oscillator: ẍ + 2βẋ + ω₀²x = (F₀/m)cos(ωt). The steady-state amplitude A(ω) = (F₀/m)/√((ω₀² − ω²)² + 4β²ω²) shows resonance at ω_r = √(ω₀² − 2β²). Phase lag φ(ω) = arctan(2βω/(ω₀² − ω²)). Users can adjust driving frequency, damping, and force amplitude. The Q factor Q = ω₀/(2β) measures resonance sharpness. Educational value includes understanding resonance, phase response, and applications in vibration isolation and circuit design.
- **CN:** 该模拟模拟阻尼受迫谐振子：ẍ + 2βẋ + ω₀²x = (F₀/m)cos(ωt)。稳态振幅 A(ω) = (F₀/m)/√((ω₀² − ω²)² + 4β²ω²) 在 ω_r = √(ω₀² − 2β²) 处共振。相位滞后 φ(ω) = arctan(2βω/(ω₀² − ω²))。用户可调节驱动频率、阻尼和力振幅。品质因数 Q = ω₀/(2β) 衡量共振尖锐度。教育价值在于理解共振、相位响应以及在隔振和电路设计中的应用。

### 137. [Double Pendulum / 双摆](https://blackmatrixblack.github.io/zero-physics/double-pendulum/)
- **EN:** This simulation visualizes the chaotic double pendulum — two pendulums connected end-to-end. The Lagrangian formulation gives coupled equations of motion. For small amplitudes, motion is quasiperiodic; for large amplitudes, it becomes chaotic with extreme sensitivity to initial conditions. The phase space trajectory is plotted. Users can adjust masses, lengths, and initial angles. The conservation of total energy is verified. Educational value includes understanding the transition from regular to chaotic motion in Hamiltonian systems.
- **CN:** 该模拟可视化混沌双摆——首尾相连的两个摆。拉格朗日形式导出耦合运动方程。小振幅时为准周期运动；大振幅时变为混沌，对初始条件极度敏感。相空间轨迹被绘制。用户可调节质量、摆长和初始角度。总能量守恒被验证。教育价值在于理解哈密顿系统中从规则到混沌运动的转变。

### 138. [Duffing Oscillator / 达芬振子](https://blackmatrixblack.github.io/zero-physics/duffing-oscillator/)
- **EN:** This simulation models the Duffing oscillator: ẍ + δẋ + αx + βx³ = γcos(ωt). The nonlinear cubic term βx³ creates rich dynamics: multiple stable states (bistability), hysteresis, period-doubling bifurcations, and chaos. Users can adjust parameters α (linear stiffness), β (nonlinearity), δ (damping), γ (drive amplitude), and ω (drive frequency). The bifurcation diagram and frequency response curve are shown. Educational value includes understanding nonlinear resonance, jump phenomenon, and routes to chaos.
- **CN:** 该模拟模拟达芬振子：ẍ + δẋ + αx + βx³ = γcos(ωt)。非线性立方项 βx³ 产生丰富动力学：多稳态（双稳态）、迟滞、倍周期分岔和混沌。用户可调节参数 α（线性刚度）、β（非线性）、δ（阻尼）、γ（驱动振幅）和 ω（驱动频率）。分岔图和频率响应曲线被展示。教育价值在于理解非线性共振、跳跃现象和通往混沌的道路。

### 139. [Henon Map / 埃农映射](https://blackmatrixblack.github.io/zero-physics/henon-map/)
- **EN:** This simulation visualizes the Hénon map: xₙ₊₁ = 1 − axₙ² + yₙ, yₙ₊₁ = bxₙ. This simple 2D map produces a strange attractor for a = 1.4, b = 0.3. Users can adjust parameters a and b, observing the transition from periodic orbits to chaotic attractors. The fractal structure of the attractor is visible under magnification. The Lyapunov exponent is computed to quantify chaos. Educational value includes understanding discrete dynamical systems, strange attractors, and fractal geometry in chaos theory.
- **CN:** 该模拟可视化埃农映射：xₙ₊₁ = 1 − axₙ² + yₙ，yₙ₊₁ = bxₙ。这个简单的二维映射在 a = 1.4、b = 0.3 时产生奇怪吸引子。用户可调节参数 a 和 b，观察从周期轨道到混沌吸引子的转变。放大可见吸引子的分形结构。李雅普诺夫指数被计算以量化混沌。教育价值在于理解离散动力系统、奇怪吸引子和混沌理论中的分形几何。

### 140. [Logistic Map / 逻辑斯蒂映射](https://blackmatrixblack.github.io/zero-physics/logistic-map/)
- **EN:** This simulation visualizes the logistic map: xₙ₊₁ = rxₙ(1 − xₙ), a classic model for population dynamics. As r increases from 0 to 4, the system undergoes period-doubling bifurcations: fixed point → 2-cycle → 4-cycle → ... → chaos at r ≈ 3.57. The bifurcation diagram shows the entire route to chaos. Feigenbaum constants δ = 4.669... (period-doubling scaling) and α = 2.502... (universal) are demonstrated. Educational value includes understanding universality in chaos and applications in ecology.
- **CN:** 该模拟可视化逻辑斯蒂映射：xₙ₊₁ = rxₙ(1 − xₙ)，种群动态的经典模型。随 r 从 0 增加到 4，系统经历倍周期分岔：不动点 → 2-周期 → 4-周期 → ... → 在 r ≈ 3.57 处进入混沌。分岔图展示通往混沌的完整路径。费根鲍姆常数 δ = 4.669...（倍周期标度）和 α = 2.502...（普适性）被演示。教育价值在于理解混沌中的普适性以及在生态学中的应用。

### 141. [Lorenz Attractor / 洛伦兹吸引子](https://blackmatrixblack.github.io/zero-physics/lorenz-attractor/)
- **EN:** This simulation visualizes the Lorenz attractor from the Lorenz equations: dx/dt = σ(y − x), dy/dt = x(ρ − z) − y, dz/dt = xy − βz, derived from atmospheric convection. For σ = 10, ρ = 28, β = 8/3, the system exhibits the iconic butterfly-shaped strange attractor. Users can adjust parameters and observe trajectories. The sensitive dependence on initial conditions (butterfly effect) is demonstrated. Educational value includes understanding deterministic chaos, strange attractors, and the Lorenz system's role in weather prediction.
- **CN:** 该模拟可视化洛伦兹方程导出的洛伦兹吸引子：dx/dt = σ(y − x)，dy/dt = x(ρ − z) − y，dz/dt = xy − βz，来自大气对流模型。在 σ = 10、ρ = 28、β = 8/3 时，系统呈现标志性的蝴蝶形奇怪吸引子。用户可调节参数并观察轨迹。对初始条件的敏感依赖性（蝴蝶效应）被演示。教育价值在于理解确定性混沌、奇怪吸引子以及洛伦兹系统在天气预报中的作用。

### 142. [Three-Body / 三体问题](https://blackmatrixblack.github.io/zero-physics/three-body/)
- **EN:** This simulation models the gravitational three-body problem — three masses interacting via Newtonian gravity: F_ij = Gmᵢmⱼ/r_ij². Most initial conditions lead to chaotic trajectories with no closed-form solution. Users can place three bodies with adjustable masses, positions, and velocities. Special solutions (figure-8 orbit, Lagrange points, Euler's collinear solution) are available as presets. The simulation uses numerical integration. Educational value includes understanding chaotic dynamics in celestial mechanics and the restricted three-body problem.
- **CN:** 该模拟模拟引力三体问题——三个质量通过牛顿引力相互作用：F_ij = Gmᵢmⱼ/r_ij²。大多数初始条件导致混沌轨迹，没有闭式解。用户可放置三个天体并调节质量、位置和速度。特殊解（8 字形轨道、拉格朗日点、欧拉共线解）以预设形式提供。模拟使用数值积分。教育价值在于理解天体力学中的混沌动力学和限制性三体问题。

---

# 9. Condensed Matter / 凝聚态物理

### 143. [Ising Model / 伊辛模型](https://blackmatrixblack.github.io/zero-physics/ising-model/)
- **EN:** This simulation visualizes the 2D Ising model of ferromagnetism. Spins sᵢ = ±1 on a lattice interact via Hamiltonian H = −J∑⟨i,j⟩sᵢsⱼ − B∑sᵢ. The Metropolis Monte Carlo algorithm simulates thermal evolution. At high T, spins are random (paramagnetic); below critical T_c, spontaneous magnetization occurs. The phase transition is second-order. Users can adjust temperature J/k_BT and external field B. Magnetization M = ⟨Σsᵢ⟩/N and susceptibility χ = dM/dB are computed. Educational value includes understanding phase transitions, critical phenomena, and universality.
- **CN:** 该模拟可视化二维伊辛模型——铁磁性的统计力学模型。自旋 sᵢ = ±1 在晶格上通过哈密顿量 H = −J∑⟨i,j⟩sᵢsⱼ − B∑sᵢ 相互作用。梅特罗波利斯蒙特卡洛算法模拟热演化。高温下自旋随机（顺磁）；低于临界 T_c 时自发磁化。相变为二级。用户可调节温度 J/k_BT 和外场 B。磁化强度 M = ⟨Σsᵢ⟩/N 和磁化率 χ = dM/dB 被计算。教育价值在于理解相变、临界现象和普适性。

### 144. [Percolation / 逾渗](https://blackmatrixblack.github.io/zero-physics/percolation/)
- **EN:** This simulation models percolation — the formation of connected clusters in a random lattice. Each site (or bond) is occupied with probability p. At the percolation threshold p_c, a spanning cluster connects opposite sides. For 2D square lattice, p_c ≈ 0.5927 (site percolation). Users can adjust p and observe cluster formation. Cluster size distribution, correlation length ξ ∝ |p − p_c|^(−ν), and fractal dimension D_f are visualized. Educational value includes understanding critical phenomena, fractal geometry, and applications in porous media, forest fires, and epidemics.
- **CN:** 该模拟模拟逾渗——随机晶格中连通簇的形成。每个位点（或键）以概率 p 被占据。在逾渗阈值 p_c 处，跨越簇连接对侧。二维正方晶格 p_c ≈ 0.5927（位点逾渗）。用户可调节 p 并观察簇形成。簇大小分布、关联长度 ξ ∝ |p − p_c|^(−ν) 和分形维数 D_f 被可视化。教育价值在于理解临界现象、分形几何以及在多孔介质、森林火灾和流行病中的应用。

---

# 10. Nuclear & Particle / 核物理与粒子物理

### 145. [Chain Reaction / 链式反应](https://blackmatrixblack.github.io/zero-physics/chain-reaction/)
- **EN:** This simulation models nuclear chain reaction: a neutron induces fission, releasing more neutrons that cause further fissions. The multiplication factor k = N₁/N₀ determines behavior: k < 1 (subcritical, dies out), k = 1 (critical, steady), k > 1 (supercritical, exponential growth). Users can adjust the number of neutrons per fission, probability of capture, and geometry. Educational value includes understanding nuclear reactor control, critical mass, and the physics behind nuclear power and atomic weapons.
- **CN:** 该模拟模拟核链式反应：中子引发裂变，释放更多中子导致进一步裂变。倍增因子 k = N₁/N₀ 决定行为：k < 1（次临界，衰减）、k = 1（临界，稳定）、k > 1（超临界，指数增长）。用户可调节每次裂变中子数、俘获概率和几何形状。教育价值在于理解核反应堆控制、临界质量以及核能和原子武器背后的物理。

### 146. [Cloud Chamber / 云室](https://blackmatrixblack.github.io/zero-physics/cloud-chamber/)
- **EN:** This simulation visualizes particle tracks in a cloud chamber. Charged particles ionize supersaturated vapor, leaving visible condensation trails. Different particles leave distinct tracks: α-particles (short, thick), β-particles (long, thin, curved), muons (long, straight). Users can introduce various radioactive sources and observe track characteristics. Track curvature in a magnetic field indicates charge sign and momentum. Educational value includes understanding particle detection, the Lorentz force, and identifying particles by their tracks.
- **CN:** 该模拟可视化云室中的粒子径迹。带电粒子电离过饱和蒸气，留下可见的凝结径迹。不同粒子留下不同的径迹：α 粒子（短而粗）、β 粒子（长而细，弯曲）、μ 子（长而直）。用户可引入不同放射源并观察径迹特征。磁场中的径迹曲率指示电荷符号和动量。教育价值在于理解粒子探测、洛伦兹力以及通过径迹识别粒子。

### 147. [Geiger Counter / 盖革计数器](https://blackmatrixblack.github.io/zero-physics/geiger-counter/)
- **EN:** This simulation models a Geiger-Müller counter for detecting ionizing radiation. Each detected particle produces an electrical pulse, counted as a \"click.\" The count rate follows Poisson statistics: P(n) = (μⁿ/n!)·e^(−μ) where μ = r·Δt is the expected count. Users can adjust source distance, shielding, and measurement time. The inverse-square law I ∝ 1/r² is demonstrated. Dead time effects and the plateau region of GM tube operation are shown. Educational value includes understanding radiation detection, statistical fluctuations, and radiation safety.
- **CN:** 该模拟模拟用于探测电离辐射的盖革-米勒计数器。每个探测到的粒子产生电脉冲，计为一次\"咔嗒\"。计数率遵循泊松统计：P(n) = (μⁿ/n!)·e^(−μ)，其中 μ = r·Δt 为期望计数。用户可调节源距离、屏蔽和测量时间。反平方律 I ∝ 1/r² 被演示。死时间效应和 GM 管坪区被展示。教育价值在于理解辐射探测、统计涨落和辐射安全。

### 148. [Nuclear Decay Chain / 核衰变链](https://blackmatrixblack.github.io/zero-physics/nuclear-decay-chain/)
- **EN:** This simulation models radioactive decay chains (e.g., uranium-238 series). Each isotope decays with characteristic half-life t₁/₂: N(t) = N₀·2^(−t/t₁/₂) = N₀·e^(−λt) where λ = ln2/t₁/₂. Secular equilibrium occurs when parent and daughter decay rates equalize. Users can select different decay chains and observe the changing composition over time. Bateman equations for multi-step decay are solved numerically. Educational value includes understanding radioactive dating (carbon-14, uranium-lead) and nuclear waste management.
- **CN:** 该模拟模拟放射性衰变链（如铀-238 系）。每个同位素具有特征半衰期 t₁/₂ 衰变：N(t) = N₀·2^(−t/t₁/₂) = N₀·e^(−λt)，λ = ln2/t₁/₂。当母体和子体衰变率相等时达到长期平衡。用户可选择不同衰变链并观察组成随时间变化。多步衰变的贝特曼方程被数值求解。教育价值在于理解放射性定年（碳-14、铀-铅）和核废料管理。

### 149. [Particle Detector / 粒子探测器](https://blackmatrixblack.github.io/zero-physics/particle-detector/)
- **EN:** This simulation models a modern particle detector (like those at CERN/LHC). Charged particle tracks are reconstructed from detector hits. The transverse momentum p_T is measured from track curvature in a magnetic field (r = p_T/(qB)). Energy is measured in calorimeters. Users can generate different particle events and observe detector responses. The invariant mass M = √((ΣEᵢ)² − (Σp⃗ᵢ)²) of decaying particles is reconstructed. Educational value includes understanding experimental particle physics and how detectors reveal fundamental particles.
- **CN:** 该模拟模拟现代粒子探测器（如 CERN/LHC 的探测器）。带电粒子径迹从探测器击中点重建。横动量 p_T 从磁场中的径迹曲率测量（r = p_T/(qB)）。能量在量能器中测量。用户可生成不同粒子事件并观察探测器响应。衰变粒子的不变质量 M = √((ΣEᵢ)² − (Σp⃗ᵢ)²) 被重建。教育价值在于理解实验粒子物理学以及探测器如何揭示基本粒子。

### 150. [Rutherford Scattering / 卢瑟福散射](https://blackmatrixblack.github.io/zero-physics/rutherford-scattering/)
- **EN:** This simulation models Rutherford scattering — alpha particles scattering from a gold foil nuclear target. The differential cross-section: dσ/dΩ = (Z₁Z₂e²/(16πε₀E))²·1/sin⁴(θ/2). Most alphas pass through, but a few scatter at large angles — demonstrating the compact nucleus. Users can adjust particle energy, nuclear charge, and impact parameter. The scattering angle distribution is plotted. Educational value includes understanding the discovery of the atomic nucleus, the Coulomb scattering formula, and the limits of classical scattering.
- **CN:** 该模拟模拟卢瑟福散射——α 粒子在金箔核靶上的散射。微分截面：dσ/dΩ = (Z₁Z₂e²/(16πε₀E))²·1/sin⁴(θ/2)。大多数 α 粒子穿过，但少数大角度散射——证明原子核的紧致性。用户可调节粒子能量、核电荷和碰撞参数。散射角分布被绘制。教育价值在于理解原子核的发现、库仑散射公式以及经典散射的局限性。

### 151. [Scanning Tunneling / 扫描隧道显微镜](https://blackmatrixblack.github.io/zero-physics/scanning-tunneling/)
- **EN:** This simulation models scanning tunneling microscopy (STM). A sharp metal tip scans a conductive surface, with tunneling current I ∝ V·e^(−2κd) where d is tip-surface distance and κ = √(2mφ)/ℏ (φ = work function). The current is extremely sensitive to distance — allowing atomic-scale resolution. Users can adjust bias voltage and tip height, observing current changes as the tip scans surface atoms. Educational value includes understanding quantum tunneling in a practical instrument and how STM images individual atoms.
- **CN:** 该模拟模拟扫描隧道显微镜 (STM)。尖锐金属尖端扫描导电表面，隧穿电流 I ∝ V·e^(−2κd)，其中 d 为尖端-表面距离，κ = √(2mφ)/ℏ（φ 为功函数）。电流对距离极度敏感——实现原子级分辨率。用户可调节偏压和尖端高度，观察尖端扫描表面原子时的电流变化。教育价值在于理解实用仪器中的量子隧穿以及 STM 如何对单个原子成像。

### 152. [Spark Discharge / 火花放电](https://blackmatrixblack.github.io/zero-physics/spark-discharge/)
- **EN:** This simulation models electrical breakdown in gases leading to spark discharge. Paschen's law gives breakdown voltage V_B = B·p·d/(ln(A·p·d) − ln(ln(1 + 1/γ))) where p is pressure, d gap distance. The simulation shows electron avalanche formation, streamer propagation, and spark channel formation. Users can adjust voltage, gap distance, and gas pressure. The transition from dark discharge to glow to arc is visualized. Educational value includes understanding plasma physics, lightning, and high-voltage insulation design.
- **CN:** 该模拟模拟气体中的电击穿导致火花放电。帕邢定律给出击穿电压 V_B = B·p·d/(ln(A·p·d) − ln(ln(1 + 1/γ)))，其中 p 为压力，d 为间隙距离。模拟显示电子雪崩形成、流注传播和火花通道形成。用户可调节电压、间隙距离和气体压力。从暗放电到辉光到电弧的转变被可视化。教育价值在于理解等离子体物理、闪电和高压绝缘设计。

---

# 11. Astrophysics / 天体物理

### 153. [Gravitational Lensing / 引力透镜](https://blackmatrixblack.github.io/zero-physics/gravitational-lensing/)
- **EN:** This simulation visualizes gravitational lensing — light deflection by massive objects. The Einstein angle θ_E = √(4GM/(c²)·(D_LS/(D_L·D_S))) determines the image separation. Users can place a lens (galaxy, black hole) between the source and observer. Strong lensing produces Einstein rings and multiple images. Weak lensing distorts background galaxy shapes. Microlensing causes temporary brightening. Educational value includes understanding tests of general relativity, dark matter mapping, and exoplanet detection.
- **CN:** 该模拟可视化引力透镜——大质量物体的光偏折。爱因斯坦角 θ_E = √(4GM/(c²)·(D_LS/(D_L·D_S))) 决定像分离。用户可在光源和观察者之间放置透镜（星系、黑洞）。强引力透镜产生爱因斯坦环和多像。弱引力透镜扭曲背景星系形状。微引力透镜导致暂时增亮。教育价值在于理解广义相对论的检验、暗物质测绘和系外行星探测。

### 154. [Gravitational Waves / 引力波](https://blackmatrixblack.github.io/zero-physics/gravitational-waves/)
- **EN:** This simulation visualizes gravitational waves — ripples in spacetime predicted by general relativity. The + and × polarizations stretch and squeeze space perpendicular to propagation. Users can observe a binary system (two black holes/neutron stars) inspiraling and merging. The wave amplitude h(t) and frequency evolve as the chirp signal. The final ringdown is shown. Educational value includes understanding LIGO detection principles, the information carried by gravitational waves about compact objects, and tests of strong-field gravity.
- **CN:** 该模拟可视化引力波——广义相对论预测的时空涟漪。+ 和 × 偏振垂直拉伸和挤压空间。用户可观察双星系统（两个黑洞/中子星）旋进并合。波振幅 h(t) 和频率演化呈现啁啾信号。最终衰荡被展示。教育价值在于理解 LIGO 探测原理、引力波携带的致密天体信息以及强场引力的检验。

### 155. [Hubble Expansion / 哈勃膨胀](https://blackmatrixblack.github.io/zero-physics/hubble-expansion/)
- **EN:** This simulation demonstrates the expansion of the universe. Hubble's law: v = H₀·d, where H₀ ≈ 70 km/s/Mpc. The scale factor a(t) evolves according to the Friedmann equations: (ȧ/a)² = (8πG/3)ρ − kc²/a² + Λc²/3. Users can adjust parameters (matter density Ω_m, dark energy Ω_Λ, curvature Ω_k) and observe the expansion history. The simulation shows galaxies receding, with redshift z = λ_obs/λ_em − 1. Educational value includes understanding the Big Bang, dark energy, and the fate of the universe.
- **CN:** 该模拟演示宇宙膨胀。哈勃定律：v = H₀·d，H₀ ≈ 70 km/s/Mpc。尺度因子 a(t) 按弗里德曼方程演化：(ȧ/a)² = (8πG/3)ρ − kc²/a² + Λc²/3。用户可调节参数（物质密度 Ω_m、暗能量 Ω_Λ、曲率 Ω_k）并观察膨胀历史。模拟显示星系退行，红移 z = λ_obs/λ_em − 1。教育价值在于理解大爆炸、暗能量和宇宙的命运。

### 156. [Kepler Orbit / 开普勒轨道](https://blackmatrixblack.github.io/zero-physics/kepler-orbit/)
- **EN:** This simulation models Keplerian orbits under Newtonian gravity. Kepler's laws: (1) elliptical orbits with Sun at one focus, (2) equal areas in equal times (dA/dt = L/(2m) = constant), (3) T² ∝ a³. Users can adjust orbital parameters (semi-major axis a, eccentricity e, inclination) and observe the orbit in 3D. Orbital energy E = −GMm/(2a) and angular momentum L are displayed. Perturbations from a second planet show orbital precession. Educational value includes understanding the foundation of celestial mechanics.
- **CN:** 该模拟模拟牛顿引力下的开普勒轨道。开普勒定律：(1) 太阳位于椭圆轨道一个焦点，(2) 等面积时间 (dA/dt = L/(2m) = 常数)，(3) T² ∝ a³。用户可调节轨道参数（半长轴 a、偏心率 e、倾角）并观察 3D 轨道。轨道能量 E = −GMm/(2a) 和角动量 L 被显示。第二颗行星的扰动展示轨道进动。教育价值在于理解天体力学的基础。

### 157. [N-Body Gravity / N体引力](https://blackmatrixblack.github.io/zero-physics/nbody-gravity/)
- **EN:** This simulation models gravitational dynamics of N-body systems (star clusters, galaxies). Each body accelerates as aᵢ = Σⱼ≠ᵢ Gmⱼ/|rᵢ−rⱼ|³·(rⱼ−rᵢ). The simulation uses numerical integration (leapfrog/Verlet) for energy conservation. Users can place multiple bodies with initial velocities and observe structure formation: clumping, tidal streams, and core collapse. The virial theorem 2⟨KE⟩ + ⟨PE⟩ = 0 for a stable system is verified. Educational value includes understanding galaxy formation, dark matter halos, and computational astrophysics.
- **CN:** 该模拟模拟 N 体系统的引力动力学（星团、星系）。每个天体加速度为 aᵢ = Σⱼ≠ᵢ Gmⱼ/|rᵢ−rⱼ|³·(rⱼ−rᵢ)。模拟使用数值积分（蛙跳/Verlet）保证能量守恒。用户可放置多个天体并赋予初速度，观察结构形成：聚集、潮汐流和核心坍缩。位力定理 2⟨KE⟩ + ⟨PE⟩ = 0 对于稳定系统被验证。教育价值在于理解星系形成、暗物质晕和计算天体物理学。

---

# 12. Computational / 计算物理

### 158. [Brownian Motion / 布朗运动](https://blackmatrixblack.github.io/zero-physics/brownian-motion/)
- **EN:** This simulation models Brownian motion — the random movement of particles suspended in a fluid. The Langevin equation m·dv/dt = −γv + √(2γk_BT)·ξ(t) governs motion, where ξ(t) is white noise. The mean squared displacement ⟨r²⟩ = 2d·Dt (d dimensions) with diffusion coefficient D = k_BT/(6πηr) from Stokes-Einstein relation. Users can adjust temperature, viscosity, and particle size. The displacement distribution is Gaussian. Educational value includes understanding the atomic nature of matter, stochastic processes, and Einstein's explanation.
- **CN:** 该模拟模拟布朗运动——悬浮在流体中粒子的随机运动。朗之万方程 m·dv/dt = −γv + √(2γk_BT)·ξ(t) 控制运动，ξ(t) 为白噪声。均方位移 ⟨r²⟩ = 2d·Dt（d 维），扩散系数 D = k_BT/(6πηr)（斯托克斯-爱因斯坦关系）。用户可调节温度、黏度和粒子大小。位移分布为高斯型。教育价值在于理解物质的原子本质、随机过程和爱因斯坦的解释。

### 159. [Diffusion Equation / 扩散方程](https://blackmatrixblack.github.io/zero-physics/diffusion-equation/)
- **EN:** This simulation solves the diffusion equation ∂c/∂t = D·∇²c numerically. Fick's first law J = −D·∇c relates flux to concentration gradient. Users can set initial concentration distributions and boundary conditions. The simulation shows concentration evolution in 1D and 2D. The analytical solution for a point source: c(r,t) = (N/(4πDt)^(d/2))·exp(−r²/(4Dt)). Educational value includes understanding transport phenomena, random walks as the microscopic basis of diffusion, and applications in heat transfer and mass transport.
- **CN:** 该模拟数值求解扩散方程 ∂c/∂t = D·∇²c。菲克第一定律 J = −D·∇c 关联通量与浓度梯度。用户可设置初始浓度分布和边界条件。模拟显示 1D 和 2D 中的浓度演化。点源的解析解：c(r,t) = (N/(4πDt)^(d/2))·exp(−r²/(4Dt))。教育价值在于理解输运现象、随机行走作为扩散的微观基础，以及在传热和传质中的应用。

### 160. [Plasma Oscillation / 等离子体振荡](https://blackmatrixblack.github.io/zero-physics/plasma-oscillation/)
- **EN:** This simulation visualizes plasma oscillations — collective oscillations of electrons against a fixed ion background. The electron plasma frequency ω_p = √(n₀e²/(ε₀m_e)) determines the oscillation rate. The simulation uses particle-in-cell (PIC) methods to track electron motions. Users can perturb the electron density and observe Langmuir wave propagation. The dispersion relation ω² = ω_p² + 3k²v_th² (Bohm-Gross) is demonstrated. Educational value includes understanding plasma physics, waves in ionized media, and applications in fusion and space physics.
- **CN:** 该模拟可视化等离子体振荡——电子相对于固定离子背景的集体振荡。电子等离子体频率 ω_p = √(n₀e²/(ε₀m_e)) 决定振荡速率。模拟使用粒子网格 (PIC) 方法追踪电子运动。用户可扰动电子密度并观察朗缪尔波传播。色散关系 ω² = ω_p² + 3k²v_th²（玻姆-格罗斯）被演示。教育价值在于理解等离子体物理、电离介质中的波以及在聚变和空间物理中的应用。

### 161. [Random Walk / 随机行走](https://blackmatrixblack.github.io/zero-physics/random-walk/)
- **EN:** This simulation models random walks in 2D and 3D. After N steps of length ℓ, the root-mean-square displacement is r_RMS = ℓ√N. The position distribution becomes Gaussian by the central limit theorem. Users can adjust step length, step number, and number of walkers. The recurrence probability (P = 1 for 1D and 2D, P < 1 for 3D) is demonstrated. Applications include polymer physics (ideal chain R_g ∝ N^(1/2)), stock market models, and animal foraging patterns.
- **CN:** 该模拟模拟 2D 和 3D 随机行走。经过 N 步（步长 ℓ）后，均方根位移为 r_RMS = ℓ√N。根据中心极限定理，位置分布变为高斯型。用户可调节步长、步数和行走者数量。返回概率（1D 和 2D 中 P = 1，3D 中 P < 1）被演示。应用包括高分子物理（理想链 R_g ∝ N^(1/2)）、股票市场模型和动物觅食模式。

---

# 13. Circuits / 电路

### 162. [LC Oscillator / LC振荡器](https://blackmatrixblack.github.io/zero-physics/lc-oscillator/)
- **EN:** This simulation models an LC circuit — an inductor and capacitor connected together. The circuit oscillates at ω₀ = 1/√(LC) with energy alternately stored in the capacitor (U_E = ½CV²) and inductor (U_B = ½LI²). The differential equation is identical to the harmonic oscillator: L·d²q/dt² + q/C = 0. Users can adjust L and C values and observe the sinusoidal voltage/current waveforms. Energy bar charts show the oscillation between electric and magnetic energy. Educational value includes understanding the analogy between electrical and mechanical oscillations.
- **CN:** 该模拟模拟 LC 电路——电感和电容连接。电路以 ω₀ = 1/√(LC) 振荡，能量交替存储在电容器 (U_E = ½CV²) 和电感器 (U_B = ½LI²) 中。微分方程与谐振子相同：L·d²q/dt² + q/C = 0。用户可调节 L 和 C 值，观察正弦电压/电流波形。能量条形图展示电能和磁能之间的振荡。教育价值在于理解电振荡和机械振荡之间的类比。

### 163. [LR Circuit / LR电路](https://blackmatrixblack.github.io/zero-physics/lr-circuit/)
- **EN:** This simulation models an LR circuit (inductor and resistor in series with a voltage source). The current growth follows I(t) = (V/R)(1 − e^(−t/τ)) with time constant τ = L/R. The decay (when source removed) follows I(t) = I₀·e^(−t/τ). Users can adjust R, L, and V. The voltage across each component is shown. The energy stored in the inductor U = ½LI² is displayed. Educational value includes understanding transient response, the inductor's opposition to current change, and the meaning of the time constant.
- **CN:** 该模拟模拟 LR 电路（电感与电阻串联，连接电压源）。电流增长遵循 I(t) = (V/R)(1 − e^(−t/τ))，时间常数 τ = L/R。衰减（移除电源后）遵循 I(t) = I₀·e^(−t/τ)。用户可调节 R、L 和 V。各元件电压被显示。电感存储能量 U = ½LI² 被展示。教育价值在于理解瞬态响应、电感对电流变化的阻碍以及时间常数的含义。

### 164. [RC Circuit / RC电路](https://blackmatrixblack.github.io/zero-physics/rc-circuit/)
- **EN:** This simulation models an RC circuit (resistor and capacitor in series). The capacitor charges as V_C(t) = V(1 − e^(−t/RC)) and discharges as V_C(t) = V₀·e^(−t/RC). The time constant τ = RC determines the charging/discharging rate. Users can adjust R, C, and V. The current I(t) = (V/R)·e^(−t/RC) is shown. The energy stored in the capacitor U = ½CV² is displayed. Educational value includes understanding exponential charging/discharging, the time constant concept, and applications in filters and timing circuits.
- **CN:** 该模拟模拟 RC 电路（电阻与电容串联）。电容充电 V_C(t) = V(1 − e^(−t/RC))，放电 V_C(t) = V₀·e^(−t/RC)。时间常数 τ = RC 决定充放电速率。用户可调节 R、C 和 V。电流 I(t) = (V/R)·e^(−t/RC) 被显示。电容存储能量 U = ½CV² 被展示。教育价值在于理解指数充放电、时间常数概念以及在滤波器和定时电路中的应用。

### 165. [RC Filter / RC滤波器](https://blackmatrixblack.github.io/zero-physics/rc-filter/)
- **EN:** This simulation models RC filters — both low-pass and high-pass configurations. For low-pass: V_out/V_in = 1/√(1 + (ωRC)²) with cutoff f_c = 1/(2πRC). For high-pass: V_out/V_in = ωRC/√(1 + (ωRC)²). The Bode plot shows magnitude (dB) and phase vs. frequency. Users can adjust R, C, and input frequency. The 3 dB point at f_c is marked. The roll-off is −20 dB/decade. Educational value includes understanding frequency response, filter design, and the decibel scale.
- **CN:** 该模拟模拟 RC 滤波器——低通和高通配置。低通：V_out/V_in = 1/√(1 + (ωRC)²)，截止频率 f_c = 1/(2πRC)。高通：V_out/V_in = ωRC/√(1 + (ωRC)²)。波特图显示幅度 (dB) 和相位随频率变化。用户可调节 R、C 和输入频率。f_c 处的 3 dB 点被标记。滚降为 −20 dB/十倍频。教育价值在于理解频率响应、滤波器设计和分贝标度。

### 166. [RLC Circuit / RLC电路](https://blackmatrixblack.github.io/zero-physics/rlc-circuit/)
- **EN:** This simulation models a series RLC circuit. The differential equation: L·d²q/dt² + R·dq/dt + q/C = V(t). The circuit can be underdamped (R < 2√(L/C)), critically damped (R = 2√(L/C)), or overdamped (R > 2√(L/C)). At resonance ω₀ = 1/√(LC), impedance Z = R is minimum. The Q factor Q = (1/R)√(L/C). Users can adjust R, L, C, and driving frequency. The frequency response shows the resonance peak. Educational value includes understanding the most complete second-order circuit, damping regimes, and resonance.
- **CN:** 该模拟模拟串联 RLC 电路。微分方程：L·d²q/dt² + R·dq/dt + q/C = V(t)。电路可以是欠阻尼 (R < 2√(L/C))、临界阻尼 (R = 2√(L/C)) 或过阻尼 (R > 2√(L/C))。谐振频率 ω₀ = 1/√(LC)，阻抗 Z = R 最小。品质因数 Q = (1/R)√(L/C)。用户可调节 R、L、C 和驱动频率。频率响应展示共振峰。教育价值在于理解最完整的二阶电路、阻尼状态和共振。

### 167. [Wheatstone Bridge / 惠斯通电桥](https://blackmatrixblack.github.io/zero-physics/wheatstone-bridge/)
- **EN:** This entry repeats the Wheatstone bridge topic (see #43) with additional focus on sensor applications. The bridge measures unknown resistance via R_x = R₃·R₂/R₁ at balance. Strain gauges change resistance under deformation: ΔR/R = G·ε (gauge factor). Users can simulate temperature measurement with a thermistor and pressure measurement with a strain gauge bridge. The differential amplifier output V_out = V_ex·(ΔR/(4R)) for a quarter-bridge configuration. Educational value includes understanding sensor interfacing and precision measurement design.
- **CN:** 该条目重复惠斯通电桥主题（见第 43 条），但侧重于传感器应用。电桥在平衡时测量未知电阻 R_x = R₃·R₂/R₁。应变片电阻随变形变化：ΔR/R = G·ε（灵敏系数）。用户可模拟使用热敏电阻的温度测量和使用应变片桥路的压力测量。四分之一桥配置的差分放大器输出 V_out = V_ex·(ΔR/(4R))。教育价值在于理解传感器接口和精密测量设计。
