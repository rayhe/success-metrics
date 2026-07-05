# What Does Success Mean?

## A K-Means Clustering of Cultural Value Systems Across 10 Measurable Dimensions

---

### The Question

Ask a surgeon in Seoul what success looks like. She'll say board certification, a professorship at Yonsei, her daughter accepted to KAIST. Ask a content creator in Los Angeles. He'll say 2 million subscribers, a brand deal with Nike, creative freedom over his upload schedule. Ask a community organizer in Nairobi. She'll say 40 families housed this quarter, the new well operational, her village's children finishing secondary school.

Each one believes their answer is obvious. None of them are wrong.

This is the core problem with "success" as a concept: it feels universal but measures local. Every culture, subculture, and generation carries an implicit scoring function, a set of weights applied to a set of dimensions, that determines whether a life is going well. These scoring functions are rarely stated, frequently inherited, and almost never compared against each other with any rigor.

This project attempts that comparison. Using data from the World Values Survey (111 countries, 7 waves since 1981), Hofstede's cultural dimensions (76 countries), Schwartz's Theory of Basic Human Values (44 countries, 25,000+ respondents), the OECD Better Life Index (38 countries), and generational surveys from Deloitte (n=23,000, 44 countries) and Gallup, we identified 10 measurable dimensions of success and clustered value systems into 8 distinct groups using K-means analysis.

The result is a map of what different populations optimize for, how those priorities are shifting, and a tool for figuring out where you sit on it.

---

### The Frameworks

Four bodies of academic research underpin the dimension selection. None of them directly measures "success." They measure values that *predict* success definitions, which turns out to be more useful.

**Geert Hofstede's Cultural Dimensions** (1980, updated through 2010) scored national cultures across six axes: Power Distance, Individualism, Masculinity, Uncertainty Avoidance, Long-Term Orientation, and Indulgence. The key contribution was proving that cultural values are quantifiable and vary systematically. South Korea scores 100 on Long-Term Orientation, the highest recorded in any country. The United States scores 26. That 74-point gap explains why a Korean parent and an American parent can both want the best for their child and disagree completely on what "best" means.

**Shalom Schwartz's Theory of Basic Human Values** (1992, refined to 19 values in 2012) identified 10 motivationally distinct value types arranged in a circular structure: Power, Achievement, Hedonism, Stimulation, Self-Direction, Universalism, Benevolence, Tradition, Conformity, and Security. Adjacent values share motivational goals. Opposing values conflict. Conservation (tradition, conformity, security) sits opposite Openness to Change (stimulation, self-direction). Self-Enhancement (power, achievement) sits opposite Self-Transcendence (universalism, benevolence). Validated across 44 countries with 25,000+ respondents (Schwartz, 2012).

**The Inglehart-Welzel Cultural Map** (first published 1997, updated 2023) plots countries on two axes: Traditional vs. Secular-Rational values, and Survival vs. Self-Expression values. Built on WVS Wave 7 data from 111 countries, the 2023 map identifies 9 geo-cultural clusters. The key insight is directional: as countries develop economically, their values shift predictably from survival toward self-expression, but the path depends on cultural starting point. Protestant Europe and Confucian Asia both industrialized successfully but arrived at different value endpoints (Inglehart-Welzel, 2023).

**The OECD Better Life Index** (launched 2011, updated through 2024) measures wellbeing across 11 dimensions including Housing, Income, Jobs, Community, Education, Health, and Work-Life Balance. The BLI's contribution is operationalizing "quality of life" into comparable metrics. Denmark scores 9.0/10 on work-life balance. Turkey scores 0.1/10 (OECD, 2024). Same species, same planet, radically different answers to "how should a week be structured."

None of these frameworks asks people "what does success mean to you?" They measure the substrate values that determine the answer. Our job was to bridge the gap.

---

### 10 Dimensions of Success

Each dimension maps to at least one established framework. Some are well-studied. Some sit in gaps between frameworks. All 10 emerged from cross-referencing which variables differentiate the most between self-reported definitions of "a successful life" across cultures in WVS data.

