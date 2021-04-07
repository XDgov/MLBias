
# AI Frameworks and Their Implications

Governments, multinational organizations, academic and research institutions, and non-governmental organizations around the world have created hundreds of  frameworks, tools and playbooks meant to promote ethical engagement with, building of, and application of AI/ML. In this section, we guide users through an important subset of these resources, highlighting elements of each that could help federal government developers, data scientists, managers, and other stakeholders critically examine their own AI/ML ethics strategies and best practices.

We have broken this piece into three sections, ordered by level of granularity and operationality:
  - AI Principles: We pinpoint and define key AI principles and concepts found across the most relevant, applicable AI/ML Ethics frameworks created by institutions outside the US federal government. 
  - Implications for Policymakers: Using aggregated insights from these frameworks, we outline best practices in governance and implementation for government policymakers planning and managing AI/ML projects. 
  - Implications for Technical Deployment: We highlight key technical considerations for AI/ML development and deployment in government agencies.

This piece, as with the rest of this toolkit, emphasizes equity, fairness, and accountability as ways to address bias. These recommendations are in no way comprehensive, and any AI practitioner involved in the process will need to consider factors specific to their use case. However this guide provides a starting point for the best practices from a domestic and global perspective. 

NOTE: As stated in many of the frameworks reviewed, developing trustworthy, fair, and accountable AI is not about checking a set of boxes once, but continuously evaluating and testing these systems. Determining whether an ML solution is appropriate is out of scope for this module, so we begin here with the assumption that the necessity of implementing an AI/ML solution has already been established. It is important any system can meet the general requirements listed below. Practitioners should not be opposed to stopping a project if at any point serious concern of fairness, accountability, or equity arise at any point in the process development or deployment. 

Everyone involved in the development and implementation process of AI systems is responsible for its end results. Ethical systems depend on all of us - a single engineer or manager has the power to be able to correct a problematic system before it is released - and we encourage teams to have all of their members review the principles and guidelines of their agencies. 


## AI Principles

This section highlights key concepts, terms, and principles that have been identified across 80+ prominent frameworks published internationally.

As a starting point, the United States published its principles on December 3, 2020 through the Executive Order 13960: Promoting the Use of Trustworthy Artificial Intelligence in the Federal Government. The principles are as follows:
  - Lawful and respectful of our Nation’s values
  - Purposeful and performance-driven
  - Accurate, reliable and effective
  - Safe, secure, and resilient
  - Understandable
  - Responsible and traceable
  - Regularly monitored
  - Transparent
  - Accountable

For a comprehensive overview of ethics principles across all frameworks (including industry frameworks), please refer to Anna Jobin, Marcello Ienca, and Effy Vayena’s “Artificial Intelligence: the global landscape of ethics guidelines,” published in 2019. For the remainder of this paper, we cover four different frameworks to highlight interesting distinctions between frameworks.

| Principle | United States | OECD | India’s National Institution for Transforming India (NITI) | European Commission | 
| --------- | ------------- | ---- | ---------------------------------------------------------- | ------------------- |
| Lawful and respectful of our Nation’s values     |   ✓    |  ✓  |  |  |
| Inclusive and diverse     |       |  ✓  | ✓  | ✓ |
| Purposeful and performance driven | ✓ | ✓ |  | ✓  | 
| Accurate, reliable and effective | ✓ | ✓ |  |  |
| Safe, secure and resilient | ✓ | ✓ | ✓ | ✓ |
| Explainable | ✓ | ✓ |  |  | 
| Democratic |  | ✓ | ✓ |  |
| Respect for Human Rights |  | ✓ | ✓ |  
| Regularly Monitored | ✓ | ✓ |  |  |
| Transparent | ✓ | ✓ | ✓ | ✓ |
| Accountable | ✓ | ✓ | ✓ | ✓ |

***NOTE: These principles are checked off based on explicit mention. Principles that could be implied/interpreted but were not mentioned as an explicit principle were not counted. Additionally, there are other principles that are important that are not listed here. It is important for your particular use case to explicitly define your values before beginning your project***


