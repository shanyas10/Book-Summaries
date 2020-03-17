# Affective Signals and Systems

This chapter overviews issues of representation in affective systems, specifically the need for a mixture of representations, spanning low to high levels of processing. Systems which can recognize, express and "have" emotions will employ processing both high-to-low and low-to-high transformations, from signal to symbo and vice-versa.

1. **Modeling an Affective System**
	- The recognition of emotion is not merely bottom-up(from signal to symbol) but also top-down, in that higher level symbols can influence the way signals are processed. 
	- The process of trying to express an emotion is usually considered to involve a transformation from symbok to signal, from high-level concepts to low-level modulation of expressions and behaviors.  
	- A person will find that an emotional state simply arises in response to perceiving or reasoning about some events and expression of that state occurs mostly involuntarily.
	-  When a computer tries to represent emotion, it may use convenient levels of abstraction, from low level representation of a signal such as waveform of heart rate to a high-level interpretation such as a sentence, "He looks sad".
	- To the extent that we imitate human mechanisms in computers, we have a bete chance of debugging them when they behave in a peculiar way, making it easier for us to interact with them.
2. **A signal representation for emotions and moods**
	- Theorists tell us that emotions usually last for less than a minute or two, while moods can last much longer.
	- How can we represent emotions, moods, influences of temperament and other affective phenomenon in a computer?
	- Physical changes indicative of emotions and moods- levels of hormones, neurotransmitters and nervous sytem activity- may be measured and made into a quantitative, physically-based model. 
	- Following is a way in which we can **computationally model** emotions and moods, accounting for properties of their behavior, at least in a qualitative sense.
	- **Ringing a bell (*Interesting*)** 
		- Consider the striking of a bell: when a bell is struck once, it emots a sound that is loud at first, and then decays in intensity.
		- It builds up quickly to a peak, becoming very loud, then gradually fades until it is too faint to be heard.
		- **Property of Response Decay**
			- If there are no repeated strikes of the bell then its sound subsides; similarly, emotional repsonses are of relatively short duration, and will decay naturally to fall below a level of perceptibility unless it is re-activated.
		- **Property of Repeated Strikes**
			- A signle stressful event may be too small to call attention to itself. However, a lot of repeated "little" stress-producing events can lead to a greater level of stress than one major stress-producing event. 
			- Rapid repeated activation of an emotion causes its perceived intensity to increase.
		- **Property of temperamental influence**
			- In the bell example, temperament is analogous to the physical characteristics of the bell. Two bells of different shapes and materials will not emit the sounds of the same form, even when struck with the exact same stimulus.
			- The innate physical properties of the bell are analogous to the innate nerochemical mechanisms of temperament; both influence the repsonse to a stimulus.
			- A person's temperament and personality influence emotion activation and response.
		- **Property of linearity and Time-Invariance**
			- The human emotional system is nonlinear but may be approxiated as a linear system for a certain range of inputs and outputs.
			- The human emotional system can be modeled as independent of time for certain durations. For short durations, habituation effects occur. For longer durations, factors such as a person's physiological circadian rythms and hormonal cycles need to be considered.
		- **Property of Activation and Saturation**	
			- Something that causes your heart rate to accelerate cannot do so indefinitely; the heart can only beat so fast 
			- Not all inputs can activate an emotion; they have to be of sufficient intensity. This intensity is not a fixed value, but depends on factors such as mood, temperament and cognitive expectation.
			- No matter how frequently an emotion is activated, at some point the system will saturate and the response of the person will no longe increase. Similarly, the response cannot be reduced below a "zero" level(imagine it being represented by sigmoid function).
		- **Property of Cognitive and Physical Feedback**
			- Inputs to the system can be initiated by internal cognitive or physical processes. For example, physiological expression of an emotion can provide feedback which acts as another input to the system, generating another emotional response.
		- **Representing Mood**
			- Moods can predispose or bias a person towards cetain emotions.
			- Moods can exert its influence by adjusting the sigmoidal non-linearities applied to the inputs. For example, a highly aroused bad mood can shift the sigmoid for negatively valenced events so thar even a slightly negative event can pass into the system and activate responses.
			- All inputs contribute to a background mood, whether or not they are below the activation level for emotions. The most recent inputs have the greatest influence on the present mood.
3. **Physiological Signals**	
	* There are many signals relevant to emotional responses that are physically measurable, especially by cameras, microphones, and sensors.
	* Patterns of low-level signls can be combined with high-level information to recognize an affective expression, as well as to charachterize an affective state.
	* The electromayogram (EMG) signal uses small elctrodes to measure a tiny voltage from a muscle indicating when it is contracted.
	* The blood volume pressure (BVP) signal is an indicator of blood flow, gathered using a technique known as photoplethysmography, which shines infrared light onto the skin and measures how much of it is reflected. The overall envelope of the signal tends to pinch when a person is startled, fearful or anxious. Am increase in BVP is observed when there is greater blood flow to the extremeties such as when a person relaxes.
	 