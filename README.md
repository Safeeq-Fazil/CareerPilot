# CareerPilot AI – End-to-End Intelligent Career Guidance Platform
## About
CareerPilot AI is an intelligent, web-based career guidance platform designed to help students and job seekers make informed career decisions. The system leverages AI-driven recommendation logic combined with rule-based filtering to provide personalized career suggestions based on user profiles, aptitude assessments, and career interests. The platform bridges the gap between academic learning and industry requirements through data-driven insights.

## Features

- User registration and profile management
- Questionnaire-based aptitude and interest assessment
- AI-based personalized career recommendations
- Career history tracking
- Rule-based and content-based career matching
- Secure backend API services
- PostgreSQL (Supabase) database integration

  ## Requirements

- Frontend: HTML, CSS, JavaScript / React
- Backend: Python (Flask/FastAPI) or Java Spring Boot
- Database: PostgreSQL (Supabase)
- API Communication: RESTful HTTP APIs
- Tools: VS Code, GitHub, Postman

  ## System Architecture

   The system follows a client–server architecture where users interact with the frontend interface to register, submit questionnaires, view career recommendations, and track career history. All requests are handled through backend API services that process user data and communicate with the database and AI recommendation engine.
  
<img width="947" height="623" alt="Architecture diagram 1" src="https://github.com/user-attachments/assets/8a8ccaae-ce65-4803-a038-b8ba033fb8ec" />

- Users interact with the system through modules such as User Registration, Questionnaire Submission, Career Recommendation, and Career History.
- HTTP requests are sent to Backend API Services.
- User profiles and career-related data are stored and managed in a PostgreSQL database (Supabase).
- The backend processes questionnaire responses and forwards them to the AI-Based Recommendation Logic.
- The recommendation engine applies rule-based filtering and content-based matching to generate career suggestions.
- Personalized career recommendations are returned as JSON responses and displayed to the user.

## Output
### Home Page :
<img width="405" height="199" alt="image" src="https://github.com/user-attachments/assets/7b1f0347-2766-4e4c-a2da-347ba3629d66" />
CareerPilot is an AI that assists users in plotting their careers with the help of personalized AI guidance. The home page enables access to career insights and development tools easily.

### Job Apply Page :
<img width="405" height="202" alt="image" src="https://github.com/user-attachments/assets/0716bb85-1ddf-46dc-a8fe-1debcc147c32" />
Job alerts are presented on this page depending on the industry and specifications of the user. They can do the application directly on their own and the system directs them to the corresponding job portal where they can apply.

### ATS Resume Analyzer Page :
<img width="405" height="205" alt="image" src="https://github.com/user-attachments/assets/f65852c9-5e48-4376-94ad-b10defedade5" />
On this page, users can post their resume and get ATS compatibility scores with suggestions on how their resumes will be better noticed and their matches with jobs increase.

### Quantitative Aptitude Practice Test:
<img width="405" height="187" alt="image" src="https://github.com/user-attachments/assets/daeebdd6-8a82-4b24-9a48-7482052f452d" />
The questions given on this page would be in the form of multiple choice questions which are accurate timed aptitude questions as it would require the user to solve numbers of problems which is a quantitative problem solving question.

### Performance Dashboard :
<img width="405" height="207" alt="image" src="https://github.com/user-attachments/assets/577ecdc7-2263-4edb-b3c3-fc55b7600991" />
This page is an illustration of performance trends and recent attempts of the quiz that enable the users to monitor their performance over time.


## Results and Impact

CareerPilot AI improves the accuracy and relevance of career guidance by combining traditional rule-based systems with AI-driven logic. The platform enhances user engagement, supports informed decision-making, and helps users align their skills with evolving industry demands, thereby improving career preparedness and employability.

## References

1.Chanchal Gupta, Suman Gupta, and Raj Jadhav, “Developing a Scientific Career Counseling Software,” Bachelor of Engineering Project Report, Department of Information Technology, Thakur College of Engineering and Technology, Mumbai, India, 2021.

2. Kazi Fakir Mohammed, Sushopti Gawade, and Vinit Nimkar, “Online Career Counseling System Using Adaptive E-Learning,” in Proceedings of the International Conference on Computer Engineering and Applications, 2017, pp. 1–6.

3. Crystal D’Mello, Rini Aranha, Boni Gregory, and Varsha Shrivastava, “Online Career Guidance System,” Bachelor of Engineering Project Report, Department of Information Technology, University of Mumbai, India, 2016.
