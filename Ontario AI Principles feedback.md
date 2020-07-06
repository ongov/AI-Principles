---
What we’ve heard so far/ Ce que nous avons entendu jusqu’à maintenant
---

Feedback is only available in the language it was received. It has been
summarized to anonymize the contributors and focus on constructive notes and
suggestions.

Les commentaires sont uniquement disponibles dans la langue dans laquelle ils
ont été reçus. Il a été résumé pour anonymiser les contributeurs et se
concentrer sur des notes et suggestions constructives.

[General feedback | Commentaires générales](#general)

[Ethical Principles | Principes pour une utilisation éthique](#ethical)

[Transparency Guidelines | Lignes directrices sur la
transparence](https://github.com/ongov/Transparency-Guidelines/blob/master/Ontario%20AI%20Transparency%20feedback.md)

General feedback | Commentaires générales <a name="general"></a>
==========================================

[Memo from Law Commission of Ontario](https://github.com/ongov/Transparency-Guidelines/blob/master/LCO%20Memo%20to%20ODS%20-%20June%2030%202020.pdf)
There is some overlap between the AI Principles and the Transparency Principles. While there don’t appear to be contradictions between them, wondering why they are kept separate?

Safes framework

-   Australia articulated 5 safes of data

    -   <https://www.aihw.gov.au/about-our-data/data-governance/the-five-safes-framework>

-   This is being expanded by a group out of Scotland into 7 safes (draft green paper)

    -   <https://ukhealthdata.org/projects/aligning-approach-to-trusted-research-environments/>

Ethical Principles | Principes pour une utilisation éthique <a name="ethical"></a>
============================================================

Definitions are lacking from this document. The initialisms AI and ML are never spelt out (“artificial intelligence” or “machine learning”), and never defined. There is still some debate over the meaning of “artificial intelligence”, some
interpreting it as General AI vs. the Narrow AI. Defining these, or pointing to a definition from another source, would be helpful.

More difficult would be defining what an automated decision is. For example, is
computing a risk-score for individuals an automated decision? Why or why not?
Answering these questions will be important for system implementers to
understand if these principles apply or not.

1 Transparent and Explainable | Transparents et explicables
------------------------------------------------------------

How and where? If these principles are for the government, can they be more specific? Should procurement favour open technologies where possible?

Recommend providing definitions and for “transparent” and “explainable”.

The 2nd sentence, “Where automated decision making…” runs long. Suggest to rewrite as: “When an automation has been used to make a decision about a human, a meaningful explanation should be provided. The explanation should include meaningful information about how the decision was made, as well as the envisaged consequences of this processing.”

Note that the phrase “about humans” may lead some to conclude it does not apply to decisions made about companies. The compound “humans or organizations” could be used, or simply “automation … to make administrative decisions”, without specifying who they apply to. Administrative decisions are those that affect the legal rights, privileges or interests.

You don’t hold the technologies accountable. You hold the people behind them accountable. You make this point later on – Suggest to clarify the language here.

2 Good and Fair | Bons et équitables
-------------------------------------

The principles included are all excellent, but it may not be immediately obvious how to meet some of them. For example, how are developers expected to build apps reflecting diversity and social justice? Readers would benefit from some additional suggestions and examples to help guide and inspire them.

-   Testing data for quality, quantity, relevance, biases, etc.

-   Testing decisions for unintended outcomes

-   Conducting an algorithmic impact assessment

-   Etc.

In addition or alternatively, it may be worthwhile to link to the Canadian Charter of Rights and Freedoms and the Ontario Human Rights Code.

There are also specific legal obligations with respect to human rights, privacy, civil liberties, etc. There is a risk of conflating these with “values” that have to be respected. They are constitutional and legal principles. So perhaps reference needs to be made to the fact that in addition to be compliant with privacy and human rights law, and consistent with constitutional principles, data driven technologies should include appropriate safeguards to ensure a fair and just society.

I realize there is a need to be concise, but how well do designers understand how they need to respect “internationally recognized labor rights”?

Should there be reference to specific normative instruments like human rights legislation, privacy law, the Charter, etc.

3 Safe | Sécuritaires
----------------------

The title of this principle is “safe” and the first paragraphs seem to be addressed to security issues, but the “why it matters section” seems to drift back to “good and fair” above. If this is an independent principle focused on security, “why it matters” should more clearly reflect this.

It is not clear what safety risk is being addressed here, and why a complete halt of operations might be required. Suggest adding a definition for safe. E.g.:

Robust: free of errors and resilient to different inputs.

Secure: protected against cyber-attacks, unauthorized access and tampering.

Safe: will not compromise the physical security or health of humans? Is robustness sufficient to achieve this?

It may be useful to state that this is more relevant in certain contexts, such as self-driving cars and medical devices.

“no longer agreeable…” seems like fairly weak language. Aren’t we talking about decisions that are unfair, problematic etc?

4 Accountable and Responsible | Imputables et responsables
-----------------------------------------------------------

It would be preferable to identify an individual responsible for meeting the principles, rather than defer to “organizations”, where individual members may assume it’s not part of their role. The head of a department, for example, could be held accountable. Suggest rewording as “Identify an individual to be held accountable for the proper functioning of the AI system in line with the *other* principles”. Suggest to replace “above principles” with “other principles”, to
also include item 5 and 6 found below.

“periodically” is too vague – how often?

“…decisions about individuals there needs to be a process for redress to better understand how a given decision was made…” Or to challenge the decision? Or both?

The “Why it matters” section sounds like it should be in the previous paragraph. It is prescriptive not explanatory.

5 Human Centric | Centrés sur l’humain
---------------------------------------

From the [Digital Nations AI Principles](https://leadingdigitalgovs.org/comunicacion/noticias/artificial-intelligence):
automated decision systems should be built starting with a clear user need and public benefit, that should be documented and made available publicly.

The opening paragraph seems like the guidance is aimed at the use of algorithms in decision-making systems. But the introduction to the principles is not so specific. Some systems will simply flag, sort or identify key information for
human decision-makers, for example. So – are these principles for algorithmic decision-making (in which case they all need to be more specific and a definition of ADM is required) or are they meant to be broader, in which case this principle and its description/discussion need to be reconsidered.

Who is the user? The government official who uses the AI-enabled system? Or a person whose data is processed using AI – so not necessarily someone who uses the tool but someone who is affected by it. Or is it a user in the sense of someone, say, who uses a chat-bot interface.

It’s possible you mean all three but it might be helpful to be specific and to give examples (perhaps in why it matters) over how each category might be affected or should be taken into account.

6 Sensible and Appropriate | Sensés et appropriés
--------------------------------------------------

In the definition of sensible and appropriate, it could include the concept that the system is necessary or/and will not unduly negatively impact the client. Or: “starting with a clear user need and public benefit”.

They actually have to be Charter compliant, not just aligned with…

Not sure what it means to be aligned with “…with Federal and Provincial AI Ethical Use.”

This is a bit vague. It doesn’t really do the work of the harm/impact assessment in the federal AIA and DADM frameworks. In any event, by-product might be the wrong term. Sometimes decision-making might be specifically about the environment (eg using AI to assess environmental impacts in deciding whether to issue a development permit). Although I may be misunderstanding this all together. Are you referring to use of AI systems in these other contexts (eg the environment) or are you suggesting that the adoption of an AI system should take into account whether it will consume so much energy as to contribute to environmental degradation?

[Transparency Guidelines | Lignes directrices sur la transparence](https://github.com/ongov/Transparency-Guidelines/blob/master/Ontario%20AI%20Transparency%20feedback.md)
=================================================================
