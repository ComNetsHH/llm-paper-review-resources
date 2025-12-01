Here is a structured review of the provided paper **“Spotlight Flooding: Enabling Point-to-Point Control Connection in Urban UAV Networks”** based on your requested criteria.

---

# **Scientific Paper Review**

## **1. Originality and Impact — Score: 4/5**

**Comment:**
The paper addresses an important and timely problem in UAV Traffic Management (UTM): enabling redundant point-to-point control connections in dense UAV networks without relying on infrastructure. The proposed Spotlight Flooding (SLF) and SLF+ protocols extend Rate Decay Flooding (RDF) in a novel, well-reasoned way. The integration of geographic forwarding logic with a flooding-based position-sharing mechanism is innovative and fills a gap between traditional FANET routing and UTM-specific requirements. The analytical selection of the immediate forwarding threshold in SLF+ is also a strong point. While the concept is incremental on the foundation laid by RDF, the contribution is meaningful for the UTM and FANET research communities.

---

## **2. Presentation — Score: 4/5**

**Comment:**
The paper is generally well written and logically structured. The flow from motivation → related work → protocol design → evaluation → conclusion is clear. Figures effectively support the explanation of the protocol mechanisms. English usage is solid, although several sentences could be tightened for readability, and a few typographical inconsistencies exist. The mathematical derivation for the forwarding area is correct but dense; it might benefit from additional explanation or visual aids. Overall, the text is coherent and complete.

---

## **3. Technical Correctness — Score: 4/5**

**Comment:**
The protocol design is carefully reasoned, and the integration with RDF appears technically sound. The simulation methodology (ns-3, 802.11p, repeated runs, confidence intervals) is appropriate and adequately reported. Performance metrics such as PDR, delay, and traffic density are standard and well justified. The assumptions — especially the homogeneous Poisson distribution of UAVs and constant mobility — are reasonable for large-scale evaluation, but the paper could discuss more explicitly how deviations (e.g., structured flight corridors, clustering, urban obstacles) may impact results. SLF+’s aggressiveness and scalability are acknowledged, though more comparison to baseline geographic routing (e.g., GPSR under identical traffic loads) would strengthen the claims. Overall, the technical foundation is solid.

---

## **4. Recommendation — Score: 4/5**

**Comment:**
This is a strong and relevant paper with a clear contribution and convincing evaluation. I recommend **acceptance with minor revisions**. The work is impactful for emerging UAV communication architectures, and the proposed protocols appear both practical and scalable. Improvements in presentation clarity and expanded discussion of limitations would further strengthen the manuscript.

---

If you'd like, I can also provide a harsher review, a reviewer-#2 style critique, or a revision plan to improve the paper before submission.
