# SucroseHydrolysis
This repo includes a Python simulation of the hydrolysis reaction of sucrose into glucose and fructose with invertase enzyme.
Data from an experiment conducted on March, 19th in Middle East Technical University, Ankara is utilized.
The main purpose of this mini-project is to simulate the hydrolysis of sucrose with Python, and to determine the maximum reaction rate and the Michaelis Menten constant.

# Information about the Model & Assumptions
The hydrolysis reaction of sucrose follows Michaelis Menten Kinetics. The main kinetic equation for Michaelis-Menten is given by
                                  v_o = \frac{v_{\text{max}}[S]}{K_M + [S]}

# Main assumptions for this kinetic model include:
  - Steady State: The concentration of the enzyme-substrate complex [ES] remains constant over the course of the reaction. This implies that the rate of formation of [ES] is equal to the rate of its breakdown. 
  - The concentration of the substrate [S] is much greater than the concentration of the enzyme [E].
  - Equal amounts of glucose and fructose are produced during the reaction.
  - No by-products are formed during the reaction
  - The stoiciometric ratio between sucrose and glucose is 1:1
  - The initial reaction rate is equal to delta concentration / delta time

# Brief information about the reaction
  - At low substrate concentrations; ([S]≪Km​): The reaction rate is directly proportional to the substrate concentration & the reaction exhibits first-order kinetics.
  - At high substrate concentrations; ([S>>Km​): The enzyme is saturated with substrate, and the reaction rate approaches its maximum value, Vmax⁡​. Reaction rate is zeroth order. (v = vmax)
  - Initially, substrate concentration is maximum, then the substrate concentration starts to decrease as conversion increases.
  - Invertase specifically hydrolyzes the glycosidic bond in sucrose, converting it into glucose and fructose.
  - The reaction rate converges into a constant value after adequate amount of time regardless of the substrate concentration due to the active sites on the enzyme being fully occupied.

# In this python model, it is aimed to:
  - Calculate the initial reaction rates over time.

  - Use the UV-Vis absorbance data of glucose to find the concentration of glucose formed over time. 

  - Accurately determine 𝑉max⁡ and 𝐾𝑚​ from the data.

# And also to plot:
  - Michaelis-Menten Plot: Plot initial reaction rate (𝑣) versus substrate concentration ([𝑆]).
  - Lineweaver-Burk Plot: Plot 1/𝑣 versus 1/[𝑆] to linearize the Michaelis-Menten equation.
  - Reaction Rate vs. Time: Plot reaction rate data over time to observe the reaction kinetics. 
  - Concentration of Glucose & Sucrose vs. Time: Convert absorbance data to concentration and plot concentration versus time.






