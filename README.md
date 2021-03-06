# VirusesSimulation
### [Problem set on MIT edx Data Science course] 
Using Python and Pylab, you will design and implement a stochastic simulation of patient and virus population dynamics, and reach conclusions about treatment regimens based on the simulation results.

### Software
- A Python-based flatform integrated development environment and pylab will be needed. Version: 3.6.
- Recommend: Spyder by Anaconda

### Background: 
Viruses, Drug Treatments, and Computational Models
Viruses such as HIV and H1N1 represent a significant challenge to modern medicine. One of the reasons that they are so difficult to treat is their ability to evolve.

As you may know from introductory biology classes, the traits of an organism are determined by its genetic code. When organisms reproduce, their offspring will inherit genetic information from their parent. This genetic information will be modified, either because of mixing of the two parents' genetic information, or through mutations in the genome replication process, thus introducing diversity into a population.

Viruses are no exception. Two characteristics of viruses make them particularly difficult to treat. The first is that their replication mechanism often lacks the error checking mechanisms that are present in more complex organisms. This speeds up the rate of mutation. Secondly, viruses replicate extremely quickly (orders of magnitude faster than humans) -- thus, while we may be used to thinking of evolution as a process which occurs over long time scales, populations of viruses can undergo substantial evolutionary changes within a single patient over the course of treatment.

These two characteristics allow a virus population to acquire genetic resistance to therapy quickly. In this problem set, we will make use of simulations to explore the effect of introducing drugs on the virus population and determine how best to address these treatment challenges within a simplified model.

Computational modeling has played an important role in the study of viruses such as HIV (for example, see this paper, by MIT graduate David Ho). In this problem, we will implement a highly simplified stochastic model of virus population dynamics. Many details have been swept under the rug (host cells are not explicitly modeled and the size of the population is several orders of magnitude less than the size of actual virus populations). Nevertheless, our model exhibits biologically relevant characteristics and will give you a chance to analyze and interpret interesting simulation data.

Spread of a Virus in a Person
In reality, diseases are caused by viruses and have to be treated with medicine, so in the remainder of this problem set, we'll be looking at a detailed simulation of the spread of a virus within a person. We've provided you with skeleton code in ps3b.py.
 
### Classs Explains
The project is divided into 2 seperated simulations.
- **simulationWithoutDrug** use **Patient** and **SimpleViruses** to create the relationship between patience and growth of viruses without any effect or resisitance of drug. 
- On the other hand, **simulationWithDrug** use **TreatedPatient** and **ResistantVirus** to create the relationship between patience (taking drug) and growth of viruses (with ability to mutate to resist with drugs).

### Testing
Uncomment some pre-coded lines to see the plots.

### Result Examples
<img src="Result_Image/withoutDrug.png">

<img src="Result_Image/withDrug.png">

### License
This project is licensed under the MIT License - see the LICENSE.md file for details
