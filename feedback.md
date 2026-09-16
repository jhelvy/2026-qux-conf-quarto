# 1

This is a discussion and demonstration of the Quarto document publishing system, which is not specifically related to UX research (because Quarto could be used by anyone). That's an OK demo but could be at almost any conference.

If accepted, I would encourage the authors to discuss aspects that are specific to Quant UX or UX research generally. For example, the pros and cons of Quarto as part of an automated *UX analysis* workflow. Some pros: repeatable, structured, powerful. Some cons: extremely time-consuming and fussy to get working the first time, incentivizes people to pay less attention to assumptions and conditions that may change.

# 2

Feels like the tool is too specialized

# 3

Not sure how this is not an advertisement for Quarto.  More importantly, not sure how it contributes to the Quant UXR practice

# 4

This seems like a sales pitch which is fine but I wonder if there are any take home nuggets for someone who doesnt pay for or use this software?

# 5

The core concept of this proposal - using Quarto as a deterministic safety net to prevent LLM hallucinations in data reporting - is a relevant and useful topic for Quant UX practitioners. As AI agents become more integrated into our workflows, finding ways to generate dynamic yet mathematically trustworthy and reproducible outputs is a critical challenge. The proposed solution of asking models for a .qmd file rather than a finished document is a clever, actionable practice that fits the conference well.

However, to make the presentation truly approachable for a "minimally technical" audience, the proposal and the talk itself would benefit from significant simplification. Currently, the abstract relies heavily on dense terminology (e.g., "probabilistic pass," "code-at-render-time model") that obscures the practical value of the talk. The proposal also feels slightly disjointed; the summary presents a high-level architectural philosophy, while the takeaways suggest a basic introduction to Quarto. I highly recommend grounding the introduction in a concrete, relatable problem, such as LLMs hallucinating data in reports, and clearly outlining how Quarto steps in to solve it.

# 6

Thank you for submitting this proposal. Using Quarto and LLMs to create reliable, automated reports is a highly practical solution for data workflows. You do a great job showing how to bridge the gap between raw code and final, usable documents like dashboards, which is a valuable time-saver for any data team.

However, looking at this strictly as a Quantitative User Experience (Quant UX) proposal, it misses a crucial element: the human user. The abstract focuses entirely on the engineering, formatting, and rendering of data, rather than how we actually measure the user experience. In Quant UX, our tools need to serve the understanding of human behavior—for example, proving that a specific metric truly measures user frustration rather than just logging a server event, or combining large-scale data with qualitative insights to understand the "why" behind the numbers.

To elevate this from a general data science workflow talk to a Quant UX presentation, I recommend shifting the focus. How does this automation help researchers better measure, understand, or improve the actual user experience? Tying the engineering back to human measurement will make this much more relevant to the audience.

# 7

13/20

Topic Fit to Audience: 4/5. Reporting research is a key job function for many at the conference.

Presenter Expertise: 4/5. The author appears to be a maintainer of Quarto, or someone deeply familiar with the tool and related tools.

Content Depth and Quality: 5/10. This talk is a product demonstration with a moderate technical depth, presented to an audience that may not be familiar with the Quarto tool (an open-source publishing system). The problem of a report keeping a great layout after edits is real. However, the proposal delves quickly into product-specific issues such as integrating languages from other libraries. I worry that the audience will have difficulty taking away key points as a talk.

I recommend the author consider making this a workshop with a somewhat smaller audience. That way, audience members will be prepared to apply these techniques during the presentation time and walk away with something reusable.