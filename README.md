**1) Courbe de Phillips dans la Zone Euro – Analyse de l’impact selon le type de chômage**

Comparer la courbe de Phillips dans deux économies de la Zone Euro, l’une dont le chômage est à dominante structurelle et l’autre conjoncturelle


**2) Courbe de Phillips dans la Zone Euro – Analyse de l’impact selon la dépendance énergétique**

Comparer la courbe de Phillips dans deux économies de la Zone Euro, l’une fortement dépendante des importations d’énergie (notamment pétrole) et l’autre non


**3) Courbe de Phillips dans la Zone Euro – Evolution de la pente**

Analyser la courbe de Phillips pour différentes sous-périodes caractéristiques de la Zone Euro (inspiration papier BdF 2018)


**4) Courbe de Phillips dans le monde – Economies matures VS émergentes**

Comparer la courbe de Phillips dans deux économies du monde, l’une mature l’autre émergente (problématique d’ancrage des anticipations d’inflation)


vac_FRA = getdata('EUROSTAT/JVS_Q_NACE2_JOBRATE_SA_B-S_TOTAL/FRA?collapse=M')

unemp_FRA = getdata('EUROSTAT/EI_LMHR_M_LM-UN-T-TOT_SA_PC_ACT/FRA')

tgdp_FRA = getdata('EUROSTAT/NAMQ_10_GDP_B1GQ_NSA_CLV10_MEUR/FRA?transform=growth_yoy')
gdp_FRA = getdata('EUROSTAT/NAMQ_10_GDP_B1GQ_NSA_CLV10_MEUR/FRA')

infl_FRA = getdata('EUROSTAT/PRC_HICP_MIDX_CP00_I15/FRA?transform=growth_yoy')

brent  = getdata('PINKSHEET/CRUDE_BRENT/WLD')
tbrent = getdata('PINKSHEET/CRUDE_BRENT/WLD?transform=growth_yoy')





