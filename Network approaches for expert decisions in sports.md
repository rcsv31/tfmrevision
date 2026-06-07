# ARTÍCULO CIENTÍFICO: Network approaches for expert decisions in sports

## METADATOS DEL ARCHIVO
- **Nombre del archivo:** Network approaches for expert decisions in sports.pdf
- **Título en Metadatos:** Network approaches for expert decisions in sports
- **Autores en Metadatos:** Andreas Glöckner
- **Fecha de creación:** D:2012

## CUERPO DEL DOCUMENTO Y TEXTO COMPLETO
--- [Página 1] ---
Network approaches for expert decisions in sports
Andreas Glöckner a,⇑, Thomas Heinen b, Joseph G. Johnson c, Markus Raab b
a Max Planck Institute for Research on Collective Goods, Bonn, Germany
b German Sport University Cologne, Institute of Psychology, Cologne, Germany
c Miami University, Department of Psychology, Oxford, OH, USA
a r t i c l e
i n f o
Article history:
Available online 27 July 2011
Keywords:
Parallel constraint satisfaction
Accumulator model
Handball
Decision making
Expertise
a b s t r a c t
This paper focuses on a model comparison to explain choices based
on gaze behavior via simulation procedures. We tested two classes
of models, a parallel constraint satisfaction (PCS) artiﬁcial neuronal
network model and an accumulator model in a handball decisionmaking task from a lab experiment. Both models predict action in
an option-generation task in which options can be chosen from the
perspective of a playmaker in handball (i.e., passing to another
player or shooting at the goal). Model simulations are based on a
dataset of generated options together with gaze behavior measurements from 74 expert handball players for 22 pieces of video footage. We implemented both classes of models as deterministic vs.
probabilistic models including and excluding ﬁtted parameters.
Results indicated that both classes of models can ﬁt and predict
participants’ initially generated options based on gaze behavior
data, and that overall, the classes of models performed about
equally well. Early ﬁxations were thereby particularly predictive
for choices. We conclude that the analyses of complex environments via network approaches can be successfully applied to the
ﬁeld of experts’ decision making in sports and provide perspectives
for further theoretical developments.
 2011 Elsevier B.V. All rights reserved.
1. Introduction
At ﬁrst glance, making decisions in sport seems to be a complex task, because they are generally
made under high pressure, limited time, and restricted resources. For the experienced athlete, often
0167-9457/$ - see front matter  2011 Elsevier B.V. All rights reserved.
doi:10.1016/j.humov.2010.11.002
⇑Corresponding author. Address: Max Planck Institute for Research on Collective Goods, Kurt-Schumacher-Str. 10, D-53113
Bonn, Germany. Tel.: +49 (0)2 28 9 14 16 857; fax: +49 (0)2 28 9 14 16 858.
E-mail address: gloeckner@coll.mpg.de (A. Glöckner).
Human Movement Science 31 (2012) 318–333
Contents lists available at ScienceDirect
Human Movement Science
journal homepage: www.elsevier.com/locate/humov

--- [Página 2] ---
the best and the most quickly recognized option in a given situation comes to mind and subsequent
behavior is aligned with this option (Brisson, 2003). Such apparently intuitive decisions by experts,
based on current information intake, are not outside the realm of mathematical modeling and can
be formalized by different models of varying complexity (Johnson, 2006; see also Glöckner &
Witteman, 2010). The goal of the present research is to compare two classes of models that allow
predicting action from attention in complex sport decisions such as the playmakers’ choice to pass
to different team members or to shoot at the goal.
Models of different complexity exist to explain how attention is associated with mental processes
and behavior in a wide range of domains, including everyday activities (Rayner, 1998), consumer
choice (Reisen, Hoffrage, & Mast, 2008), and sports (Memmert & Perl, 2009; Williams, Janelle, &
Davids, 2004). These models, applied to many ﬁelds, differ in their purposes, such as explaining the
processes associated with reading, the inﬂuence of choice strategies on the saccade sequence, the simulation of creative behavior in ambiguous situations, or explaining whether experts and novices use
different gaze strategies anticipating a tennis return. Here we will follow suit with the assumption
that looking, in terms of directing gaze and shifting attention (cf., Vickers, 2007), towards information
rich areas drives and reﬂects preferences and importance (Shimojo, Simion, Shimojo, & Scheier, 2003)
and thus we will use gaze behavior to predict choices in complex decisions in sports.
More speciﬁcally, we will apply two popular general classes of models in this ﬁeld called Parallel
Constraint Satisfaction (PCS) and accumulator models. Both classes can be expressed as networks
(Busemeyer & Johnson, 2004) and have been used previously in many domains, and especially in
sports (Johnson, 2006; Raab, 2001). Both types of models are prepared to predict action, based on
attention, often measured in terms of eye-tracking sequences of ﬁxations and saccades, using keyboard responses (Thomas & Lleras, 2007).
The ﬁrst model we used was a speciﬁc implementation of a PCS model for decision making (Betsch
& Glöckner, 2010; Glöckner & Betsch, 2008a). PCS accounts use a spreading activation mechanism to
model the construction of coherent interpretations based on the overall constellation of available
information (Gestalten; see Read, Vanman, & Miller, 1997). These mechanisms rely on parallel processing, are extremely powerful, operate to a large degree without conscious awareness and have been
suggested as core processes underlying intuition (Betsch & Glöckner, 2010; Glöckner & Betsch,
2008a). Naturally, PCS models can be used to model highly complex processes of perception
(McClelland & Rumelhart, 1981), information chunking in social perception (Read & Miller, 1998),
and coherence construction and interpretation (Thagard, 1989). However, PCS networks have also
been successfully applied to decision tasks similar to the ones considered in the current work, such
as probabilistic inferences (Glöckner, Betsch, & Schindler, 2010; Glöckner & Bröder, in press; Glöckner
& Hochman, in press; Hochman, Ayal, & Glöckner, 2010; see also Glöckner & Betsch, 2008b; Glöckner,
2009), legal intuition in complex tasks (e.g., Glöckner & Ebert, in press; see also Holyoak & Simon,
1999; Simon, 2004), preferential decisions (Simon, Krawczyk, & Holyoak, 2004), selection of plans
(Thagard & Millgram, 1995), and risky choices (Glöckner & Herbold, 2011; see also Glöckner & Betsch,
2008c). Most directly, Raab (2001) has applied such a coherence-constructing network model to ball
allocation decisions in basketball. In the current work, we use the amount of gaze-time directed to certain options as indicator for the information speaking for selecting this option and use this information
as a cue in the previously developed PCS model for decision making (Glöckner & Betsch, 2008a).
The second model class we used was the accumulator models (see Ratcliff & Smith, 2004, for an
overview and comparison). These models have also been very successful in accounting for robust
trends across a variety of domains, including early applications to basic processes such as perceptual
discrimination (Laming, 1968; Link & Heath, 1975) to more recent work on higher-order cognitive processes such as preferential choice (see Busemeyer & Johnson, 2004, for a survey). These models have
also been cast in neural network architectures (Busemeyer, Jessup, Johnson, & Townsend, 2006; Roe,
Busemeyer, & Townsend, 2001) and have been validated in neuroscientiﬁc studies (see Gold &
Shadlen, 2000; and Ratcliff, Cherian, & Segraves, 2003 for two among many examples). Generally,
accumulator models suggest that one or more ‘‘counters’’ keep track of the relative preference for each
option in a set of options, where the position of the counter(s) is updated by momentary ﬂuctuations
in attended information. Our speciﬁc model in this class is based on the simpliﬁed assumption that
gaze to a speciﬁc region of interest provides evidence in favor of options in the corresponding region.
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333
319