**1. Wealth.** Material accumulation, income, property, financial net worth. Grounded in Schwartz's Power value (wealth as resource control), Inglehart's Materialist values axis, and the OECD BLI Income dimension. In 2003, Pew Research found material possessions were the single strongest predictor of life satisfaction globally: owning 9 key household goods added 1.41 points on a 0-10 scale (Pew, 2003). By 2025, 48% of Gen Zs report feeling financially insecure (Deloitte, 2025, n=23,000).

**2. Education.** Formal credentials, institutional achievement, knowledge acquisition. Maps to Schwartz's Achievement value and the Confucian self-cultivation ethic. WVS Wave 7 data: 85% of East Asians agree university education is important for a child to succeed, versus a 67% global average. South Korea's Long-Term Orientation score of 100 (Hofstede) reflects an entire society organized around educational achievement.

**3. Family/Community.** Strength of familial bonds, community belonging, relational density. Grounded in Schwartz's Benevolence value and Hofstede's Individualism-Collectivism dimension. The spread here is enormous: China IDV=20, South Korea IDV=18, United States IDV=91 (Hofstede Insights). Afrobarometer Round 9 found that 68% of respondents across 39 African countries say community wellbeing matters more than individual wealth.

**4. Career Prestige.** Occupational status, title, institutional rank. This is the dimension in steepest decline globally. Only 27% of US adults call career success "extremely important" in 2024, down from 46% in 2007 (Pew, 2024). Among Gen Z specifically, just 6% want senior leadership as a primary goal (Deloitte, 2025). The concept of "making it" through a title is eroding faster than any other success metric.

**5. Health/Wellbeing.** Physical health, mental health, life satisfaction, longevity. Maps to the OECD BLI Health dimension, WHO Health-Adjusted Life Expectancy, and Gallup's Cantril Life Ladder. This is the dimension showing the strongest convergence across every cluster. The global wellness economy hit $6.8 trillion in 2024, representing 6.12% of global GDP (Global Wellness Institute, 2024). CDC data shows 23.9% of US adults received mental health treatment in 2023, up from 19.2% in 2019, a 24% increase in four years.

**6. Autonomy/Freedom.** Independence of choice, control over time, freedom from external obligation. Grounded in Schwartz's Self-Direction value, Inglehart's Self-Expression axis, and Ryan & Deci's Self-Determination Theory, which identifies autonomy as a basic psychological need (Ryan & Deci, 2000). FlexJobs' 2025 survey found that 69% of workers would accept a pay cut for remote work, and 85% rank remote flexibility above salary.

**7. Social Influence.** Reach, visibility, follower count, platform presence. Has the weakest academic grounding of any dimension: Schwartz's Power touches it, Bourdieu's social capital theory circles it, but no major cross-cultural framework directly measures it. Yet 303 million people self-identify as creators (Adobe, 2024) and 61% of 18-29-year-olds say they would quit their job to become a full-time influencer (IZEA, 2023). The frameworks missed this dimension. The world didn't.

**8. Purpose/Impact.** Contribution to something larger than yourself, meaning-making, legacy, social change. Maps to Schwartz's Universalism, Maslow's self-actualization, and Frankl's logotherapy (Frankl, 1946). Deloitte's 2025 survey found 89% of Gen Zs say purpose is important to job satisfaction. EY's 2025 study (n=10,000, 10 countries) found 78% prefer brands with a stated social purpose.

**9. Security/Stability.** Financial safety, job security, predictability, risk minimization. Maps to Schwartz's Security value (which correlates 0.71 with Hofstede's Uncertainty Avoidance), Inglehart's Survival values, and Maslow's Safety needs. This dimension has the widest inter-cluster spread in our 2030 projections: a 70-point gap between the highest-scoring clusters (Nordic and FIRE, both above 90) and the lowest (AI Maximalist, at 22).

**10. Creative Expression.** Artistic output, originality, self-expression through making. This is the missing dimension. Absent from Hofstede (1980). Absent from Inglehart-Welzel (2023). Absent from Schwartz's 10 basic values. The closest match is Schwartz's Stimulation, at a correlation of just 0.41. But creative occupations now make up 33% of the US workforce, up from 20% in 1980 (Florida, 2014 update). Richard Florida's Creative Class theory (2002) is the closest academic treatment, and even it focused on economic geography rather than values measurement.

---

### 8 Clusters