The OECD’s principles, which have been adopted by 42 countries to date, focus on how:
  - AI should benefit people and the planet by driving inclusive growth, sustainable development and well-being.
  - AI systems should be designed in a way that respects the rule of law, human rights, democratic values and diversity, and they should include appropriate safeguards –  for example, enabling human intervention where necessary – to ensure a fair and just society.
  - There should be transparency and responsible disclosure around AI systems to ensure that people understand when they are engaging with them and can challenge outcomes.
  - AI systems must function in a robust, secure and safe way throughout their lifetimes, and potential risks should be continually assessed and managed.
  - Organisations and individuals developing, deploying or operating AI systems should be held accountable for their proper functioning in line with the above principles.

In 2017, Finland created an Artificial Intelligence Programme and a Steering Group to explore how to best support the public and private sectors in developing AI ethically. Key objectives were to (taken verbatim from the document): 
  - “Develop new operating models to shift from organisation-based activities to systems-wide approaches.”
  - “Adapt the role of government to ensure that citizens have the right to independently determine how their data are used, while protecting the privacy of the citizens.”
  - “Improve the interoperability of government data, and open up this data to fuel innovation in all sectors; encourage companies to share data as well.”
  - “Create a Centre of Excellence for AI, a virtual AI university and a Masters programme in AI to strengthen the talent pool for both the private and public sectors.”
  - “Pursue and build a network for public-private partnerships to allow for collaborative initiatives, knowledge exchange and better adoption of multidimensional thinking.”
  - “Hold a public discussion on AI ethics at in-person events and online.”
  - “Break down silos within and between businesses and public services.”
  - “Revise procurement law to enable effective public-private co-development.”

India’s National Institution for Transforming India (NITI) Aayog also recently published principles for building “responsible AI,” a follow-up from its 2018 National Strategy for AI. Its principles focused on:
  - Safety and reliability 
  - Equality 
  - Inclusivity and non-discrimination 
  - Privacy and security
  - Transparency 
  - Accountability
  - Protection and reinforcement of positive human values

The European Commission created the Independent High-Level Expert Group on Artificial Intelligence, which set up seven requirements AI systems should meet:
  - Human agency and oversight
  - Technical robustness and safety
  - Privacy and data governance
  - Transparency
  - Diversity, non-discrimination and fairness
  - Environmental and societal well-being
  - Accountability

As shown in the table above, transparency, accountability, and safety/security were universally important to mention as guiding principles for federal government AI/ML. Other principles varied, partially based on language and definitions, as well as cultural/governmental priorities. For example, AI guidelines developed in Europe specifically called out privacy as a critical consideration. Additionally, inclusivity and diversity were express principles called out in international frameworks.


## Implications for Policymakers
When it comes to translating AI principles into action, there are two key issue areas for policymakers to consider in ensuring bias is minimized: (1) following a process that identifies consistent key moments to evaluate the work and (2) involving the community voice in the process.

There are several efforts to create processes and standards associated with public sector AI/ML. While the National Institute of Standards and Technology builds out standards in the coming months, the American Council for Technology-Industry Advisory Council (ACT-IAC) has published the AI Playbook for the U.S. Federal Government. This playbook offers a step by step process for designing AI/ML for the public sector, including key questions to answer to address bias.

**Procuring Ai/ML**
Another method of implementing AI/ML in the federal government, however, is procurement. Both the ACT-IAC’s AI Playbook and The World Economic Forum’s AI Procurement in a Box guide government officials through how to source and vet AI/ML responsibly when implementing the technology through third party procurement. This is especially critical as governments still do not have needed internal capacity to develop all algorithms in-house and may consider procuring out-of-the-box solutions developed by companies. Their guidelines offer a set of steps to follow through the procurement process, such as assessing risks through specific frameworks early on and what to incorporate in an agency’s or department’s request for proposals.  These processes also may be helpful in the middle ground AI design scenario in which a federal agency manages the AI/ML design process but hires third-party contractors to develop the solution itself.

