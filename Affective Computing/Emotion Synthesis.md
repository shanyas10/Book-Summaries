# Emotion Synthesis

This chapter describes emotion synthesis, specifically focusing on models that employ both cognitive and non-cognitive mechanisms for generating emotion. Cognitively generated emotions have been the easiest to implement in AI systems, as emotion theories are usually described with rules and lend themselves directly to rule-based implemntation in a computer. This chapter also describes various ways to synthesize emotion's influence on other processes: both cognitive and physical.

Emotions implemented in agents today are primarily cognitively generated. Furthermore, they have mostly been used only for entertainment purposes instead of using emotions to help manage information overload, regulate prioritization of activities, and make decisions more flexibly, creatively, and intelligently. This is a fine ue, and valuable for many applications, but it should not be the the only use.

1. **Emotion Synthesis via Cognitive Mechanisms**

	- **The Ortory Clore Collins (OCC) Cognitive Model**
		- In 1988 Ortony, Clore and Collins published their book, *The Cognitive Structure of Emotions*, setting forth a model of cognitive appraisal for emotions that has come to be called the *OCC* model.
		- They believed that AI systems must be able to *reason about* emotions- especially for natural language understanding, cooperative problem solving, and planning.
		- The OCC model addresses the problem of representing emotions by grouping emotions, according to cognitive eliciting conditions.
		- It assumes that emotions arise from valenced reactions to situations consisting of events, agents, and objects.
		

	- **Roseman's Cognitive Appraisal Model**
		- Roseman has developed a categorization of the appraisals people make about the events that cause emotions.
		- He and his collegues constructed a model in which a small number of appraisals interact to give rise to seventeen emotions. 
		

2. **Emotion Synthesis via Multiple Mechanisms**
		The OCC and Roseman theories provide a rule-based mechanism for cognitive generation of emotions. However, in humans, emotions are generated not only by explicit reasoning, but also by low-level noncognitive influences. This section descibes three models which encompass not only cognitive reasoning for generating emotion, but also additional low-level mechanisms, inspired by human emotion system.
	- **Four Elicitors for Emotion Synthesis**
		- Carroll Izard (Izard, 1993) proposed that there are four types of elicitors of emotions in humans as below:
			- *Neural* : Effect of neurotransmitter and other neurochemical processes. These processes run independently, in the background, and are influenced by hormones, sleep, diet, depression medication, etc.
			- *Sensorimotor* : Effect of posture, facial expression, muscular tension, and other central efferent activity. These effects primarily intensify a given emotional state, but in some cases appear to be capable of generating new affective states.
			- *Motivational* : Effect of sensory provocations such as anger provoked by paon, of drives such as hunger, and emotions evoking each other.
			- *Cognitive* : Effect of cortical reasoning, implemented here via an adaption of Roseman's theory.
		- Emotional behaviors compete for control, with the value of each beahvior determined by a linear combination of *releasing mechanisms.*
		- It is an important first step toward development of a complete computational emotion system.


	- **Emotions, Hormones, and Homeostasis**
		-	Dolores Canamero, at the Free university of Brussels, has built a system in which emotions trigger changes in synthetic hormones, and in which emotions can arise as a result of simulated physilogical changes.
		- Emotions can be trigerred by external events of they can be trigerred by internal physiological changes or patterns. 
		- Emotions also influence perception. For example, a state of high endorphines reduces the perception of pain.
		-Canamoero's system illustrates the ability of a computer to simulate physiological elicitors of emotion, as well as emotion's influence on physiology .
		-Such simulations are important way to learn about emotion synthesis.

