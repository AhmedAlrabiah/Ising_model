Hi!


I finished this project on the 14th of April, 2022. The project was a mini & optional class project for the thermal and statistical physics course. 

Let us start! The project is a study of the Ising model of ferromagnets. Paramagnets are materials that get magnetized under the influence of an external magnetic field,
i.e. their magnetic dipoles respondonly to the external magnetic field but not to their neighboring dipoles, and once this field is removed they become not magnetized.
In real life, ideal paramagnets do not exist! There is always an interaction between neighboring dipols. In some materials there is some tendency of the neighboring 
dipols to align themselves parallel to each other, these materials are called ferromagnets. Meanwhile antiparallel alignment tendency materials are called antiferromagnets. 

Without loss of generality, let us focus on ferromagnets and the same treatment can be done for antiferromagnets. With raising the temperature, there will be random fluctuations that would 
decrease the overall magnetization of the ferromagnet. Decreasing the temperature will not make a significant change until reaching a specific temperature (called the Curie temperature) where
a sudden phase transition occurs and domains in the ferromagnet are observed. Notation in the code: N is the total number of atomic dipoles, s_i is the current state of the ith dipole with s_i = 1
means poiting up and s_i = -1 means pointing down.

The code would generate an animation:

https://github.com/user-attachments/assets/a8341fe9-1746-4111-b205-0fadbbd2b2d1

in which in each frame the temperature is decreased by a unit from 10.5 to 0.5 in some temperature units. We can see that at a certain point, the material suddenly magnetizes and that is the
Curie temperature.
