# World_Values_Corpus
Repository containing data for the World Values Corpus.

Files: 
 - WVC_for_RVR_training_and_testing.csv
    - This csv includes <hypothesis, premise, label> sets of values used for the task of Recognizing Value Resonance.
    - This csv includes neutrals generated from the WVC.
    - Random Sample Data Preview:

|     | premise                                                                                                                                                                         | hypothesis                                                                     | label     |   label_coded |
|----:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------|:----------|--------------:|
| 413 | They've managed to raise an amazing kid with an independent mind and no patience for most people.                                                                               | Men and women should decide whether to use condoms together.                   | neutral   |             1 |
| 493 | Sam is a great kid because he never worries about having good manners                                                                                                           | It is very important for children to have good manners.                        | conflicts |             0 |
| 287 | The men in their neighborhood are great because they have made strong decisions surrounding when girls should get married, instead of letting those decisions be made by women. | Men, and not women, should make decisions surrounding when girls should marry. | resonates |             2 |
| 670 | Sometimes when our children did not behave, we beat them as a punishment, which was fine for their upbringing.                                                                  | It is justifiable for parents to beat their children.                          | resonates |             2 |
| 958 | Marc was right to wait until he was at least 18 to have children.                                                                                                               | I would consider myself lower middle class.                                    | neutral   |             1 |

 - annonymized_WVC.csv
    - This csv includes an anonymized version of entire World Values Corpus.
    - Random Sample Data Preview:

|     | WVS_question_id   | WVS_question                                                                        |   annotator | annotation_value_relationship   | textual_premise                                                                                                                                            | value_hypothesis                                                                                        | resonance_label   |   resonance_coded |
|----:|:------------------|:------------------------------------------------------------------------------------|------------:|:--------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------|:------------------|------------------:|
| 602 | Q217              | Political actions online: Searching information about politics and political events |           0 | narrative_restatement           | Jose said he would vote if only he knew about the candidates' platforms and I keep telling him my preferred method is to just just search for them online. | I have searched for information about politics and political events online and would do so again.       | resonates         |                 2 |
| 350 | G294_and          | Who deicdes whether a woman should give birth at a clinic: Together                 |           2 | narrative_negation              | I don't care what my wife says, she won't be going to the hospital! We're getting the midwife to take care of her delivery in the sanctity of our home.    | Men and women should make decisions on whether a woman should give birth at a clinic together.          | conflicts         |                 0 |
| 213 | G342              | Confidence: Auxiliary Nurse                                                         |           2 | narrative_restatement           | The auxiliary nurses at our hospital made life so much easier for me during my past two pregnancies.                                                       | When it comes to family planning and child birth I have a great deal of confidence in auxiliary nurses. | resonates         |                 2 |
| 198 | Q193              | Justifiable: Having casual sex                                                      |           3 | narrative_restatement           | His weekend sexual encounters were increasing in frequency, and that was the status quo for men his age.                                                   | Having casual sex is  is justifiable.                                                                   | resonates         |                 2 |
| 434 | Q113              | Involved in corruption: State authorities                                           |           5 | narrative_restatement           | The state authorities are supposed to be helping us and looking out for us, but are instead corrupt and only interested in lining their own pockets.       | Most state authorities are involved in corruption.                  | resonates         |                 2 |