--- [Página 3] ---
We state that, as gaze shifts over time, evidence accumulates for options in the corresponding region—
i.e., gaze in a particular region increments the preference ‘‘counter’’ for the options in that region.
More speciﬁcally, our model implies a direct and positive relationship between gaze duration and evidence for a speciﬁc option.
Thus, our conceptual approach suggests that, when people are faced with an ill-deﬁned decision
task, their attention (in terms of directing gaze to a speciﬁc region), during information assessment,
provides a strong indication of their corresponding behavior, which can be formalized with different
models of varying complexity. There is concluding evidence for the existence of such a direct and positive relationship in team handball. Raab and Johnson (2007), for instance, examined expertise-based
differences in visual search and option-generation strategies. Their results show interactions between
gaze behavior and option generation strategies, as well as interactions between the two factors and
expertise of handball players. The authors conclude that option generation strategies are strongly affected by gaze strategies or information search in a complex situation. Further evidence comes from
current studies in cognitive psychology (Glaholt & Reingold, 2009), risky choices (Glöckner & Herbold,
2011), and other decisions (Armel, Beaumel, & Rangel, 2008; Innocenti, Rufa, & Semmoloni, 2010;
Shimojo et al., 2003), demonstrating a clear gaze bias effect toward preferred options.
In this paper, we applied both general classes of PCS and accumulator models to a playmaker decision task. For the PCS model, we used variants of a general decision model for probabilistic inferences
(Glöckner & Betsch, 2008a) for predicting choices in sports. For the accumulator model, we relied on a
previously established simple linear accumulator model for sports decisions (Johnson & Raab, 2003;
Raab & Johnson, 2007). With both general classes of models, we simulated data from a previous study
on passing decisions by handball players. Because previous applications of PCS often use a deterministic outcome (e.g., Glöckner & Betsch, 2008; Glöckner & Bröder, in press) and accumulator models often use a probabilistic outcome (e.g., Johnson, 2006), we will model probabilistic and a deterministic
versions of both model classes in order to allow direct comparisons.
We predicted that both classes of models can model participants’ choices based on sequences of
ﬁxations. As this was the ﬁrst attempt to compare models of these two classes in complex environments in sports, we were open to the question which model would ﬁt and predict best. One rationale
was also to test different implementations of these models with and without free parameters.
The implementation of accumulator and PCS models used in this study implies in the ﬁrst instance
that ﬁxations have the same meaning over the whole inspection period. Because it might be criticized
that this assumption does not hold particularly in complex playmaker decisions, we additionally applied both classes of models to analyze the development of ﬁxations over time in order to capture the
dynamics of gaze behavior across time to predict participant’s choices.
2. Method
2.1. Description of the dataset
We used gaze behavior and option-generation data of 74 participants (handball players) who were
recruited from the state training center and clubs in north Germany and were successful in their
respective divisions. They formed a sub-sample (wave 1 and wave 2) from the study of Raab and
Johnson (2007). Participants provided informed consent before participating in the study, which
was carried out according to the ethical guidelines and with the approval of the University of
Flensburg.
The participants’ task was to list possible options in realistic game situations in handball (see Raab
& Johnson, 2007, for methodological details and descriptive results). On each of the 11 trials at two test
intervals, a video clip was frozen after approximately 10 s of play development. At that moment the
ball was in the possession of one of the players (the playmaker). The frozen frame was held for 6 s
during which participants were asked to generate all plausible courses of action that the playmaker
should consider. The response data of participants was reduced to a discrete value and was coded
by spatial location, such that each response could be classiﬁed as an action directed to the left third,
middle third, or right third of the playing ﬁeld (again, see Raab & Johnson, 2007, for rationale).
320
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333

--- [Página 4] ---
During the decision-task, we collected eye-tracking data by means of a video-based head-mounted
infrared eye tracker from BioMed Jena (2003, version 2.0). These gaze behavior data were classiﬁed
into three regions of interest. To do this, the eye tracker was calibrated to a large video screen for each
trial of the decision-making video test, providing a realistic visual situation from the perspective of the
backcourt facing the goal, near the position of the playmaker. The position of the eyeball was tracked
in real time (25 Hz) and the gaze direction was calculated with regard to the video screen. The eyetracking data were reduced to a sequence of ﬁxation regions (left third, middle third, and right third)
and their respective durations.
Basically, the data consists of information on eye-ﬁxation durations towards the left, the middle, or
the right side of the playing ﬁeld and information on participants’ initial passing option to the left, the
middle, or the right side of the ﬁeld, which should be predicted by our models. In the following, for
simplicity, we refer to this initially generated passing option also as the playmakers’ choice.
2.2. Model Descriptions
In the PCS as well as in the accumulator models, we made the simplifying assumption that ﬁxation
to a speciﬁc area of the visual ﬁeld indicated evidence for the options in the corresponding portion of
the ﬁeld. Speciﬁcally, the total duration of ﬁxation to any region was used as an indicator of the
strength or amount of evidence for the respective part of the ﬁeld. We simulated eight variants of
models in total, four versions of accumulator models and four versions of PCS models. Half of them
were deterministic model implementations (i.e., the model predicts one speciﬁc choice); the other half
were probabilistic model implementations (i.e., the models predict the likelihood for choosing the
favored option). For half of the simulations, we do not ﬁt any parameter; for the other half we do
(although to a different degree; see below). So the total modeling design is a 2 (PCS vs. accumulator
models)  2 (probabilistic vs. deterministic)  2 (parameter ﬁtting yes vs. no) (Table 1).
2.2.1. Parallel constraint satisfaction (PCS) model
The PCS network model for decision making by Glöckner and Betsch (2008a) was adapted to take
into account ﬁxations as cues (Fig. 1). The model consists of a layer of option (i.e., pass options) and
cue nodes (i.e., cues for passing to the respective side). Connections between option and cue nodes
represent cue values, that is, the total amount of information in support of selecting the respective option. Connections between the general weighting node and the cue nodes represent the cue weighting,
that is, the weighting or importance of cues.
Although this network structure is the core of the PCS model by Glöckner and Betsch (2008a), the
original model additionally describes the interaction between automatic-intuitive spreading activation mechanisms and deliberate processes. The latter are assumed to be activated if the network does
not ﬁnd a sufﬁciently coherent interpretation and can, for instance, be used for double-checking. For
pragmatic reasons, in this work we consider the network part of the model only.
PCS models are simulated by setting up the constraints and links among units, and then allowing
the model to converge to a stable pattern of activation after some number of iterations. Activation of
option nodes represents their evaluation; that is, activation of the node for Option A is interpreted as
support for the hypothesis that ‘‘passing to Option A is good.’’ The activation of cue nodes represents
subjective trust in the cue. In other words, higher activation corresponds to more faith or ‘‘weight’’
given to the corresponding cue, which is referred to as cue weighting. To start with, activation spreads
from the general weighting node (i.e., the activation/driver node) in the network to the cue nodes and
Table 1
Overview of Simulated Models.
Without parameter ﬁtting
With parameter ﬁtting
Deterministic
Probabilistic
Deterministic
Probabilistic
PCS
Basic PCSdet
Basic PCSprob
Fitted PCSdet
Fitted PCSprob
Accumulator
Summation Modeldet
Summation Modelprob
Individual Modeldet
Individual Modelprob
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333
321

