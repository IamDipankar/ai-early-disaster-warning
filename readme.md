# AI early warning system with voice agent

Despite significant advancements in early warning systems, a critical gap persists in effectively communicating disaster alerts to vulnerable communities at the last mile. Limitations such as poor connectivity, delayed dissemination, and lack of localized, easily understandable messaging prevent timely and actionable information from reaching at-risk populations. This communication failure often results in inadequate preparedness and increased loss of life and property, particularly in disaster-prone regions. This project proposes an AI voice agent for context-aware disaster guidance and real-time risk mapping designed to bridge the last-mile gap through an intelligent, inclusive, and scalable framework. The system integrates disaster prediction models with an AI-powered communication infrastructure to ensure rapid, personalized, and accessible dissemination of alerts. The workflow begins with continuous monitoring of meteorological and environmental data, combined with predictive modeling for multiple hazards such as floods and cyclones. Time-based forecasts (ranging from immediate nowcasts to multi-day predictions) are generated and fed into a centralized AI system. This system is connected to a call center infrastructure and utilizes a database of residents in vulnerable areas to initiate automated outreach. A key innovation of the proposed solution is the use of voice-enabled AI to conduct real-time, two-way communication with community members through basic feature phones, eliminating the need for smartphones or internet access. The system employs multilingual automatic speech recognition and AI-based conversational agents to assess local conditions, deliver personalized safety instructions in native language, and collect ground-level data. The collected information is processed to extract actionable insights, including potential property damage and community preparedness levels. These insights are stored in a centralized database and used to generate dynamic risk maps, such as vulnerable population distributions and probable damage assessments. The system further supports decision-making by providing real-time situational awareness to governments and NGOs, enabling targeted interventions and efficient resource allocation. Overall, this framework enhances disaster preparedness by transforming early warning systems into interactive, community-centered platforms. By combining AI technologies with inclusive communication strategies, the proposed solution aims to significantly improve last-mile connectivity, reduce disaster impacts, and strengthen resilience in vulnerable communities.

# Instructions for using it

the main_agent file should be run in google colab or any other suitable jupyter notebook environment.
(Direct link: https://colab.research.google.com/drive/1SA8ezOuUbrXR-HQuPI5gn1FmeHd1eOPo?usp=sharing)

**Important**

- You should log in via your google cloud console account
- In your cloud console account you have to configure and project with Google Cloud Text to Speech Enabled
- You should put that project id in the command below

- Also, you need hf token and open_ai_api key
- You have to accept terms and conditions for the model (https://huggingface.co/ai4bharat/indic-conformer-600m-multilingual)

**Required files**

Four files should be in the current working directory

1. `output_union_damage.csv`
2. `conversation script.txt`
3. `Cyclone guideline instruction.txt`
4. `flood guideline instruction.txt`

(All of these files are in the github repository)
