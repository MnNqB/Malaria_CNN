# Introduction
Throughout history one of the deadliest diseases humanity has faced is malaria. It was dubbed the "single biggest killer of humans in history" by the YouTube channel, 'Kurzgesagt - In a nutshell', who published a great video on its transmission and the ways scientists today are trying to fight it. However, before any treatment plan can be recommended the infection needs to identified and the condition diagnosed. This fact, combined with the disease’s severity and prevalence, means that an accurate, fast, and inexpensive detection method should be available to everyone and not just people from first world countries. 

The CDC recognizes this, and recommends malaria be promptly treated to prevent further spread in the community as well as to prevent severe disease and potentially death for the patient. However, at the same time they highly discourage "presumptive treatment" (treatment without a confirmed diagnosis,) as overuse of antimalarial drugs may lead to drug-resistant strains as well as unwanted side effects for the patient.

Diagnostic tests can be performed through either blood smear microscopy or PCR testing. PCR testing is more sensitive and specific than microscopy, but the testing is more expensive, and the results are not available as fast as microscopy. 

Because of this, it is proposed that as part of a standard medical screening for populations in high-risk areas of malaria that a portion of blood drawn be devoted to an automated batch microscopy scanning by computer. Automating the task means testing could be implemented for large population sizes at little cost and only requiring minimal personnel with no more than technician level training. Outbreaks could be identified early, and human incurred disability could be minimized.

This could be implemented using machine learning and artificial neural networks. To show the feasibility, a model CNN will be trained using a small data set and only minimal computer resources. The dataset used in training the model contains images of blood cell slides with and without parasitic infection. Before real-world implementation, a larger dataset and additional training processor-hours would be required. However, even on this small scale the results prove promising. A well-trained model hosted in the cloud could potentially enable any cellphone with an internet connection to function as a malaria testing device.


Stained thin blood smear slides from 150 infected and 50 healthy patients were collected and photographed by the  Chittagong Medical College Hospital in Bangladesh. These
The data with images of infected blood cells, as well as uninfected blood cells. Our goal is to create a model that can differentiate between the two. Let's visualize the two side-by-side:


Sources:

Rajaraman S, Antani SK, Poostchi M, Silamut K, Hossain MA, Maude RJ, Jaeger S, Thoma GR. 2018. Pre-trained convolutional neural networks as feature extractors toward improved malaria parasite detection in thin blood smear images. PeerJ 6:e4568 https://doi.org/10.7717/peerj.4568 

https://www.youtube.com/watch?v=TnzcwTyr6cE

https://www.cdc.gov/malaria/diagnosis_treatment/clinicians1.html#eval


