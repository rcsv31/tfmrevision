# ARTÍCULO CIENTÍFICO: Statistical modelling of gaze behaviour as categorical time series

## METADATOS DEL ARCHIVO
- **Nombre del archivo:** Statistical modelling of gaze behaviour as categorical time series.pdf
- **Título en Metadatos:** 
- **Autores en Metadatos:** 
- **Fecha de creación:** D:2011

## CUERPO DEL DOCUMENTO Y TEXTO COMPLETO
--- [Página 1] ---
RESEARCH REPORT
Statistical modelling of gaze behaviour as categorical time series:
what you should watch to save soccer penalties
C. Button • M. Dicks • R. Haines • R. Barker •
K. Davids
Received: 1 July 2010 / Accepted: 25 November 2010 / Published online: 8 December 2010
 Marta Olivetti Belardinelli and Springer-Verlag 2010
Abstract
Previous research on gaze behaviour in sport has
typically reported summary ﬁxation statistics thereby largely ignoring the temporal sequencing of gaze. In the present
study on penalty kicking in soccer, our aim was to apply a
Markov chain modelling method to eye movement data
obtained from goalkeepers. Building on the discrete analysis
of gaze employed by Dicks et al. (Atten Percept Psychophys
72(3):706–720, 2010b), we wanted to statistically model the
relative probabilities of the goalkeeper’s gaze being directed
to different locations throughout the penalty taker’s
approach (Dicks et al. in Atten Percept Psychophys
72(3):706–720, 2010b). Examination of gaze behaviours
under in situ and video-simulation task constraints reveals
differences in information pickup for perception and action
(Attention, Perception and Psychophysics 72(3), 706–720).
The probabilities of ﬁxating anatomical locations of the
penalty taker were high under simulated movement response
conditions. In contrast, when actually required to intercept
kicks, the goalkeepers initially favoured watching the
penalty taker’s head but then rapidly shifted focus directly to
the ball for approximately the ﬁnal second prior to foot-ball
contact. The increased spatio-temporal demands of in situ
interceptive actions over laboratory-based simulated actions
lead to different visual search strategies being used. When
eye movement data are modelled as time series, it is possible
to discern subtle but important behavioural characteristics
that are less apparent with discrete summary statistics alone.
Keywords
Gaze behaviour  Markov chain modelling 
Representative design  Time series
Introduction
Recent decades have seen signiﬁcant advances in the
capability to examine human movement behaviour in
reﬁned detail. New and emerging technologies for such
purposes includes motion analysis systems, functional
magnetic resonance imagers, GPS devices, accelerometers
and mobile eye-movement trackers, which greatly enhance
the ability to collect detailed, high-dimensional data from
participant observations. Alongside such rapid developments in data-collection techniques, there is an ongoing
requirement to develop sophisticated data analysis procedures that allow us to understand and interpret the volume
and detail of information that is generated (Michieli et al.
2010; Rein et al. 2010). As Feng (2006) acknowledged, the
current challenge in studying eye movement behaviour is
to map the complex and diverse patterns observed to a
small set of parameters that can be understood.
In the sports expertise literature, there have been
many attempts to examine the gaze behaviours of skilled
athletes in different performance contexts (Mann et al.
2007; Vickers 2007). In terms of visual anticipation,
C. Button (&)
School of Physical Education, University of Otago,
Otago, New Zealand
e-mail: chris.button@otago.ac.nz
M. Dicks
Institute of Cognitive and Team/Racket Sport Research,
German Sport University Cologne, Cologne, Germany
R. Haines  R. Barker
Department of Mathematics and Statistics,
University of Otago, Otago, New Zealand
K. Davids
School of Human Movement Studies,
Queensland University of Technology,
Brisbane, Australia
123
Cogn Process (2011) 12:235–244
DOI 10.1007/s10339-010-0384-6

