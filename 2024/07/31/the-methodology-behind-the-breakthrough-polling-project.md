# The methodology behind The Breakthrough polling project

Published :`2024-07-31 15:36:44`

---

The Breakthrough is a project from CNN, Georgetown University, the University of Michigan, SSRS and Verasight.

Each week, 1,000 Americans are asked to share what they have seen, read or heard about major presidential candidates in their own words. The results build on similar work in the 2016 and 2020 presidential elections, and provide a unique window into how people across the country are experiencing this year’s historic campaign.

Interviews for this project began on June 21, just before CNN’s presidential debate between President Joe Biden and former President Donald Trump, and will run through the Sunday after Election Day.

Results for the survey are collected online from Friday through Monday each week, in English, among a nationwide sample of approximately 1,000 adults per week via the SSRS Opinion Panel Omnibus survey and Verasight’s verified panel. Results from the two surveys are combined using SSRS’s Encipher Hybrid methodology for blending probability and non-probability samples.

Survey takers are asked about the major party candidates: “What, if anything, have you heard, read or seen in the past few days about Donald Trump?” and “What, if anything, have you heard, read or seen in the past few days about Kamala Harris?” Respondents are also asked the same question about independent candidate Robert F. Kennedy, Jr. The question about Harris was added to the survey on July 19, shortly before Biden announced his decision to end his reelection campaign. Respondents have also been asked the same question about Biden since the start of the project.

The order in which the questions are asked is randomized, so that not all respondents are asked about the candidates in the same order. Exact responses to these questions are coded based on traditional text preprocessing for word frequency analysis, topic modeling for topic analysis, and deep learning for sentiment analysis. The code-base is jointly developed by Lisa Singh at Georgetown University with input from her research team and the Massive Data Institute Technical Team and Josh Pasek, Michael Traugott and Ceren Budak at the University of Michigan.

As the campaign progresses, the words associated with individual topics may change, which could result in changes to the relative position of those topics in older results. Those changes are necessary in order for current comparisons to be valid. To develop topics, topic words are manually identified and augmented with words and topics identified using a combination of Noiseless Latent Dirichlet Allocation (NLDA) and Guided Topic-Noise Model (GTM). Sentiment is coded using RoBERTa pretrained on English tweets and finetuned with SemEva.

The research team conducting analysis of the results of The Breakthrough and managing fielding of the survey are: Jennifer Agiesta, Ariel Edwards-Levy, Edward Wu and Dana Elobaid from CNN; Lisa Singh, Le Bao, Yanchen Wang and Mohamed Ahmed from Georgetown University; Josh Pasek, Michael Traugott and Ceren Budak from the University of Michigan; Akilah Evans-Pigford, Hope Wilson, Cameron McPhee and multiple members of the SSRS Advanced Methods and Data Science team from SSRS; and Peter K. Enns, Gretchen Streett, Amelia Goranson, and Jake Rothschild from Verasight.

---