Other methods of evaluating algorithms on ascribed AI principles is to leverage an algorithmic impact assessment (AIA), such as Canada’s AIA or the EU’s Assessment List for Trustworthy Artificial Intelligence.

**Involving the Community**
The second key method for ensuring federal AI/ML minimizes bias is by including the community voice in the process. Research on methods of community co-design from The Montréal Declaration Responsible AI has shown a given user will be more inclined to trust an AI system if they understand the system and feel they have a role in its development. To this end, their research recommends the following. 
  - Offer a public forum for dialogue on AI development issues and their social impact. 
  - Engage a diverse set of stakeholders from your intended user and creator groups. 
  - Openly discuss the challenges and tradeoffs for making different decisions in the final implementation of a system. 
  - Explain what mechanisms will be in place for evaluation and further discussion. 
  - Update this user group with system audit and evaluation information periodically. 

Do not limit this to one such forum, this is best carried out over multiple iterations so the systems can truly be co-developed with users. 

Additional methods for community co-design come from WeBuildAI and Value-Sensitive Algorithm Design, that offer two variations on how to engage communities in co-designing AI/ML that benefits them. These approaches are more easily applicable at local levels where community engagement through town halls, council meetings, and department calls for comment are more common. At the federal level, community voice and participation may manifest differently.

This toolkit is still in its early stages. As we continue to collect more case studies across federal agencies on how they have implemented AI/ML in their work and mitigated bias throughout the process, we will publish more actionable content for all agencies to facilitate these critical steps in the AI development and deployment process.


## Technical Guidelines for Federal AI/ML 



### Summary of AI Priniples Frameworks
Below, we have summarized the contributions and salient points of various frameworks:

| Principle                        | Policy Implications                                                                           | Technical Implications and Considerations                                                                                                   | 
|-------------------------------|-----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------| 
| **Purposeful and performance-driven**        | Require agencies to design AI where the benefits significantly outweigh the risk                                                                           | Agencies must assess the risks of designing, implementing and developing AI and ensure that any risks produced from the product can be assessed and managed                | 
| **Transparent** | Require reports on how an AI model has generated insights or decisions                                      |Agencies must incorporate precise and explicit design methods in addition to any information of how they plan to use AI to the public while protecting privacy laws                                | 
| **Inclusive & Diverse**        | Require use a diverse set of training data to minimize bias; audit all datasets before use                                                                             | Require staff training on diversity equity and inclusion. Provide staff with diversity standards for training data sets                    | 
| **Privacy**      | Evaluate all potential datasets on whether the data is intended for the use case in question; facilitate privacy audit on desired data use leveraging citizens and subject matter experts     | Use opt-in rather than opt-out for data collection options. Default should always be: no data is being collected                                      |
| **Explainability**   | Develop guidelines to make the model understandable by stakeholders, users and others affected by the model’s conclusions         |Create an explainability guideline of how the model was designed, trained, implemented and how it is reaching certain conclusions                            | 
| **Accountable**            | Governments should hold agencies developing AIs accountable for the proper functioning in line with the principles outlined by the government                                                                            | Companies should be held responsible for implementing, enforcing and monitoring the implementation of guidelines to stay in accordance with government principles and policies                                           | 
| **Regularly Monitored**            | Governments should build sustainable infrastructure that is capable of continuously assessing  AI systems as they are rapidly changing                                                                            | Agencies should continuously update their guidelines as AI models change and develop. Companies must continuously test their AI application to ensure they are in line with governmental guidelines and policies                                           | 
| **Safe, secure, and resilient**             | Governments should enforce regulations for safety standards when agencies deploy AI to prevent and avoid vulnerabilities in its systems rather than reactively responding to it                                                                            | Agencies should develop security practices that align with government policies and constantly update them as the technology changes                                          | 

## Bibliography



