KNSIT Project Symposium | Nov 2025 | Date: 13/11/2025 | 
Dept. Of AIML 1 www.knsit.com
DISEASE PREDICTION USING MACHINE LEARNING
Sumaya Fathima1
, Bharati Sindagi2
, Priyadarshini S3
, Shrushti Tambe4
, Spoorthi K5
1Asst. Professor, Dept. of AIML, KNSIT, Bengaluru 
2-4UG Students of 7th Semester, Dept. Of AIML, KNSIT, Bengaluru
Abstract—The unprecedented growth of digital health 
innovations has accelerated the demand for intelligent 
diagnostic systems. This research introduces a web-based 
disease prediction framework integrating Machine 
Learning with the Django web architecture. The system 
empowers users to identify probable diseases through 
data-driven analysis of selected symptoms. A Decision 
Tree Classifier, trained on a meticulously curated and 
labeled dataset, forms the computational backbone of the 
model. The algorithm predicts potential illnesses with high 
precision and presents results instantaneously via an 
interactive interface. This fusion of artificial intelligence 
and web technology fosters scalable, accessible, and 
automated medical assistance. The framework serves as
an efficient preliminary diagnostic tool, bridging the 
healthcare divide in underserved regions. Ultimately, it 
contributes toward intelligent, inclusive, and proactive 
healthcare systems for early disease detection.
Keywords—DjangoFramework,Machine 
Learning,Decision Tree Classifier
I. INTRODUCTION
Healthcare is a fundamental necessity for individuals and 
communities, yet its accessibility remains a persistent global 
challenge. Factors such as inadequate infrastructure, 
geographical barriers, and rising costs hinder the availability 
of quality healthcare services for many people, particularly in 
rural and under served areas. In this context, mobile health (m 
Health) technology emerges as a trans-formative solution, 
leveraging mobile devices and digital tools to deliver 
healthcare services efficiently and affordably. Disease 
Prediction is an innovative m Health application designed to 
address these challenges by providing an integrated platform 
for healthcare services. The app enables users to access virtual 
consultations, personalized wellness plans, and real-time 
health tracking, creating a comprehensive ecosystem that 
prioritizes preventive care and long-term well-being. By 
leveraging advancements in mobile technology, data analytic, 
and user-friendly interfaces, Disease Prediction bridges the 
gap between patients and healthcare providers, ensuring 
equitable access to essential healthcare 
services.
II. LITERATURE SURVEY
The rapid advancement of Artificial Intelligence (Al) and 
Machine Learning (ML) has significantly influenced healthcare 
innovation, enabling data-driven diagnosis and personalized 
treatment solutions. Several studies have explored the 
integration of ML techniques into digital health systems, laying 
the foundation for intelligent disease prediction models.
[1] Exploring Medicine Recommendation Using Machine 
Learning
Authors: Ligandro Singh Yumnam, Aditya Jain, Dr. Usha G, Dr. 
Prettyana Cyril C
Journal: International Journal for Multidisciplinary Research 
(IJMR), 2024 This study integrates ML. olgorithms with 
traditional medicine to improve personalized healthcare 
recommendations. Using Decision Tree and Neural Network 
models, the system achieved an 82% prediction accuracy. The 
proposed Disease Prediction System extends this approach by 
incorporating a wider range of medical attributes, adopting more. 
advanced Al algorithms, and providing comprehensive 
recommendations covering both physical and mental health 
domains.
[2] "Vaidyah"- A Machine Learning-Based Medication 
System
Authors: Sharad G. Nayak, Sharuth V., Praful M., S.R. Rudra 
Gouda
Journal: International Research Journal of Modernization in 
Engineering, Technology, and Science The "Vaidyah" system 
utilizes Natural Language Processing, pattern recognition, and 
predictive modeling to ensure medication adherence and patient 
safety. While it primarily focuses on prescription management, 
the proposed system offers a broader, holistic healthcare 
framework, enabling real-time disease detection and health 
assessment through a web-based interface.
[3] Determining the Nature of the Human Body Using Al
Authors: T. Thanushree, K.G. Manjunath
Journal: Journal of Pharmaceutical Negative Results, 2022
This study applies Al algorithms to analyze individual body 
compositions for generating personalized health profiles. While 
effective in quantifying human parameters, it lacks 
comprehensive disease evaluation. The proposed system 
enhances this by combining Al-driven diagnostics with medical 
symptom analysis, offering improved accuracy and adaptive 
patient-specific results
KNSIT Project Symposium | Nov 2025 | Date: 13/11/2025 | 
Dept. Of AIML 2 www.knsit.com
[4] Intelligent Medicine System for Arthritis 
Authors: Lakmi Hewapathirana, Shehan Mallawaarachchi, 
Wasundara Samaranayaka, Chathurani Jayangika, N.H.P. 
Ravi Supunya Swarnakantha, P.K. Suriyaa Kuma 
Journal: 2023 This system integrates machine learning with 
modern medicine to diagnose and treat arthritis, using X-ray 
image analysis, blood report monitoring, and personalized 
treatment plans. While it focuses on a specific condition, 
Disease Prediction offers a more versatile solution applicable 
to a wider range of health issues, ensuring a comprehensive 
healthcare approach
III. BLOCK DIAGRAM
From the API Gateway, the system branches into two main 
modules: the Symptom Analysis Module and the Treatment 
Recommendation Module. The Symptom Analysis Module is 
responsible for analyzing user symptoms, and it interacts with 
Data Storage and the Predictive Analytics Engine to compare 
user data with existing medical patterns. The User Profile and 
Data Storage component maintains records of user history and 
medical data for personalized analysis. On the other side, the 
Treatment Recommendation Module uses a Knowledge Base
a repository of medical knowledge and treatment guidelines to 
generate suitable treatment suggestions based on the analyzed 
symptoms.
Fig-1 Block diagram
A. Hardware Components
1. High-performance desktop or laptop (minimum 16GB 
RAM, SSD storage) 
2. Mac for iOS development (latest macOS version, Xcode) 
3.Windows or Linux machine for Android development 
(latest Android Studio) 
4.RAM: 256MB 
5.Processor: Pentium IV or above 
6.Speed: 2.50 GHz
B. Software Components
1.Phase 1: Website 
2.Operating System: Windows 10 / Ubuntu 20.04 / macOS
3.Programming Language: Python 3.x
4.Framework: Django (for web development)
5.Machine Learning Libraries:
6.Pandas/NumPy: Efficient data handling and transformations. 
Sci-kit-learn: Preprocessing, model training, and evaluation. 
7..Matplotlib: Visualize confusion matrices and results.
8.Database (optional): SQLite (default), MySQL/PostgreSQL (if 
scaling)
9.Web Technologies (Frontend): HTML5, CSS3, JavaScript
10..Browser: Google Chrome / Mozilla Firefox (for testing)
Virtual Environment: venv or conda for isolated package 
management IDE/Text Editor: VS Code / PyCharm / Jupyter 
Notebook (for development and testing)
IV. METHADOLOGY
A. Acquisition and Structuring of Experimental Data: The 
data-set employed in this investigation was procured from 
multiple publicly accessible open-source repositories to ensure 
comprehensive coverage and representative of the study domain. 
Following acquisition, the data-set underwent a systematic 
partitioning into two distinct subsets: a training corpus and a 
validation corpus. The training corpus facilitated the model’s 
learning process by enabling the extraction and assimilation of 
relevant predictive features. These features were utilized to 
calibrate and optimize the learning parameters of the proposed 
system. Conversely, the validation corpus was reserved 
exclusively for performance assessment, providing an unbiased 
evaluation of the model’s generalization and predictive efficacy 
on previously unseen data instances. 
B. Development and Architectural Design of the Predictive 
Framework: The construction of the proposed analytical 
framework was achieved through the integration of advanced 
Machine Learning (ML) paradigms. Machine Learning, a core 
discipline with artificial intelligence, empowers computational 
systems to autonomously infer complex patterns and 
correlations from empirical datasets without explicit 
programming. The architectural design encompassed multiple 
procedural stages: data preprocessing, feature engineering, 
algorithmic training, model optimization, and performance 
validation. Each stage was meticulously structured to ensure 
computational robustness, scalability, and reproducibility of 
experimental results.
C. Selection and Justification of Learning Algorithms: To 
ensure methodological rigor and predictive reliability, three 
well-established ML algorithms were employed: Naïve Bayes 
Classifier, Decision Tree Classifier, and Random Forest 
Ensemble Model. These algorithms were judiciously selected 
owing to their superior performance in data-driven diagnostic 
systems and their proven ability to handle multidimensional 
feature spaces. The integration of these algorithms enhances 
classification accuracy, minimizes overfitting, and strengthens 
model generalization capabilities. 
1) Probabilistic Modelling via Naïve Bayes Classifier The Naïve 
Bayes Classifier constitutes a probabilistic supervised learning 
approach grounded in Bayesian Inference Theory. It operates 
under the fundamental assumption of conditional independence 
among predictors, thereby simplifying complex probability 
KNSIT Project Symposium | Nov 2025 | Date: 13/11/2025 | 
Dept. Of AIML 3 www.knsit.com
computations in high-dimensional datasets. The mathematical 
formulation of Bayes’ Theorem is expressed as: 
 P(H|E) = [P(E|H) × P(H)] / P€
