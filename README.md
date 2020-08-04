# ATLAS-classifier
Project Summary: 
As part of the Ben Gurion University's Heavy Ion's Research Laboratory, 
the physicists try to explore the first moments of the universe. 
In their research, they use the particle accelerator experiment - 
In Switzerland CERN (Large-Hydron-Collider Group) LHC. 
LHC supply's better look to the way particles crating vis high energy collisions. 
The main tool in these studies is ATLAS, a detector that records the events in LHC. 
In the research process, physicists analyze the detector observations. 
At the step of the analysis, data must be separated between the data Noise and  
the quality data source from "significant collisions", that chosen by Physical parameters. 
Despite the knowledge and technology This task is complicated because, 
sometimes in Single event happening Multiple collisions that happened in Infinitesimal 
time one of each other and in a small distance, so the particle classification task is difficult, 
and currently there no good method that capable to solve it whit high confidence.  
The reason for choosing the most significant collision in event, 
is because it will provide the Most significant information to physicists, 
while the rest of the data will be background noise . 
The purpose of our research is to reduce the uncertainty in the classification of data that related to the main event. 
During the Research, we were faced with some challenges, 
the most tuff one was retrieval and preparation the data due to the complexity of the data structure of the detector output ATLAS .  
Our method was to Build a non-linear model that can provide high-quality classification
for particles that was created at 0.75 mm from each other. 
Different from previous research that was dealing with problem in linear tools 
and high-level of mistakes. 
As part of the Research we investigated several models and different Methods, 
that by the end we succeeded by finding model that capable of classifying particles 
with a level of accuracy of 90% and with an error level of less than 2% for particles 
formed in distances of 0.75 mm from the main collision.