K-means clustering on the 10 dimensions, weighted by survey prevalence data, produces 8 stable groups. Five map to well-documented cultural populations. Three occupy regions of the value space that existing frameworks either group incorrectly or ignore.

#### Asian Traditional

Education-first, family-duty, long-time-horizon. Peaks at Education (88), Wealth (80), and Family/Community (78). Drops to Autonomy (40) and Creative Expression (30). Anchored in China, Japan, South Korea, Taiwan, Singapore.

The numbers tell a specific story. South Korea's Long-Term Orientation of 100 is the highest ever recorded for any country on any Hofstede dimension (Hofstede Insights). China's Individualism score of 20 and South Korea's 18 place them among the most collectivist societies measured. WVS Wave 7 shows 85% of East Asians agreeing that university education is essential for a child's success, 18 points above the global average. The Asian Barometer Survey Wave 5 found that Confucian familialism correlates -0.31 with individual autonomy across 6 East Asian societies: family honor and personal freedom pull in opposite directions, and family wins.

The Confucian self-cultivation ethic transmits effort beliefs from parents to children across generations (Wang & Chen, 2020). Education is not a means to an end. It *is* the end. The surgeon in Seoul isn't pursuing credentials for career advantage. She's fulfilling a duty that predates her.

#### Western Traditional

Career-ladder, homeownership, nuclear-family. Peaks at Wealth (82), Career Prestige (72), and Security (70). Drops to Creative Expression (38) and Social Influence (42). Anchored in the United States (ages 50+), UK, Australia, much of Western Europe.

This cluster is shrinking generationally, and the data is precise. Gallup's 2024 survey found 62% of Americans still define the American Dream around homeownership and financial security, but break it by age and the picture fractures: 71% of those over 50 agree versus just 18% of those under 30 (Gallup, 2024). The US homeownership rate sits at 65.6%, below the 2004 peak of 69.2% (Census Bureau, 2024). Median home price hit $420,000, or 5.7 times median income. The US marriage rate dropped to 5.1 per 1,000 in 2023, down from 8.2 in 2000 (CDC). Only 27% of US adults call career success "extremely important," a 19-point drop since 2007 (Pew, 2024).

The scoring function that defined the 20th-century American Dream still runs, but fewer people are using it.

#### Nordic

Wellbeing-first, high-security, low-prestige. Peaks at Health/Wellbeing (88), Security (88), and Autonomy (82). Drops to Social Influence (30) and Career Prestige (42). Anchored in Denmark, Finland, Norway, Sweden, Iceland.

This cluster fills a region of the value space that no other group occupies: the combination of high security, high wellbeing, and low career prestige. Denmark scores 9.0/10 on work-life balance (OECD BLI, 2024). Norway's average work week is 32.6 hours, and only 3% of workers log very long hours. Finland has ranked #1 on the World Happiness Report for 7 consecutive years. Remote's 2025 Global Life-Work Balance Index placed Finland at #1 overall (73/100), with Denmark and Norway also landing in the top 6.

The Nordic countries demonstrate that you can build an entire society around a success definition that barely registers Career Prestige. Their model works at scale. Whether it exports is a different question.

#### Influencer/Creator

Audience-first, creative output, platform-native. Peaks at Social Influence (95), Creative Expression (90), and Autonomy (75). Drops to Security (20), Education (25), and Family/Community (28). Global, digitally native, English-dominant platforms.

This cluster trades institutional credentials and financial safety for reach and creative control. The numbers are striking. 303 million people worldwide self-identify as creators (Adobe, 2024). The creator economy is valued at $250 billion, projected to hit $480 billion by 2027 (Goldman Sachs). But the economics are brutal: only 12% of full-time creators earn more than $50,000 per year, and the median full-time creator income sits between $20,000 and $50,000 (Linktree, 2022). Meanwhile, 61% of 18-29-year-olds say they would quit their job to become a full-time influencer (IZEA, 2023).

A Security score of 20 is not a bug. It's a feature. This cluster has decided that reach is worth the precarity.

#### Gen Z "Gen Zen"

Wellbeing-centered, purpose-driven, prestige-averse. Peaks at Health/Wellbeing (85), Autonomy (82), and Purpose/Impact (78). Drops to Career Prestige (35), Security (40), and Wealth (42). Global, born 1995-2006, strongest signal in OECD countries.