where P(H|E) denotes the posterior probability of the 
hypothesis H given evidence E; P(E|H) represents the 
likelihood; P(H) corresponds to the prior probability; and P(E) 
denotes the marginal probability of the evidence. The 
algorithm employs these probabilistic estimations to perform 
efficient classification and predictive analysis across 
categorical datasets. 
2) Hierarchical Rule-Based Modelling via Decision Tree 
Algorithm The Decision Tree Algorithm represents a 
hierarchical, rule-based learning structure utilized for both 
classification and regression tasks. The model recursively 
partitions the dataset based on selected feature thresholds, 
thereby constructing a tree-like structure that facilitates
interpretability and analytical transparency. Each internal 
node signifies a decision criterion based on an attribute, 
branches represent the conditional outcomes of such criteria, 
and terminal nodes correspond to specific class labels. Despite 
its interpretability, the Decision Tree is susceptible to 
overfitting, particularly when dealing with complex or noisy 
datasets, necessitating the application of regularization or 
ensemble techniques. 
3) Ensemble-Based Learning through Random Forest 
Classifier To mitigate the inherent limitations associated with 
individual decision trees, the Random Forest Classifier—an 
ensemble-based learning approach—was implemented. 
Random Forest constructs a multitude of independent decision 
trees during the training phase and synthesizes their outputs 
via majority voting (for classification) or averaging (for 
regression). This ensemble methodology substantially reduces 
variance, enhances model stability, and improves prediction 
accuracy. Additionally, Random Forest provides intrinsic 
metrics for feature importance evaluation, enabling 
interpretability of variable influence within the predictive 
framework. The ensemble’s collective decision mechanism 
effectively balances bias-variance trade-offs, thereby 
achieving superior generalization on unseen datasets. 
D. Experimental Workflow Representation: The overall 
experimental workflow adopted in this study follows a 
structured, multi-phase approach designed to ensure 
methodological rigor, analytical precision, and reproducibility 
of outcomes. The complete process encapsulates data 
acquisition, preprocessing, model construction, training, 
validation, and performance evaluation. The proposed 
workflow is systematically organized as follows: 1. Data 
Acquisition 2. Data Preprocessing 3. Feature Engineering and 
Selection 4. Model Construction and Training 5. Model 
Validation and Evaluation 6. Result Interpretation and 
Visualization
V. IMPLEMENTATION
Setting up the environment is the first and most critical step in 
project implementation. It ensures that the required tools, 
frameworks, and dependencies are properly configured for 
development,testing, and deployment.IDE (Integrated 
Development Environment): Visual Studio Code / Py Charm for 
writing and debugging the code. 
1. Django (Python) for back-end development. 
2. Bootstrap for front-end styling Package Managers: 
3. pip: Python package manager for Django libraries. 
API Testing Tools: Postman for testing API endpoints. 
4. Database Management: PostgreSQL for managing structured 
data. SQLite was used during local development. 
5. Deployment Tools: Heroku / AWS for deploying the web 
application
Installing dependencies the environment was set up with the 
following steps: 
1. Python and Django Setup: o Install Python 3.x. o Install 
Django and other required 
libraries: pip install django djangorestframework psycopg2-
binary django-cors-headers. 
2. Front-End Setup: 
• Install Node.js for managing front-end dependencies: 
• npm install axios bootstrap react-router-dom 
3. Database Setup: 
• Install PostgreSQL and create a database named Disease 
Prediction. 
The back-end implementation is the core of the Disease 
Prediction Application, responsible for processing user requests, 
handling business logic, storing and retrieving data, and 
integrating Third party services. Built using Django, a robust and 
scalable Python web framework, the backend ensures seamless 
communication between the user interface and the underlying
system, making the application responsive, scalable, and feature￾rich
The front-end serves as the point of interaction between users 
and the system. It is responsible for: 
• Capturing user input for features like health data logging, 
appointment scheduling, and 
chatbot queries. 
• Displaying dynamically updated data from the back-end, such 
as personalized 
wellness plans and consultation schedules. 
• Ensuring compatibility and responsiveness across a variety of 
devices, from 
desktops to smartphones. 
• Enhancing user engagement through visually appealing layouts, 
animations, and transitions.
The system can be a cost-effective solution for flood 
management in the long run by preventing damage and reducing 
the need for expensive recovery measures.
KNSIT Project Symposium | Nov 2025 | Date: 13/11/2025 | 
Dept. Of AIML 4 www.knsit.com
Fig-2 Implementation
Ⅵ. RESULT AND FUTURE SCOPE
A.RESULT
Disease Prediction is a cutting-edge healthcare platform that 
has demonstrated its potential to revolutionize digital 
healthcare services by integrating modern-technologies such 
as Django, PostgreSQL, machine learning (via sci-kit-learn), 
and AI-powered tools. The experimental results show that the 
platform is robust, secure, and user-friendly, offering critical 
functionalities such as role-based login systems for patients, 
doctors, and administrators; disease prediction powered by 
trained datasets; an intelligent chat-bot for real-time 
interaction; a seamless appointment booking system; and a 
comprehensive doctor-patient portal. These features address 
some of the most significant challenges in traditional 
healthcare, including accessibility, efficiency, and patient 
doctor communication.
Fig-3 Results(login page)
Fig-4 Results(Symptoms Dataset)
B.FUTURE SCOPE
Disease Prediction has the potential to grow into an even more 
advanced and comprehensive healthcare platform by 
incorporating the following future enhancements:
Multilingual and Accessibility Support: 
Introduce support for multiple languages in the chat bot and 
platform interface to cater to users from diverse linguistic 
backgrounds. Enhance accessibility with features such as voice 
commands, screen readers, and adaptive interfaces for users with 
disabilities.
Telemedicine and Remote Monitoring: 
• Integrate telemedicine features, allowing patients to consult 
doctors virtually through video calls and chat. 
Cloud-Based Scalability: 
• Migrate the platform to cloud infrastructure to ensure 
scalability, reliability, and availability 
for a growing user base. 
Advanced Security Features: 
• Incorporate state-of-the-art encryption methods, such as 
homomorphic encryption, to secure sensitive medical data. 
Ⅶ. CONCLUSION
The disease prediction module achieved high accuracy,
precision, and recall, demonstrating its ability to provide 
valuable support for early diagnosis and treatment 
planning.The chat-bot proved effective in answering 
queries and redirecting complex cases to human experts, 
improving patient engagement and reducing the
workload on healthcare staff. Additionally, the 
appointment booking system and portal showed 
excellent usability and responsiveness, enabling 
smoother management of healthcare 
processes. However, the platform also revealed areas for 
improvement, such as optimizing prediction accuracy for 
rare diseases, enhancing system performance under peak
load conditions, and refining the admin dashboard for
KNSIT Project Symposium | Nov 2025 | Date: 13/11/2025 | 
Dept. Of AIML 5 www.knsit.com
ease of use. it can adapt to the evolving needs of the 
healthcare sector, making it a promising tool for 
modern medical services.
 ACKNOWLEDGMENT
