
ABSTRACT
 
This project involves design and implementation of a learning environment for an electrical lab in the topic of “Factor analysis for achieving high efficiency Solar Cells”. In the electrical lab we look into why we need higher efficiencies for solar cells, what are the theoretical limitations associated with solar cells, how to model a solar cell, how solar cell reflection coefficient, cell temperature, series/parallel resistances, shadow patters affect the solar cell efficiency with the help ofsimulations. The learning environment is built using MATLAB Live Scripts and MATLAB Simscape Simulink. The lab file can be shared easily using MATLAB Online platform where the users have the direct access to the materials or can be shared as a file. In that case, the users must have their own MATLAB software installed into the computer to access the lab material. And lab file is compatible across any OS and with any device even with mobile phones.
 
ACRONYMS  
 
OS – Operating System 
UI – User Interface 
PV – Photovoltaic
Voc – Open Circuit Voltage
Isc – Short Circuit Current

CHAPTER 1

INTRODUCTION

Solar energy plays a major role in the current global wave towards the renewable energy sources. As electrical engineering undergraduates, it is important that we have a better understanding in the field of renewable energy. This product is developed focused on giving a thorough knowledge to anyone specially university students who are interested in understanding the theories and practicality behind solar cell technology.

The need of higher solar cell efficiencies arises because yearly we receive 26,000 TW of power per year from the sun which is enough to power the whole planet over a year, but we only have been able to extract much less portion from the energy that we are receiving. With the current Solar PV Cell efficiencies, it is impossible to depend only on Solar power since the limitation of the land. 

Furthermore, this project is dedicated to improving the conventional learning methods in the universities that we see today for the benefit of both the university students and the lecturers. 
                                                                                                           
1.1	MOTIVATIONS

Motivations for the project are,
•	Current demand for method of conducting university academics including practical online due to COVID-19 pandemic.
•	Current demand of Solar Cell generated energy in renewable energy sector.
•	Continuous development in the field of Solar energy.

1.2	 OBJECTIVES AND SCOPE

This project is mainly focused on providing theoretical plus practical analysis on the factors affecting the solar cell efficiency and to provide learning environment for university academics including practical. Large portion of the university academics including practical can be developed using this method and, in this case, learning environment is developed focusing on the topic “Factor analysis for high efficiency Solar Cells”.
People will be influenced to engage in academics using this type of learning platforms as they recognize the benefits of using such platform.

1.3 METHODOLOGY 
 
1.3.1 Used Software Tools

	MATLAB Live Scripts
	MATLAB Simulink
	MATLAB Online

MATLAB Live Scripts renders all the content of the lab file. It handles the user inputs and all the outputs generated including outputs from simulations. To manipulate or to view the simulation models MATLAB Simulink is used. MATLAB Online is used to host the lab file online.

1.3.2 Lab Model
  
Above model describes the how the communication is happening among user and the different software tools when the lab file is running. User inputs are inserted through sliders, buttons. Then the user inputs are executed by MATLAB/ MATLAB Live. If the MATLAB Simulink is needed for the execution, input data is sent to the Simulink model, and it provides the simulation output to the Lab interface. MATLAB drive holds all required files for the Lab.

1.3.3 Solar Cell Model

Instead of a single diode solar cell model, two diode solar cell model is used for the simulations to represent a more practical cell model which is capable of modeling real life solar cells accurately. 

1.3.5 Process 

•	User (Student) may receive the live lab script as a MATLAB file which you can open from MATLAB software in your computer, or you may gain access to a MATLAB Online platform where you can directly interact with the lab.

•	After opening the lab file, user will have the access to the lab. User can interact with the MATLAB Simulink simulations through different controllers. In case the user is interested in interacting with the Simulation directly through Simulink software, he/she can open the simulation through the lab by clicking on the button “Open Model”.
 
•	Any user who is interacting with the lab file will have full access to all the resources including simulations in case they are interested in experimenting on the facts deeper. 


REFERENCES

[1]: https://www.researchgate.net/publication/239441364_Critical_Factors_that_Affecting_Efficiency_of_Solar_Cells
Furkan Dinçer, Mehmet EminMeral University of Yuzuncu Yil, Department of Electrical and Electronics Engineering, Van, Turkey. Received February 17th, 2010; revised May 7th, 2010; accepted May 8th; Critical Factors that Affecting Efficiency of Solar Cells. January 2010
Smart Grid and Renewable Energy 01(01):47-50. DOI: 10.4236/sgre.2010.11007 
[2]: https://sci-hub.do/10.1109/ICETEEEM.2012.6494522 
Dhass, A. D., Natarajan, E., & Ponnusamy, L. (2012). Influence of shunt resistance on the performance of solar photovoltaic cell. 2012   International Conference on Emerging Trends in Electrical Engineering and Energy Management (ICETEEEM).      DOI:10.1109/iceteeem.2012.6494522 
[3]: https://sci-hub.do/https://www.tandfonline.com/doi/abs/10.1080/01430750.2016.1181567
Abdulrahman Babiker Hussain, Abdelrahman S. Abdalla, Abdellahi Sidi Mukhtar, M. Elamin, R. Alammari & A. Iqbal (2016):      Modeling and Simulation of Single and Triple Junction Solar Cell Using MATLAB/SIMULINK, International Journal of Ambient   Energy, DOI:  10.1080/01430750.2016.1181567 
[4]: https://sci-hub.do/https://www.sciencedirect.com/science/article/pii/S2352484717302378 
Pendem, S. R., & Mikkili, S. (2018). Modeling, simulation and performance analysis of solar PV array configurations (Series, Series–  Parallel and Honey-Comb) to extract maximum power under Partial Shading Conditions. Energy Reports, 4, 274287.   DOI:10.1016/j.egyr.2018.03.003 
[5]: https://sci-hub.do/https://www.academia.edu/download/33409367/157-868-2-PB.pdf 
Tarak Salmi, Mounir Bouzguenda, Adel Gastli, Ahmed Masmoudi(2012): MATLAB/Simulink Based Modelling of Solar Photovoltaic Cell,   International Journal of Renewable Energy Research,Vol.2, No.2, 2012
[6]: https://www.coursera.org/learn/