--- [Página 2] ---
Table 1 summarises a number of interesting features that
have been shown to distinguish skilled from less-skilled
performers (typically novices) in existing research. For
example, during visual anticipation tasks, skilled athletes
are considered to utilise gaze behaviours that comprise
fewer ﬁxations of longer durations (perceiving more useful
information) in comparison with less-skilled performers
(e.g., Savelsbergh et al. 2002).
The predominant measure most commonly reported is
summary gaze ﬁxations and associated gaze behaviour
characteristics such as relative location, duration and frequency of occurrence (Table 1). One important limitation
of such measures is that they denote an average statistical
function of performance (across participants and/or trials),
the use of which can mask functional levels of performance
variability within and between individuals (Button et al.
2006; Feng 2006). Indeed, the overwhelming majority of
studies of gaze behaviour in sport have tended to examine
performance by summarising and averaging data at discrete
time periods across trials and participants (for exceptions,
see: Singer et al. 1998; Croft et al. 2010). For example,
the ‘quiet eye’ perspective comprehensively studied by
Vickers and colleagues (Vickers 1996; Panchuk and
Vickers 2006) reﬂects the average duration of the ﬁnal
ﬁxation prior to movement onset in visually controlled
tasks. Arguably, the procedure of averaging eye movement
data reﬂects an implicit assumption that participants of
comparable skill level utilize the same optimal pattern of
gaze from one situation to the next (for a contrasting
approach, see: Withagen and van der Kamp 2010).
Therefore, it is perhaps not surprising that the rich, timedependent nature of eye movements has typically been
sacriﬁced in favour of summary analysis by averaging over
time. As an aside similar data analysis procedures have
characterised the motor learning discipline in the past,
partly attributable to a long held belief that movement
patterns converge to one optimal solution across individuals as a function of skill level. Such ‘one-size-ﬁts-all’
thinking in the movement sciences has been vigorously
challenged in recent times resulting in the advocation of
more sophisticated and sensitive data analysis procedures
(Button et al. 2006; Glazier and Davids 2009; Rein et al.
2010).
We propose that a more comprehensive understanding of
gaze behaviour may be offered by statistical analyses of
time-series data. Interestingly, this approach has recently
gained support from the analysis of other visually guided
behaviours such as reading (Feng 2006) and surgery
(Sodergren et al. 2010). In contrast to traditional data
analysis procedures in eye movement research, Markov
chain modelling assumes that the next state of a variable
(i.e., location of gaze) depends on the current or earlier
states. Feng (2006) proposed that eye movements in reading
can be statistically modelled as random time series variables. In that study, an Input–Output Hidden Markov model
was used to describe the characteristics of beginning and
proﬁcient readers and other well-known psycholinguistic
effects (Feng 2006). Not only could the analysis distinguish
between different skill levels but it was better suited than
discrete variables, such as ﬁxation duration and saccade
length, for identifying individual differences within the
groups. A 3-component lognormal mixture model was
required to best ﬁt the ﬁxation duration data and a hierarchical model was applied for saccade length (Feng 2006).
As the ﬂow of information in tasks such as reading is fairly
static and predictable, it was of interest in the present study
to ﬁnd out whether a similar procedure can characterise eye
movements in a more dynamic, less predictable task.
Table 1 Summary of research ﬁndings from visual anticipation literature comparing skilled and less skilled participants in sport
Finding
Source
Sport/task
Dependent variables
Experts make fewer ﬁxations
Singer et al. (1998)
Return of tennis serve
Fixation number, location, duration,
percentage of tracking versus saccades
Experts make longer ﬁxations
Ripoll et al. (1995)
Boxing
Fixation, number, location and scan-path
Rodrigues et al. (2002)
Table tennis
Quiet eye duration
Experts attend to relevant
information (less easily
distracted)
McPherson and Vickers
(2004)
Return of serve in volleyball
Fixation, location, duration, frequency
Savelsbergh et al. (2002,
2005)
Soccer goalkeeper facing
penalty
Fixation number, duration, location,
scan-path
Experts use more consistent gaze
strategies
Ward et al. (2002)
Tennis
Fixation location, duration, rate and
chronological order
Experts more sensitive to
anticipatory visual information
Goulet et al. (1989)
Receiving a tennis serve
Fixation number and duration
Where VSM was the video simulation movement condition, ISM was an in situ movement condition, and ISI was an in situ interceptive condition
236
Cogn Process (2011) 12:235–244
123