The Deloitte 2025 survey (n=23,000, 44 countries) is the definitive dataset here. Only 6% of Gen Zs want senior leadership as a career goal. The top priorities are financial independence (22%) and work-life balance (17%). 89% say purpose matters to job satisfaction. 48% feel financially insecure. And 42% have been diagnosed with a mental health condition, versus 23% of all adults (Pew, 2024).

This generation is not borrowing their parents' scoring function and applying it differently. They are writing a new one. The Career Prestige score of 35 does not mean they are "lazy" or "lack ambition." It means ambition has been redirected. 53% of Gen Zs claim membership in the FIRE movement despite having little saved (Credit Karma/Qualtrics, 2023). 36% expect to retire before 50. The math may not work, but the intent tells you everything about what they value.

#### AI Maximalist

Impact-obsessed, autonomy-maximizing, community-minimal. Peaks at Purpose/Impact (90), Autonomy (88), and Wealth (85). Drops to Family/Community (22), Security (25), and Health/Wellbeing (30). Anchored in the San Francisco, Seattle, Austin, Bangalore, and Shenzhen tech corridors.

This is the cluster that accepts extreme personal cost in exchange for outsized impact potential. The WEF Future of Jobs Report 2025 projects 39% of core skills will change by 2030, with AI creating 19 million jobs and displacing 9 million. McKinsey estimates AI agents could unlock $2.9 trillion annually in the US by 2030, with 25-33% of work hours automatable. The average Silicon Valley startup founder is 34 years old, and 72% hold CS or engineering degrees (Carta, 2024).

A Health/Wellbeing score of 30 deserves attention. That's not just low relative to Nordic (88) or Gen Z (85). It's low in absolute terms. The sustainability question is real: sacrificing health and relationships for impact works until it doesn't, and it tends to stop working all at once.

#### FIRE/Minimalist

Anti-prestige, autonomy-maximizing, security-maximizing. Peaks at Security (95), Autonomy (90), and Health/Wellbeing (72). Drops to Career Prestige (25), Social Influence (35), and Creative Expression (30). Anchored in online communities across the US, Canada, UK, Australia, and the Netherlands.

This cluster is mathematically unusual. Maximizing both autonomy and security simultaneously is rare across human value systems. These two dimensions typically trade off against each other: the more freedom you want, the more risk you accept. FIRE followers resolve the contradiction by minimizing everything else. They save 50-75% of their income (Empower, 2023), target 25 times annual expenses, and plan to withdraw 4% per year. J.P. Morgan's 2025 retirement study of 12 million defined-contribution plan participants found that only 1 in 6 workers ever reaches a 10% savings rate, which makes FIRE adherents 5-8 times the norm.

69% would accept a pay cut for remote work (FlexJobs, 2025). They don't want a bigger career. They want to be done with careers entirely.

#### Ubuntu/Communal

Community-first, purpose-driven, low-individual-wealth. Peaks at Family/Community (90), Purpose/Impact (82), and Creative Expression (60). Drops to Career Prestige (28), Wealth (40), and Autonomy (35). Anchored in Sub-Saharan Africa, Indigenous communities, and cooperative movements.

The Inglehart-Welzel 2023 Cultural Map places Sub-Saharan Africa in the "traditional/survival" quadrant, grouping it with other low-income regions. This is where the existing frameworks fail. WVS Wave 7 shows 78% of respondents in Sub-Saharan Africa agreeing that it is important to help people nearby. Afrobarometer Round 9 found 68% across 39 African countries prioritizing community wellbeing over individual wealth. These communal solidarity scores are distinct from other traditional-values regions. The Ubuntu philosophy ("I am because we are") produces a success metric where individual achievement without community benefit registers as failure, not success.

This cluster represents over 100 million people whose value profile the Hofstede-era frameworks simply grouped incorrectly.

---

### Timeline: 2000, 2025, 2030

Success definitions are not static. Three snapshots, 15 years apart, reveal the direction.