We are grateful to the Founder & Late Chairman of our 
college, Mr. C. K. Jaffer Sharief, for having provided us with 
excellent facilities in the college during the course to emerge 
as responsible citizen with Professional Engineering Skills 
and moral ethics.
We are indebted to the Chairman of our college, Mr.Abdul 
Rahman Sharief, for his constant support, motivation and 
encouragement to excel in academics and carryout project
Works.
We thank our Principal, Dr. S. M. Prakash, for facilitating a 
congenial academic environment in the college.
We are thankful to our HOD. Dr. Aijaz Ali Khan, for his kind 
support, guidance and motivation during the B.E Degree 
Course and especially during the Course of any project work.
We thank our Guide, Mrs.Sumaya Fathima for her valuable 
guidance, suggestions and Encouragement throughout my 
project work.
We are also thankful to all the staff members of the 
Department of Artificial Intelligence and Machine Learning 
Engineering and all those who have directly or indirectly 
helped with their valuable suggestions in the successful 
completion of this project report.
Ⅷ. REFERENCES
[1] A. K. Sahoo, P. Jena, and S. Mohapatra, "AI-Powered 
Healthcare Chatbots2022. 
[2] D. Johnson, M. Patel, and R. Gupta, "Role-Based Access 
Control for Securing Web-Based 
Healthcare Systems," Journal of Cybersecurity and Healthcare 
IT, vol. 15, no. 2, pp. 67-74, 2021. 
[3] P. Fernandez, L. Zhao, and K. Smith, "Patient-Centric 
Design in Healthcare Portals," ACM 
Transactions on Human-Computer Interaction in Healthcare, 
vol. 10, no. 5, pp. 159-176, 2022.
[4] J. Wang, H. Lee, and Y. Kim, "Security Challenges in 
Web-Based Healthcare Systems," 
Journal of Information Security in Medicine, vol. 14, no. 3, pp. 
47-56, 2021. 
[5]T. Green and C. Lopez, "Natural Language Processing in 
Healthcare Chatbots
