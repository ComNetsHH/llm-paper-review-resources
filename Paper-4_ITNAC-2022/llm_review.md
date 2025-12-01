
Below is a full peer-review–style evaluation of the provided paper “Analysis of the IEEE 802.11 DCF for Wireless Seismic Data Acquisition Networks”

Review
## **Originality and Impact — Score: 4/5**                   

**Comment:**
The paper addresses an application-specific extension of IEEE 802.11 DCF modeling tailored to Wireless Geophone Networks (WGNs)—a niche but important domain in seismic exploration. The primary contributions—incorporating unsaturated traffic with deterministic arrivals, modeling average backoff slot duration with channel-state Markov chains, and integrating packet drop probability—constitute a meaningful combination of ideas not jointly treated in previous models. The originality is solid, although most components build on well-known prior frameworks (Bianchi, Felemban, Daneshgaran). The impact is moderate but relevant for researchers working at the intersection of wireless communications and seismic acquisition systems.

## **Presentation — Score: 3.5/5**

**Comment:**
The paper is generally well organized, following a conventional structure with clear sections. The writing is understandable but occasionally dense, with some long sentences and minor grammatical issues. Figures (e.g., Markov chains on page 4 and 5 and validation plots on page 8) are informative but visually crowded. Some transitions between sections could be smoother, and the notation could be standardized more consistently (e.g., some variables appear before being explained). Overall presentation is adequate but could benefit from polishing for clarity.

## **Technical Correctness — Score: 4/5**

**Comment:**
The technical framework is detailed and carefully constructed. The mathematical modeling of the DCF under WGN-specific constraints is logically consistent. The integration of the channel-state Markov chain (Fig. 3, page 5) into the backoff duration computation is well developed. The validation results (Fig. 5 on page 8) show close agreement with simulation for reasonable load levels, which strengthens correctness. Some assumptions (e.g., binary queue, strictly deterministic arrivals, quasi-static channel error model) may be restrictive and could be challenged, especially near saturation. Nonetheless, the derivations and arguments appear technically sound.

## **Recommendation — Score: 4/5 (Accept with Minor Revision)**

**Comment:**
This paper provides a useful and rigorous analytical model tailored to WGN scenarios, supported by simulation validation. Minor revisions to improve clarity, notation consistency, and discussion of assumptions will strengthen the paper.

### Summary for the Authors

This paper presents a comprehensive analytical framework extending IEEE 802.11 DCF modeling to Wireless Seismic Data Acquisition (WSDA) networks. It incorporates realistic features such as unsaturated deterministic traffic, backoff counter freezing, average slot duration under channel-state dynamics, and packet drop probability. The model is implemented and validated through OMNeT++ simulations, showing good agreement under typical operating conditions. The work is a meaningful extension of existing literature and contributes a useful tool for designing and evaluating WGN subnetworks.