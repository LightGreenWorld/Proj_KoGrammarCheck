※해당 모델은 국립국어원에 공개 승인을 받은 후에 올리는 것이며, 모델에 사용된 Train, Dev, Test 데이터들은 국립국어원에 귀속되어있으므로 업로드하지 않았습니다.

"Korean_Grammatical_Kobert.ipynb" 파일은 국립국어원 <모두의 말뭉치>에서 2021. 09. 15 ~ 2021. 11. 01, 45일 간 진행한 인공지능 언어 능력 평가의 '문장 문법성 판단'에 대한 코드입니다. 그 당시 저는 문법성 판단 섹션만 맡았으며, 문장 문법성 판단은 Matthew’s Corr를 기준으로 점수가 매겨졌습니다.

아래 RAVI TANWAR의 BERT for English Grammar Checking 글을 참고하여 코드를 작성하였으며, SKT에서 pre-train한 KoBERT를 활용했습니다. 
(https://analyticsindiamag.com/how-to-use-bert-transformer-for-grammar-checking/)



※ This post was approved by National Institute of Korean Language, and I don't upload all datasets(Train, Dev and Test) since the copyright of them belongs to National Institute of Korean Language.

This file "Korean_Grammatical_Kobert.ipynb" is about codes of AI language comprehension evaluation hosted by National Institute of Korean Language <everyone's corpus> throughout the period from Sep 15th 2021 to Nov 1st 2021. Unlike other assignments, an assignment of sentence grammatical evaluation was scored based on Matthew's Corr.

I dealt with the Korean grammatical evaluation with using KoBERT pre-trained by SKT. In order to do, I referred to "BERT for English Grammar Checking" by RAVI TANWAR below and designed my own codes. 
(https://analyticsindiamag.com/how-to-use-bert-transformer-for-grammar-checking/)
