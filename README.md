# particleTrackML
TrackML particle tracking kaggle challenge 2018 

 
Project Description: 

Description of the challenge provided by the organizers: 

A data science competition to stimulate both the ML and HEP communities to renew the toolkit of physicists in preparation for the advent of the next generation of particle detectors in the Large Hadron Collider at CERN. With event rates already reaching hundred of millions of collisions per second, physicists must sift through ten of petabytes of data per year. Ever better software is needed for processing and filtering the most promising events. This will allow the LHC to fulfill its rich physics programme, understanding the private life of the Higgs boson, searching for the elusive dark matter,  or elucidating the dominance of matter over anti-matter in the observable Universe.

To mobilise the scientific community around this problem, we are organizing the TrackML challenge, which objective is to use machine learning to quickly reconstruct particle tracks from points left in the silicon detectors. The challenge will be conducted in two phases: 
the on-going Accuracy phase May-Aug 2018 :  favoring innovation of algorithms reaching the highest accuracy, with no speed concern.This phase has been accepted as an official IEEE WCCI 2018 competition (Rio de Janeiro, July 2018) This phase is hosted by Kaggle.
the Throughput phase Jul-Oct 2018 : focussing on speed optimisation. This phase has been accepted as an official NIPS 2018 competition (Montreal, December 2018). That phase will be hosted by Codalab.

Dependencies/Pre-requisites:
matplotlib
numpy 
pandas
sklearn


DATA Access: 
To load the data, import trackml-library that was built for this purpose.

Under your kernel's Settings tab -> Add a custom package -> GitHub user/repo (LAL/trackml-library)

Restart your kernel' s session and you will be good to go.

from trackml.dataset import load_event, load_dataset
from trackml.score import score_event

Usage: 
At the moment, the modules here are for data exploration and better understanding the challenge. Each can be implemented easily with google colab using its single GPU.
At the moment this repo is being used as my playground to understand the TrackML challenge and gather different band-solutions in one place. 
If you don't have access to GPUs, the python programs and notebooks provided here work with google colab, you have to install the libraries first then import. 

Future Plans:
Once I understand the problem better, I'll put together an ensemble solution. 