--- [Página 5] ---
then onto the option nodes. All links are bidirectional, such that increased activation in a node produces an increase of activation for any connected node with a positive link, and a decrease in activation for those connected nodes with negative links. Interconnections between options are all
inhibitory, suggesting a competitive structure where only one option can be selected.
Connections between cues ck ðk 2 f1; 2; 3gÞ and the general weighting node (i.e., wvk) are referred to
as cue weights, which represent a priori judgments about the predictive power or trustworthiness of
cues from the different regions. We set these to a constant in one version of the model and ﬁt it in
another. Connections between option nodes ol ðl 2 f1; 2; 3gÞ and cue nodes ck represent the cue value,
that is, the amount of evidence in region k in favor of selecting option l. We calculated the respective
link weights wck-ol between cues and options (i.e., cue values) based on aggregated ﬁxation durations
to the respective part of the ﬁeld by dividing the absolute aggregated ﬁxations time (in s) by 10. Due to
the fact that the overall ﬁxation time was about 6 s, this scales cue weights down to a conventionally
used range (i.e., they add up to .6).
Once the general weighting or ‘‘driver’’ node is activated, activation spreads through the network in
iterative steps (details below). This continues until a stable level of activation (consistency maximization) is reached which is operationalized by a threshold for changes in activation. Once this state is
achieved, the option with the highest activation is chosen. Activation in the network is spread using
the standard iterative activation function proposed by McClelland and Rumelhart (1981; see also Read
& Miller, 1998):
aiðt þ 1Þ ¼ aiðtÞð1  decayÞ þ
if
inputi < 0
inputiðaiðtÞ  floorÞ
if
inputi P 0
inputiðceiling  aiðtÞÞ

ð1Þ
with
inputiðtÞ ¼
X
j¼1!n
wijajðtÞ
ð2Þ
The parameter ai(t) represents the activation of the node i at iteration t. The parameters ﬂoor and
ceiling stand for the minimum and maximum possible activation (in our model, set to a constant value
of -1 and + 1). Inputi(t) is the amount activation node i receives at iteration t, which is computed by
summing up all products of activations and connection weights wij for node i. Decay is a constant
decay parameter. According to Eq. (1), the activation of all nodes is repeatedly updated in each
Pass right 
ao1
Pass middle 
ao2
Pass left 
ao3
Cues right 
ac1
Cues middle
ac2
Cues left 
ac3
general 
weight 
wv1
wv2
wv3
wc1-o1
wc3-o3
wc2-o2
wo1-o2
wo2-o3
wo1-o3
cue values 
cue weights 
Fig. 1. Parallel Constraint Satisfaction model for passing decisions.
322
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333

