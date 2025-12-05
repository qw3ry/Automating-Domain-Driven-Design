# Interview Structure

## Part 1: Introduction and Goal Alignment (5 minutes)
The objective of this phase was to brief the expert on the purpose of the study.
- Introduction: A brief overview of the thesis goal: to evaluate the effectiveness of LLMs in identifying bounded contexts from complex enterprise requirements.
- Context: Explanation of the two cases: SecuRooms as a validation case against a known benchmark, and SecuMails as an exploratory case for a monolithic modernization challenge.
- Task: Clarification that the expert’s role is to critique the AI-generated models based on their deep domain knowledge and experience with Domain-Driven Design.

## Part 2: Comparative Evaluation of SecuRooms (20 minutes)
This part focused on directly comparing the LLM-generated model against the existing, human-designed architecture for SecuRooms.
- Qualitative Probing Questions:
    - "Does the extracted Ubiquitous language represent the real language used for SecuRooms?"
    - "Do the extracted events represent all the events that happen in the SecuRooms domain? Do you miss anything here?"
    - "Did the LLM identify any alternative groupings or potential improvements that we missed during the manual design? Conversely, what critical elements did it completely omit?"
    - "Do you think the extracted Aggregates represent the real core aggregates we currently have?"

## Part 3: Standalone Evaluation of SecuMails (20 minutes)
This part was conceptualized to assess the LLM-generated architecture for SecuMails on its own merits as a viable modernization strategy.
- Qualitative Probing Questions:
    - "Based on your understanding of the SecuMails monolithic challenges, does this AI-proposed architecture represent a plausible and effective path forward? Why or why not?"
    - "If you were tasked with modernizing SecuMails, would you consider this LLM output a useful starting point? What would you change, and what would you keep?"
    - "Would this proposal be helpful to you as the architect who is tasked with defining a modernized architecture"

## Part 4: Overall Impressions and Conclusion (10 minutes) This final part should capture the experts’ holistic views on the practical implications of this technology.
- Discussion Questions:
	- "Overall, how would you describe the utility of the LLM as an ’architectural sparring partner’ in the domain modeling process?"
	- "To what extent could this approach accelerate or improve the quality of architectural design at FTAPI, especially considering constraints like tight deadlines and business pressure?"
	- "What are the most significant limitations or risks you foresee in relying on LLMs for these critical design tasks?"
	- "Do you have any final recommendations for how this methodology could be improved or applied in the future?"