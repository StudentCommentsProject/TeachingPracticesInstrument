Instrument for Teaching Practices Analysis
================
## Documentation and details

We provide here two versions of the Instrument for the analysis of effective and malfunctional teaching practices in student comments of teaching evaluation surveys, in JSON format. 

The short version includes the 21 practices resulting from the construct validation process through Exploratory-Multidimensional Item Response Theory. In this case, within the "dimension" key, which also divides the practices into effective and malfunctional, there is a "trait" key that organizes the practices according to the latent dimension in which they presented loadings in the respective MIRT model.

The extended version includes the 44 practices resulting from the content validation by the expert panel. The "dimension" key separates effective practices from malfunctional ones. Although we recommend the use of the short version, testing the extended version in other datasets may be of value to continue the validation process of the instrument and the teaching dimensions it measures.


| Instrument | Content validation by expert panel | Construct validation through E-MIRT |  
|:---|:---|:---|
|[Short version](https://github.com/StudentCommentsProject/TeachingPracticesInstrument/blob/259242c073798f454840eaf98b53437847a14830/Instruments/Short_instrument_for_teaching_practices.json)| YES | YES | 
|[Extended version](https://github.com/StudentCommentsProject/TeachingPracticesInstrument/blob/259242c073798f454840eaf98b53437847a14830/Instruments/Extended_instrument_for_teaching_practices.json)| YES | NO | 



## Data
The data used correspond to the Estudent Feedback Analysis Dataset (Herath et al. 2022), available on HuggingFace: [NLPC-UOM/Student_feedback_analysis_dataset](https://huggingface.co/datasets/NLPC-UOM/Student_feedback_analysis_dataset)

> Herath, M., Chamindu, K., Maduwantha, H., & Ranathunga, S. (2022, June). Dataset and Baseline for Automatic Student Feedback Analysis. In Proceedings of the Thirteenth Language Resources and Evaluation Conference (pp. 2042-2049)

Our labeling of teaching practices is available in JSON format:

[Labeled dataset](https://github.com/StudentCommentsProject/TeachingPracticesInstrument/blob/33c03b02be7cd57b77bc489943a4ee5bbc667f1c/Data/Student_Feedback_Analysis_Dataset%20-%20labeled%20teaching%20practices.json)



## Further details

### Description of extracted teaching practices from prior research

| Type | Teaching Practice | Description | Source | Original |
|:---|:---|:---|:---|:---|
| Effective teaching practices | Active learning. | Students are actively engaged in their learning, either stimulated by the instructor or the curriculum, or due to their personal approach to their studies. | Smith & Baik |  |
|  | Application of Knowledge. | Encouraging students to apply what they have learned in increasingly authentic, real-world contexts and/or in real-world-like problems. | Smith & Baik | Wilson, K., Lizzio, A., & Ramsden, P. (1997). The Development, Validation and Application of the Course Experience Questionnaire. Studies in Higher Education, 22(1), 33–53. |
|  | Clarity in Course Objectives. | Defining clear objectives and expectations to guide students. | Schneider & Preckel: |  |
|  | Contextualized Exemplification. | Providing students with examples of the application or materialization of concepts through detailed, specific, and anecdotal real-life stories. |  |  |
|  | Project-Based Learning. | Engaging students in complex and authentic tasks that foster the development of practical skills under faculty supervision. | Schneider & Preckel: |  |
|  | Providing Intellectual Challenges. | Challenging students to analyze, elaborate on new learning, and understand its theoretical and practical implications. | Schneider & Preckel: |  |
|  | Relating Content to Students’ Lives and Interests. | Highlighting how new content connects with students’ personal contexts to facilitate integration with prior knowledge. | Schneider & Preckel: |  |
|  | Constructive alignment. | Designing curriculum activities that support the achievement of objectives and reflect assessments. | Smith & Baik | Biggs, J. 1996. “Enhancing Teaching Through Constructive Alignment.” Higher Education 32 (3): 347–64. |
|  | Problem-Based Learning. | Providing students with problems to solve, actively applying previously addressed knowledge. | Smith & Baik | Dagyar, M., & Demirel, M. (2015). Effects of problem-based learning on academic achievement: A meta-analysis study. Egitim ve Bilim, 40(181), 139–174. <doi:10.15390/EB.2015.4429> |
|  | Course Structure. | Providing students with clarity in both the representation of conceptual content, the relationships between ideas, and the progressive development of learning toward a well-defined purpose and goal. | Smith & Baik | Marsh, H. W. 1982. “SEEQ: A Reliable, Valid, and Useful Instrument for Collecting Students’ Evaluations of University Teaching.” British Journal of Educational Psychology 52 (1): 77–95. <doi:10.1111/j.2044-8279.1982.tb02505.x> |
|  | Stimulating Student Interest. | Engaging students by stimulating their interest in course material to foster better learning outcomes. | Smith & Baik | Marsh, H. W. 1982. “SEEQ: A Reliable, Valid, and Useful Instrument for Collecting Students’ Evaluations of University Teaching.” British Journal of Educational Psychology 52 (1): 77–95. <doi:10.1111/j.2044-8279.1982.tb02505.x> |
|  | Previous knowledge activation. | Providing opportunities to recall previously learned ideas from memory; the active process guided by reconstruction cues. | Smith & Baik | Trigwell, K., Ashwin, P., & Millan, E. S. (2013). Evoked prior learning experience and approach to learning as predictors of academic achievement. British Journal of Educational Psychology, 83(3), 363–378. <doi:10.1111/j.2044-8279.2012.02066.x> |
|  | Collaborative Learning. | Students learning in teams (also known as team-based learning). | Smith & Baik | Travis, L. L., Hudson, N. W., Henricks-Lepp, G. M., Street, W. S., & Weidenbenner, J. (2016). Team-Based Learning Improves Course Outcomes in Introductory Psychology. Teaching of Psychology, 43(2), 99–107. <doi:10.1177/0098628316636274> |
|  | Peer learning. | Engage students in peer evaluation or peer teaching. | Smith & Baik | Hecimovich, M., & Volet, S. (2014). Simulated learning in musculoskeletal assessment and rehabilitation education: comparing the effect of a simulation-based learning activity with a peer-based learning activity. BMC Medical Education, 14, 253. <doi:http://dx.doi.org/10.1186/s12909-014-0253-6> |
|  | Encouraging Questions and Discussions. | Encouraging students to ask questions and participate in discussions inside or outside the classroom. | Schneider & Preckel: |  |
|  | Close Teacher-Student Relationship. | Teacher availability and willingness to help students or answer questions. | Smith & Baik | |
|  | Clarity and Comprehensibility. | Ensuring that course content is delivered clearly and comprehensibly to enhance student learning. | Schneider & Preckel: |  |
|  | Modelling. | Allowing students to witness problem-solving or reasoning so that thought processes, planning, or approaches become explicit. | Smith & Baik | Hilbert, T. S., Renkl, A., Kessler, S., & Reiss, K. (2008). Learning to prove in geometry: Learning from heuristic examples and how it can be supported. Learning and Instruction, 18(1), 54–65. <doi:10.1016/j.learninstruc.2006.10.008> |
|  | Teacher Enthusiasm for the Course. | Demonstrating enthusiasm for the course or content to inspire students and create a positive learning environment. | Schneider & Preckel: |  |
|  | Awareness of Learning/Progress. | Enabling students to recognize how they have developed/learned. | Smith & Baik | Masui, C., & Corte, E. (2005). Learning to reflect and to attribute constructively as basic components of self-regulated learning. British Journal of Educational Psychology, 75(3), 351–372. <doi:10.1348/000709905X25030> |
|  | Frequent Feedback from Teachers. | Providing timely and high-quality feedback to help students understand their progress and areas for improvement. | Smith & Baik |  |
|  | Quality and Fairness in Exams. | Ensuring that exams are fair, well-structured, and aligned with learning objectives to accurately assess achievement. | Schneider & Preckel: |  |
|  | Student Self-Assessment. | Encouraging students to evaluate their own work, promoting reflection and self-awareness in learning. | Smith & Baik | Masui, C., & Corte, E. (2005). Learning to reflect and to attribute constructively as basic components of self-regulated learning. British Journal of Educational Psychology, 75(3), 351–372. <doi:10.1348/000709905X25030> |
|  | Teacher Sensitivity to Class Level and Progress. | Adapting teaching and assessment practices to align with students’ current levels and progress. | Schneider & Preckel: |  |
| Malfunctional teaching practices | Monotony in instructional activities. | Faculty use the same teaching-learning activities repeatedly or for a long-time within the lesson. | Astleitner (2020) | Daschmann, E. C., Goetz, T., & Stupnisky, R. H. (2011). Testing the predictors of boredom at school: Development and validation of the precursors to boredom scales. British Journal of Educational Psychology, 81, 421–440. doi: <https://doi.org/10.1348/000709910X526038> |
|  | No perceptual arousal. | There are no (unexpected) changes in the learning environment concerning visual or auditory parameters. | Astleitner (2020) | Schmidt, C. P., Andrews, M. L., & McCutcheon, J. W. (1998). An acoustical and perceptual analysis of the vocal behavior of classroom teachers. Journal of Voice, 12, 434–443. doi: <https://doi.org/10.1016/S0892-1997(98)80052-0> |
|  | No inquiry arousal. | There are no open questions, unsolved problems, or mysteries which need knowledge-seeking behavior. | Astleitner (2020) | Yoon, H. G., Joung, Y. J., & Kim, M. (2012). The challenges of science inquiry teaching for pre-service teachers in elementary classrooms: Difficulties on and under the scene. Research in Science Education, 42, 589–608. doi: <https://doi.org/10.1007/> s11165-011-9212-y |
|  | Unbalanced goals. | The learning objectives omit relevant areas or, conversely, cover too many aspects to be manageable. | Astleitner (2020) | Maynard, B. R., Solis, M. R., Miller, V. L., & Brendel, K. E. (2017). Mindfulness‐based interventions for improving cognition, academic achievement, behavior, and socioemotional functioning of primary and secondary school students. Campbell Systematic Reviews, 13, 1–144. doi: <https://doi.org/10.4073/CSR.2017.5> |
|  | Unclear goals. | Goal statements are missing, non-transparent, unspecified, incomplete, or incomprehensible. | Astleitner (2020) | Seidel, T., Rimmele, R., & Prenzel, M. (2005). Clarity and coherence of lesson goals as a scaffold for student learning. Learning and Instruction, 15, 539–556. doi: <https://doi.org/10.1016/j.learninstruc.2005.08.004> |
|  | No guiding overviews about new contents. | Maps, organizers for gaining an impression or a first model on what must be learned are missing. | Astleitner (2020) | Dhindsa, H. S., & Anderson, O. R. (2011). Constructivist-visual mind map teaching approach and the quality of students’ cognitive structures. Journal of Science Education and Technology, 20, 186–200. <https://doi.org/10.1007/s10956-010-9245-4> |
|  | No preparing tasks. | There are no tasks for students which activate prior knowledge and link it with new contents. | Astleitner (2020) | Spires, H. A., & Donley, J. (1998). Prior knowledge activation: Inducing engagement with informational texts. Journal of Educational Psychology, 90, 249–260. doi: <https://doi.org/10.1037/0022-0663.90.2.249> |
|  | No focus on past learning. | Summaries of prerequisite contents or evaluations of past work are missing. | Astleitner (2020) | Fernández-Alonso, R., Suárez-Álvarez, J., & Muñiz, J. (2015). Adolescents’ homework performance in mathematics and science: Personal factors and teaching practices. Journal of Educational Psychology, 107, 1075–1085. <https://doi.org/10.1037/edu0000032> |
|  | Disorganization. | There is no clear structure on contents, activities, or in time. | Astleitner (2020) | Hebert, M., Bohaty, J. J., Nelson, J. R., & Brown, J. (2016). The effects of text structure instruction on expository reading comprehension: A meta-analysis. Journal of Educational Psychology, 108, 609–629. doi: <https://doi.org/10.1037/edu0000082> |
|  | No support for integration of new knowledge. | There are no elaborative questions, illustrations, or worked examples. | Astleitner (2020) | Renkl, A. (2011). Instruction based on examples. In R. E. Mayer & P. A. Alexander (Eds.), Handbook of research on learning and instruction (pp. 272–295). New York: Routledge. |
|  | No modeling. | There are no activities which demonstrate how to perform desired activities or which articulate the reasoning necessary for the activities. | Astleitner (2020) | Ness, M. (2016). Learning from K-5 teachers who think aloud. Journal of Research in Childhood Education, 30, 282–292. doi: <https://doi.org/10.1080/02568543.2016.1178671> |
|  | No coaching. | There are no activities which monitor, analyze, and regulate the learners’ knowledge and skill developments. | Astleitner (2020) | Van den Bosch, R. M., Espin, C. A., Chung, S., & Saab, N. (2017). Data‐based decision‐making: Teachers’ comprehension of curriculum‐based measurement progress‐monitoring graphs. Learning Disabilities Research & Practice, 32, 46–60. doi: <https://doi.org/10.1111/ldrp.12122> |
|  | Inadequate or insufficient scaffolding. | The presentation of the content or assessment activities (e.g., assignments) does not match the students’ level of knowledge and skills. | Astleitner (2020) | Allington, R. L., McCuiston, K., & Billen, M. (2015). What research says about text complexity and learning to read. The Reading Teacher, 68, 491–501. doi: <https://doi.org/10.1002/trtr.1280> |
|  | No validation of assessment and grades. | There are no attempts to learn about and improve the criteria-based quality of assessments and resulting grading. | Astleitner (2020) | McMillan, J. H., Myran, S., & Workman, D. (2002). Elementary teachers’ classroom assessment and grading practices. The Journal of Educational Research, 95, 203–213. doi: <https://doi.org/10.1080/00220670209596593> |
|  | No constructive feedback. | There is no feedback on the learning process which is explicit, goal-evaluative, specific, positive, and directive-preventive. | Astleitner (2020) | Van den Bergh, L., Ros, A., & Beijaard, D. (2013). Teacher feedback during active learning: Current practices in primary schools. British Journal of Educational Psychology, 83, 341–362. doi: <https://doi.org/10.1111/j.2044-8279.2012.02073.x> |
|  | Bad timing in feedback. | Feedback on learning is too delayed or too early, or irregular in time. | Astleitner (2020) | Shute, V. J. (2008). Focus on formative feedback. Review of Educational Research, 78, 153–189. doi: <https://doi.org/10.3102/0034654307313795> |
|  | No suggestions to think about connections or analogies. | There are no activities in which students have to group problems or invent similar problems. | Astleitner (2020) | Fuchs, L. S., Fuchs, D., Prentice, K., Burch, M., Hamlett, C. L., Owen, R., Hosp, M., & Jancek, D. (2003). Explicitly teaching for transfer: Effects on third-grade students’ mathematical problem solving. Journal of Educational Psychology, 95, 293–305. doi: <https://doi.org/10.1037/0022-0663.95.2.293> |
|  | No application of knowledge and skills in different contexts. | Knowledge and skills are not applied in varying scenarios or with different experiences. | Astleitner (2020) | Paas, F. G., & Van Merriënboer, J. J. (1994). Variability of worked examples and transfer of geometrical problem-solving skills: A cognitive-load approach. Journal of Educational Psychology, 86, 122–133. doi: <https://doi.org/10.1037/0022-0663.86.1.122> |
|  | Disrespectful treatment. | This includes any expression by the instructor that, even if unintentional, has the effect of belittling, humiliating, or ridiculing students. This includes behaviors such as destructive feedback and speaking to students in a condescending manner. |  | Kari Stamland Gusfre, Janne Støen, and Hildegunn Fandrem. 2023. Bullying by teachers towards students—A scoping review. International journal of bullying prevention 5, 4 (2023), 331–347.; <br><br>Eun-Jun Park and Hyunwook Kang. 2021. Experiences of undergraduate nursing students with faculty incivility in nursing classrooms: A meta-aggregation of qualitative studies. Nurse Education in Practice 52 (2021), 103002. <https://doi.org/10.1016/j.nepr.2021.103002> |
|  | Discriminatory treatment. | Faculty treats students unfairly based on characteristics such as gender, ethnic background, religion, or social class. |  | Muhammad Rashid Ali, Badar Nadeem Ashraf, and Chuanmin Shuai. 2019. Teachers’ Conflict-Inducing Attitudes and Their Repercussions on Students’ Psychological Health and Learning Outcomes. International Journal of Environmental Research and Public Health 16, 14 (2019). <https://doi.org/10.3390/ijerph16142534> |


### Descriptions of added practices, suggested by expert panel

| Practice | Category | Description | Reference|
|:---|:---|:---|:---|
| Authentic assessment| Effective | Evaluation using situations, tasks, or standards similar to those that professionals usually face. | |
| Peer assessment| Effective | Students evaluate the quality of their peers’ work and provide feedback to one another| | |
| Interactive materials| Effective | Provide students with materials they can interact with beyond the classroom (quizzes, exercises, or others)| | |
| Clarity and comprehensibility explanations| Effective | Ensure that the course content is delivered clearly and understandably to improve student learning| | |
| Clarity of course materials| Effective | Class visual resources (such as presentations or others) are understandable and facilitate content comprehension| | |
| Lack of intellectual challenges| The course content, activities, or assignments do not present an interesting challenge for the students, their level of knowledge, and their skills.| | |

### Frequencies in our dataset


### Correlations among latent traits of E-MIRT models


#### Final model for Effective Teaching Practices

| | Teaching and assesement consistency| Fostering an emotional connection with content| Student-faculty relationship|  Clear content transmition|
|:---|:---|:---|:---|:---|
| Teaching and assesement consistency| 1.00 |  | | |
| Fostering an emotional connection with content| 0.001 | 1.00 | | |
| Student-faculty relationship| -0.176| 0.218 |1.00 | |
| Clear content transmition| 0.288| 0.031 | 0.035| 1.00|

#### Final model for Malfunctional Teaching Practices

| |Breakdown of constructive alignment | Lack of pedagogical support | Problems in curriculum design|
|:---|:---|:---|:---|
| Breakdown of constructive alignment| 1.00 |  | |
| Lack of pedagogical support,|  0.028| 1.00 | |
| Problems in curriculum design| 0.097| 0.195|1.00 |





