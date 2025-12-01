# Review 1

Orginality	Scientific/Technical Quality	Presentation Quality	Overall Recommendation
Marginal 2		Marginal 2		    Marginal 2			Reject 2

## Strengths
The situation, of a network used for seismic measurements, is interesting and warrants study.

## Weaknesses
The paper lacks professional writing style. Also, it seems to slavlishly follow previous work.

## Comments to Authors

Review of paper 1570854583

Analysis of the IEEE 802.11 DCF for Wireless Seismic Data Acquisition Networks

Abstract
--------

[The abstract is unusually long, and is not written as an abstract.
An abstract should not contain motivation, justification,
or non-essential explanation, just summary of what the paper contains.]

I. INTRODUCTION
---------------
[The paragraphs are much too long. Paragraphs help the reader
to understand the paper. It is essential to use them in this way,
to help the reader. Each paragraph should contain one important
idea, which connects with the previous, and the following, all
of which are coordinated by the headings.]

propagates down
-->
propagate through

and are recorded at the surface
-->
and some of the reflections are recorded at the surface

to wireless telemetry system
-->
to wireless telemetry systems

WGNs often employs
[agreement of plurality]
-->
WGNs often employ

e.t.c.
-->
etc.

Consequently, analysis of how geophones access the shared
wireless medium based on the IEEE 802.11 DCF
[DCF has not been defined yet. It is defined later, but
it should have been defined before the first use. It would
be good, also, to cite, eg, the 802.11 spec. at this point.]

WGNs come with a num-
ber of challenges such as high data rate requirement due to
large aggregate seismic data volume, large scale geophone
deployment, low latency, wireless coverage and connectivity
e.t.c.
[What about the medium. These issues affect all networks.
The reader needs explanation of "Geo"! What does this imply?
Surely there is more to it than the fact that the network
is employed at geological sites?]

error can occur as a result of collision due to
-->
error can occur as a result of collisions due to


[The introduction fails to explain the key difference
between the Geophone context and the usual situation
for 802.11 systems. I am assuming that the key difference
is the behaviour of the medium. But this doesn't seem to 
have been mentioned. If there is nothing _unusual_ about
the medium, and so the only difference is the nature
of the traffic, surely this subject has been fully explored?]

II. RELATED WORK

in most 802.11 networks as majority of real data
-->
in most 802.11 networks as in majority of real situations

Authors in [12], [13]
-->
The authors in [12], [13] [multiple times]

but however fail to incorporate
-->
but however thet failed to incorporate

Nonetheless,
to properly analyze an IEEE 802.11-based geophone station
under the proposed WGN traffic model described in section
III, the model has to take into account unsaturated traffic
conditions, real channel conditions, back-off counter decre-
menting probability, as well as probability to drop a packet.
[Ok. But what makes this case different from those just considered?
I.e. what difference is due to "Geo"?]


III. WIRELESS GEOPHONE NETWORK TRAFFIC MODEL

[It appears from this section's introduction that the
key difference between this work and previous work is
the geophone traffic model. Thus, there is no significant
difference in the medium. The fact that the sensors are geophones
is only significant in this way. This should be made clear in
the introduction.]

Fig. 1
[The quality of this diagram is poor. It needs to be improved.]

we assume a binary queue length
[What does this mean? Binary is a representation format for numbers.
How is this relevant to queue length?]


IV. NETWORK MODEL


A. Geophone Markov Chain Model

(i) Fixed number of homogeneous
geophone nodes with no hidden terminals, and fixed packet
size under unsaturated traffic and real channel conditions in
accordance with the proposed traffic model in [17]
[Not a sentence, lacks punctuation]
-->
(i) there is a fixed number of homogeneous
geophone nodes with no hidden terminals, and fixed packet
size under unsaturated traffic and real channel conditions in
accordance with the proposed traffic model in [17];
[Same comments apply throughout this paragraph]

m denotes the maximum transmission stage,
-->
where m denotes the maximum transmission stage,

backoff = rand
[If multicharacter variable names are used, in latex, 
they should be inside \hbox{.}. The font used inside
mathematics, in latex, should not be used for multicharacter variable
names. This is explained in TeX documentation.]

Fig. 2
[Fonts should be larger. Diagram is hard to interpret. Could be simpler.]

