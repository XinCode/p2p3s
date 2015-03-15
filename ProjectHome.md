This project creates a trace-driven simulator, which compares all the current maintenance strategies(eager repair, deterministic lazy repair, randomized lazy repair and proactive repair) in the same context. It can also generate synthetic traces in different manners. The results are produced in different files for users to study.


# Getting Started #
The snapshot of p2p3s is showed as follows:

![http://p2p3s.googlecode.com/files/overview1.png](http://p2p3s.googlecode.com/files/overview1.png)

The text panel is used to show the log during the running, including simulation time, number of available nodes at each time point, etc. Users can cancel the running experiment by pressing the button _Stop this experiment_.

# Functionality #
This simulator provides the functionalities of performing experiments to compare the maintenance strategies as well as generating synthetic data and normalizing the trace.

## Generating synthetic trace ##
This simulator can generate synthetic trace in two modes. One is that all the peers have the same and constant departure/rejoin rate in the entire simulation. The other is that the departure rate and rejoin rate are adaptable and based on the behavior of another trace, which is specified by the user.

![http://p2p3s.googlecode.com/files/generator.png](http://p2p3s.googlecode.com/files/generator.png)

## Normalizing trace ##
This simulator can also normalize the trace specified by the user.

![http://p2p3s.googlecode.com/files/normalization.png](http://p2p3s.googlecode.com/files/normalization.png)

## Configuring the parameters ##
When the trace is ready, users can perform the experiments. P2p3s provides the friendly UI for users to configure the parameters used in the simulation.

![http://p2p3s.googlecode.com/files/config.png](http://p2p3s.googlecode.com/files/config.png)

For more details, please check the corresponding documents.