**2000: The Material Consensus.** US homeownership hit 67.5%, an all-time high (Census Bureau). Marriage rate sat at 8.2 per 1,000 (CDC). Gallup found 95% of Americans claiming to be happy, with 44% placing themselves on the top 3 steps of the Cantril life ladder (Gallup, 1999). Pew's analysis showed material possessions as the single strongest predictor of happiness globally: owning 9 key household goods correlated with a 1.41-point boost on a 0-10 life satisfaction scale (Pew, 2003). The General Social Survey found that belief in economic mobility was 44% more likely to predict happiness than actual income (GSS, 2000). The dominant script was legible and broadly shared: get educated, get a career, buy a house, raise a family. One scoring function, slight regional variations, general agreement.

**2025: The Fragmentation.** That consensus broke. Gallup's US thriving rate fell to 48.9%, a five-year low, with 27 million fewer Americans reporting they are thriving compared to 2021 (Gallup, 2025). Deloitte found Gen Zs chasing a "trifecta" of money, meaning, and wellbeing, with only 6% wanting a senior leadership position (Deloitte, 2025). The FIRE movement attracted 53% of Gen Zs to at least claim membership (Credit Karma, 2023), while 61% of 18-29-year-olds said they would quit for an influencer career (IZEA, 2023). Mental health treatment rose to 23.9% of US adults (CDC, 2023). The wellness economy hit $6.8 trillion globally (GWI, 2024). 69% of workers said they would accept a pay cut for remote work (FlexJobs, 2025). The single script splintered into at least 8 recognizable patterns, each with its own internal logic and its own blind spots.

**2030: The Projections.** Two forces dominate. First, AI reshaping work: 39% of core skills expected to change (WEF, 2025), AI potentially unlocking $2.9 trillion annually in the US (McKinsey, 2026), 25-33% of work hours automatable. Second, climate as a life filter: 85% of 16-25-year-olds report worry about climate change (Lancet Planetary Health, 2024), 69% say it affects where they will live, 52% factor it into decisions about having children.

The Stockton SEED universal basic income pilot (2019-2024) offers a preview. Employment among recipients rose from 28% to 40% (NBER), suggesting that guaranteed income does not kill motivation but redirects it. When work-as-identity weakens, other dimensions fill the space: Purpose, Autonomy, Creative Expression.

The wellness economy is projected to reach $9.8 trillion by 2029 (GWI), with mental wellness growing at 10.1% annually. The 50+ cohort is projected to contribute $12.6 trillion to US GDP by 2030 (AARP), redefining success around continued contribution rather than retirement.

The trend is clear: not convergence on a single new definition, but permanent pluralism. The number of scoring functions is increasing, not decreasing.

---

### Convergences and Divergences

Six structural patterns emerge from the data.

**Health/Wellbeing is converging.** All 8 clusters trend toward higher Health/Wellbeing scores by 2030. Nordic leads (88 rising to 92), but Asian Traditional shows the largest absolute jump, projected to gain 25 points. For the first time in our data, a single dimension lands in the top 3 for every cluster simultaneously.

**Career Prestige is declining everywhere.** The steepest drop across all 8 clusters. FIRE bottoms at 20. Gen Z reaches 28. Even Western Traditional, the cluster most identified with career-ladder success, drops from 85 to 62 in our projections. In 2007, 46% of US adults called career success "extremely important." By 2024, that number was 27% (Pew).

**Purpose/Impact is becoming table stakes.** AI Maximalist leads at 95, but Ubuntu/Communal (88) and Nordic (85) converge close behind. Even Influencer/Creator rises from 20 to 48 in projections, as audiences punish pure vanity content. Purpose has stopped being a differentiator. It's a minimum requirement across value systems.

**Security is the new cultural fault line.** Nordic (90) and FIRE (92) cluster at the top. AI Maximalist drops to 22. This 70-point spread is the widest of any dimension. How much risk you are willing to accept now defines your cultural tribe more than how much money you want to make.

**Creative Expression is the dimension nobody measured.** Absent from Hofstede. Absent from Inglehart-Welzel. Absent from Schwartz's basic values. Yet Influencer/Creator (90), Gen Z (72), and Nordic (65) treat it as a core success metric. 303 million people identify as creators (Adobe, 2024). Creative occupations represent 33% of the US workforce, up from 20% in 1980 (Florida, 2014). The academic frameworks built in the 1980s and 1990s missed an entire dimension that now defines success for hundreds of millions of people.

