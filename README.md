# Air-standard-Cycle-using-python
**AIM:**

To write a python code that can solve an otto cycle and to plot a PV diagram and also to show the  the thermal efficiency of the engine.

**THEORY:**

An Otto cycle is an idealized thermodynamic cycle that describes the functioning of a typical spark ignition piston engine. The Otto cycle is a description of what happens to a mass of gas as it is subjected to changes of pressure, temperature, volume, addition of heat, and removal of heat. The mass of gas that is subjected to those changes is called the system. The system, in this case, is defined to be the fluid (gas) within the cylinder. By describing the changes that take place within the system, it will also describe in inverse, the system's effect on the environment.

Otto Cycle is a constant volume cycle on which petrol and gas engines work. The Otto cycle consists of 4 processes and are as follows.

![1](https://user-images.githubusercontent.com/104487026/179738232-f7f64e9c-9eba-44d5-a934-d89986410b2b.jpg)


Process 1-2: Reversible Adiabatic Compression or Isentropic Compression
Process 2-3: Constant Volume heat supply
Process 3-4: Reversible Adiabatic Expansion or Isentropic Expansion
Process 4-1: Constant Volume Heat Rejection



**Governing equation:**

Swept volume  (Vs) ,
![e1](https://user-images.githubusercontent.com/104487026/179738295-cade9ec2-41ce-436a-bd09-c7499419b96b.png)

clearance volume(Vc)
![e2](https://user-images.githubusercontent.com/104487026/179738354-70230d0f-6dad-4a50-aff0-e9e15f6873a3.png)
  
Volume trace,  
![e3](https://user-images.githubusercontent.com/104487026/179738386-12d2a687-e8b6-4514-92cb-cfd398479653.png)

Isentropic process equation,
![e4](https://user-images.githubusercontent.com/104487026/179738423-3f97eea3-8df7-4380-a6bb-cd8b4e263436.png)

combined gas equation,
![e5](https://user-images.githubusercontent.com/104487026/179738460-9488b0cf-5daf-4d77-902c-390977b53d57.png)

Thermal effiiciency of Otto cycle,
![e6](https://user-images.githubusercontent.com/104487026/179738488-315faf37-0bab-42f2-af85-10560b05f3df.png)

   

PROGRAM

INPUTS:

1. Engine geometric parameters;

          Bore diameter=0.1m

          Stroke length =0.1m

          Connecting rod length= 0.15m

          Compression ratio =12

2. Static variables at state point 1;

          pressure=101.325 kPa

          Temperature=500k

3.Static variables at state point 3;

           Temperature=2300k

4.Ratio of specific heat;

           gamma=1.4(for air)





OUTPUT:

![2](https://user-images.githubusercontent.com/104487026/179738603-1c68749d-9a0d-48ec-bd7b-0cebbff65e6d.png)
 

 Thermal efficiency of Otto cycle = 56.472%

 PV diagram:
![3](https://user-images.githubusercontent.com/104487026/179738632-8d335a81-d28e-4878-8961-ca0f4c75c1a0.png)

      

OBSERVATION:

      The PV diagram has been plotted using process equations and the thermal efficiency has been calculated. It can be observed that the efficiency varies inversely with the compression ratio.
