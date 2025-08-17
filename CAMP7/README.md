# Exploring Reflexive Pronoun Development and Usage in Mandarin-Learning Toddlers: A Comparative Study of ASD and TD Groups
in [California Meeting on Psycholinguistics 7]([https://blogs.ncl.ac.uk/cls2024/](https://camp7.ucsd.edu/home)) (CAMP7)

Mandarin Chinese has two reflexive forms: the bare reflexives (e.g., ziji‘self’) and compound reflexives (e.g., ta-ziji‘himself/herself’), and the bare forms can function not only as syntactically bound anaphors, but also as logophors, generic pronouns (akin to English you/one), and intensifiers (e.g. Wang & Pan 2021, examples in Fig.1). We refer to these as 'discourse-semantic uses', because they are sensitive to a variety of semantic, pragmatic and discourse factors (e.g. Wang & Pan, 2021, see examples in Figure 1).

Previous research indicates that Mandarin-learning typically developing (TD) toddlers grasp bare reflexives earlier than compound reflexives, and by the age of two, they exhibit an earlier understanding of the syntactically-governed uses compared to other discourse-semantic uses which are typically comprehended around 4;0 (Li, 2024). In contrast, children with Autism Spectrum Disorder (ASD) face challenges in acquiring reflexives and their binding conditions and have later syntactical acquisition of anaphors around the age of 6;0 (Wuyun et al., 2023). However, previous research has not examined how Mandarin-learning toddlers with ASD acquire discourse-semantic contrastive uses. Language impairment is one of the most prominent early indicators of ASD, often first noticed by parents. Additionally, Mandarin reflexives represent a multifaceted system that incorporates various levels of linguistic features. Therefore, studying the reflexive pronoun development of children with and without ASD not only facilitates early diagnosis and interventions for ASD but also provides a window to explore the complex relationship between different levels of linguistic constraints and broader cognitive functions. This study offers valuable insights that improve our understanding of typical and atypical populations and their impact on pronoun acquisition and language acquisition in general.

In this study, we analyzed the parental input and child production of Mandarin reflexives by monolingual TD toddlers (N = 21) and those with ASD (N = 7) through naturalistic parent-child play sessions, longitudinally sampled over two years of time domain (Rangeage 4;0 - 6;0). The TD data were sourced from the Chang Play Corpus from T alkBank (Chang, 2019), and the ASD data were sourced from the Mandarin Shanghai Corpus from ASDBank (Zhou, 2006). Despite the limited dataset, preliminary findings reveal there are no significant differences in the parental input to TD vs ASD children, except for the TD parents providing more generic pronouns and intensifiers compared to the ASD parents (see details in Figure 2). In terms of child production, the TD children begin producing both bare and compound reflexives around the age of 4;0, indicating an earlier emergence compared to their ASD peers who show a delay with their first production of compound reflexives at 4;4, and bare reflexives at 4;5. Interestingly, neither group exhibited logophoric use of ziji, potentially due to its rare occurrences in parental input (N = 3, Input Proportion = 0.01% - 0.04%). Further distinctions were found in the use of anaphoric reflexives. ASD children did not produce anaphoric reflexives at all, whereas their TD peers began producing it around the age of 5;4, which aligns with previous research and suggests there might be a syntactical delay among the children with ASD. The discourse-semantic uses were the most common usages observed in both groups, with an earlier emergence of around 4;0, which is earlier than previously reported, indicating an accelerated developmental onset of the uses. Our results also suggest children with ASD may more successfully use reflexive types sensitive to semantics and discourse/pragmatics compared to syntactical bound uses, suggesting they may not be significantly impaired in terms of semantics, pragmatics, or discourse. Overall, our findings underscore distinct developmental trajectories in how both typical and atypical children acquire different types of Mandarin reflexive pronouns, which provide valuable insights into the linguistics binding theories and the cognitive mechanisms underlying language acquisition.

## Citation 
Chen, Y., Su, Y., (2024, November). Exploring Reflexive Pronoun Development and Usage in Mandarin-Learning Toddlers: A Comparative Study of ASD and TD Groups. [Poster] California Meeting on Psycholinguistics 7 (CAMP7), San Diego, CA.
## References
Chang, C. (2005). Parent-child interaction and child language/literacy development [T technical report]. T aipei, T aiwan: National Science Council, T aiwan. (NSC-91-2413-H-152-017, NSC-92-2413-H-003-074, NSC-93-2413-H-152-010)

Li, R. (2024). The Acquisition of Anaphora in Child Mandarin: Reflexive Binding and Argument Dropping. T aylor & Francis.

Wang, Y ., & Pan, H. (2021). Chinese reflexives. Oxford Research Encyclopedia of Linguistics.

Wuyun, G., Zhang, L., Wang, K., & Wu, Y . (2023). Discourse prominence effects on the interpretation of the reflexive pronoun “ziji” in children with ASD. Reading and Writing, 36(6), 1393-1417.

Zhou, 2006, ASDBank Mandarin Shanghai Corpus. [Online]. Available: https://doi.org/10.21415/T5HW46

## Acknowledgments
We are deeply grateful to Dr. Elsi Kaiser and Dr. Zuzanna Fuchs from USC, for their invaluable guidance and to all the lab members of the Psycholinguistics Meeting at USC for their support and suggestions.

# Employing Machine Learning and Language Models to Differentiate Language Patterns in Mandarin-Speaking Preschoolers with Autism Spectrum Disorder
in [California Meeting on Psycholinguistics 7]([https://blogs.ncl.ac.uk/cls2024/](https://camp7.ucsd.edu/home)) (CAMP7)

Autism Spectrum Disorder (ASD) is a neurodevelopmental disorder with significant challenges in communication and language. Verbal preschoolers with ASD can exhibit difficulties in lexical and grammatical domains such as shorter Mean Length of Utterance (MLU) compared to their typical developing (TD) peers (Su et al., 2018; Zhou et al., 2015). However, research on identifying ASD preschoolers using machine learning (ML) and language models (LM) based on naturalistic production data remains sparse. This paper describes a pilot study that applies ML and LM to distinguish between ASD and typical utterances, offering a potential for ecologically valid, cost-effective ASD screening that enables early intervention.

Primary data used utterances produced by Mandarin-speaking ASD (N = 7, AgeRange = 4;0 - 6;0) and TD children (N = 43, AgeRange = 3;0 - 6;0), extracted from adult-child interaction recordings from existing corpora. The ASD data were derived from the Mandarin Shanghai Corpus from the ASDBank (longitudinal, NASD_utterance = 2975), and the TD data were derived from the Beijing Child Mandarin Corpus (cross-sectional, Mai et al., in prep, NTD_utterance = 3016). Data preprocessing included manual cleaning to screen out one-word utterances, non-verbal elements and disfluencies  (details in Table 1). Four ML models were employed: a Chinese BERT (Devlin et al., 2019), a multilingual XLM-RoBERTa, and ChatGPT to provide classification directly based on cleaned utterances and Logistic Regression to provide classification based on numerical data (e.g., MLUw) calculated from the cleaned transcripts. Except for ChatGPT which employs in-context learning, all models were trained on 78% of the data with a validation set consisting of 10% of the data, and tested on the remaining 12% data which avoids speaker overlap and ensures unbiased results. A trained speech therapist manually coded 20% of the test data (Nutterance = 150) for comparison.

Preliminary results revealed shorter MLUw and reduced lexical diversity of the ASD utterances, aligning with previous research. A significant difference was observed in MLUw (p < 0.05), suggesting that an increase in MLUw corresponds to a decreased likelihood of ASD. As shown in Table 2, all models showed high accuracy and precision with strong reliability in classifying utterances produced by ASD children, except for ChatGPT. Rating of the speech therapist exhibited lower accuracy, likely due to different criteria adopted (e.g., stereotyped and idiosyncratic use of words or phrases across utterances, more disfluencies, which were missing from the utterances judged). The results suggest a potential for ML applications as an easy, early and economical screening tool for ASD before comprehensive human rating. The disparity in performance between the four models and human rating on the other is attributable to differences in evaluative criteria. ChatGPT, like human raters, may incorporate broader contextual and pragmatic knowledge about the production and behavioral characteristics of ASD when assessing the given utterances.

Overall, this study highlights the effectiveness of ML methods in identifying ASD using readily available child speech data, paving the way for future development of practical, non-invasive early detection tools for Mandarin-speaking children in clinical settings.

## Citation 
Chen, Y., Mai, Z., Chen, Y., (2024, November). Employing Machine Learning and Language Models to Differentiate Language Patterns in Mandarin-Speaking Preschoolers with Autism Spectrum Disorder. [Poster] California Meeting on Psycholinguistics 7 (CAMP7), San Diego, CA.

## References
ASDBank Mandarin Shanghai Corpus. [Online]. Available: https://doi.org/10.21415/T5HW46

Conneau, A. "Unsupervised cross-lingual representation learning at scale." arXiv preprint arXiv:1911.02116 (2019).

Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2018). Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805.

Baird, Gillian, and Courtenay Frazier Norbury. "Social (pragmatic) communication disorders and autism spectrum disorder." Archives of Disease in Childhood 101.8 (2016): 745-751.

Rice, Mabel L., et al. "Mean length of utterance levels in 6-month intervals for children 3 to 9 years with and without language impairments." (2010).

Sandbank, Micheal, and Paul Yoder. "The association between parental mean length of utterance and language outcomes in children with disabilities: A correlational meta-analysis." American Journal of Speech-Language Pathology 25.2 (2016): 240-251.

Su, Y., Naigles, L. R., & Su, L. Y. (2018). Uneven expressive language development in Mandarin-exposed preschool children with ASD: Comparing vocabulary, grammar, and the decontextualized use of language via the PCDI-Toddler Form. Journal of autism and developmental disorders, 48(10), 3432-3448.

Zhou, P., Crain, S., Gao, L., Tang, Y., & Jia, M. (2015). The use of grammatical morphemes by Mandarin-speaking children with high functioning autism. Journal of Autism and Developmental Disorders, 45, 1428-1436.

## Acknowledgments
We are deeply grateful to our colleagues and collaborators: Jingyao Liu, Xuening Zhang, Yuqing Liang, and Jiaqi Nie. We are also grateful to Dr. Elsi Kaiser and Dr. Zuzanna Fuchs from USC, for their invaluable suggestions and comments. The Research grants awarded to Ziyin Mai: “Input and experience in early trilingual development”, RGC/GRF, 2021-2024; “Input and caretaker proficiency in early bilingual development: mothers, helpers and toddlers ”, RGC/ECS, 2023-2025.}

