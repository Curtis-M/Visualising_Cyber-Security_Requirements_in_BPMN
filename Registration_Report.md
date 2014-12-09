####Using Game Technology To Represent Cyber-Security Requirements In BPMN 2.0

#####1.	Introduction
At present, BPMN (Business Process Model and Notation) has no industry standard for representing cyber-security requirements. There have been several attempts, but current extensions are being created with primary focus on semantics and very little on symbolic design. Nor the overall diagram design; the inclusion of security requirements greatly impacts the readability of an already over-elaborate modelling language. Thus, notations are required which can be included in diagrams without too drastically altering the complexity of them.

This report evidently shows that the inclusion of cyber-security requirements in BPMN is not a simple task, but a detailed process which is going to require much exploration and investigatory work. Throughout the document a research project is proposed which aims to address the problem, by utilisation of the third-dimension. The first section is a literature review of current extensions, identifying both strengths and weaknesses in their design. The report then continues to detail research aims, proposed design and methodology, and a plan of work for the project.


#####2. Literature Review
######2.1.	Background
A business process can be described as a set of linked tasks which must be executed in a specific order, collectively resulting in 
a business objective or policy goal being achieved. These tasks can be conducted across one or multiple organisations [1]. 

*Business process* model and notation (BPMN) can be used to graphically represent such processes and their component relationships 
in a common standard between organisations [2]. 

######2.2.	Existing Extensions and State-of-the-Art Technologies
BPMN fulfilled the requirement of a modelling language to represent business processes and is now the industry standard [1]. However, it doesn’t contain notations for modelling cyber-security requirements. Current extensions have made attempts, but they are being constructed unsystematically, without any empirical evidence to support their choice of concepts, or symbolic design [2].

The first problem lies with a lack of clear, predetermined security concepts which should be modelled. This can cause a symbol deficit language; without an adequate number of notations, modellers can’t accurately portray their requirements. The only solution is to reuse existing ones; this then leads to symbol overload [3]. Defeating the purpose of even creating new ones, as now notations could be representing any one of several concepts.

Typically, an expert in business processes and an expert in security will design their respective domain in pre-development stages. BPMN has been created as a language which can be interpreted by both final users and such experts [1]. As most final users -and business process experts for that matter- don’t customarily have expert knowledge in cyber security [4], notations are required which can both, bridge this knowledge divide, but still provide a formal, usable language. As such, the design choices made when creating notations have just as much importance, if not more than the semantics behind each one [3].

However, BPMN diagrams can quickly become over-elaborate without including security requirements (possibly explaining why so few notations are created in current extensions). There is a need for an extension (or standard) which can be used to display security requirements at a similar abstraction level as business processes, without adding to the complexity of reading them.

A solution to this problem is to include the third dimension in BPMN. Currently only two are being utilised (x and y), introducing the third dimension (z) can not only provide ample more space to display notations but also allow for better understanding of more complex concepts. 

When it comes to utilising 3D to its full potential, game technology is unrivalled. Technical advancements in game technology include rendering, realistic physics, lighting, audio, graphical user interfaces (GUI), head up displays (HUD), inputs and scripting [6]. The application of this technology to a currently static 2D diagram has exciting prospects.

######3.	Research Aims and Objectives

….. Where there is a current (though imperfect) solution for representing business processes in a notational format; there is 
yet a language capable of specifying cyber-security requirements in such detail. This project aims to address the problem by 
creating an industry standard 3D visualisation tool. That will allow both business and security experts to work in coherence 
at design stages. Providing the ability to not only specify their exact requirements, but have some understanding of how each 
domain works and interacts with each other.

To avoid previous mistakes and ensure all necessary concepts are included, as a prerequisite to the implementation of the 
application, an ontology of cyber-security requirements will be created. 

...

References

[1] 	A. T. M. Chinosi, “BPMN: An introduction to the standard,” Computer Standards & Interfaces, pp. 124-134, 2012. 
[2] 	“Home: BPMN,” OMG, [Online]. Available: http://www.bpmn.org/. [Accessed 1 December 2014].
[3] 	M. M. S. R.-M. M. Leitner, “An Analysis and Evaluation of Security Aspects in the Business Process Model and Notation,” in 2013 International Conference on Availability, Reliability and Security, 2013. 
[4] 	D. Moody, “The "Physics" of Notations: Toward a Scientific Basis for Constructing Visual Notations in Software Engineering,” IEEE Transactions on Software Enineering, vol. 35, no. 6, pp. 756-779, 2009. 
[5] 	E. F.-M. M. P. A. Rodriguez, “A BPMN Extension for the Modeling of Security Requirements in Business Processes,” IEICE Transactions on Information and Systems, pp. 745-752, 2007. 
[6] 	C. Maines and S. Tang, “An Application of Game Technology to Virtual University Campus Touring and Interior Navigation,” in 7th International Conference on Development in e-Systems Engineering (DESE2014), Phapos, 2014. 
