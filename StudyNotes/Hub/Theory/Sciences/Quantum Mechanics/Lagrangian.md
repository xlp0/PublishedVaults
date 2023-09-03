---
Aliases: Lagrangian Mechanics, Lagrangian
---

#Symmetry 

Lagrangian mechanics is a mathematical formalism that provides an alternative description of classical mechanics. It was developed by Italian-French mathematician Joseph-Louis Lagrange in the late 18th century. Unlike Newtonian mechanics, which is based on forces and accelerations, Lagrangian mechanics describes the motion of a system using generalized coordinates and a quantity called the Lagrangian.

In Newtonian mechanics, the motion of a system is determined by solving second-order differential equations derived from Newton's laws of motion. This approach requires knowledge of forces acting on each particle in the system. However, in Lagrangian mechanics, the focus is on finding a function called the Lagrangian that encapsulates all the dynamics of the system.

The Lagrangian is defined as the [[Subtraction|difference]] between kinetic energy (T) and potential energy (V) of a system:

L = T - V

The generalized coordinates are used to describe the configuration of a system instead of specifying positions and velocities for each individual particle. The Lagrangian then provides a single function that encodes all the information necessary to determine the equations of motion for the system.

To derive these equations, Lagrange's equations are employed. These equations express how different quantities related to each other through time derivatives and partial derivatives with respect to generalized coordinates. Solving these equations yields information about how the generalized coordinates evolve over time.

The relationship between Lagrangian mechanics and Hamiltonian mechanics is closely intertwined. Hamiltonian mechanics is another mathematical formalism developed by Irish mathematician William Rowan Hamilton in the 19th century. It provides an equivalent description of classical mechanics but uses different quantities known as generalized momenta.

In Hamiltonian mechanics, instead of working with generalized coordinates, one works with generalized momenta (p_i), which are conjugate variables to generalized coordinates (q_i). These momenta are defined as partial derivatives of the Lagrangian with respect to velocities (v_i):

p_i = ∂L/∂v_i

The Hamiltonian (H) is then defined as the Legendre transformation of the Lagrangian:

H = ∑(p_i * v_i) - L

Hamilton's equations of motion are derived from the Hamiltonian, and they provide an alternative way to describe the dynamics of a system.

## Lagrangian and the Least Action Principle

The Lagrangian is a function in classical mechanics that plays a fundamental role in the formulation of the equations of motion. It is defined as the difference between the kinetic energy and potential energy of a system, and depends on the coordinates and velocities of the particles in the system.

[[Least Action Principle|The principle of least action]], also known as Hamilton's principle, states that the motion of a system between two points is such that the action integral is minimized. The action integral is defined as the integral of the Lagrangian over time, and represents a measure of how much a physical system deviates from its desired path.

To understand this principle, let's consider a simple example. Suppose we have a particle moving along a straight line under the influence of gravity. The Lagrangian for this system can be written as:

L = T - V

where T is the kinetic energy and V is the potential energy. In this case, T = (1/2)mv^2 and V = mgh, where m is mass, v is velocity, g is the acceleration due to gravity, and h is the height.

The action integral can be written as:

S = ∫ L dt

where S represents the total action over some interval of time.

According to the principle of least action, for any given path taken by the particle between two points A and B, there exists an actual path that minimizes S. In other words, out of all possible paths that connect A and B, nature chooses the one that minimizes the action.

To find this path mathematically, we use variations. We consider nearby paths and calculate their respective actions. By applying calculus variations techniques (Euler-Lagrange equations), we can find an equation called Euler-Lagrange equation which describes how particles move under certain forces or constraints.

Once we have obtained this equation for our specific system (in our example case), we can solve it to find the path of the particle that minimizes the action.

The Lagrangian and the principle of least action provide a powerful framework for understanding and predicting the motion of physical systems. By considering the difference between kinetic and potential energy and minimizing the action integral, we can derive equations of motion that accurately describe how particles move in a given system.


# Conclusion
In summary, Lagrangian mechanics provides a concise and elegant formalism for describing the motion of physical systems using generalized coordinates and a Lagrangian function. It complements Newtonian mechanics by offering an alternative approach to solving problems in classical mechanics. The key idea in Lagrangian mechanics is to define the motion of a system in terms of generalized coordinates, which are independent variables that fully describe the configuration of the system. These coordinates can be chosen to simplify the problem and eliminate unnecessary degrees of freedom.

The Lagrangian function is then defined as the difference between the kinetic and potential energies of the system. It encapsulates all relevant information about the system's dynamics and can be used to derive the equations of motion, known as Euler-Lagrange equations, through variational calculus.

One advantage of Lagrangian mechanics is its ability to handle systems with constraints. Constraints are conditions that restrict the motion of a system, such as fixed lengths or angles. By introducing appropriate constraint forces, Lagrangian mechanics can accurately describe the constrained motion without having to explicitly enforce these conditions.

Another benefit is its [[Symmetry|symmetry properties]]. The Lagrangian formalism naturally incorporates conservation laws, such as conservation of energy and momentum, through Noether's theorem. This allows for a deeper understanding of fundamental principles in physics.

Lagrangian mechanics also offers a more elegant description of rotational dynamics compared to Newtonian mechanics. By using appropriate generalized coordinates and taking into account rotational inertia, one can derive equations that directly relate angular velocities and torques.

Overall, Lagrangian mechanics provides a powerful tool for analyzing complex physical systems by simplifying their description and revealing fundamental principles. Its mathematical elegance and broad applicability make it an essential framework in classical mechanics and beyond.

# References

[[@physicswithelliotLagrangianHamiltonianMechanics2021]]

[[@fancymanifoldCanYouDerive2022]]