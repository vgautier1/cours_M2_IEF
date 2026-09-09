# **Courbe de Phillips**

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

unemp_NOR = getdata('EUROSTAT/EI_LMHR_M_LM-UN-T-TOT_SA_PC_ACT/NOR')
infl_NOR = getdata('EUROSTAT/PRC_HICP_MIDX_CP00_I15/NOR?transform=growth_yoy')
infl_NOR = getdata('IMF/CPI_CPI_T_IX_M/NOR?transform=growth_yoy')

tgdp_FRA = getdata('EUROSTAT/NAMQ_10_GDP_B1GQ_SCA_CLV10_MEUR/FRA?transform=growth_yoy')

gdp_FRA = getdata('EUROSTAT/NAMQ_10_GDP_B1GQ_SCA_CLV10_MEUR/FRA')

infl_FRA = getdata('EUROSTAT/EI_CPHI_M_TOTAL_HICP2025/FRA?transform=growth_yoy')

brent  = getdata('PINKSHEET/CRUDE_BRENT/WLD')

tbrent = getdata('PINKSHEET/CRUDE_BRENT/WLD?transform=growth_yoy')



# **PPA & PTI**

**1) PPA : Absolue vs. Relative**

Calculer/estimer les deux versions de la PPA pour 2 économies minimum

**2) PTI : Taux directeur vs. taux long**

Calculer/estimer les deux versions de la PTI pour 2 économies minimum

**3) PPA & PTI : Economies matures vs. émergentes**

Calculer/estimer la PPA et de la PTI pour 2 économies minimum (1 mature et 1 émergente) + estimation PPA/PTI combinée

**4) PPA & PTI: Déterminants fondamentaux et complémentaires**

Estimer une version combinée PPA/PTI et une version combinée PPA/PTI augmentée d’autres déterminants pour 3 économies minimum

usdmxn = getdata('BIS/XRU_D_A/MEX?collapse=M')

usdbrl = getdata('BIS/XRU_D_A/BRA?collapse=M')

usdjpy = getdata('BIS/XRU_D_A/JPN?collapse=M')

usdcad = getdata('BIS/XRU_D_A/CAN?collapse=M')


library(quantmod)

usdvnd = getSymbols("VND=X", src = "yahoo", from = "2000-01-01", periodicity = "monthly", auto.assign = FALSE)


cpi_euz = getdata('BIS/LONG_CPI_628/EUZ?collapse=M')

cpi_mex = getdata('BIS/LONG_CPI_628/MEX?collapse=M')

cpi_bra = getdata('BIS/LONG_CPI_628/BRA?collapse=M')

cpi_jpn = getdata('BIS/LONG_CPI_628/JPN?collapse=M')

cpi_can = getdata('BIS/LONG_CPI_628/CAN?collapse=M')

cpi_usa = getdata('BIS/LONG_CPI_628/USA?collapse=M')

cpi_vnm = getdata('IMF/CPI_CPI_T_IX_M/VNM?collapse=M')