3. **Synthesizing Emotion's Influences**

	This section describes the models for synthesizing emotion's interaction with other processes in the computer, specifically, how it can be used to realize multiple concerns, influence learning and behavior, and bias memory retrieval and decision making.
	
	- **Realizing Multiple Concerns**
		- Several researchers have suggested that emotions are manifestations of a system that realizes multiple concerns and operates with limited resources in an upredictable environment.
		- ACRES, *Artificial Concern REalisation System*, (Frijda 1987) tries to satisfy the following six concerns"
			- Avoid being killed
			- Preserve reasonanle waiting times, i.e. respond promptly
			- Receive correct input
			- Receive varied("interesting") input
			- Safety (preserving the concept in ACRE's concept-based structure).
			- Vicarious learning (from the user's experience).
		- When one of the concerns is active, ACRES may react emotionally. It illustrates that emotions are not just for entertainment, but they can provide low-level regulatory functions needed by a system with a limited resources and multiple goals operating in a complex and unpredictable behavior.

	- **Emotions influencing learning and behavior**
		- Mowrer and his colleagues, through many experiments , determined that learning is best thought of not as the single stage of stimulus response , but as two stages, with the first involving the generation of an emotion.
		- Implementing emotion's influence on learning is an important piece of implementing the fifth component of an emotion system.
		- One of the problems with buoilding creatures that exhibit emotions is how to map emotional states to behaviors. Emotions motivate and bias behavior but they do not completely determine them.
		- Giving emotions to systems appears to be a means to achieve multiple goals, only one of which is more flexible learning. For e.g., if, while learning, the machine predicts it will feel even worse if it does not forward you a piece of urgent and important news , then it might interrupt its own learning experience to get the news to you.
		- An emotional state produces internal control signals in a machine running several tasks at once and can signal its attention when its time for a change. These same signals cam influence not only learning, but also memory, perception, and many other important functions.

	- **Affective Decision making**
		- An integral component of human decision making is emotion, and this component could potentially be given to computers.
		- Computers can be given abilities where emotions influence their decision making and other cognitive processes to the same degree that these influences are beleived to occur in humans. These abilities can be useful especially when facing problems where all the optons can not be fully explored.
		- Humans use feelings to help them navigate the oceans of inquiry, to make decisions in the face of combinatorial complexity. These feelings might be called "intuition" or a sense of "knowing" or just "*gut feelings*".
		- An integral component of human decision making is emotion, and this component could potentially be given to component.

	- **Emotions that interact with memory**	
		- The same emotion that influences a person's learning and decision making also influences memory retrieval and a host of other cognitive processes.
		- Good feelings likely enocode knowledge of effectiveness, familiarity, opportunity, and associations with positive outcomes. Bad feelings likely encode knowledge of ineffectiveness, unfamiliarity, risk, and associations with bad outcomes.
		- When it is time to take decisions, valenced feelings help bias a person away from bad outcomes and toward good ones. 
		- Studies of patients with prefrontal brain damage show, these biasing mechanisms are apparently at work *before* declarative knowledge for reasoning is activated.
		- Araujo (Araujo, 1994) has built a model that attempts to integrate both low-level physiological emotional responses and their high-level influences on cognition.
		- It consits of two interacting neural-networks- the "emotional network" and the "cognitive network." These are designed to roughly approximate the roles of the limbic and cortical structures in the human brain, respectively.
		- Araujo acknowledges that bot nets should influence each other to miimc the influences in human brain, even though he only takes time to address the influence in one direction.
		- Computers and humans have very different bodies, so computer and human feelings are likely to be very different. In other words, the emotional experience we can give to a computer does not duplicate humans; computers cannot feel what we feel.
	
	- **Emotion as an umbrella**
		- Human emotion system consists of many different components, and not all emotions use all the components in the same way. For e.g., to implement low-level fear, we need crude pattern recognition and fast responses capable of hijacking other cognitive responses.
		- When it comes to synthesizing emotion, different components are likely to require different mechanisms, like in the human brain, where we know fear blazes its own fast path through the limbic system, while emotions like hope are believed to be more cortical.
		- The term "emotion" is perhaps best thought of as an umbrella, under which a variety of processes cluster. Therefore, while synthesizing emotion, we do not need to pick just one aspect of cognitive, phyiological, or behavorial model, but we need to consider how each of these works with others.
		- This is not to say that a different model is required for every emotion but one unified model would not provide the best solution either.