Fig. 3
[Fonts should be larger. The diagram appears to have been distorted.]


B. The Channel State Markov Chain Model

To properly model the time spend
-->
To properly model the time spent

after a collision process.If “c”
-->
after a collision process. If c
[The variable, c, should use a different font.]



V. PERFORMANCE EVALUATION

A. System Throughput

Equations 23 gives the expression for T_s and T_c for basic access mechanism.
-->
Equation (23) gives ...
[even better]
Expression for T_s and T_c for basic access mechanism are 
[Equations, like this, are part of the sentence. The should be
punctuated in that way, not as if they are a different form of expression
than English. Equations should be written grammatically, and with
correct punctuation. This applies to all equations in the paper.]



B. Offered Load (η)


C. Medium Access Delay (D M AC )


D. Model Validation

Fig. 4
[Fonts too small. Diagram appears to be slightly distorted and unclear.]

Fig. 5
[Diagrams are all too small.]

VI. CONCLUSION



# Review 2

Orginality	Scientific/Technical Quality	Presentation Quality	Overall Recommendation
Excellent 4		Excellent 4		   Excellent 4		    Accept 4


## Strengths
This paper utilises Markov Chain Model to expand on a recently proposed method by analytically investigating the performance of the IEEE 802.11 protocol. The study investigates single-hop ad hoc wireless geophone networks under unsaturated traffic and non-ideal channel conditions. The effectiveness of the proposed method is assessed using a set of simulation-based experiments. The results show that the proposed method is able to improve the performance of the baseline method.
As this is not my domain of expertise, my comments are limited to general aspects rather than the technical details of the paper.

## Weaknesses
Please check my comments below.

## Comments to Authors
The paper is well-written and easy to follow; however, I expected to see some comparison to the baseline method in the results section, especially since this is an extended method. Hence, please add comparison results. 
It will also be great to see some statistical significance tests conducted on the results to highlight the significance of the obtained performance.
Can you please justify the parameter settings in Table 1.



# Review 3

Orginality	Scientific/Technical Quality	Presentation Quality	Overall Recommendation
Average 3		Average 3		   Excellent 4		    Accept if Room 3

## Strengths
Based on the well-known Bianchi's model, the authors introduced some modifications taking into account certain specifics of wireless geophone networks. 
This makes their work interesting from a theoretical point of view.


## Weaknesses

The authors of the work devoted a lot of time to modeling of the IEEE802.11 standard network operating in DCF mode, while this mode is rather rarely used, or even abandoned in practice (having in mind more advanced solutions). The authors did not put forward any convincing arguments for e.g. to reject the EDCA mode. Why would such a solution (EDCA) or a hybrid proposal be inferior or unusable in the case of "wireless seismic data acquisition" and "wireless geophone networks".

The simulation parameters at least partly, more refer to the classical Ethernet than to Wi-Fi (e.g. packet lengths). There is no discussion (or explanation) related neither to lengths of MAC&PHY headers  nor ACK.
There is no explanation why only relatively old versions of the IEEE 802.11 standard were used in simulation experiments. Does it mean that the transmission rate does not play any essential role in case of WGNs?

As it was stated earlier the work is interesting from the theoretical point of view, but there is no e.g. comparison with results that could be obtained why applying the classical Bianchi’s model.
Such comparison could show real improvements introduced by the authors.

## Comments to Authors

The authors of the work devoted a lot of time to modeling of the IEEE802.11 standard network operating in DCF mode, while this mode is rather rarely used, or even abandoned in practice (having in mind more advanced solutions). The authors did not put forward any convincing arguments for e.g. to reject the EDCA mode. Why would such a solution (EDCA) or a hybrid proposal be inferior or unusable in the case of "wireless seismic data acquisition" and "wireless geophone networks".

The simulation parameters at least partly, more refer to the classical Ethernet than to Wi-Fi (e.g. packet lengths). There is no discussion (or explanation) related neither to lengths of MAC&PHY headers  nor ACK.
There is no explanation why only relatively old versions of the IEEE 802.11 standard were used in simulation experiments. Does it mean that the transmission rate does not play any essential role in case of WGNs?

As it was stated earlier the work is interesting from the theoretical point of view, but there is no e.g. comparison with results that could be obtained why applying the classical Bianchi’s model.
Such comparison could show real improvements introduced by the authors.

