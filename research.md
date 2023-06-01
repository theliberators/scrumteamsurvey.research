This research protocol outlines how we plan to perform our investigation of Agile teamwork and the influence of team longevity and stability on team functioning. We publish this protocol openly and publicly for the sake of transparency. And feedback is welcome at [info@theliberators.com](mailto:info@theliberators.com).

This study is performed by [Christiaan Verwijs](https://www.linkedin.com/in/christiaanverwijs/), [Daniel Russo](https://www.linkedin.com/in/danielrusso1/), and [Ornela Vasiliauskaite](https://www.linkedin.com/in/ornela-vasiliauskaite-670a023/). We plan to submit our findings to peer review and publish them in a recognized scientific journal in Software Engineering.

# Context

Alpha (a pseudonym) develops and supports an online marketplace with a global reach. Most teams at Alpha work according to the principles of Agile (software) development and with a strong focus on teamwork, learning, and quality. The company is home to roughly 150 teams and over 1.500 employees. Teamwork is essential to Alpha, as well as many other modern organizations.

Teamwork is believed to benefit from stability and longevity. This reflects a broad academic consensus, although it may be biased by rigid definitions of what constitutes a "team". Moreover, many Agile methodologies also (implicitly) assume stable, long-lived teams. At the same time, many organizations struggle to create such stable, long-lived teams that possess all the skills needed to achieve a goal. It also doesn’t always provide members with enough opportunities to practice the skills they enjoy practicing. 

So some companies have begun to experiment with more dynamic and fluid approaches to teamwork. Alpha recently designed its own approach to fluid team formation. In this model, teams (“mission teams”) are dynamically formed to achieve a specific short-term goal (“mission”) as the need arises. Mission teams are formed from a larger meta team (“Subdomain”). With this model, Alpha hopes to quickly launch temporary/virtual (Mission) teams, foster a healthy environment and allow team members to satisfy their social needs similarly to longer-lived teams.

# Related Work

Traditionally, teams are defined as “a permanent and formal group of at least two interdependent individuals who are collectively responsible for the accomplishment of one or several tasks set by the organization (Gladstein, 1984; Sundstrom, De Meuse, & Futrell, 1990)”. Mortensen & Haas (2018) note that teams are rarely that permanent and with such clear boundaries in practice. Teams often have temporary members who bring specialized skills that aren’t needed continuously or are scarce (citation needed) or are even formed dynamically from what Mortensen & Haas (2018) call a “meta team” as the need arises. 

Recently, organizations have begun experimenting with more flexible approaches to team design, i.e. dynamic reteaming, unFIX, and fluid teaming (citations needed). The “meta team” (Mortensen & Haas, 2018) from which subteams are formed generally ranges from 20 to 100 members. Subteams range between 2 and more members and are focused on achieving a short-term goal after which they usually dissolve back into the metateam. 

Dynamic teaming approaches challenge two established notions of team design. The first is that they emphasize flexibility over the longevity and stability of teams. A hypothesis in most academic literature is that teams develop “team cognition” as members work together over a longer period of time. Research has linked team cognition to higher performance and motivation (Mathieu et al, 2000), increased effectiveness (Kearny, Gebert & Voelpel, 2009), and generally explains a substantial amount of the variance (~19%) in the effectiveness of teams (De Church & Mesmer-Magnus, 2010). Just like muscle memory, team cognition requires time to form as the members of a team work together on shared tasks. In turn, this facilitates further collaboration. Kozlowski & Ilgen (2006) describe this reciprocity as “process begets structure, which in turn guides process”. This appears to favor stable and long-lived teams.

The second area where dynamic teaming approaches challenge established notion is in the size of teams. The meta team from which subteams are formed is larger than traditional teams, whereas subteams can be as small as 2 members. This brings into question the role of team size as a predictor of effectiveness. Although the optimum size depends on many factors, several studies have recommended around 5 members (plus or minus 2) for regular workgroups (see Horwitz, 2005). For software teams specifically, studies have shown that teams with 9 or more members are significantly less effective than smaller teams (ISBSG, 2007, Rodriguez et. al., 2012). As teams become larger, the quality of their group experience generally diminishes (Aube, Rousseau & Tremblay, 2011). In a study of 97 teams, they found that this is largely moderated by counterproductive behaviors in teams that occur (or not) as teams grow larger, like boastfulness, social loafing, aggression, and low safety. Large teams tend to show lower performance than smaller teams (Gooding & Wagner, 1985; Hoegl, 2005; Kerr, 1989; Poulton & West, 1999; Shepperd, 1993). Members in larger teams tend to show more absenteeism, higher turnover, lower mental health, and less satisfaction with work (Campion, Medsker, & Higgs, 1993; Hausknecht, Trevor, & Howard, 2009; Markham, Dansereau, & Alutto, 1982; Wegge, Roth, Neubach, Schmidt, & Kanfer, 2008). Larger teams may show more counterproductive behaviors that emerge from the lower social cohesion, like boastfulness, aggression, lower safety, and social loafing (Aube, Rousseau & Tremblay, 2011). “In effect, the more members there are in a team, the more likely they are to try to single themselves out from the others to access resources and rewards (Loch, Galunic, & Schneider, 2006; Pierce & White, 1999). The individualistic, even competitive, work atmosphere that may result is apt to foster the adoption of boastful behaviors.”

Dynamic teaming approaches aim to overcome bottlenecks and constraints in the allocation of skills in modern organizations. The need for cross-functional teams has become increasingly important with the rise of Agile methodologies as a means to reduce dependencies and increase responsiveness (Schwaber, 1995; Highsmith, 2009). Particularly in software teams, this includes an ever-growing range of skills necessary to achieve shared goals (i.e. coding, testing, analysis, security, deployment, and discovery). But in practice, it is hard to create stable teams that are small enough and still have all the required skills present. Thus, dynamic teaming approaches attempt to remedy this by introducing the notion of a meta team and one or more dynamic subteams.

An assumption of dynamic teaming is that the social and cognitive benefits of stable team membership are retained through the meta team, whereas the need for dynamically allocated skills is retained through their subteams. Few studies have yet attempted to investigate this. In a review of existing literature on fluid teams, Bushe & Chu (2011) note: “Fluid teams may never have the same potential as stable teams to develop into synergistic, high-performing teams, but sometimes the situation makes them unavoidable”.

Mortensen & Haas (2018) outline some of the challenges associated with research of fluid team designs. Members can be a member of one or more subteams, in addition to their metateam, which means that any measures need to take this into account. They also call for more time-varying measures and techniques like dyadic relationship analysis. 

# Research Questions

- RQ1: How do short-lived teams compare to more long-lived teams in terms of their effectiveness? How does their effectiveness change over time?
- RQ2: What kind of support systems are needed in environments that use dynamic teaming approaches to maintain team effectiveness?

# Hypotheses

- H1: Psychological safety, social/task cohesion, team goal commitment, social identification, and (low) relational conflict contribute to positive team outcomes
- H2: The longer a team works together, the higher their psychological safety, social/task cohesion, team goal commitment, and social identification, and the lower their relational conflict
- H3: Subteams formed from a meta team (i.e. dynamic teaming) are effective more quickly than teams that are not formed from a metateam (“Carryover Hypothesis”)
- H4: The carryover effect of dynamic teaming is moderated by the degree to which metateams and subteams are supported in their use of dynamic teaming and their autonomy

# Research Model

![image](https://github.com/theliberators/scrumteamsurvey.research/assets/39433533/fb3e62ff-d9df-4497-8e68-dd160615a437)

# Study Design

- Structured interviews of informants from Alpha* on the benefits, risks and challenges of dynamic teaming approaches compared to more traditional ones.
- Structured interviews of informants from Alpha* on how organizations support, or can support, dynamic teaming approaches to offset some of the disadvantages compared to long-lived, stable teams
- Structured interviews of informants from Alpha* on how the metateam interacts with subteams
- A quantitative survey study to track how teams perform based on their longevity and their use of dynamic teaming at Alpha*. The questionnaire will be taken at the start of a newly formed subteam and at the end of each "iteration".

*: While Alpha has presented itself as the first collaborator in this study, additional companies may join.

# Data Analysis

To be determined

# Ethical Considerations

# Timeline

- Interview timeline
-
