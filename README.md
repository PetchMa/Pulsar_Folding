# Pulsar Signal Folding - Breakthrough Listen Data
This notebook illustrates the implementation of pulsar folding and searching techniques from scrath. It finds the period of pusles within fairly noisy data. 

<p align="center"> 
    <img src="https://github.com/PetchMa/pulsar_notebooks/blob/master/assets/FAST_folding.gif?raw=true">
</p>

# Fast Folding

The algorithm is simple. You take each period and you fold the signals ontop of itself. If the period you guessed matches the true period of the pulse then by law of superposition it will increase the signal to noise ratio! This spike in signal to noise ratio can be seen in the following graph.

<p align="center"> 
    <img src="https://github.com/PetchMa/pulsar_notebooks/blob/master/assets/SNR.png?raw=true">
</p>

# Future
Currently looking into building a pulsar timming model. But that will be completed on a later date.