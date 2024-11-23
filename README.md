# ANSWER_EVALUATION
A DESCRIPTIVE ANSWER EVALUATION SYSTEM USING COSINE SIMILARITY TECHNIQUE
ABSTRACT
Subjective paper evaluation is a tricky and tiresome task to do by manual labor. Insufficient understanding and acceptance of data are crucial challenges while analyzing subjective papers using Artificial Intelligence (AI). Several attempts have been made to score students’ answers using computer science. However, most of the work uses traditional counts or specific words to achieve this task. Furthermore, there is a lack of curated data sets as well. This paper proposes a novel approach that utilizes various machine learning, natural language processing techniques, and tools such as Wordnet, Word2vec, word mover’s distance (WMD), cosine similarity, multinomial naive bayes (MNB), and term frequency-inverse document frequency (TF-IDF) to evaluate descriptive answers automatically. Solution statements and keywords are used to evaluate answers, and a machine learning model is trained to predict the grades of answers. Results show that WMD performs better than cosine similarity overall. With enough training, the machine learning model could be used as a standalone as well. Experimentation produces an accuracy of 88% without the MNB model. The error rate is further reduced by 1.3% using MNB

INTRODUCTION
Subjective questions and answers can assess the performance and ability of a student in an open-ended manner. The answers, naturally, are not bound to any constraint, and students are free to write them according to their mindset and understanding of the concept. With that said, several other vital differences separate subjective answers from their objective counterpart. For one, they are much longer than the objective questions. Secondly, they take more time to write. Moreover, they carry much more context and take a lot of concentration and objectivity from the teacher evaluating them. 
Evaluation of such questions using computers is a tricky task, mainly because natural language is ambiguous. Several preprocessing steps must be performed, such as cleaning the data and tokenization before working on it. Then the textual data can be compared using various techniques such as document similarity, latent semantic structures, concept graphs, ontologies. The final score can be evaluated based on Similarity, keywords presence, structure, language. Several attempts have been made in the past to solve this problem, but there is still room for improvements, some of which is discussed in this paper. Subjective exams are considered more complex and scary by both students and teachers due to their one fundamental feature, context. A subjective answer demands the checker check every word of the answer for scoring actively, and the checker’s mental health, fatigue, and objectivity play a massive role in the overall result. 
Therefore, it is much more time and resource-efficient to let a system handle this tedious and somewhat critical task of evaluating subjective answers. Evaluating objective answers with machines is very easy and feasible. A program can be fed with questions and one-word answers that can quickly map students’ responses. Nevertheless, subjective answers are much more challenging to tackle. They are varied in length and contain a vast amount of vocabulary. Furthermore, people tend to use synonyms and convenient abbreviations, which makes the process that much tricky

SYSTEM ANALYSIS
EXISTING SYSTEM
It appears there might be some confusion. The information you provided in your previous message seems to be more focused on the proposed system and its objectives rather than describing the existing system. The existing system typically refers to the state of affairs or methodologies in place before the implementation of the proposed system. If you have information about the existing system, you could provide details on how the assessment of descriptive answers is currently handled, whether it's manual evaluation by teachers or any existing tools or methods in use. 
LIMITATIONS
Subjectivity and Bias:
Issue: Manual evaluation can be subjective, leading to variations in grading among different evaluators.
Impact: Inconsistencies in grading may result in unfair assessments and disparities in students' grades.
Time-Consuming:
Issue: Manual grading of descriptive answers is a time-consuming process, especially in scenarios with a large number of students or complex questions.
Impact: Teachers may face challenges in providing timely feedback to students, and the overall assessment process may be delayed.
Scalability Challenges:
Issue: As the number of students and assessments increases, scalability becomes a significant challenge for manual evaluation.
Impact: Educational institutions may struggle to efficiently manage and scale the assessment process, particularly during peak times.
Limited Feedback:
Issue: Due to time constraints, detailed and constructive feedback on each student's response may be limited in a manual evaluation system.
Impact: Students may miss out on valuable insights into their strengths and weaknesses, hindering the learning process.
Resource Intensive:
Issue: Manual evaluation requires a significant allocation of human resources, involving multiple teachers and graders.
Impact: This resource-intensive process may strain the available workforce and could potentially lead to increased costs for educational institutions.


LIMITATIONS OF EXISTING SYSTEM