--- [Página 3] ---
In much of the existing gaze behaviour studies, eye
movement
registration
technology
has
constrained
researchers to design studies in which limited participant
movement was mandated. For example, experimental tasks
have typically required participants to produce verbal
judgments (e.g., Abernethy 1990) or simulated movement
(e.g., Savelsbergh et al. 2005) responses in preference over
in situ measures (such as interceptive actions) in experimental
conditions
that
are
representative
of
typical
performance environments (Dicks et al. 2009). However,
meta-analyses have revealed differences between laboratory studies and natural experimental settings for several
variables related to perceptual expertise (Mann et al.
2007). Hence, laboratory studies may yield different gaze
behaviours than natural in situ studies due to deﬁcits
in representative design. Brunswik (1956) stressed that
experimental stimuli should be sampled from the organism’s natural environment to be representative of the population of stimuli to which the organism has adapted and to
which empiricists wish to generalize ﬁndings. Brunswik’s
advice is supported by a number of recent eye-movement
studies that have examined in situ gaze behaviours of
goalkeepers in different sports wearing mobile eye-tracking
equipment (Panchuk and Vickers 2006; Dicks et al. 2010b).
Previous work in which participants watched video simulations indicated that goalkeepers extract advance information from the movements of an approaching penalty
taker which can be used to judge future shot direction
(Savelsbergh et al. 2005). However, when goalkeepers are
required to make an in situ interceptive response, they
make comparatively earlier and longer ﬁxations on the
object to be intercepted (Panchuk and Vickers 2006; Dicks
et al. 2010b). Such differences in gaze behaviour result
from the different task constraints, reﬂecting the increased
spatio-temporal demands of interceptive actions over simulated actions or perceptual judgements (van der Kamp
et al. 2008).
Revealing that gaze behaviours differ with varying
levels of representative design in experiments is an
important ﬁnding with numerous implications for the study
of visual expertise in sport (Dicks et al. 2009). However,
further information is required concerning the sequence of
eye movements that are made in the moments before the
kick is taken. It is conceivable that as a function of the
variation in the penalty taker’s run-up in different contexts
(i.e., video vs. in situ), a number of different ‘scan paths’
may be employed that give rise to earlier and longer ball
ﬁxations. In other words, the sequence of features that gaze
is directed towards may also differ as well as the duration
and timing of ﬁxations. The motivation for the present
study was a desire to build upon the discrete analysis
employed by Dicks et al. (2010b) using a time-dependent
Markov chain procedure. To our knowledge, this is the ﬁrst
time such analysis has been employed to examine eye
movements in a sport context.
In summary, new and innovative data analysis procedures in relation to human movement behaviour are
evolving rapidly in response to improvements in data collection technology. Historically, investigations of athletes’
gaze behaviours have reported discrete, descriptive statistics such as number, duration and frequency of ﬁxations
(e.g., Savelsbergh et al. 2005). Whilst informative, such
summary variables largely ignore the temporal structure of
gaze behaviour thereby discerning much useful information. In the present study, our aim was to explore an
alternative
analysis
method
by
developing
statistical
models that maintain the inherent time structure, but still
summarise key features of the data. Building on the ﬁndings of Dicks et al. (2010b), we wanted to quantify and
compare the relative probabilities of the goalkeeper’s gaze
being directed to different locations at different times
during the penalty taker’s approach. We predicted that time
series modelling of a goalkeeper’s gaze data will reveal the
relative likelihood of gaze location on the ball increases as
the penalty taker approaches the ball. On the basis of
previous research highlighting differences between in situ
and laboratory-based designs, we hypothesised that participant gaze will be directed towards the ball comparatively earlier and for a longer duration in situ than in video
display or simulated movement contexts (Panchuk and
Vickers 2006; Dicks et al. 2010b; Savelsbergh et al. 2005).
Methods
Participants
Eight experienced association football goalkeepers aged
22.8 ± 4.1 years were recruited (for further details, see:
Dicks et al. 2010a). Participants reported a mean of
11.63 ± 4.4 years
association
football
experience
as
goalkeepers and had played to at least the standard of the
New Zealand Southern Premier League or equivalent.
One penalty taker aged 24 years was recruited to
execute all kicks. The player was appropriately matched
to the goalkeepers by standard and length of experience to
ensure they were of the level typically encountered by the
goalkeepers during matches (Panchuk and Vickers 2006).
The player had 16 years playing experience and had
regular experience of taking penalties in competition. The
goalkeepers had no prior experience of facing penalty
kicks executed by the selected penalty taker. Prior to
testing and contacting participants, ethical clearance was
obtained from the local University ethics committee. All
players provided written consent prior to participation in
the study.
Cogn Process (2011) 12:235–244
237
123

--- [Página 4] ---
Apparatus
The participants performed all trials in front of a full-size
goal (7.32 9 2.44 m) represented by a white screen in an
indoor Astroturf training facility. Following Savelsbergh
et al. (2002), six target areas (0.81 9 1.50 m) were marked
on either side of the screen (top, middle, and bottom) as a
target reference for the penalty taker. A regulation size 5
football was used with kicks taken at a distance of 11 m
from the goal as stipulated by Fe´de´ration Internationale de
Football Association laws (FIFA 2006). Penalty taking
accuracy was recorded by an experimenter after every trial.
Kicks that were judged to have been directed outside of the
desired target location were repeated at a later stage in the
testing protocol. Ball ﬂight time was recorded using a pinhead microphone placed beside the ball to register the
moment of foot-ball contact, and a second microphone was
positioned next to the screen to register the point of ball
impact with the goal.
Visual search behaviours were recorded using an eyetracking system (MobileEyeTM, ASL Ltd, Massachusetts,
USA). The MobileEye is a head-mounted, monocular eyetracking system that computes point of gaze within a scene
through calculation of the vector (angle and distance)
between the participant’s pupil and cornea. The vector
displacements were calibrated to a nine-point grid positioned within the scene of view for each condition. A
positional cursor highlighting the point of visual gaze is
superimposed on the scene camera by the MobileEye
system with an accuracy of ±0.5 of visual angle and
resolution of 0.1 (the diameter of the cursor centre was
2). Participants were instructed to hold their head stable
and move their eyes only during the calibration. Accuracy
of calibration was checked by asking participants to ﬁxate
on different objects in the task environment, a procedure
that was followed after every ﬁve trials during testing.
Visual search behaviour data were collected at a rate of 25
frames per second and subjected to a frame-by-frame
analysis using Focus X2 (Elite Sports Analysis, Fife,
United Kingdom). Pilot testing indicated that wearing the
MobileEye did not restrict goalkeeping performance.
Video simulation test ﬁlm
Video simulation footage of the penalty taker was recorded
prior to testing using a 50-Hz digital video camera (Canon
MVX200i) positioned in the middle of the goal at a height
of 1.60 m. Each ﬁlm clip included the penalty taker’s runup, the kick action and the initial portion of ball ﬂight
(Savelsbergh et al. 2002). The footage consisted of 20
different kicks (see Procedure below). The ﬁlm clips were
projected (Panasonic PT-LB20NTEA) onto a large screen
(2.4 9 1.5 m) positioned 4.3 m from the participant. The
image of the penalty taker at ball contact was set at 0.72 m
to ensure it subtended a visual angle of 10.6, thereby
replicating the height of the penalty taker at ball contact for
the in situ conditions.
Procedure
Performance was measured using a video simulation
movement condition (VSM), an in situ movement condition
(ISM), and an in situ interceptive condition (ISI). The VSM
condition required the goalkeepers to move a handheld
joystick in response to video footage of the penalty taker as
though to intercept the ball (Savelsbergh et al. 2005; Savelsbergh et al. 2002). In the ISM condition, the participants
had to face the actual penalty taker and were required to
initiate a representative goalkeeping whole-body movement
(i.e., side-step) with arms directed towards the anticipated
goal location without intercepting the ball. Finally, the
goalkeepers were also required to attempt to intercept penalty kicks taken in situ (ISI). In each condition, participants
were instructed to initiate movement at a moment equivalent
to when they would move to save the kick in a game.
For each condition, the penalty taker followed a test
script which included instruction about which part of the
goal to aim each kick. The player initiated the run-up at an
approach angle of between 10 and 30, 4.0 m from ball
contact for each trial. Performance was analysed for 15 of
the 20 trials faced by each goalkeeper in each condition.
Kicks in these trials were directed towards the bottom
corners of the goal (eight to the right and seven to the left).
The data set therefore comprised a total of 240 trials (120
for each condition). The remaining kicks for each condition
were directed to varying predetermined goal locations to
remove the participant’s awareness of the task procedure.
The intended location of the penalty kicks was randomized
for each condition, but presented in the same order for each
participant. The order of each condition completion was
counterbalanced
between
participants.
No
augmented
feedback was provided about performance. The goalkeepers performed ten familiarization trials for each condition
prior to testing.
Data analysis
In the current study, trial initiation time included the penalty taker’s run-up and a portion of his preparation time to
provide sufﬁcient duration before penalty kick action initiation (Panchuk and Vickers 2006). The onset of each trial
was preset at 2,000 ms prior to penalty taker foot-ball
contact. The trial endpoint used to compare gaze for the
three conditions was 120 ms post foot-ball contact, as data
were available for all trials in all conditions for this
duration.
238
Cogn Process (2011) 12:235–244
123