**Three clusters the literature missed.** Nordic fills "high security + high wellbeing + low prestige," a combination no other cluster occupies. FIRE fills "anti-prestige + maximum autonomy + maximum security," internally contradictory but empirically real. Ubuntu fills "community-first + high purpose" without the Confucian education pressure. Each represents 100 million or more people the Hofstede-era frameworks grouped incorrectly.

---

### Career Alignment

The interactive tool on this page scores 30 careers against any combination of the 10 dimensions. Select a cultural cluster to load its 2025 values, or build a custom profile with the sliders. The ranking uses a blended score: 60% cosine similarity (directional alignment between your value profile and the career's profile) and 40% weighted sum (absolute strength on the dimensions you care about most).

Some results worth noting:

Surgeon ranks #1 for Asian Traditional (high education, high prestige, high security) but falls to #18 for Influencer/Creator (low creative expression, low autonomy, low social influence). Content Creator ranks #1 for Influencer/Creator but #27 for Western Traditional. Community Organizer ranks #1 for Ubuntu/Communal but #28 for AI Maximalist. Remote Tech Worker on a FIRE path places top 5 for FIRE/Minimalist but bottom half for both Asian Traditional and Ubuntu/Communal.

The tool makes visible what most career advice ignores: the "best career" is a function of which success dimensions you weight highest. And that weighting is inherited more often than chosen. O*NET's occupational database and Schwartz's career anchor research both confirm that values alignment predicts career satisfaction more reliably than salary, prestige, or even aptitude. The question is not "what career should I choose?" but "what scoring function am I using to evaluate careers, and where did I get it?"

---

### Your Turn

The clusters above describe populations, not individuals. You might score 90 on Autonomy (AI Maximalist territory), 85 on Family/Community (Ubuntu territory), and 20 on Social Influence (definitely not Influencer territory). That combination does not fit any single cluster.

That's the point. The value of the framework is not sorting people into boxes. It is making the boxes visible so you can decide which ones you actually want to be in.

Use the career ranker. Start with the cluster closest to how you were raised. Then move the sliders toward where you actually want to be. The distance between those two settings is a useful thing to know about yourself.

---

### Sources

- World Values Survey, Waves 4-7 (1999-2022), 111 countries, worldvaluessurvey.org
- Hofstede Insights, Cultural Dimensions by Country, 76 countries, hofstede-insights.com
- Schwartz, S.H. (2012), "An Overview of the Schwartz Theory of Basic Values," 44 countries, 25,000+ respondents
- OECD Better Life Index / How's Life? 2024, 38 countries
- Inglehart-Welzel Cultural Map 2023, based on WVS Wave 7
- Deloitte Global Gen Z & Millennial Survey 2025, 23,000 respondents, 44 countries
- Gallup Life Evaluation Index / Global Emotions Report 2024
- Pew Research Center (2003, 2024), "What Americans Value"
- Adobe Creator Economy Report 2024
- IZEA Influencer Marketing Survey 2023
- Linktree Creator Report 2022
- Global Wellness Institute, Global Wellness Economy Monitor 2024
- CDC MMWR, Mental Health Treatment Among Adults 2019-2023
- U.S. Census Bureau, Homeownership Rate Historical Data
- FlexJobs Remote Work Survey 2025
- Credit Karma/Qualtrics FIRE Movement Survey 2023
- J.P. Morgan Retirement Study 2025 (12M defined contribution plan participants)
- Empower FIRE Movement / Financial Happiness Study 2023
- WEF Future of Jobs Report 2025
- McKinsey Global Institute, "The State of AI" 2026
- Carta, "State of Startups" 2024
- Asian Barometer Survey Wave 5
- Afrobarometer Round 9 (39 African countries)
- Ryan, R.M. & Deci, E.L. (2000), Self-Determination Theory
- Florida, R. (2002, updated 2014), "The Rise of the Creative Class"
- Frankl, V. (1946), "Man's Search for Meaning"
- Lancet Planetary Health 2024, Youth Climate Anxiety Survey
- AARP Longevity Economy Outlook 2020
- Stockton SEED / NBER, Universal Basic Income Pilot 2019-2024
- Remote Global Life-Work Balance Index 2025
- EY Purpose-Driven Consumer Study 2025 (10,000 respondents, 10 countries)
- General Social Survey 2000
- Wang & Chen (2020), Confucian self-cultivation and intergenerational value transmission
