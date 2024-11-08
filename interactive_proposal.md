Diego Daniel Munoz Batista

# Data sources:

CONEVAL (Mexican Institute that measures poverty): https://www.coneval.org.mx/Medicion/MP/Paginas/Programas_BD_2022.aspx

INEGI (National Institute of Statistics): https://www.inegi.org.mx/programas/ccpv/2020/

# Description

CONEVAL has databses for 2016, 2018, 2020, and 2022 about poverty in Mexico. They use national-wide surveys to build their indicators to know if one surveyed household has any kind of poverty.

Use data to display evolution of different types of poverty by state. For example: extreme poverty, alimentary poverty, and educational poverty (there are more). Each household in their databases have weight factor in order to have good representation. Each database (year) has around 250,000 households so we have around 1,000,000 observations. We will collapse data by state and display that information in an interactive way

# Plots

1. The main page will have a choropleth map of Mexico that shows extreme poverty for year 2022. The user can select one state. The first click will display main information such as name, extreme poverty rate, alimentary poverty rate, and population. The second click will redirect the user to a new page that displays more information about that state

Similar to this one: https://theoceancleanup.com/sources/

2. The beginning of each state page will use a simulation that looks like this one: https://www.nytimes.com/interactive/2018/03/27/upshot/make-your-own-mobility-animation.html

It will use buckets as four different levels of alimentary poverty. Instead of black vs white (sadly we do not have race data), we will use educational level as color. I think we may see alimentary poverty in each educational level for certain states (for example, Chiapas).

3. Lastly, I want to add a plot that adds different lines for years 2016, 2018, 2020, and 2022. The user will choose the poverty measure they want to display (poverty rate, extreme poverty, alimentary poverty, access to electricity, etc.)

# Questions

My main concern is to do not have enough time to build every single functionality I want. Do you think is reasonable to achieve all the plots mentioned before? If the answer is no, which one do you find more interesting?

Even if you consider that I dont have enough time, what are the main tools I will use to develop each one of those? I would like to complete this project even after the course ends



