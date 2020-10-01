# Socieconomic analysis of ENEM participants
Analysis of the socioeconomic factors that impact the student’s grades on the Brazilian National High School Exam (**ENEM**) using <ins>machine learning</ins>.

# Background
> Meritocracy means that every individual is able to prosper only with his or her abilities without needing the help of society, the state or the family.<br><br>
> But the question is: Does meritocracy really exists?<br>

According to the demographic census of IBGE from 2010 (Instituto Brasileiro de Geografia e Estatística), the number of adults who have access to universities has increased considerably and has spread to other regions of Brazil, as shown in the graphs below.
<br>

![](https://i.imgur.com/SACDTmV.png)

Based on this observation, it is expected that this distribution will occur equally between the different socioeconomic classes that will have access to federal universities.
# Objectives
In this project, we chose to take into consideration the ENEM grades obtained by the [TRI](https://vestibular.brasilescola.uol.com.br/enem/teoria-resposta-ao-item-tri-no-enem.htm) calculation. We intend to analyze the exam success rates based on the family's socioeconomic level, taking as a reference the answers given by the participants on the 
socioeconomic status questionnaire of 2019's ENEM.

## Goals
- Development of a predictive model using ___semi supervised learning___;
- Consider socioeconomic characteristics to predict the main factors that impact the student’s grade score;
- Predicting a student profile can give good directions where there should be an investment by the government in schools and quality education which is in line with the **4th** of the 17 Sustainable Development Goals proposed by the UN.Learning benefits every human being and should be available to all.; 
- Promoting social inclusion to provide better conditions for people to attend higher education, achieve and sustain the income growth of the poorest population, guarantee equal opportunities and reduce inequalities in results, endorsing the **8th** and **10th** Sustainable Development Goal.

![](https://i.imgur.com/Fkzz8AK.png)

# Dataset
The dataset we are going to use is available on [INEP website](http://inep.gov.br/microdados): all editions have a .csv file with available data of each edition of the exam, but only 2019's edition will be considered for this analysis;<br> 
The subject Dataframe will contain personal data of enrolled students which took the exam, in addition to the characteristics of their educational institutions and its location;
The analysis will be based on the socioeconomic survey, with 25 questions, conducted during the registration process; 
Measures socioeconomic status are contextual indicators of for the investigation of inequalities in access, trajectory and student learning.


Analysis by [_Allan Gonçalves_](#), [_Davi Souza_](#), [_Emanuel Betcel_](#), [_Everton Vinícius_](#) and [_Oziel Alves_](https://github.com/ozielalves) (*ozielalves@ufrn.edu.br*), 2020.6
