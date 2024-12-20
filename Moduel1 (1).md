Coursera Data Management and Visualization 과제
# MODULE 1
## 1단계: 작업할 데이터 집합을 선택 **Gapminder Codebook**
. Gapminder는 세계 인구, 건강, 경제 등 다양한 사회 지표에 대한 데이터를 이해하기 쉽게 제공하는 비영리 단체 및 데이터 도구임  
. 저는 다양한 국가들의 통계에서 상관관계를 파악하기 위해 Gapminder의 코드북을 사용하기로 결정했습니다. 

## 2단계: 연구 질문과 가설을 제시
Gapminder Codebook을 살펴보면 다음의 열로 구성되어 있습니다.
![image](https://github.com/user-attachments/assets/a44ae182-beae-4897-ad0e-b23fce09547c)



국가에 따라 다양한 변수들이 존재하고 있는데, 저는 여기서 다음의 두가지 주제를 분석하고자 합니다. 

**1. 유방암 발생률과 소득간의 상관관계 분석**
변수: breastcancerper100th (100명당 유방암 발생률)와 incomeperperson (인당 소득)  
연구 주제: 국가별 100명당 유방암 발생률과 인당 소득 간의 상관관계를 분석함으로써, 소득이 건강과 생명에 미치는 영향을 파악할 수 있습니다. 이를 통해 경제 발전이 인구 건강에 어떤 역할을 하는지 탐구할 수 있습니다.
![image](https://github.com/user-attachments/assets/6cb0cf2d-0c60-4c04-8559-9839a977298f)




**2. 인터넷 사용자 비율과 유방암 발생률간의 상관관계 분석**
변수: Internetuserate (인터넷 사용자 비율)과 breastcancerper100th (100명당 유방암 발생률)  
연구 주제: 인터넷 사용률이 높은 국가들이 경제적으로 더 발전했는지, 혹은 인터넷 사용이 국민 건강의 중요한 요인인지 분석할 수 있습니다.  
디지털화가 국민 건강에 미치는 영향을 이해하는 데 유용한 주제가 될 수 있습니다.
![image](https://github.com/user-attachments/assets/f3a6547a-5f1e-4049-98bb-88d32e0533f3)

**연구 가설 : 소득이 높을 경우 100명당 유방암 발생률이 낮을 것으로 추정되며, 인터넷 사용자 비율이 높을수록 유방암 발생률이 낮을 것으로 예상됨**

## 3단계: 문헌검토
100명당 유방암 발생률과 인당 소득/인터넷 사용자비율에 대한 다양한 선행연구가 존재하며 몇가지 레퍼런스가 있어 아래와 같이 기록해둔다.  

선행연구1 (Socioeconomic risk factors for breast cancer: distinguishing individual- and community-level effects)  
Stephanie A Robert 1, Indiana Strombom, Amy Trentham-Dietz, John M Hampton, Jane A McElroy, Polly A Newcomb, Patrick L Remington
School of Social Work, Center for Demography of Health and Aging, Institute for Research on Poverty, University of Wisconsin-Madison, 53706, USA. sarobert@wisc.edu
링크 : https://pubmed.ncbi.nlm.nih.gov/15232405/

선행연구2 (Internet usage among women with breast cancer: an exploratory study)  
J L Pereira 1, S Koski, J Hanson, E D Bruera, J R Mackey
Division of Palliative Care, Department of Oncology, University of Alberta, Palliative Care Program, Grey Nuns Community Hospital & Health Centre, Edmonton, Canada. jose.pereira@ualberta.ca
링크 : https://pubmed.ncbi.nlm.nih.gov/11899653/