--- [Página 5] ---
Ten locations were used to categorize position of gaze:
the penalty taker’s head, upper body (including arms),
upper kicking leg and hip, upper non-kicking leg and hip,
kicking leg (including foot), non-kicking leg (including
foot), turf between the player and ball, the ball, the turf in
front of the ball, and ‘other’. The ‘other’ category was
noted when the gaze could not be coded due to extraneous
jarring movements by the participant, or when gaze was
directed outside of the ﬁxation location categories. Fixation/tracking (F/T) behaviour was coded when the gaze
remained within 3 of visual angle of a location or moving
object for a minimum duration of 3 frames or 120 ms
(Panchuk and Vickers 2006).
Randomly selected trials (N = 8) were re-coded by the
same experimenter and a second researcher. Intra and interoperator reliability ranged between r = .98–1.0 for the
same experimenter and r = .899–.937 for the two coders.
Summary statistics
Three dependent variables were calculated from gaze data
collected between the trial beginning and endpoints. These
data included the mean number of ﬁxations, the mean
number of areas ﬁxated upon and the mean ﬁxation duration for each trial. Each variable was analysed separately
using repeated measures ANOVA (3 9 condition). Main
effects were explored with pair-wise Bonferroni comparisons. The signiﬁcance threshold was set at P \ .05.
Markov chain model
Using Bayesian inference, three repeated-measures Markov
chain models were ﬁtted to the data across participants from
each experimental condition. For these models, it was
assumed that the current gaze location (state) depends only
on the previous state. This assumption was used for simplicity and could be relaxed. Markov chain Monte Carlo
(MCMC) was used to obtain a posterior sample of transition
probabilities at each time point (calling changes in gaze
location ‘transitions’), and also of initial state probabilities.
Because the number of transition probabilities was large,
we smoothed them by modelling them as sampled from a
ﬁrst-order autoregressive process. For readers not familiar
with this analysis, note that ‘Markov chain’ in MCMC
refers to a particular procedure for simulating posterior
distributions in Bayesian inference by drawing samples
sequentially, with the distribution of sampled draws
depending on the last value drawn (Gelman et al. 2004). In
contrast, the three Markov chain models are particular
models that we have formulated to describe our data.
To summarise using more familiar terms, we calculated
a number of derived quantities. Marginal probabilities were
one summary used, giving the actual probability of gaze
being directed to a particular location at a speciﬁed point in
time. Another was the probability of ‘ﬁxation’, in the sense
that these were probabilities of gaze direction remaining
settled on a location from one time point to the next.
Detailed description of the model used and of the calculation of marginal and ﬁxation probabilities is included in
‘‘Appendix’’.
Results
Main effects were present for the mean number of areas
ﬁxated upon (F(2,14) = 4.83, P \ .026, g2 = 0.41), the
mean ﬁxation duration for each trial (F(2,14) = 3.08,
P \ .05, g2 = 0.35) and the mean number of ﬁxations
(F(2,14) = 5.24,
P = .021,
g2 = 0.43).
There
were
moderately more areas ﬁxated upon in the ISM condition
(3.51 ± 0.69) than the ISI condition (3.10 ± 0.59), but
the VSM condition (3.49 ± 0.26) was not different from
either of the other conditions. In terms of ﬁxation duration, the average duration was longer in the VSM condition (0.51 ± 0.11 s) than either the ISM (0.43 ± 0.07 s)
or ISI conditions (0.45 ± 0.08 s). The mean number of
ﬁxations was least in the VSM condition (4.39 ± 0.78)
with the other two conditions having a similar number of
ﬁxations per trial (ISM: 4.92 ± 1.0; ISI: 4.96 ± 0.54).
Therefore, different visual search patterns were used in
the VSM condition with fewer, longer ﬁxations made.
The simulated movement tasks seem to result in ﬁxations
to more different locations than the interceptive task
(Fig. 1).
The relative probability that gaze was located at one of 9
possible categories is depicted in Fig. 2 (only minimal data
were recorded for the ‘other’ category, therefore we proceeded with 9 ﬁxation locations for the Markov chain
analysis). At the beginning of each trial, the probability of
ﬁxation on any location was below 0.4, although in all
conditions the penalty taker’s head seemed to be a common
location (pink line, approximately 0.3) as expected. Some
interesting temporal differences in gaze behaviour then
began to emerge between conditions. For example, the
probability of gaze being directed at the ball, rather than
the penalty taker or other sources of information, gradually
increased to high levels (i.e., [0.5) during the middle
portion of trials in the interception condition (yellow line).
In contrast, there were more rapid, later increases in ball
ﬁxation likelihood towards the end of VSM and ISM trials.
In the simulated movement tasks, the penalty taker’s lower
legs become the most likely ﬁxation location during the
middle portion of the trial (green/light blue, probability of
0.4–0.5).
Interestingly
the
ﬂickering
of
probabilities
between the kicking and non-kicking legs (most evident in
VSM) indicated how the goalkeeper switched ﬁxations
Cogn Process (2011) 12:235–244
239
123

--- [Página 6] ---
between legs during the ﬁnal few strides of the penalty
taker. These ﬁndings help to explain from the summary
statistics why more locations tended to be ﬁxated in the
VSM and ISM conditions than the ISI condition.
There are also some interesting effects at and just after
ball contact (?2,000 ms) where the most likely ﬁxation
location in the simulated movement conditions decreased
rapidly from the ball back to the penalty taker’s legs
(Fig. 2). In the ISI condition, the ball and turf after the
ball remained the most likely ﬁxation locations. Once
more it is likely that participants took advantage of the
artiﬁcial spatio-temporal constraints in the simulated
movement trials to exploit further information from the
penalty taker’s orientation (e.g., orientation of supporting
foot). In the interceptive condition, ball ﬂight was still
available after foot-ball contact, so it is not surprising that
the participants should scan ahead of the ball’s predicted
trajectory.
Figure 3 displays the plots of the difference in (logits of)
ball ﬁxation probabilities for each pair of conditions. Here
is further evidence that the ﬁxation probabilities differed
meaningfully between the ISI and VSM conditions, with
the 95% credible interval excluding zero for almost the
entire time period. The difference is positive indicating
goalkeepers were more likely to ﬁxate on the ball in ISI
than VSM. At about 75 ms, the probability of gaze being
directed at the ball drops to around zero in VSM, and as the
ISI and ISM conditions did not display such a drop-off, we
observed a large difference in ball ﬁxation probability
between VSM and the other conditions. During the interception
condition,
the
goalkeepers
placed
a
greater
emphasis on watching the ball throughout the penalty
taker’s run-up.
Discussion
The aim of the study was to model the goalkeeper’s eye
movement data as categorical time series thereby revealing
how gaze behaviour unfolds throughout the penalty taker’s
approach to the ball. On the basis of previous research
highlighting differences between in situ and laboratorybased designs, we predicted gaze to be directed towards the
ball comparatively earlier and for a longer duration in situ
than in video display or simulated movement contexts
(Panchuk and Vickers 2006; Dicks et al. 2010b; Savelsbergh et al. 2005). Partly contrary to expectations, the
summary statistics indicated that more efﬁcient visual
search patterns were used in the VSM condition with
fewer, longer ﬁxations made. However, when the time
series data were explored more thoroughly with regard to
when the ﬁxations occurred, it became clear that the
0
0.1
0.2
0.3
0.4
0.5
0.6
0.7
0.8
0.9
1
0
1
2
3
4
5
6
VSM
ISM
ISI
Time (s)
Fixations
Number of categories
Number
Duration
Fig. 1 Summary of discrete ﬁxation variables between conditions
Fig. 2 Marginal probabilities of gaze being directed to a particular
location averaged across participants at a speciﬁed point in time
240
Cogn Process (2011) 12:235–244
123

--- [Página 7] ---
summary ﬁxation data provided limited information. The
probabilities of ﬁxating anatomical locations of the penalty
taker were typically higher in the VSM and ISM conditions
and approaching negligible levels in the ISI, particularly in
the ﬁnal second or so prior to foot-ball contact. In contrast,
when actually required to intercept kicks, the goalkeepers
initially favoured watching the penalty taker’s head, presumably to detect information about what part of the goal
the penalty taker was looking toward (Wilson et al. 2009).
From approximately 500 ms onwards, the ball was the
most likely ﬁxation location in ISI, whereas these odds did
not occur in the other conditions until approximately
1,500 ms (see Fig. 2). The Markov chain model provides a
useful addition to existing work by generating a statistical
estimate of this relationship over time.
The simulated movement conditions (VSM and ISM)
gave rise to a more comprehensive search strategy with
ﬁxations upon more different locations than the ISI condition (Dicks et al. 2010b). It seems that participants
tended to ﬁxate on fewer different information sources, in
particular the penalty taker’s head and the ball, in the
interceptive trials than in the simulated movement trials.
This ﬁnding is complementary to the observations of
Dicks et al. (2010b) and there are two potential explanations. First, it is possible that the degradation of
information that arises when participants are presented
with video footage versus actual performance scenarios
means that the goalkeepers are forced to scan more
comprehensively for anticipatory information about the
penalty taker’s future actions (e.g., the upper and lower
body). For example, depth related information would be
less apparent when represented in two dimensions; hence,
the goalkeeper may need to watch the penalty taker more
closely. However, this explanation cannot be applied to
the differences in gaze behaviour shown between the two
in situ conditions (ISM and ISI). Second, it is also possible that the increased spatio-temporal demands presented by the interceptive task inﬂuenced the goalkeeper’s
gaze constraining them to anchor ﬁxations on the ball for
earlier and longer than in the simulated movement conditions. Supporting evidence for this explanation have
been offered by van der Kamp et al. (2008) who suggest
that the neural pathways supporting vision for perception
differ from those used with vision for action. It is difﬁcult
to tease apart either explanation with the current experimental design, and it seems likely that each factor could
have some inﬂuence on the ﬁndings.
This study demonstrated that useful information can be
extracted from the temporal sequencing of ﬁxations which
to date has largely been ignored in the sports expertise
literature. When eye movement data are modelled as time
series, it is possible to discern subtle but important
behavioural characteristics that are not apparent with discrete summary statistics alone. Speciﬁcally, the Markov
chain model estimated the relative likelihood at each
moment of time of gaze being directed to one of the
locations available to the goalkeeper. This complementary
analysis allowed us to determine how the goalkeeper’s
gaze patterns evolved continuously during the run-up of the
penalty taker. This level of behavioural dimensionality was
not observable at discrete time points (see Dicks et al.
2010b).
Furthermore, the comparison of state probabilities in
terms of difference in logits (Fig. 3) provides researchers
Fig. 3 Comparison of mean ball ﬁxation probabilities between
conditions
Cogn Process (2011) 12:235–244
241
123

--- [Página 8] ---
the opportunity to objectively conﬁrm exactly when, and
in which direction, meaningful differences in gaze allocation arise. Whilst similar to the traditional approach of
calculating the signiﬁcance (or effect size) of a statistical
test, importantly the Markov chain also determines when
participant’s gaze is directed towards information sources.
In future work, this analysis may be particularly valuable
for identifying the key informational variables that are
required to co-ordinate movements effectively with the
environment. The width of the 95% conﬁdence interval
also nicely captures the variability in the probability
measures over time in contrast to summary, time independent measures such as the standard deviation or variance. In Fig. 3, the conﬁdence interval of probabilities
over trials remains relatively stable except a common
trend across conditions to decrease towards the end of the
trial.
There were a number of limitations in the study that
would be useful to address in future research. Although we
have used fairly simple descriptions of the evolution of the
Markov chain during the soccer penalty-kick, we envisage
future analyses in which hypotheses about particular gaze
strategies are formulated in terms of constraints on the
Markov chain. This approach would allow a more formal
statistical approach to the assessment of gaze strategy
hypothesis than is possible through use of simple summary
statistics. The nature of the penalty kicks taken in the study
may limit the generality of our ﬁndings. In the in situ
conditions, there was concern regarding the risk of the ball
ricocheting and causing damage to the Mobile Eye or
injury to the participants. Thus, for the sake of participant
safety, the penalty taker was instructed to aim penalties to
two goal locations (approximately hip height, 1 m from
either post), rather than the bottom corners of the goal.
Although slightly different from those of the other conditions, the kick locations remained representative of those
recorded for world-class performance (Morya et al. 2005).
Whilst the range of observed mean ball-ﬂight times (i.e.,
580–597 ms) were representative of those of comparably
skilled performers (Kellis and Katis 2007), it is likely that
some elite level competitive penalties have quicker ﬂight
times than we created. Finally, but perhaps most importantly, the penalty taker was instructed to use a nondeceptive strategy in order to minimize any variability in
his kicking action within and between conditions. It is
plausible that under easier (non-deception) conditions, a
greater diversity of information-movement couplings can
be exploited by goalkeepers in order to accurately anticipate penalty kick direction in comparison with more difﬁcult
deception
kicks
commonly
encountered
in
competition (Dicks et al. 2010a). In order to address this
limitation, future research should examine differences in
goalkeeper’s
gaze
when
facing
deceptive
and
nondeceptive penalty kicks. Moreover, a related and important
issue concerns whether goalkeeper gaze differs between
successful and unsuccessful attempts to save penalties as
has been demonstrated for goaltending performance in ice
hockey (see Panchuk and Vickers 2006).
To conclude, future studies of visual anticipation in
sport should include more detailed analyses of gaze
behaviour over time as it seems increasingly likely that a
number of perceptual strategies can give rise to the same
behavioural outcome (Savelsbergh et al. 2004). We argue
that this emerging analytical approach is vital for studying
eye movements in tasks where availability of informative
perceptual information is not predictable and which may
become
relevant
at
any
time
during
a
performer’s
response. For example, Ripoll et al. (1995) showed that in
boxing the sequencing of scan paths adopted for more
complex combat situations (reacting to attacks, openings
and feints) differed considerably from those preferred in
simple situations. In the case of facing a penalty kick in
association football, our analysis showed that experienced
goalkeepers tended to ﬁxate initially on the penalty
taker’s head and then on the ground at the ball. It was not
the aim of the present article to explore individual differences between performers; however, it does seem that
a shift in thinking away from a ‘one-size ﬁts all’ perceptual strategy should be considered in sport expertise
research as it is in other disciplines of movement science.
Different individuals have different strengths and weaknesses relative to their own action capabilities, which
constrain the pickup of information during visually guided
behaviour such as saving a penalty kick (Dicks et al.
2010c). We advocate that other researchers should consider adopting statistical tools such as the Markov chain
to provide a sensitive and objective approach to analysing
gaze data. Clearly as our capability to measure human
movement and perceptual behaviour develops so too must
our ability to appropriately describe and interpret the rich
data sets that result.
Appendix: General model
Models were ﬁtted separately to the data for each experimental condition. For a given condition, we let ytk denote
the observed gaze location at time t = 1,2,…,T (T = 54),
in trial k = 1,2,…,120. This gaze location was categorised
as discussed in the Data Analysis section, but because there
were no observations were recorded in the ‘other’ category,
the possible values for ytk are 1,2,…,9.
We let pi represent the probability that the gaze was
directed at state i at t = 1, for i = 1,2,…,9. The probability
of transition of gaze location from state i (at time t) to state
j (at time t ? 1) is denoted by wðtÞ
ij , for t = 1,2,…,T - 1
242
Cogn Process (2011) 12:235–244
123

--- [Página 9] ---
and i, j = 1,2,…,9. Thus, the vector wðtÞ
i
gives the probabilities of transition from state i at time t.
For each condition, we model
y1k  Categorical(pÞ
ytk  Categorical wðt1Þ
yðt1Þk


The initial probability vector was given a Dirichlet prior
distribution (with a a vector of ones of equal length to p):
p  Dirichlet(aÞ
Similarly, each row of the ﬁrst transition matrix was also
given a Dirichlet (a) prior distribution.
Autoregressive smoothing
From the ﬁrst transition matrix, we calculate (using the
ninth column as the reference):
gð1Þ
i
¼ m log itðwð1Þ
i Þ
A ﬁrst-order autoregressive process is then applied (for
t = 2,…,T - 1):
gð1Þ
i
 Nðgðt1Þ
i
; sÞ
A Gamma prior distribution on the precision parameter
was used:
s  Gammað0:5; 0:5Þ
A range of values for the parameters in this prior
distribution were tried, and it was found that the results
were not sensitive to this choice.
With back-transformation, we get the rest of the transition probabilities:
wðtÞ
ij ¼
exp gðtÞ
ij


P9
j¼1 exp gðtÞ
ij


Summaries
We denote the marginal probabilities by cit, and these give
the probability that the gaze is directed to state i at time
t. These were calculated by:
ci1 ¼ pi
cit ¼
X
9
j¼1
wðt1Þ
ji
cjðt1Þ
Fixation probabilities, which were the probability of
gaze remaining directed at state i from time t - 1 to time t,
were denoted by xit. They were calculated using:
xit ¼ wðt1Þ
ii
ciðt1Þ
References
Abernethy B (1990) Anticipation in squash: differences in advance
cue utilization between expert and novice players. J Sport Sci
8:17–34
Brunswik E (1956) Perception and the representative design of
psychological experiments. 2nd edn. University of California
Press, Berkeley
Button C, Davids K, Scho¨llhorn W (2006) Co-ordination proﬁling of
movement systems. In: Davids K, Bennett S, Newell KM (eds)
Movement system variability. Human Kinetics, Champaign,
pp 133–152
Croft J, Button C, Dicks M (2010) Visual strategies of sub-elite
cricket batsmen in response to different ball velocities. Hum
Mov Sci 29(5):751–763
Dicks M, Button C, Davids K (2009) Representative task designs for
the study of perception and action in sport. Int J Sport Psychol
Special issue on Skill Acquisition and Sport Performance
(40:4):506–524
Dicks M, Button C, Davids K (2010a) Availability of advance visual
information constrains association-football goalkeeping performance during penalty kicks. Perception 39:1111–1124
Dicks M, Button C, Davids K (2010b) Examination of gaze behaviors
under in situ and video simulation task constraints reveals
differences in information pickup for perception and action.
Atten Percept Psychophys 72(3):706–720
Dicks M, Davids K, Button C (2010c) Individual differences in the
visual control of intercepting a penalty kick in association
football. Hum Mov Sci (in press)
Feng G (2006) Eye movements as time-series random variables: a
stochastic model of eye movement control in reading. Cogn Syst
Res 7:70–95
FIFA (2006) Laws of the game 2006. Fe´de´ration Internationale de
Football Association. http://www.ﬁfa.com/documents/ﬁfa/laws/
LOTG2006_e.pdf. Accessed 1 May 2007
Gelman AB, Carlin JS, Stern HS, Rubin DB (2004) Bayesian data
analysis, 2nd edn. Chapman and Hall/CRC, Boca Raton
Glazier PS, Davids K (2009) Constraints on the complete optimization of human motion. Sports Med 39(1):15–28
Goulet C, Bard C, Fleury M (1989) Expertise differences in preparing
to return a tennis serve: a visual information processing
approach. J Sport Exerc Psychol 11:382–398
Kellis E, Katis A (2007) Biomechanical characteristics and determinants if instep soccer kick. J Sports Sci Med 6:154–165
Mann DTY, Williams AM, Ward P, Janelle CM (2007) Perceptualcognitive expertise in sport: a meta-analysis. J Sport Exerc
Psychol 29(4):457–478
McPherson S, Vickers JN (2004) Cognitive control in motor
expertise. Int J Sport Exerc Psychol 2:274–300
Michieli I, Medved B, Ristov S (2010) Data series embedding and
scale invariant statistics. Hum Mov Sci 29(3):449–463
Morya E, Bigata˘o H, Lees A, Ranvaud R (2005) Evolving penalty
kick strategies: world cup and club matches 2000–2002. In:
Reilly T, Cabri J, Arau´jo D (eds) Science and football v. Taylor
& Francis, London, pp 237–242
Panchuk D, Vickers JN (2006) Gaze behaviors of goaltenders under
spatial-temporal constraints. Hum Mov Sci 25:733–752
Rein R, Button C, Davids K, Summers J (2010) Investigating
coordination in discrete multi-articular movements using cluster
analysis. Mot Control 14(2):211–239
Ripoll H, Kerlizin Y, Stein J-F, Reine B (1995) Analysis of
information processing, decision making, and visual strategies
in complex problem solving sport situations. Hum Mov Sci
14(3):325–349
Cogn Process (2011) 12:235–244
243
123

--- [Página 10] ---
Rodrigues ST, Vickers JN, Williams AM (2002) Head, eye and arm
coordination in table tennis. J Sports Sci 20:187–200
Savelsbergh GJP, Williams AM, van der Kamp J, Ward P (2002)
Visual search, anticipation and expertise in soccer goalkeepers.
J Sports Sci 20(3):279–287
Savelsbergh GJP, van der Kamp J, Oudejans RRD, Scott MA (2004)
Perceptual learning is mastering perceptual degrees of freedom.
In: Williams AM, Hodges NJ (eds) Skill acquisition in sport:
research, theory and practice. Routledge, Taylor & Francis,
London, pp 374–389
Savelsbergh GJP, van der Kamp J, Williams AM, Ward P (2005)
Anticipation and visual search behaviour in expert soccer
goalkeepers. Ergonomics 48(11–14):1686–1697
Singer RN, Williams AM, Frehlich SG, Janelle CM, Radlo SJ, Barba
DA, Bouchard LJ (1998) New frontiers in visual search: an
exploratory study in live tennis situations. Res Q Exerc Sport
69(3):290–296
Sodergren M, Orihuela-Espina F, Clark J, Darzi A, Yang G-Z (2010)
A hidden markov model-based analysis framework using eyetracking data to characterise re-orientation strategies in minimally invasive surgery. Cogn Process (in press)
van der Kamp J, Rivas F, van Doorn H, Savelsbergh G (2008) Ventral
and dorsal contributions in visual anticipation in fast ball sports.
Int J Sport Psychol 39(2):100–130
Vickers J (1996) Visual control when aiming at a far target. J Exp
Psychol Hum Percept Perform 22:343–354
Vickers J (2007) Perception, cognition and decision training: the quiet
eye in action. Human Kinetics, Champaign
Ward P, Williams AM, Bennett S (2002) Visual search and biological
motion perception in tennis. Res Q Exerc Sport 73(1):107–112
Wilson MR, Wood G, Vine SJ (2009) Anxiety, attentional control,
and performance impairment in penalty kicks. J Sport Exerc
Psychol 31(6):761–775
Withagen R, van der Kamp J (2010) Towards a new ecological
conception of perceptual information: lessons from a developmental systems perspective. Hum Mov Sci 29(1):149–163
244
Cogn Process (2011) 12:235–244
123