--- [Página 6] ---
time-step t + 1, on the basis of the incoming activation from other nodes (i.e., input). This incoming
activation is weighted by the difference in activation of the respective node from the maximum
(i.e., ceiling) or the minimum (i.e., ﬂoor) activation level. Additionally, a proportional decay of previous
activation in each iteration step is assumed. In simple networks as the ones considered in this paper,
the activation of nodes approaches stable levels most often after less than 500 iterations. Activation
changes become very small and stability is considered to be reached after activation changes over several iterations are below a certain threshold. Speciﬁcally, it is determined whether changes in the
overall consistency (Energy) in the network are below a certain threshold over several iterations. Energy is calculated by:
EnergyðtÞ ¼ 
X
i
X
j
wijaiaj
ð3Þ
The iterative algorithm minimizes energy and maximizes consistency under parallel consideration
of all constraints.1 From a more abstract perspective, this can be understood as the best explanation (or
interpretation) given the overall constellation of hypotheses and evidence.
PCS models for the playmaker decision can be constructed on different levels of abstraction. Similar
to PCS models proposed for social perception (Read & Miller, 1998), an overall PCS model with multiple layers of nodes with increasingly complex meanings would be possible. For the sake of simplicity
and considering the limited amount of data, we used the PCS model introduced in Fig. 1 only.
Although the PCS model is rather simple, it basically allows for identifying individual parameters
concerning the (a priori) weighting of cue evidence wvk. However, in the data set the number of different scenarios is at a maximum of 22,2 and therefore we have restricted data for reliable individual
data ﬁtting (cf. Geman, Bienenstock, & Doursat, 1992). Multiple observations per scenario might reduce
the danger of over-ﬁtting. We therefore decided to ﬁt PCS parameters over the total data set of individual
observations (i.e., including data from all subjects) instead of ﬁtting parameters individually for each person. This, of course, makes the model hard to compare to the individual accumulator model which uses
individual parameter ﬁtting and is introduced below.
We simulated a basic PCS that used all equal cue weights and parameters from previous simulations
(Glöckner et al., 2010). No parameter was ﬁtted for this model; we hence applied this model without
relying on any free parameters. We compared this basic PCS model with a ﬁtted PCS in which we ﬁxed
the weight of cue 1 (wv1) and estimated weights for cues 2 and 3 by determining optimal weights for
wv2 and wv3 over all participants. The parameters are summarized in Table 2. In contrast to previous
simulations, we used a lower stability criterion for pragmatic reasons to ﬁnd quicker convergence in
parameter optimization simulations.
In the basic PCS simulation, we used an equal weighting standard parameter for all weights:
wv1 = wv2 = wv3 = .10. For each choice of each participant, we used the aggregated ﬁxation times to
each region to predict the playmakers’ choice. For the deterministic implementations basic PCSdet
and ﬁtted PCSdet, the option that received the highest activation in the network was used as deterministic choice prediction of PCS. To evaluate the model, the proportion of predictions in line with playmakers’ choices pcorr was determined for each participant. For probabilistic implementations basic
PCSprob and ﬁtted PCSprob, we calculated a choice probability for the favored option based on an exponential choice rule that transforms the activation of option nodes into a choice probability (see Appendix). For these models, pcorr was determined for each participant as the average predicted probability
of the chosen option.
In the ﬁtted PCS model simulation, we set wv1 = 0.5 (i.e., the middle of the scale) and used a complete-search algorithm to ﬁnd optimal wv2 and wv3 weights in the parameter space [0.1, 0.2, 0.3 . . .
0.9]. In detail, for each set of parameters, we calculated the proportion of correct choice predictions
for the training set (even trials) and identiﬁed the parameter set that maximized it. A best set was
1 In complex networks, local instead of global minima of energy might be reached by the algorithm. In simple networks as the
one considered here, both usually fall together.
2 Note that some missing values were also encountered if passing decisions could not be classiﬁed as clearly belonging to one or
the other category. We a priori excluded two participants from the initial total of 76 participants for which the overall number of
valid observations was low (subject # 6, 56).
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333
323

--- [Página 7] ---
identiﬁed: wv1 = 0.5, wv2 = 0.8 and wv3 = 0.4, and used to predict choices in the test trials (i.e., odd trials). The set of parameters was determined for the probabilistic version ﬁtted PCSdet and the same
parameters were used for ﬁtted PCSprob.
The resulting PCS model and parameters can be interpreted as follows. The aggregated ﬁxation
duration, measured by eye-tracking, is used to determine the cue values in the model; this is the
strength of the evidence for the option in the given region (see Table 2). For instance, if half of the
ﬁxation time was in the left region, and the remaining half was divided evenly among the middle
and right region, then we assumed that there was twice as much evidence for the left options as
compared to the options in the middle or right regions, and the latter evidence would be equal
(i.e., wo1-c1/2 = wo2-c2 = wo3-c3). The ﬁnal (ﬁt) values of the cue weights suggest that evidence in the
middle region was, on average, weighted most (wv2 = 0.8), followed by the left (wv1 = 0.5), and then
by the right region (wv3 = 0.4). Stated differently, there was a bias towards the center in that even if
there was the same sum of ﬁxation times to all three regions, the center region was more likely to
be chosen (see also the baseline model below).
2.2.2. Accumulator models
In order to evaluate the quantitative ﬁt of the model, we compared the PCS models to two
accumulator models in deterministic and probabilistic implementations, respectively. These models
used the same data (eye-tracking ﬁxations) to predict the same outcome (choices), but in a different framework. The PCS models used ﬁxation duration in the aggregate to determine the cue
value—how much evidence speaks for passing to region k? The PCS models also ﬁt the weighting
of each cue as free parameters (or assume that weights are all equal). Weights indicate how
strongly one should consider cue information (ﬁxations) contained in region k in the decision. Another interpretation, formalized below, is to use the ﬁxation duration to ‘‘hard-code’’ the relative
attention to each region instead, under the assumption that visual attention to a region produces
consideration of, or ‘‘weight to’’, the evidence in that region. Hence, the proportion of weight to a
region is simply proportional to the ﬁxation time spent in the region. Then, in the accumulator
model, the link between attention and evidence was assumed to be holistic, which means that,
given that attention is in region k, attention is complete to every single option in that region.
For instance, if gaze shifts to the right for 800 ms and then to the middle for 1600 ms, this model
would expect more evidence for options in the middle. Note that the same result is reached in PCS
by determining cue values from gaze durations (see Table 2).
We used an additive model, implying a direct and positive relationship between gaze duration and
evidence for a speciﬁc option. Thus, spreading activation in an accumulator network and spreading
Table 2
Model Parameters for PCS Simulations.
Value/Function
Comment
Decay
.05
Decay parameter for node activation; inﬂuences the
overall activation level of the nodes, the higher the value
the lower the ﬁnal activation level.
wo1-o2
-.20
Inhibitory connection between options; inﬂuences the
size of information distortions (coherence shifts); the
stronger the inhibitory connection the stronger the
coherence shifts.
wo1-o3
wo2-o3
wc1-o1
w = (ﬁx_time/10)
CUE VALUES: Connection between cues and options
representing the strength of the evidence.
wc2-o2
wc3-o3
wv1
constant or ﬁtted
CUE WEIGHTS: Links between general weighting node
and cues representing a priori cue weighting.
wv2
wv3
ceiling/ﬂoor
1/-1
Upper and lower limit for cue activations.
Stability criterion
10 trials energy change < 104
Stopping criterion for the iterative updating algorithm.
324
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333

--- [Página 8] ---
activation in a PCS network are conceptually different, such that in the accumulator model, gaze
behavior is accumulated dynamically, whereas in the PCS network it is aggregated a priori to serve
as a static cue for inference. From this point of view, the accumulator model suggests evidence E
for a speciﬁc region r after a speciﬁc stream of n gaze ﬁxations can be formalized as follows:
ErðnÞ ¼ b  Erðn  1Þ þ trðnÞ
ð4Þ
As can be seen from Eq. (4), Er(n) is equal to a weighted sum of the previous evidence Er(n-1) and
the current ﬁxation duration to the corresponding region tr(n). The parameter b can be used to incorporate growth or decay of evidence for a speciﬁc region. If b departs from zero, Er(n) reﬂects either primacy (b > 1) or recency (b < 1) effects. If the parameter b is equal to 1, then evidence is equal to the
total ﬁxation duration to the region. b = 0 suggests extreme decay such that evidence is based only
on the most recent ﬁxation. We used an individual’s stream of gaze ﬁxations and durations on a given
trial to compute evidence for all three regions (left, middle, right), reﬂecting the potential options in
these areas. In the next step, we used a ratio choice rule to compute the probability that the choice
(i.e., the initially generated option for the trial) would be generated within each region:3
Pr½Initial option in region k ¼
EkðnÞ
P ErðnÞ
ð5Þ
In the ﬁrst step, we incorporated no primacy or recency effects in our model (b = 1 for each individual). We refer to this model as a summation model. In the second step, we adjusted the parameter
b to maximize the average probability of a correct prediction across trials for each participant. We refer to this model as the individual model (b adjusted).
For the probabilistic implementations summation modelprob and the individual modelprob, we calculated pcorr as the probability (Eq. (5)) that the model correctly predicted the region on each trial and
then averaged across trials, for each individual. For the deterministic implementations summation
modeldet and the individual modeldet, the prediction was that the option with the highest probability
is chosen. We calculated pcorr as the proportion of correct predictions per person.
Baseline model. To evaluate further the suggested models, we created two simple baseline models as a benchmark. The ﬁrst model was a deterministic baseline model. Most choices were for the
middle region; hence, it had the highest base-rate probability. So the best prediction without data
would be to predict choices for the middle region. For each person we calculated the proportion of
correct predictions with this simple rule as baseline. The second baseline model had a probabilistic
structure. It referred solely to participants’ global proportion of choices across trials and for different regions. For example, if 70% of a participant’s choices across trials were for the left region
compared to other regions, then the baseline model would predict choices for the left region of
.70 for every trial.
2.3. Model comparison procedure
In order to correct for overﬁtting, we used a cross-validation procedure. Models with free parameters were ﬁtted to half of the data according to an even–odds method and the resulting parameters
were used to predict the other half of the data. Hence, the comparison of pcorr between models in the
cross-predicted test trials is the most informative one. The overall ﬁt is, in contrast, only partially
informative and the comparison between ﬁtting and test trials provides information concerning the
prevalence of overﬁtting. Note that for all models (except for baseline) predictions are made on an
individual level, that is, predictions are derived for each choice situation and each participant separately taking into account persons’ individual ﬁxation data. Note also that the ﬁtted PCS models do
use two free parameters to ﬁt the total sample, whereas the ﬁtted individual model uses one parameter per person (which means 74 parameters for the total dataset). The ﬁtted models are therefore
only partially comparable.
3 Ek(n⁄) refers to evidence for (ﬁxations to) the chosen option in region k; Er(n⁄) refers to evidence for all options.
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333
325

--- [Página 9] ---
3. Results
In order to compare the models, we calculated the overall prediction performance of choice from
gaze behavior for each of the models in both the deterministic and the probabilistic version. In a second step, we performed cross-validation tests on all models, incorporating only the even trials
(n = 485; i.e., participants X trials) for model ﬁtting, and predicting the odd trials from the corresponding model equations (n = 529). In a third step, we conducted an additional analysis on the development of ﬁxations over time in order to capture the dynamics of gaze behavior across time.
3.1. Performance in prediction
The performance of the two PCS models and the two accumulation models are shown along with
the performance baseline in Table 3. The baseline model achieved a mean accuracy across participants
of .436, which is better than chance performance of one-third (t-test against l = .33: t(73) = 7.13,
p < .001). Accuracy in the even trials was higher than in the odd trials, indicating that there were fewer
choices for the middle region in the odd trials.
Overall, all considered models performed better than chance and better than the baseline in their
predictions (test trials). The deterministic implementations of the models predicted better than their
probabilistic counterparts: by about 4 to 5%. The performance differences in predictions between the
different types of models (PCS vs. accumulator models) and ﬁtted vs. unﬁtted implementation were
small. The performance of the deterministic models was essentially equal with differences of less than
half a percent. The individual modeldet was the best model. The almost equal performance is thereby
due to the extremely high overlap of predictions instead of aggregation. Basic PCSdet and summation
modeldet, for example, make the same predictions for all but three cases in which the PCS model did
not converge.
Concerning probabilistic implementations of the models, the basic PCS was the best model in prediction, which was about 2% better than the worst model, the individual model. The individual model
seemed to suffer from overﬁtting, in that there was a particularly large difference between ﬁtting and
prediction performance. The low number of observations that were ﬁtted with one parameter seemed
to have induced the problem. Therefore, the data do not speak against the argument that individual
Table 3
Simulation Results.
Proportion Correct (pcorr)
Baseline
model
Basic PCS (equal
weighting)
Fitted PCS
(ﬁtted weighting)
Summation
model (b = 1)
Individual model
(b adjusted)
Probabilistic Models
Fitting/Training (even trials)
.457 (.013)
.523 (.017)
.514 (.016)
.512 (.016)
.605 (.017)
Prediction/Test (odd trials)
.320 (.013)
.509 (.014)
.498 (.013)
.497 (.012)
.483 (.022)
Overall
.388 (.010)
.516 (.013)
.506 (.011)
.505 (.011)
.570 (.013)
Deterministic Models
Fitting/Training (even trials)
.475 (.021)
.596 (.026)
.597 (.024)
.597 (.026)
.691 (.020)
Prediction/Test (odd trials)
.404 (.021)
.545 (.022)
.548 (.023)
.549 (.022)
.549 (.027)
Overall
.436 (.015)
.570 (.018)
.572 (.019)
.572 (.018)
.666 (.015)
Notes: The baseline (deterministic) model predicts choices based on base-rates only. Because most choices were for the middle
region, it predicts the middle region for all choices. The basic PCS model predicts choices from cue values that are estimated
from ﬁxation durations to the respective areas using equal weights for all ﬁxations. The ﬁtted PCS model uses optimized
weighting of cue values. The data is best explained by a middle-region choice bias in that choices for the middle region are more
likely for the same ﬁxation times to this region (cue weights: wv1/right = 0.5, wv2/middle = 0.8 and wv3/left = 0.4; weights were ﬁtted
for ﬁtted PCSdet and the same weights were used for the ﬁtted PCSprob). The summation model uses Eq. (4) with b = 1, and the
individual model uses Eq. (4) with most accurate b value for each individual. Fitting/training refers to the even trials that were
used for data ﬁtting. Prediction/Test refers to the models prediction performance in the odd trials which are most informative
for model comparisons (bold). Overall values refer to all trials. Standard errors are provided in parentheses. We used data from
N = 74 experts including n = 485 even trials and n = 529 odd trials.
326
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333

--- [Página 10] ---
differences in weighting play a role as suggested by the individual model. However, more observations
seem to be necessary to ﬁt these parameters.
3.2. Development of ﬁxations over time
The implementation of accumulation and PCS models used in this study implies that ﬁxations have
the same meaning over the 6 s inspection period. PCS models aggregates over all ﬁxations a priori and
the accumulation models add them up to overall preference values after weighting them. It might be
criticized that this simplifying assumption does not hold particularly in complex playmaker decisions.
According to an initial-scanning hypothesis, one could assume that in order to maximize information
input initial ﬁxations are used for scanning all options. Hence, initial ﬁxations might be unrelated to
preferences for speciﬁc option. Initial scanning would lead to a ﬂat distribution of ﬁxations over all
options in the ﬁrst seconds. After a preliminarily favored option has been identiﬁed, ﬁxations might
show a J-shaped distribution in that people strongly focus on the favored option, which then might
represent preferences.
Alternatively, it might be possible that cues in the scene direct ﬁxations automatically and instantly
to the favored option without a necessity for scanning all options. One might therefore also predict the
exact opposite, namely a relatively early focusing on the favored options, which has also been found in
recent studies (Innocenti et al., 2010). According to the PCS model by Glöckner and Betsch (2008a) and
other default-interventionist models for dual processing (see Evans, 2008, for an overview), it might
be argued, furthermore, that these quick automatic processes are followed by deliberate checking processes which include checking and comparing with non-favored options. Hence, the second prediction
from this perspective would be that there are more ﬁxations to the non-preferred options in the later
part as compared to the earlier part of the inspection period.
To investigate this issue, we divided ﬁxations into the categories ‘‘early’’, ‘‘middle’’ and ‘‘late’’,
according to whether ﬁxations started in the ﬁrst, middle or last two seconds of the inspection period.
We ﬁnd that the proportion of ﬁxation time towards the favored option decreased over time (Fig. 2,
left). A regression of the proportion-of-ﬁxation-time-index on a linear time-period variable (with values 1, 2, 3 for ‘‘early’’, ‘‘middle’’ and ‘‘late’’ ﬁxations) correcting for clusters in observations and for
ﬁxed effects of trial and training session due to repeated measurement (Rogers, 1993) turned out signiﬁcant, b = -.045, t = 7.30, p < .0001.
Furthermore, if we aggregate ﬁxation times separately for the three time periods, the predictive
performance of, for example, the basic PCSdet model is highest when using data from the ﬁrst 2 s
and it decreases over time (Fig. 2, right). As mentioned above, the other considered models make
essentially the same predictions and therefore show the same development. Note that considering
the ﬁxations from the ﬁrst 2 s only, the predictions of the model would be almost 10% better than
when using ﬁxations from the last two seconds and even 2% better than when considering all
ﬁxations.
Both ﬁndings support the prediction of PCS and other default-interventionist models that there is a
quick intuitive reaction that might later on be checked by further inspections of other areas. The data
speak against the initial-scanning hypothesis and later ﬁxation to the favored region. The results
might also indicate that playmakers are able to identify the favored option very quickly and that
choices might not be due to a summation of preference values over the whole inspection time.
4. Discussion
The goal of the present research was to compare two classes of models with varying complexity
and formalization to predict individuals’ courses of actions from gaze behavior data, representing
players’ visual attention. We were especially interested in the extent to which models with varying
complexity and in different implementations can predict speciﬁc choices. We approached this goal
by using eye-tracking and option-generation data from expert handball players and modeled choices
(in terms of courses of action) from gaze behavior (in terms of ﬁxation sequences) in a realistic
decision-task.
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333
327

--- [Página 11] ---
4.1. Performance in prediction
We found that the models we calculated were better than chance level and a baseline model in predicting option-generation from eye gaze. For deterministic implementations of PCS and accumulation
models, we found essentially equal performance in prediction between all models with a slight advantage for the individual modeldet. Interestingly, this similarity in performance was not due to aggregation, but caused by the fact that the models essentially make the same predictions for almost all
decision tasks for which they can be calculated. The predictive accuracy for probabilistic models
was in general 4 to 5% lower than for deterministic models and showed some differences between
models. Considering probabilistic models only, the basic PCSprob model performed best in prediction
and was 2% better than the worst-performing individual modelprob. We thereby took the problem of
overﬁtting seriously and followed the cross-validation procedure (cf. Mosier, 1951; see Browne,
2000, for discussion), instead of taking into account the overall accuracy. Performance of models
was evaluated on the basis of performance in the predicted (test) trials only.
In our small sample of observations, ﬁtting additional model parameters did not increase predictive
performance of the models substantially. The ﬁtted PCS did not outperform the basic PCS, nor did the
individual accumulation model outperform the summation model in predictions. Hence, the higher
complexity did not lead to higher performance. This ﬁnding, should, however, only be interpreted with
caution. It might be partially due to the fact that the ﬁtting sample was too small.
Taking a broader perspective, the reasonable ﬁt of PCS models as well as accumulation models provide further evidence supporting the notion that the attention given to certain cues that are measured
by perceptual information acquisition can predict subsequent choice behavior. Theoretically, it is
interesting to compare the nature of the explanations for the different models. The PCS models incorporated visual attention (ﬁxation duration) to represent cue values, that is, how much evidence supports the option in that region, and ﬁts the weight of each cue as free parameters (or sets it to a
constant). In contrast, the evidence accumulation models used visual attention to determine how
much relative weight was given to each region, using the data rather than ﬁtting this construct as free
parameters (or assuming a uniform constant). The only free parameter in the evidence accumulation
.46
.48
.5
.52
.54
.56
p
early
middle
late
starting time of fixation
Proportion of Fixation Time to the Favored Option
.46
.48
.5
.52
.54
.56
p(corr)
early
middle
late
starting time of fixation
Proportion correct for PCS
Fig. 2. Development of the proportion of ﬁxations to the favored option over time (left) and proportion of correct predictions of
the basic PCSdet model over time. Each category on the x-axis represents ﬁxations from consecutive 2 s time-frames.
328
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333

--- [Página 12] ---
models was used to measure the dynamic inﬂuence of the ﬁxation stream. This also highlights a key
distinction between the current simpliﬁed implementation of PCS and evidence accumulation approaches. Passage of time in the PCS models occurs only in terms of activation updating iterations,
and the dynamic nature of the input data is lost (ﬁxation durations were entered in the model after
being aggregated over time per choice). However, in the evidence accumulation models, the dynamic
input is central to the function of the model, and the idiosyncratic use of this information over time is
embodied in the single free parameter b. This allows the accumulation models to make speciﬁc
predictions about the dynamics of processing that the PCS models in the simpliﬁed implementation
used in this paper do not (but see below). In contrast, the ﬁtted parameter in the PCS model might
incorporate something like an overall choice bias. Higher values for certain areas mean that choices
are more likely for this area given the same amount of ﬁxations. Note that the ﬁtted parameter was
highest for the middle region, for which also the majority of choices was observed.
4.2. Development of ﬁxations over time
Taking a closer look at the development of ﬁxations over time indicates that expert playmakers
show an early focus of attention towards the chosen option within the ﬁrst 2 s. Afterwards, however,
they shift attention more strongly towards the non-favored options. One explanation for this ﬁnding is
that expert playmakers have learned to react intuitively to certain cues that shift attention to the
favored option. Later on, more deliberate information search processes might be activated to
double-check this automatic orientation reaction, which include comparisons with other options. This
explanation would be in line with default-interventionist dual-process models (see Evans, 2008, for an
overview). It would also accord with the full dual processing PCS model by Glöckner and Betsch
(2008a) from which in this paper only the (ﬁrst layer) network part was modeled. The ﬁndings are also
in line with results demonstrating quick ﬁxations to the preferred option (Innocenti et al., 2010), an
over-time increase in between gamble comparisons in risky choices (Glöckner & Herbold, 2010), as
well as the ﬁnding that people are able to generate complex intuitive responses within less
than 2 s (Glöckner & Betsch, 2008b; Glöckner & Hodges, in press).
4.3. Relation to the quiet-eye concept
Our results extend empirical evidence regarding the well-elaborated quiet eye concept (Vickers,
2007). Quiet eye is a stabilization of the retinal picture during which the gaze is directed at a speciﬁc
position in the visuomotor workspace for a minimum of 100 ms. It occurs prior to the ﬁnal movement
of a task, and its onset and offset depend on speciﬁc movements in the task. In other words, it is seen
as the last piece of visual information before performing the ﬁnal critical movement in a speciﬁc skill
such as putting or shooting a basket. This piece of visual information is thought to be the most important information an athlete needs in order to perform the skill successfully (quiet eye duration). In line
with this point of view, most often the quiet eye duration is analyzed and shifts in attention over time
prior to this ﬁnal ﬁxation are neglected. However, instead of analyzing only the last piece of visual
information prior to the ﬁnal critical movement in a speciﬁc skill, our research clearly demonstrates,
that—at least in our experimental task—shifts in attention over time need to be acknowledged in order
to predict playmakers’ choices and their success. The systematic shifts in attention over time indicate
that the six-second period in our experimental task should not be interpreted as an unweighted accumulation process, which leads to a choice at the end. Choice preferences seem to be reached much earlier and—according to the above-suggested interpretation—early vs. late ﬁxations might have
conceptually very different meanings for handball players. Perceptual expertise in handball seems
to depend on the recognition of information about a speciﬁc pattern of play in a given situation,
and on the exploration of possible choices and their consequences (Gobet, 1997).
4.4. Probabilistic vs. deterministic implementations
It is interesting that the accumulator models discussed here are usually applied in a probabilistic
implementation, whereas the PCS model is often used in a deterministic one. We ﬁnd, however, that
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333
329

--- [Página 13] ---
each type of model is particularly good in the implementation that is less often used. This ﬁnding
might inspire fruitful further developments of the models. The ﬁnding that deterministic models show
a higher pcorr score compared to probabilistic models should not be over-interpreted because a methodological difference should be kept in mind: for deterministic models, pcorr was determined as the
average proportion of correct predictions per person (i.e., correct predictions/all predictions) because
the models’ outputs are speciﬁc choice predictions. Probabilistic models, in contrast, predict probabilities of choice for each option; hence, pcorr was determined as the average proportion for selecting the
option, which was actually chosen by the playmaker. Further research is needed to determine whether
this methodological difference drives the lower performance of probabilistic models.
4.5. Possible developments and further investigations
A crucial comparison of further applications of these general types of models seems to depend on
the underlying conceptual assumptions such as whether overall gaze is used as a cue, such as in the
current PCS implementation, or if a more complex temporal weighting of associations between attention and choice is assumed such as in the accumulator model. Interestingly, the good ﬁt for both types
of models suggest that even conceptually different models are able to describe how gaze informs
choices. Whether one model or the other may in general predict behavior in complex environments
better is a matter of further empirical investigations that may use further type of models as comparison standards as well as demonstrated in this special issue.
In spite of its good ﬁt, the simplifying assumption of the current implementation of PCS are certainly unsatisfying from a theoretical perspective and should be reﬁned in further versions of the model. Using ﬁxations as a proxy for cue values can only be a ﬁrst step to understand experts’ (intuitive)
decision making. One advantage of PCS is, however, that it can be easily extended in this direction. It
has already been discussed elsewhere how the PCS approach to experts’ decision making could take
into account training effects and construction of complex knowledge structures in expertise development (Herbig & Glöckner, 2009; Holyoak, 1991; Spellman, 2010). Similar to expertise development in
chess, experts in handball are likely to acquire complex knowledge structures which allow chunking of
information, instantly recognizing increasingly complex constellations of the game and reacting
appropriately. In further research, the simple cue value approximations used in the current PCS model
should be replaced by complex information chunks that are represented in multiple layers of nodes
with increasing complexity of meaning (Holyoak, 1991). Investigations of these issues would, however, necessitate considerably more in-depth analyses of mental structures, as well as much more
observations per individual to allow a more ﬁne-grained analysis of mental representations and ﬁtting
of PCS. In such an attempt, PCS could take into account primacy and the recency parameter as well if
they prove to be important mediators in further work on accumulator models.
4.6. Perspective for improved practice
From a Bayesian perspective, and assuming that there are no costs for information, models should
maximize and use all information. However as the application to probabilistic and dynamic decisions
in sports shows, athletes may end up not using all information available (Vickers, 2007). Far from providing conclusions on how to optimize decision-making in ill-deﬁned task, we acknowledge that expert decision makers are not born, but made through a combination of developmental experiences as
children, and then through quality coaching that provides on- and off-court decision making training
opportunities (Farrow & Raab, 2008). Coaches should be encouraged to use training programs which
implement tasks that vary in temporal as well as spatial demands, so that the developing athlete has
the opportunity to explore his/her individual gaze behavior and option generation strategy. Moreover,
athletes could be encouraged to generate options in situation where a limited set of options are available (Raab & Johnson, 2007).
We believe that our research makes an important contribution in providing further evidence for the
link between perception and cognition. In particular, it highlights the ability to predict choice behavior
directly from perceptual inputs from different points of view and even in the absence of detailed
assumptions about mental representations or transformations thereof. Nevertheless, on the basis of
330
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333

--- [Página 14] ---
our work, more complex model implementations might be developed that could take into account
mental structures as described above. An important challenge for future modeling approaches is
the observation from this and other papers (e.g., Innocenti et al., 2010) that early ﬁxations are more
predictive for choice than later ones. Furthermore, it has to be explained how early orientation reactions towards the preferred option arise.
Although sports tasks provide a useful test bed for our models, it is important to generalize the
ﬁndings of the current study beyond the sports domain. We have no reason to believe that the current
results are speciﬁc to the sports domain. Our models could be applied to many domains, situations or
tasks studied within the naturalistic decision making approach (Klein, 1993) such as parking and
selecting living spaces (Gettys, Pliske, Manning, & Casey, 1987) or problem-solving in chess (Gobet,
1997), just to name a few. First attempts have been done to do so in risky decision (Glöckner &
Herbold, 2011), but much more work in this direction is needed.
Appendix
One of the differences between PCS and the accumulation models is that the former are usually
implemented as deterministic models whereas the latter are implemented as probabilistic models.
Hence, it might be argued that differences in predictive performance might result from this difference.
Therefore we tested both models in probabilistic and deterministic implementations. For accumulation models the implementations are described in the main text. For PCS the probabilistic implementation was done as follows:
We implemented the basic PCSprob and the ﬁtted PCSprob as probabilistic model using an exponential choice rule on the ﬁnal activation of the option nodes according to
Pr½chosen k ¼
ekaok
P
i¼1!3ekaoi ;
with aok indicating the network activation of the chosen option, aoi indicating the activation of all
three options (which are summed up), and k as scaling parameter that was ﬁtted to the data (in
the interval [0, 3]). We ﬁtted k for even trials using a complete search algorithm and used it to predict
odd trials resulting in k = 2.90.
References
Armel, K. C., Beaumel, A., & Rangel, A. (2008). Biasing simple choices by manipulating relative visual attention. Judgment and
Decision Making Journal, 3, 396–403.
BioMed Jena GmbH (2003). Handbuch für das biovision eye-tracking [Handbook of biovision eye-tracking] Version 2.0. Jena,
Germany: Eigenverlag.
Betsch, T., & Glöckner, A. (2010). Intuition in judgment and decision making: Extensive thinking without effort. Psychological
Inquiry, 21, 279–294.
Brisson, T. (2003). Player’s perspective: Therese Brisson. In J. L. Starkes & K. A. Ericsson (Eds.), Experts performance in sports:
Advances in research on sport expertise (pp. 216–218). Champaign, IL: Human Kinetics.
Browne, M. W. (2000). Cross-validation methods. Journal of Mathematical Psychology, 44, 108–132.
Busemeyer, J. R., & Johnson, J. G. (2004). Computational models of decision making. In D. J. Koehler & N. Harvey (Eds.), Blackwell
handbook of judgment and decision making (pp. 133–154). Malden, MA: Blackwell Publishing.
Busemeyer, J., Jessup, R., Johnson, J., & Townsend, J. (2006). Building bridges between neural models and complex decision
making behaviour. Neural Networks, 19, 1047–1058.
Evans, J. S. B. T. (2008). Dual-processing accounts of reasoning, judgment, and social cognition. Annual Review of Psychology, 59,
255–278.
Farrow, D., & Raab, M. (2008). A recipe for expert decision making. In D. Farrow, J. Baker, & C. MacMahon (Eds.), Developing sport
expertise. Researchers and coaches put theory into practice (pp. 137–154). London & New York: Routledge.
Geman, S., Bienenstock, E., & Doursat, R. (1992). Neural networks and the bias/variance dilemma. Neural Computation, 4, 1–58.
Gettys, C. F., Pliske, R. M., Manning, C., & Casey, J. T. (1987). An evaluation of human act generation performance. Organizational
Behavior and Human Decision Processes, 39, 23–51.
Glaholt, M. G., & Reingold, E. M. (2009). The time course of gaze bias in visual decision tasks. Visual Cognition, 17, 1228–1243.
Glöckner, A., & Betsch, T. (2008a). Modeling option and strategy choices with connectionist networks: Towards an integrative
model of automatic and deliberate decision making. Judgment and Decision Making, 3, 215–228.
Glöckner, A., & Betsch, T. (2008b). Multiple-reason decision making based on automatic processing. Journal of Experimental
Psychology: Learning, Memory, and Cognition, 34, 1055–1075.
Glöckner, A., & Betsch, T. (2008c). Do people make decisions under risk based on ignorance? An empirical test of the Priority
Heuristic against Cumulative Prospect Theory. Organizational Behavior and Human Decision Processes, 107, 75–95.
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333
331

--- [Página 15] ---
Glöckner, A., & Ebert, I. D. (in press). Legal intuition and expertise. In M. Sinclair (Ed.), Handbook of intuition research.
Northampton, MA: Edward Elgar.
Glöckner, A., & Herbold, A.-K. (2011). An eye-tracking study on information processing in risky decisions: Evidence for
compensatory strategies based on automatic processes. Journal of Behavioral Decision Making, 24, 71–98.
Glöckner, A., & Hodges, S. D. (in press). Parallel constraint satisfaction in memory-based decisions. Experimental Psychology.
Glöckner, A., Betsch, T., & Schindler, N. (2010). Coherence shifts in probabilistic inference tasks. Journal of Behavioral Decision
Making, 23, 439–462.
Glöckner, A. (2009). Investigating intuitive and deliberate processes statistically: The Multiple-Measure Maximum Likelihood
strategy classiﬁcation method. Judgment and Decision Making, 4, 186–199.
Glöckner, A., & Bröder, A. (in press). Processing of recognition information and additional cues: A model-based analysis of
choice, conﬁdence, and response time. Judgment and Decision Making.
Glöckner, A., & Hochman, G. (in press). The interplay of experience-based affective and probabilistic cues in decision making:
Arousal increases when experience and additional cues conﬂict. Experimental Psychology.
Glöckner, A., & Witteman, C. L. M. (2010). Beyond dual-process models: A categorization of processes underlying intuitive
judgment and decision making. Thinking & Reasoning, 16, 1–25.
Gobet, F. (1997). A pattern-recognition theory of search in expert problem solving. Thinking and Reasoning, 3, 291–313.
Gold, J., & Shadlen, M. (2000). Representation of a perceptual decision in developing oculomotor commands. Nature, 404,
390–394.
Herbig, B., & Glöckner, A. (2009). Experts and decision making: First steps towards a unifying theory of decision making in
novices, intermediates and experts. MPI Collective Goods Preprint, No. 2009/2. Available at SSRN: <http://ssrn.com/
abstract=1337449>.
Hochman, G., Ayal, S., & Glöckner, A. (2010). Physiological arousal in processing recognition information: Ignoring or integrating
cognitive cues? Judgment and Decision Making, 5, 285–299.
Holyoak, K. (1991). Symbolic connectionism: Toward third-generation theories of expertise. In K. A. Ericsson & J. Smith (Eds.),
Toward a general theory of expertise (pp. 301–336). Cambridge: Cambridge University Press.
Holyoak, K. J., & Simon, D. (1999). Bidirectional reasoning in decision making by constraint satisfaction. Journal of Experimental
Psychology: General, 128, 3–31.
Innocenti, A., Rufa, A., & Semmoloni, J. (2010). Overconﬁdent behavior in informational cascades: An eye-tracking study. Journal
of Neuroscience, Psychology, and Economics, 3, 74–82.
Johnson, J. G. (2006). Cognitive modeling of decision making in sports. Psychology of Sport and Exercise, 7, 631–652.
Johnson, J. G., & Raab, M. (2003). Take the ﬁrst: Option generation and resulting choices. Organizational Behavior and Human
Decision Processes, 91, 215–229.
Klein, G. A. (1993). A recognition-primed decision (RPD) model of rapid decision making. In G. A. Klein, J. Orasanu, R. Calderwood,
& C. E. Zsambok (Eds.), Decision making in action: Models and methods (pp. 138–147). Westport, CT: Ablex Publishing.
Laming, D. (1968). Information theory of choice-reaction times. New York: Academic Press.
Link, S., & Heath, R. (1975). A sequential theory of psychological discrimination. Psychometrika, 40, 77–105.
McClelland, J. L., & Rumelhart, D. E. (1981). An interactive activation model of context effects in letter perception: I. An account
of basic ﬁndings. Psychological Review, 88, 375–407.
Memmert, D., & Perl, J. (2009). Analysis and simulation of creativity learning by means of artiﬁcial neural networks. Human
Movement Science, 28, 263–282.
Mosier, C. (1951). The need and means of cross validation. I. Problems and designs of cross-validation. Educational and
Psychological Measurement, 11, 5–11.
Raab, M. (2001). T-ECHO: Model of decision making to explain behavior in experiments and simulations under time pressure.
Psychology of Sport and Exercise, 3, 151–171.
Raab, M., & Johnson, J. (2007). Expertise-based differences in search and option-generation strategies. Journal of Experimental
Psychology: Applied, 13, 158–170.
Rayner, K. (1998). Eye movements in reading and information processing: 20 years of research. Psychological Bulletin, 124,
372–422.
Ratcliff, R., & Smith, P. (2004). A comparison of sequential sampling models for two-choice reaction time. Psychological Review,
111, 333–367.
Ratcliff, R., Cherian, A., & Segraves, M. (2003). A comparison of macaque behavior and superior colliculus neuronal activity to
predictions from models of two-choice decisions. Journal of Neurophysiology, 90, 1392–1407.
Read, S. J., & Miller, L. C. (1998). On the dynamic construction of meaning: An interactive activation and competition model of
social perception. In S. J. Read & L. C. Miller (Eds.), Connectionist models of social reasoning and social behavior (pp. 27–68).
Mahwah, NJ: Lawrence Erlbaum Associates Publishers.
Read, S. J., Vanman, E. J., & Miller, L. C. (1997). Connectionism, parallel constraint satisfaction processes, and gestalt principles:
(Re)introducing cognitive dynamics to social psychology. Personality and Social Psychology Review, 1, 26–53.
Reisen, N., Hoffrage, U., & Mast, F. W. (2008). Identifying decision strategies in a consumer choice situation. Judgment and
Decision Making, 3, 641–658.
Roe, R., Busemeyer, J., & Townsend, J. (2001). Multiattribute decision ﬁeld theory: A dynamic, connectionist model of decision
making. Psychological Review, 108, 370–392.
Rogers, W. H. (1993). Regression standard errors in clustered samples. Stata Technical Bulletin, 13, 19–23.
Shimojo, S., Simion, C., Shimojo, E., & Scheier, C. (2003). Gaze bias both reﬂects and inﬂuences preference. Nature Neuroscience, 6,
1317–1322.
Simon, D., Krawczyk, D. C., & Holyoak, K. J. (2004). Construction of preferences by constraint satisfaction. Psychological Science,
15, 331–336.
Simon, D. (2004). A third view of the black box: Cognitive coherence in legal decision making. University of Chicago Law Review,
71, 511–586.
Spellman, B. A. (2010). Judges, expertise, and analogy. In D. Klein & G. Mitchell (Eds.), The psychology of judicial decision making
(pp. 149–163). Oxford: Oxford University Press.
332
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333

--- [Página 16] ---
Thagard, P. (1989). Explanatory coherence. Behavioral and Brain Sciences, 12, 435–502.
Thagard, P., & Millgram, E. (1995). Inference to the best plan: A coherence theory of decision. In A. Ram & D. B. Leake (Eds.), Goaldriven learning (pp. 439–454). Cambridge, MA: MIT Press.
Thomas, L. E., & Lleras, A. (2007). Moving eyes and moving thought: On the spatial compatibility between eye movements and
cognition. Psychonomic Bulletin & Review, 14, 663–668.
Vickers, J. N. (2007). Perception, cognition, and decision training. The quiet eye in action. Champaign, IL: Human Kinetics.
Williams, A. M., Janelle, C. M., & Davids, K. (2004). Constraints on the search for visual information in sport. International Journal
of Sport and Exercise Psychology, 2, 301–318.
A. Glöckner et al. / Human Movement Science 31 (2012) 318–333
333