# Review 1

- Scientific/Technical Quality (Excellent 4)  
- Innovation (Average 3)	
- Presentation Quality (Excellent 4)  
- Overall Recommendation (Accept if Room 3)


## Strengths
- The targeted research area is specific and state-of-the-art, with the need of additional research results towards efficient LDACS aur-to-air communications in sparse networks
- The proposed solution does not exhibit big technical flaws, even if it is not strongly original from the methodological/algorithmic perspectives
- The reported simulation results are sound and relevant, adequately novel if compared with the related state-of-the-art literature
- The paper is generally well organized and well written

## Weaknesses
- From the methodological/algorithmic perspectives, the paper contribution is not of outstanding technical originality: the Authors propose a variant to greedy forwarding that works on a fixed-size subset of neighbors. The application of this algorithm to LDACS is anyway of sufficient novelty
- The paper does not describe any software prototype that implements the proposed solution. No implementation optimizations, no in-depth technical implementation insights, no systems engineering considerations
- The reported simulation results are scarcely reproducible. For example, the developed simulation code is not made available to the community of researchers and practitioners in the field. Please remember that result reproducibility is very relevant for our research community

## Constructive Feedback to Authors
My major revision recommendations, suggestions, and comments have already been listed in the previous parts of this review form. Here I simply add that the paper is generally well organized and well written, with no specific need of minor revision work in order to improve its writing/presentation style.



# Review 2
- Scientific/Technical Quality (Excellent 4)  
- Innovation (Average 3)	
- Presentation Quality (Excellent 4)  
- Overall Recommendation (Accept 4)



## Strengths
The Interesting aspect of this research is the introduction of Greedy-k routing, which improves geographic greedy routing by incorporating k-hop neighborhood information enhancing performance in sparse networks

## Weaknesses
- The density and distribution of nodes is not clear. It require more clarifications.
- It is suggested to elaborate the mobility model in more detail. please see the comments below

## Constructive Feedback to Authors
- It is suggested to show quantitatively how k-greedy algorithm perform vs. the greedy algorithm with respect to amount of possible overhead reduction/addition.
- what would be the best k with respect to different performance metrics?


# Review 3

- Scientific/Technical Quality (Marginal 2)  
- Innovation (Marginal 2)	
- Presentation Quality (Average 3)  
- Overall Recommendation (Reject 2)


## Strengths
The work considers routing and network coverage issues for L-band Digital Aeronautical Communications Systems (LDACS).


## Weaknesses
The coverage and connectivity issues of networks have been well studied in the past years.
Unfortunately, the work did not mention and compare with these efforts in the research area.

## Constructive Feedback to Authors
Theoretical modelling and solution approaches to the coverage issue in wireless sensor networks or UAV networks have been proposed by many research efforts. The work formulates problem from a similar perspective. Why cannot these approaches be directly applied? If the existing solutions to the coverage issue cannot applied, details of discussion should be provided.

The evaluation is not sufficient. The proposed greedy algorithm should be compared with the state of the art.


# Review 4
- Scientific/Technical Quality (Average 3)  
- Innovation (Average 3)	
- Presentation Quality (Excellent 4)  
- Overall Recommendation (Accept 4)


## Strengths
The paper is well written. All important statements are supported by quotations. The results are relevant as there is an application for civil aviation. The proposed approach offers an improvement in sparse networks. Moreover, the figures and plots are of high quality.

## Weaknesses
The research on geographic routing is not new. Also the idea of combining it with greedy forwarding in order to avoid dead-ends which are common in sparse networks.

## Constructive Feedback to Authors
The evaluation methodology need to be described in more detail. It is important to mention the radio channel model you used in your simulations? What was the pathloss model, transmission power, noise, ...