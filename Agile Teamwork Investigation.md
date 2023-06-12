# Investigation the quality of teamwork and how it shaped by team characteristics and support structures

This research protocol outlines how we plan to perform our investigation of teamwork and the influence of team longevity and stability on team functioning. We publish this protocol openly and publicly for the sake of transparency. And feedback is welcome at [info@theliberators.com](mailto:info@theliberators.com).

This study is performed by [Christiaan Verwijs](https://www.linkedin.com/in/christiaanverwijs/), [Daniel Russo](https://www.linkedin.com/in/danielrusso1/), and [Ornela Vasiliauskaite](https://www.linkedin.com/in/ornela-vasiliauskaite-670a023/). We plan to submit our findings to peer review and publish them in a recognized scientific journal in Software Engineering.

## Context

Alpha (a pseudonym) develops and supports an online marketplace with a global reach. Most teams at Alpha work according to the principles of Agile (software) development and with a strong focus on teamwork, learning, and quality. The company is home to roughly 150 teams and over 1.500 employees. Teamwork is essential to Alpha, as well as many other modern organizations.

Teamwork is believed to benefit from stability and longevity. This reflects a broad academic consensus, although it may be biased by rigid definitions of what constitutes a "team". Moreover, many Agile methodologies also (implicitly) assume stable, long-lived teams. At the same time, many organizations struggle to create such stable, long-lived teams that possess all the skills needed to achieve a goal. It also doesn’t always provide members with enough opportunities to practice the skills they enjoy practicing. 

So some companies have begun to experiment with more dynamic and fluid approaches to teamwork. Alpha recently designed its own approach to fluid team formation. In this model, teams (“mission teams”) are dynamically formed to achieve a specific short-term goal (“mission”) as the need arises. Mission teams are formed from a larger meta team (“Subdomain”). With this model, Alpha hopes to quickly launch temporary/virtual (Mission) teams, foster a healthy environment and allow team members to satisfy their social needs similarly to longer-lived teams.

## Related Work

Traditionally, teams are defined as “a permanent and formal group of at least two interdependent individuals who are collectively responsible for the accomplishment of one or several tasks set by the organization (Gladstein, 1984; Sundstrom, De Meuse, & Futrell, 1990)”. Mortensen & Haas (2018) note that teams are rarely that permanent and with such clear boundaries in practice. Teams often have temporary members who bring specialized skills that aren’t needed continuously or are scarce (citation needed) or are even formed dynamically from what Mortensen & Haas (2018) call a “meta team” as the need arises. 

Recently, organizations have begun experimenting with more flexible approaches to team design, i.e. dynamic reteaming, unFIX, and fluid teaming (citations needed). The “meta team” (Mortensen & Haas, 2018) from which subteams are formed generally ranges from 20 to 100 members. Subteams range between 2 and more members and are focused on achieving a short-term goal after which they usually dissolve back into the metateam. 

Dynamic teaming approaches challenge two established notions of team design. The first is that they emphasize flexibility over the longevity and stability of teams. A hypothesis in most academic literature is that teams develop “team cognition” as members work together over a longer period of time. Research has linked team cognition to higher performance and motivation (Mathieu et al, 2000), increased effectiveness (Kearny, Gebert & Voelpel, 2009), and generally explains a substantial amount of the variance (~19%) in the effectiveness of teams (De Church & Mesmer-Magnus, 2010). Just like muscle memory, team cognition requires time to form as the members of a team work together on shared tasks. In turn, this facilitates further collaboration. Kozlowski & Ilgen (2006) describe this reciprocity as “process begets structure, which in turn guides process”. This appears to favor stable and long-lived teams.

The second area where dynamic teaming approaches challenge established notion is in the size of teams. The meta team from which subteams are formed is larger than traditional teams, whereas subteams can be as small as 2 members. This brings into question the role of team size as a predictor of effectiveness. Although the optimum size depends on many factors, several studies have recommended around 5 members (plus or minus 2) for regular workgroups (see Horwitz, 2005). For software teams specifically, studies have shown that teams with 9 or more members are significantly less effective than smaller teams (ISBSG, 2007, Rodriguez et. al., 2012). As teams become larger, the quality of their group experience generally diminishes (Aube, Rousseau & Tremblay, 2011). In a study of 97 teams, they found that this is largely moderated by counterproductive behaviors in teams that occur (or not) as teams grow larger, like boastfulness, social loafing, aggression, and low safety. Large teams tend to show lower performance than smaller teams (Gooding & Wagner, 1985; Hoegl, 2005; Kerr, 1989; Poulton & West, 1999; Shepperd, 1993). Members in larger teams tend to show more absenteeism, higher turnover, lower mental health, and less satisfaction with work (Campion, Medsker, & Higgs, 1993; Hausknecht, Trevor, & Howard, 2009; Markham, Dansereau, & Alutto, 1982; Wegge, Roth, Neubach, Schmidt, & Kanfer, 2008). Larger teams may show more counterproductive behaviors that emerge from the lower social cohesion, like boastfulness, aggression, lower safety, and social loafing (Aube, Rousseau & Tremblay, 2011). “In effect, the more members there are in a team, the more likely they are to try to single themselves out from the others to access resources and rewards (Loch, Galunic, & Schneider, 2006; Pierce & White, 1999). The individualistic, even competitive, work atmosphere that may result is apt to foster the adoption of boastful behaviors.”

Dynamic teaming approaches aim to overcome bottlenecks and constraints in the allocation of skills in modern organizations. The need for cross-functional teams has become increasingly important with the rise of Agile methodologies as a means to reduce dependencies and increase responsiveness (Schwaber, 1995; Highsmith, 2009). Particularly in software teams, this includes an ever-growing range of skills necessary to achieve shared goals (i.e. coding, testing, analysis, security, deployment, and discovery). But in practice, it is hard to create stable teams that are small enough and still have all the required skills present. Thus, dynamic teaming approaches attempt to remedy this by introducing the notion of a meta team and one or more dynamic subteams.

An assumption of dynamic teaming is that the social and cognitive benefits of stable team membership are retained through the meta team, whereas the need for dynamically allocated skills is retained through their subteams. Few studies have yet attempted to investigate this. In a review of existing literature on fluid teams, Bushe & Chu (2011) note: “Fluid teams may never have the same potential as stable teams to develop into synergistic, high-performing teams, but sometimes the situation makes them unavoidable”.

Mortensen & Haas (2018) outline some of the challenges associated with research of fluid team designs. Members can be a member of one or more subteams, in addition to their metateam, which means that any measures need to take this into account. They also call for more time-varying measures and techniques like dyadic relationship analysis. 

## Research Questions

- RQ1: How do short-lived teams compare to more long-lived teams in terms of their effectiveness? How does their effectiveness change over time?
- RQ2: What kind of support systems are needed in environments that use dynamic teaming approaches to maintain team effectiveness?

## Hypotheses

- H1: Psychological safety, social/task cohesion, team goal commitment, social identification, and (low) relational conflict contribute to positive team outcomes
- H2: The longer a team works together, the higher their psychological safety, social/task cohesion, team goal commitment, and social identification, and the lower their relational conflict
- H3: Subteams formed from a meta team (i.e. dynamic teaming) are effective more quickly than teams that are not formed from a metateam (“Carryover Hypothesis”)
- H4: The carryover effect of dynamic teaming is moderated by the degree to which metateams and subteams are supported in their use of dynamic teaming and their autonomy
- H5: The effects of context variables, process variables and team outcomes is no different between stable and fluid teams

## Research Model

![Model](https://github.com/theliberators/scrumteamsurvey.research/assets/39433533/1b3b4fdb-b23e-45de-9100-927e0c17a16e)

## Study Design

- Qualitiative study:
  - Structured interviews of informants from Alpha* on the benefits, risks and challenges of dynamic teaming approaches compared to more traditional ones.
  - Structured interviews of informants from Alpha* on how organizations support, or can support, dynamic teaming approaches to offset some of the disadvantages compared to long-lived, stable teams
  - Structured interviews of informants from Alpha* on how the metateam interacts with subteams
- Quantitative study:
  - Survey study to track how teams perform based on their longevity and their use of dynamic teaming at Alpha*. The questionnaire will be taken at the start of a newly formed subteam and at the end of each "iteration".

*: While Alpha has presented itself as the first collaborator in this study, additional companies may join.

## Sample

- Qualitiative study:
  - Interview 2 managers at Alpha* that can evaluate the support structures at Alpha* to support team formation and development
  - Interview representatives from 10 subteams at Alpha* that have at least 6 months experience with fluid team designs
  - Interview 2 (Agile) coaches at Alpha* who are responsible for the fluid team design structure
- Quantitative study: 
  - An a priori power test in GPower shows that a sample size of approx. 320 measurements should be enough to identify signficant effects.
  - We will be collecting repeated measures at Alpha* from [XXXX] teams
  - We will also be collecting repeated measures from other teams at other organizations, although this may be less systematic than at Alpha*.
  - Data collection will be performed through the Scrum Team Survey diagnostic.

## Data Analysis

- Qualitiative study:
  - Gioia approach to develop a grounded theory
  - Interviews will be transcribe
  - Reseach teram will generate inductive categories based on meaningful units in the interview data
  - Research team will compare and refine categories (while journaling)
  - Create codebook
  - Research team applies codebook to interview data and analyzes patterns and relationships
  - Reporting of results
  - H1-5 will be answered from the interview data (if possible)
- Quantitative study:
  - Dataset will be cleaned from careless responses and very extreme outliers if they exist
  - CFA will be performed to assess proper factorial structure
  - Cronbach's Alpha will be calculated for each scale to assess proper reliability
  - HTMT analysis will be performed to assess discriminant validity
  - Common Method Bias tests will be performed to identify and isolate bias due to common method
  - Research team will use Structural Equation Modelling to determine model fit between the theoretical model and the data
  - Fit indices to be used: CFI, RMSEA, SRMR, GFI
  - Assumptions to be verified; normality of distributions, homoscedasticity, linearity and multicollinearity
  - H1 will be answered by testing the significant of paths of the variables to team outcomes
  - H2 will be answered by performing a longitudinal analysis in SEM (time factor) to see if team outcomes improve over time
  - H3 will be answered by investigating direct and indirect effects in SEM
  - H4 will be answered by investigating direct and indirect effects in SEM
  - H5 will be answered with a multigroup analysis in SEM

## Ethical Considerations

- The interviews at Alpha* will be performed exclusively by members of the Research Team who are not affiliated with Alpha*. The identifies of the participants will only be known to the Research Team. In the transcribing and reporting of interview data, only anonymous pseudonyms will be used to protect the identify of informants (e.g. SM1, DEV2).
- Questionnaire data will be anonymized and aggregated to the team-level. Participants will be made aware that their (anonymized and aggregated) responses may be used for scientific research.

## Potential biases & confounders

- Only teams that are doing well participate. We can address this by communicating clearly to teams that they won't be judged/penalized on their results. Furthermore, we can use scores on team outcomes to see if there is an even spread (i.e. not only high performing teams)
- Substantial changes may happen around teams that impact their results, but are not captured by our model. We can address this partially by including a question in the repeated measures to assess if the organization underwent big changes (i.e. reorganization) since the previous measurement. We should remove teams where this happens. The questionnaire includes two ordinal items ('Team Change' and 'Organisation Change') to assess to what extent teams or their environment changed since the previous measurement.
- Attrition is a big risk in longitudinal surveys. We can address this by providing useful and actionable feedback after each measure, and encouraging teams to return.

## Timeline

- Quantitative Study:
  - Data collection at Alpha* starts on July 1, 2023. It will run until December 30, 2023. At this point, a determination will be made if sufficient data has been collected.
  - Kickoff Workshop to instruct and train teams at Alpha* on how to participate in [July, 2023]
  - Teams at Alpha* will take the "Baseline" measure (all factors) at the start of each new subteam. Every iteration, or at least [every month], they will take the "Intermittent" measure (only process factors and team outcomes)
- Quantitative Study: 
  - Interviews at Alpha* will be scheduled and performed in Q4 of 2023.