PROPOSED SYSTEM
The proposed system, "A Descriptive Answer Evaluation System Using Cosine Similarity Technique," offers a transformative approach to address the limitations of traditional manual evaluation methods for descriptive answers. The primary objective is to leverage computer-assisted assessment tools, particularly in the context of the evolving challenges posed by the COVID-19 pandemic. The system aims to alleviate the subjectivity and bias inherent in manual grading by introducing an automated evaluation process based on the cosine similarity technique. This method allows for a more objective assessment of descriptive answers, irrespective of their length, enabling a fairer and more consistent grading system.
One of the key features of the proposed system is its ability to significantly reduce the time required for assessment. By automating the evaluation process, teachers can allocate more time to providing detailed and timely feedback to students. The scalability of the system addresses the challenges associated with handling a large number of assessments efficiently. This shift towards a computer-assisted solution not only streamlines the evaluation process but also minimizes the resource-intensive nature of manual grading, potentially leading to cost savings for educational institutions.
Moreover, the proposed system enhances the feedback loop for students by providing pictorial representations of the results using the cosine similarity technique. This visual representation not only facilitates a quick understanding of the assessment outcome but also serves as a valuable learning aid. The web-based application aspect further modernizes the assessment approach, making it more adaptable to the digital learning environment. In essence, the proposed system strives to revolutionize the assessment of descriptive answers, making it more objective, efficient, and accessible in the contemporary educational landscape.
ADVANTAGES 
Objective Assessment:
The system employs the cosine similarity technique, a quantitative measure that provides an objective evaluation of descriptive answers. This helps eliminate subjective biases often associated with manual grading, ensuring fairness and consistency in assessments.
Time Efficiency:
Automated evaluation significantly reduces the time required for grading descriptive answers. This efficiency benefits both teachers and students by expediting the feedback process, allowing for quicker identification of areas of improvement and enhancing the overall learning experience.
Scalability:
The proposed system is designed to handle a large volume of assessments efficiently. As the number of students and evaluations increases, the automated approach ensures scalability, addressing the challenges posed by manual grading in terms of time and resource constraints.
Enhanced Feedback:
The system provides visual representations of assessment results using the cosine similarity technique. These pictorial representations offer a clear and concise overview of performance, aiding students in understanding their strengths and weaknesses. This enhanced feedback supports a more targeted approach to learning and improvement.
Resource Optimization:
By automating the evaluation process, the proposed system optimizes the use of resources. It reduces the need for a large workforce dedicated to manual grading, potentially leading to cost savings for educational institutions. This resource optimization allows institutions to allocate resources more strategically to other educational initiatives.


ADVANTAGES OF PROPOSED SYSTEM

SYSTEM ARCHITECTURE                                                     

 ![image](https://github.com/user-attachments/assets/34aeef19-ef5d-4f81-97ff-97f2e5253382)

 ![image](https://github.com/user-attachments/assets/65809d4e-2f6c-47d2-9ab9-8a216646a465)






 

MODULES
User Authentication and Management:
This module is responsible for managing user authentication, including roles such as administrators, teachers, and students. It ensures secure access to the system, allowing authorized users to perform their respective tasks.
Answer Submission Interface:
The answer submission module provides a user-friendly interface for students to submit their descriptive answers. It allows for the efficient uploading and storage of responses in the system, ensuring that the evaluation process can commence seamlessly.
Automated Evaluation Engine:
At the core of the system is the automated evaluation engine. This module utilizes the cosine similarity technique to objectively assess and score descriptive answers. It compares student responses with predefined model answers, generating quantitative results for further analysis.
Result Presentation and Visualization:
Once the evaluations are complete, this module is responsible for presenting the results to both teachers and students. It may include visual representations of assessment outcomes using the cosine similarity technique, providing an easy-to-understand overview of performance.
Feedback and Reporting:
The feedback and reporting module facilitates communication between teachers and students. It allows teachers to provide detailed feedback on individual responses, highlighting areas of strength and improvement. Additionally, it generates comprehensive reports for administrators to gain insights into overall system performance and usage.



HARDWARE REQUIREMENTS 

MINIMUM (Required for Execution)	      MY SYSTEM (Development)
System	Pentium IV 2.2 GHz	             i3 Processor 5th Gen
Hard Disk	20 Gb	                       500 Gb
Ram	1 Gb	                              4 Gb


SOFTWARE REQUIREMENTS

Operating System	          Windows 10/11
Development Software	      Python 3.10
Programming Language	      Python
Domain	                    Image Processing & Cloud Computing
Integrated Development 
Environment (IDE)	         Visual Studio Code
Front End Technologies    	HTML5, CSS3, Java Script
Back End Technologies 
or Framework	              Django
Database Language	         SQL
Database (RDBMS)          	MySQL
Database Software	         WAMP or XAMPP Server
Web Server or Deployment 
Server	                   Django Application Development Server
Design/Modelling	         Rational Rose


REFERENCES
[1] J. Wang and Y. Dong, ‘‘Measurement of text similarity: A survey,’’ Information, vol. 11, no. 9, p. 421, Aug. 2020. 
[2] M. Han, X. Zhang, X. Yuan, J. Jiang, W. Yun, and C. Gao, ‘‘A survey on the techniques, applications, and performance of short text semantic similarity,’’ Concurrency Comput., Pract. Exper., vol. 33, no. 5, Mar. 2021.



