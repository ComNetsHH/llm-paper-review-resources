Review 1

Summary: Please comment briefly on the following: What are the major contributions of the paper? Do you consider them important? Comment on the degree of relevance, novelty, technical depth and presentation quality of the paper. What are the strengths and weaknesses of the paper?

This paper proposes dynRDF, an extension of the Rate Decay Flooding protocol that uses deep contextual bandits to dynamically adapt flooding parameters in urban UAV networks. The method learns optimal configurations based on network size or local UAV density, achieving up to 12% performance gain over a brute-force–derived baseline while exploring only 2.7% of the configuration space. The authors have demonstrated their proposal using ns-3 simulator.

Originality and Impact: Assess the originality of the work and its contribution to the area of research

Has merit but mostly incremental (3)

Presentation: Assess the quality of the presentation in terms of English, organization and completeness

Readable (3)

Technical Correctness: Assess the technical correctness of the work

Flaws but Easy to Correct (3)

Relevance: How relevant is the paper to MSWiM?

Somewhat Relevant (3)

Reviewer Familiarity: Please assess your familiarity with the subject matter of the paper

Familiar with this area of research (3)

Recommendation: What is your overall recommendation for the paper?

Likely reject (Top 50%, but not top 30%) (2)

Detailed Comments: Please provide detailed comments and suggestions to the authors for improving the paper.

Despite the paper has worthy it presents some issues that it should be addressed:

The related work section presents some papers in the literature, but no differences have been highlighted and addressed with respect of the authors’ proposal.
Mobility model is “random direction,” which may not fully capture structured urban UAV movement patterns
In “Dynamic Rate Decay Flooding” section, the authors set some thresholds but the motivations about these choices are not well argued. For instance, why a time threshold call T_cada is 736? They refer to another paper in the literature, but it is not clear the study done about this value.
In the same section, the authors state: “Actions consist of the parameter pair (i0,q)”, please provide a better explanation of the two terms i0 and q for making the readers more aware and provide the motivation of the choice of the two values indicated in the text.
It could be useful to provide a simulation parameters table in which providing a summary of the parameters and the values used in the simulations.
Although learning efficiency is emphasized, an analysis of the computational resources of the proposed approach is not reported in the paper.
Finally, the proposed approach is compared only against the previous RDF configuration; including other adaptive flooding or RL-based methods from the literature would strengthen the comparative claim.
Review 2

Summary: Please comment briefly on the following: What are the major contributions of the paper? Do you consider them important? Comment on the degree of relevance, novelty, technical depth and presentation quality of the paper. What are the strengths and weaknesses of the paper?

The authors applied the contextual bandit ML approach to find out the best parameters for their own selective flooding protocol (rdf, then dyn-rdf). Overall I like the paper and the experimental campaign. The paper is timely for the IA part but...a little bit behind SOTA for the dynRDF part as it is for 802.11p for UAVs. I know that 5G NR ProSe is a breathtaking mess, but all in all, we ns3 users should migrate to it in the end. Presentation is technical and clear. Minor details in the dedicated section.

Originality and Impact: Assess the originality of the work and its contribution to the area of research

Good Contribution (4)

Presentation: Assess the quality of the presentation in terms of English, organization and completeness

Definitely Well written (5)

Technical Correctness: Assess the technical correctness of the work

Good (5)

Relevance: How relevant is the paper to MSWiM?

Definitely Relevant (5)

Reviewer Familiarity: Please assess your familiarity with the subject matter of the paper

Working in this area of research (5)

Recommendation: What is your overall recommendation for the paper?

Definite accept (Top 10%) (5)

Detailed Comments: Please provide detailed comments and suggestions to the authors for improving the paper.

Not clear why deep contextual bandits w.r.t other ML approaches. What happens with other methods? Friis is not good for the scenario. There is a specific model for that: https://www.nsnam.org/docs/release/3.45/doxygen/db/d40/classns3_1_1_itu_r1411_nlos_over_rooftop_propagation_loss_model.html#details Idk if an entire Section and a Figure is necessary for the neural network part. A table and a small paragraph would have been sufficient. Specify better that you use a simulative approach to "validate" data and that the model is good even when fed real data from real traces or actually flying UAVs. Right now it is not written in the manuscript.

Review 3

Summary: Please comment briefly on the following: What are the major contributions of the paper? Do you consider them important? Comment on the degree of relevance, novelty, technical depth and presentation quality of the paper. What are the strengths and weaknesses of the paper?

This paper addresses the problem of managing dense UAV deployments. More specifically, it tackles the problem of position dissemination storm in flying ad hoc networks.

Originality and Impact: Assess the originality of the work and its contribution to the area of research

Has merit but mostly incremental (3)

Presentation: Assess the quality of the presentation in terms of English, organization and completeness

Good (4)

Technical Correctness: Assess the technical correctness of the work

Flaws but Easy to Correct (3)

Relevance: How relevant is the paper to MSWiM?

Definitely Relevant (5)

Reviewer Familiarity: Please assess your familiarity with the subject matter of the paper

Familiar with this area of research (3)

Recommendation: What is your overall recommendation for the paper?

Accept if room (Top 30% but not top 20%) (3)

Detailed Comments: Please provide detailed comments and suggestions to the authors for improving the paper.

The contribution of this paper is incremental. It is built on top of a classical protocol designed to tackle the problem of position dissemination storm, which is the RDF protocol.

There is no comparison with RDF and other related works.