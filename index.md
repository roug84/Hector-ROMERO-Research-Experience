
***

# **PhD research**
## System identification using neural networks

Neural networks are powerful tools for modeling complex nonlinear systems when considering the plant as a black box. However, it is well known that they require a large number of neurons to deal with complex systems. Numerous neurons favour a better approximation but lead to a more complex model, and higher computational cost. To address this problem, in my thesis, I proposed a complete system identification methodology leading balanced accuracy, complexity and computational cost neural network-based models. Moreover, for the cases where training data contain outliers, I included a robust estimation approach.  

The main contributions presented in my thesis, are now published in five journal papers [[J1](http://dx.doi.org/10.1016/j.neucom.2012.08.013), [J2](http://dx.doi.org/10.1016/j.neucom.2015.04.022), [J3](http://dx.doi.org/10.1007/s00521-014-1716-8), [J4](http://dx.doi.org/10.1115/1.4032687)]:

In a first paper [[J1](http://dx.doi.org/10.1016/j.neucom.2012.08.013)], I proposed a dedicated neural network design and an original model reduction approach in order to improve the balance between complexity and accuracy of black box nonlinear system identification models. The proposed neural network design, based on a recurrent three-layer architecture, helps to reduce the number of parameters of the model after the training phase without any loss of estimation accuracy. The reduction procedure is developed in two steps. The first step consists in training the proposed architecture under two nonrestrictive assumptions. In the second step, the recurrent three-layer neural network is transformed into a representation of two layers with a significantly reduced number of parameters. These results were also presented in an international conference, [[C1](http://dx.doi.org/10.1109/CCCA.2012.6417884)]. 

In a second paper [[J2](http://dx.doi.org/10.1016/j.neucom.2015.04.022)] I focused on the improvement of the computational cost required to achieve the balanced simplicity-accuracy models presented in [[J1](http://dx.doi.org/10.1016/j.neucom.2012.08.013)]. More precisely, the improvement consists of a significantly computational cost reduction of the neural network-training phase. These results were also presented in a international conference, [[C2](http://dx.doi.org/10.1109/CCCA.2012.6417886)].

To demonstrate that the two assumptions, required to achieve the model complexity and computational cost reduction procedures, are not restrictive, I derived different model families [[J3](http://dx.doi.org/10.1007/s00521-014-1716-8)]. These models were used for identifying different dynamic systems. Results validate the interest of this complete system identification approach.

Finally, I proposed an estimation algorithm robust to outliers. Classically, the model's parameters minimize a L2-norm-based criterion. However, when using strongly corrupted data, namely outliers, the L2-norm-based estimation algorithms become ineffective. To ensure both, balance between simplicity and accuracy, and robustness to outliers, I proposed a robust estimation algorithm [J4], based on the minimization of the Huberian function, for training the neuromodels presented in [[J1](http://dx.doi.org/10.1016/j.neucom.2012.08.013), [J2](http://dx.doi.org/10.1016/j.neucom.2015.04.022), [J3](http://dx.doi.org/10.1007/s00521-014-1716-8), [J4](http://dx.doi.org/10.1115/1.4032687).

To validate the system identification approaches presented in [J1](http://dx.doi.org/10.1016/j.neucom.2012.08.013), [J2](http://dx.doi.org/10.1016/j.neucom.2015.04.022), [J3](http://dx.doi.org/10.1007/s00521-014-1716-8), [J4](http://dx.doi.org/10.1115/1.4032687) different systems were identified. For instances, a Wiener-Hammerstein benchmark system, a robot arm, a real-world benchmark regression problem (delta elevators), an acoustic duct, and a piezoelectric actuator were identified. Comparisons with others black box system identification methods shown that the proposed methodology yielded, in all the application cases, the best balance between simplicity, accuracy, and computational cost. Moreover, results on the identification of the piezoelectric actuator, which output data contain strong natural outliers, shown that the proposed robust estimation approach yields significantly better performances than the others black box methods [[J4](http://dx.doi.org10.1115/1.4032687)[J5](https://doi.org/10.1007/s11071-016-2733-1)].  

***

# **Lecturer and research assistant**
## Adaptive control system based on neural networks

During my Lecturer and research assistant experience, my research consisted in the application of the neural networks that I developed during my thesis, to the maximum power point tracking for photovoltaic panels. 

In the field of power optimization of photovoltaic panels (PV), there exist many maximum power point tracking (MPPT) control algorithms. Perturb and observe (P&O) is one of the most widely used due to its simplicity. However, the major drawback of this kind of algorithm is the lack of accuracy due to oscillations around the maximum power point. Other MPPT control algorithms, based on neural networks (NN), have shown to be a very efficient solution in terms of accuracy. However, this approach remains complex. 

To improve both P&O and NN MPPT control algorithms, I combined the P&O algorithm with a neural network to improve the accuracy of the P&O MPPT controller. The neural network was based in my previous works [[J1](http://dx.doi.org/10.1016/j.neucom.2012.08.013), [J2](http://dx.doi.org/10.1016/j.neucom.2015.04.022), [J3](http://dx.doi.org/10.1007/s00521-014-1716-8), J4], therefore the optimized P&O-NN control algorithm leaded a good compromise between accuracy and complexity. The proposed control algorithm was tested on two different models of a solar panel that were experimentally validated. Results show good accuracy and reduced complexity. This work was presented in an international conference [C3]. The paper was selected to be published in an international journal [[J5](http://dx.doi.org/10.1016/j.egypro.2013.11.067)].

***

# **Postdoctoral research**
## Adaptive control system for heart rate regulation

Currently, I am a postdoctoral researcher at LTSI. I am working on the INTENSE project (Initiative Nationale Technologique d’Envergure pour une NeuroStimulation Evoluée). My research is oriented to the design and implementation of real-time adaptive control systems for heart rate regulation, via vagus nerve stimulation (VNS). Vagus nerve stimulation offers an alternative therapy in various pathologies, such as epilepsy, supraventricular arrhythmias, and heart failure. However, the VNS therapy is commonly delivered in an open-loop approach, with fixed stimulation parameters, without any feedback regulation.

The main contributions I have done to this project are: 

* To design, implement, and experimentally validate an original adaptive heart rate regulation system, based on a state-transition model, which is described in four patents submitted in collaboration with SORIN group [P1-P4]. The proposed controller is implemented as two interconnected elements 1) a state-transition model and 2) a state-transition algorithm. The states of the state-transition model are composed of a set of stimulation parameters. The state-transition algorithm selects the states leading the lower error between a given target and the instantaneous heart rate. This original controller, which allows to modulate five stimulation parameters, improve results obtained by a proportional integral (PI) controller in terms of accuracy, complexity, and energy consumption. Results on the experimental validation of the proposed controller are described in two articles to be submitted to TNSRE, IEEE.   

* To develop a model-based control design (MBD) framework used to develop the different control types that were experimentally validated on sheep. This framework consists of 1) a complete physiological model representing the cardiovascular system and the autonomous nervous system implemented on a computer (Computer 1); 2) a control system implemented on Computer 2; and 3) a vagus nerve stimulation device. The three components are connected in closed-loop configuration. The advantage of the proposed framework is that allows to experimentally validate the controller, once it was tuned on the model, by easily replacing Computer 1 by the real animal (or patient). For instance, the proposed MBD was used to design a PI controller, which was experimentally validated on eight sheep. Results were published in [[J6](http://dx.doi.org/10.1109/TBME.2015.2498878), [C4](http://dx.doi.org/10.1109/NER.2015.7146659)]. 

Others contributions I have done to this project are:

* To develop system identification models representing the effect of VNS (input) on the heart rate (output). The model structures I used were the linear ARX, OE, and ARMAX models and the nonlinear NLARX model. Recently I used extreme learning machine (ELM) methods and support vector machines (SVM) methods.

* To implement an on-off controller, which was tested on four sheep. Results were presented in the 36th Annual International Conference of the Engineering in Medicine and Biology Society (EMBC) conference in Chicago [[C5](http://dx.doi.org/10.1109/EMBC.2014.6945060)].  

***

**Publication list:** http://roug84.github.io/Hector-ROMERO-Publication-list

**CV:** http://roug84.github.io/Hector-ROMERO-CV
