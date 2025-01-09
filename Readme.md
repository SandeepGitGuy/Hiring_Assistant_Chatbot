# 🤖 AI Technical Interviewer  
An Intelligent Chatbot for Seamless Technical Screening  

[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)  
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  

---

## ✨ About the Project/ Project Overview
The AI Technical Interviewer is a next-generation solution for conducting initial technical interviews. Designed with Python and powered by OpenAI's GPT-4o/GPT-4o-mini, it offers an interactive and adaptive interview experience tailored to a candidate's technical expertise.

---

## 🔍 Key Features  
- 🧠 **Dynamic Questioning**: Automatically generates skill-specific technical questions based on the declared technology stack.  
- 🎯 **Experience-Based Adjustment**: Adapts question difficulty based on the candidate's experience level.  
- 🔒 **Content Moderation**: Ensures safe and professional interactions using advanced filtering.  
- 🌐 **Professional UI**: Powered by **Gradio** with a sleek and responsive design.
- 🛡️ **Secure Data Handling**: Complies with GDPR and encrypts sensitive information.  
- ⏱️ **Real-Time Feedback**: Provides instant feedback on candidate responses to enhance the interview experience.  
- 🤖 **Customizable Interview Flow**: Easily configure interview structures to align with specific hiring needs. 
  

---

## 🛠️ Tech Stack  
- **Language**: Python
- **Frameworks/Libraries**: Gradio, OpenAI API, CSS  
- **Features**:  
  - Dynamic interaction 
  - Content moderation  
  - Conversation context tracking  

---

## 🧪 Example Use Cases  
- Conducting technical screenings for candidates with a specific tech stack (e.g., Python, JavaScript, or AWS).  
- Scaling recruitment processes without compromising interview quality.  

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- OpenAI API KEY

### Installation
1. Clone the repo:
git clone https://github.com/SandeepGitGuy/Hiring_Assistant_Chatbot.git

2. Navigate to the project directory:
cd Hiring_Assistant_Chatbot

3. Install the required dependencies:
pip install -r requirements.txt

- Please note: OpenAI API keys are required for the project to function. You can obtain them from the OpenAI website and change the same in the code. 

4. Run the main file from Jupyter environment:
"PG-AGI AIML Intern Assignment.ipynb"

5. Access the application through your web browser at http://127.0.0.1:7861

---

## 🚀 Usage Guide 
1. Launch the application and input your OpenAI API key.
2. Start the interview process by filling in basic details (e.g., name, email, experience).  
3. Respond naturally to technical questions tailored to your skills.
4. End the interview anytime by typing "exit", "quit", or "end".

---

## 🛠️ Challenges & Solutions  
- 🔄 **Context Management**:  
  - **Challenge**: Maintaining coherent conversation flow.  
  - **Solution**: Implemented a robust message history system.

- 📈 **Difficulty Scaling**:  
  - **Challenge**: Adjusting question difficulty for varied experience levels.  
  - **Solution**: Designed experience-based question tiers with a balanced mix of conceptual, coding, and debugging queries.  

- 🛡️ **Security**:  
  - **Challenge**: Handling sensitive user data securely.  
  - **Solution**: Encrypted API keys and ensured compliance with GDPR standards.

- 🎭 **Edge Case Detection**:
    - **Challenge**: Identifying and appropriately handling unexpected or off-track responses, including attempts to manipulate the interview process or provide non-relevant information.
    - **Solution**: Implemented an advanced response validation system that:
                    Detects response patterns that deviate from expected interview flow
                    Identifies potential attempts to bypass technical assessment
                    Gracefully redirects conversation back to relevant topics or terminate the process

---

## 🎯 Prompt Design

The chatbot's prompt engineering was carefully crafted to create a structured yet natural technical interview experience. Here's a detailed breakdown of how the prompts were designed:

### 🧩 Core Components

1. **🎭 Role Definition**
   - The prompt begins by establishing the chatbot's role as a technical recruiter.  
   - Emphasizes being "helpful and context-aware" to ensure natural interactions.  
   - Sets clear expectations about the interview's purpose and scope.  

2. **📋 Information Gathering Strategy**
   - Implements a staged approach to data collection.  
   - Starts with basic information (name, contact details, experience).  
   - Progresses to technical skills assessment.  
   - Uses specific prompting patterns to ensure complete responses.  

3. **🛠️ Technical Assessment Design**  
   The technical question generation system follows a sophisticated three-tier structure:  

   a) **📊 Experience-Based Difficulty Scaling:**  
   - 🟢 Junior (0-2 years): Basic concepts and syntax.  
   - 🟡 Mid-level (3-5 years): Implementation and use cases.  
   - 🔴 Senior (5+ years): Architecture and optimization.  

   b) **📝 Question Type Distribution:**  
   - 💡 Conceptual Understanding.  
   - 💻 Practical Coding Challenges.  
   - 🐛 Debugging Scenarios.  
   - 🌐 Real-world Application Cases.  

4. **🔄 Conversational Flow Control**
   - Dynamic question generation based on declared tech stack.  
   - 3-5 questions per technology to ensure comprehensive assessment.  
   - Questions are presented sequentially with context maintenance.  
   - Built-in mechanisms for handling unclear or incomplete responses.  

5. **🛡️ Safety and Compliance Features**
   - GDPR-compliant data handling instructions.  
   - Fallback mechanisms for unexpected responses.  
   - Clear protocols for handling inappropriate behavior.  
   - Structured conversation termination procedures.  

### ✨ Design Principles

1. **📈 Progressive Complexity**
   - Questions evolve from fundamental concepts to complex scenarios.  
   - Difficulty adapts based on candidate's experience level.  
   - Ensures comprehensive skill assessment.  

2. **🔗 Context Retention**
   - Maintains conversation history.  
   - References previous answers.  
   - Uses appropriate pronouns and context markers.  

3. **⚙️ Error Handling**
   - Clear fallback mechanisms.  
   - Clarification requests for vague responses.  
   - Graceful handling of off-topic interactions.  

4. **💬 Natural Conversation Flow**
   - Professional yet approachable tone.  
   - Smooth transitions between topics.  
   - Clear signposting of interview stages.

---

## 🚀 Future Scope  
- 🌍 **Multilingual Support**: Enable interviews in multiple languages for global candidates.  
- 🔗 **Integration with ATS**: Seamless connection to Applicant Tracking Systems to streamline hiring workflows.  
- 🔎 **Advanced Analytics**: Provide detailed insights on candidate performance, skills, and behavioral traits.  
- 🧠 **Emotion Detection**: Enhance interviews by incorporating AI to track, identify and adapt to candidate emotions.  
- 🎨 **Customizable Templates**: Allow recruiters to tailor question templates to suit specific roles or industries.   

---

## 🛡️ License  
Distributed under the MIT License. See the `LICENSE` file for details.  

---

## 💬 Contact  
For queries or feedback, feel free to reach out:  

- **Email**: jobsforsandeepb@gmail.com 
- **GitHub**: https://github.com/SandeepGitGuy/  
- **LinkedIn**: www.linkedin.com/in/sandeepbjan1998/
- **Website** : https://sandeepgitguy.github.io/

---