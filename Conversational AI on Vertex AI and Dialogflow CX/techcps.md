
### 💡 Course Link: [Conversational AI on Vertex AI and Dialogflow CX](https://www.cloudskillsboost.google/course_templates/892)

### 🚀 Course Solution [Watch Here](https://youtu.be/Fe98R0pKBYk)

---

### ⚠️ Disclaimer
- **This script and guide are provided for  the educational purposes to help you understand the lab services and boost your career. Before using the script, please open and review it to familiarize yourself with Google Cloud services. Ensure that you follow 'Qwiklabs' terms of service and YouTube’s community guidelines. The goal is to enhance your learning experience, not to bypass it.**

### ©Credit
- **DM for credit or removal request (no copyright intended) ©All rights and credits for the original content belong to Google Cloud [Google Cloud Skill Boost website](https://www.cloudskillsboost.google/)** 🙏

---

## **Generative AI for Dialogflow CX Quiz**

1. **Recently, some of your customers have been asking questions that your Dialogflow CX virtual agent is unable to answer. You realize that intents have not been defined for these types of questions. What generative AI feature would you add to your solution to handle conversations that have gone off-track?**  
   - Generative Fallback

2. **What are two of the key benefits of using generative AI features in Dialogflow CX? (Select two options)**  
   - Generated content is restricted to what you want it for
   - Chatbots provide accurate and helpful information

3. **What are two of the main generative AI capabilities that have been added to Dialogflow CX? (Select two options)**  
   - Generators
   - Generative AI Agent

4. **You have been asked to add generative AI capabilities to your Dialogflow CX virtual agent that will enable it to reference the existing FAQs on the company website. What generative AI feature would you add to your solution to enable this functionality?**  
   - Generative AI Agent

---

## **Generators quiz**

1. **When configuring a Generator there are some controls that can be used to customize the behavior of the generative responses. What are the controls available to you to customize the generative AI responses?** (Select two options)
   - LLM parameters, such as Temperature, Top P and Top K
   - Text Prompt

2. **With generators, you can make a prompt contextual by marking words as placeholders by adding a $ before the word. These placeholders usually hold a position in the prompt that will be substituted for user input data at runtime. What session parameter can you associate with the $text prompt placeholder?**  
   - Any of the session parameters identified in the Intents

3. **Which two language models can a Generator use to generate code? (Select two options)**  
   - code-bison
   - text-bison

4. **Read the text prompt below and answer the following question. What information would the highlighted $conversation placeholder parse into the prompt? Your goal is to summarize a given conversation between a Human and an AI. Conversation: $conversation{USER:"Human:" AGENT:"AI:"}Human: $last-user-utterance A concise summary of the conversation in 1 or 2 sentences is:**  
   - The conversation between the agent and the user, excluding the very last user utterance.


5. **Generators have a particular set of capabilities that can be utilized by a Dialogflow CX virtual agent in a customer conversation. What are two capabilities of Generators?** (Select two options)
   - Sentiment analysis of customer responses
   - Conversation Summarization

6. **What is the correct syntax for a Generator’s output parameter?**
   - $request.generative
---

## **Generative Fallback quiz**

1. **A Dialogflow CX flow has been designed for booking diving trips. A particular page in the flow is configured to assist users with group reservations or full charters, the intent description states: ‘Currently you can assist users who are looking for a group reservation or a full charter. Initially collect travel details including departure period, destination, number of guests (min 4 max 15 people), contact details. The destination must be one of the following in the Pacific: Costa Rica, Mexico, Galapagos Islands.’ Which Generative Fallback enablement levels would be triggered if the user tries to book a full charter for 18 people?** (Select two options)
   - The page-level would be triggered as the minimum and maximum number of guests is specified in the intent description. The LLM also uses this description to generate the response.
   - The parameter-level would be triggered as the minimum and maximum number of guests is defined as an entity parameter. The LLM uses the intent description to generate the response.


2. **Generative Fallback is a mechanism for handling points in a conversation with a Dialogflow CX virtual agent, where the user moves away from the intended flow and doesn't trigger another action or flow, known as a No Match error. What kind of user response could invoke a No Match error?** (Select two options)
   - Saying something unexpected
   - An invalid input while form filling

3. **You can add a list of banned phrases for your Generative Fallback response. What happens if a banned phrase has been entered by a user as part of their response?**  
   - A prescribed answer defined in Agent Says will be used to respond.

4. **Which statement is true for Generative Fallback:**  
   - Aim to prevent no-match scenarios by providing good, varied training phrases to your intents.

5. **You have been asked to enable generative responses for no-match events for specific pages, by enabling it in the Agent response section of the event handler. Where would you provide the information for the LLM to reference to generate its response?**
   - Intent description


6. **What is the correct definition of the $route-descriptions prompt placeholder?**
   - The intent descriptions of the active intents.

---

## **Generative AI for virtual agents quiz**

1. **Which two features are used by Generative AI Agents to provide a response based on your data?** (Select two options)
   - Data stores
   - Large Language Models

2. **Data stores are used to find answers for end-user's questions. A data store can consist of different sources. What types of source data are available for data stores in a Vertex AI Search and Conversation?**
   - Website, structured and unstructured data.

3. **What are two other important and useful features that are part of Generative AI Agents and data stores?** (Select two options)
   - Data store prompt
   - Grounding confidence

4. **Which two statements are true for Generative AI Agents? (Select two options)**  
   - With Hybrid Agents you can use a mix-and-match approach to leverage both intent-based flows and generative AI use cases.
   - Keep what is working well in Dialogflow CX and add generative AI capabilities.

5. **A Virtual Agent uses intent detection to route customer questions to the relevant information. Generative AI capabilities can be added to handle certain intent detection routes. Which aspect of Dialogflow CX Agent intent detection do Generative AI Agents cover?**  
   - State handlers

---

## **Vertex AI Search and Conversation architecture and security quiz**

1. **The website team is creating a microservice that will be responsible for creating controls and serving configs to filter out what data is presented to users after they perform a query. Which role should you assign them?**
   - Discovery Engine Admin

2. **Choose the answer that best describes the security posture of Vertex AI Search and Conversation.**
   - Vertex AI Search and Conversation offers the same security capabilities as other Google Cloud Perimeter products like BigQuery, including data encryption, no data sharing across customers, and Google will never use your data to train foundation models.


3. **The development team is creating a microservice that will be responsible for ingesting new documents into the Vertex AI Search and Conversation unstructured data store on bulk every hour. Which role should you assign them?**
   - Discovery Engine Editor

4. **The security team needs to perform some audit tasks to your datastores on Vertex AI Search and Conversation to make sure the right documents and user events are being ingested. Which role should you assign them?**
   - Discovery Engine Viewer

---

## **Generative Playbooks quiz**

1. **What can you do to improve the accuracy of the agent’s behaviour?**
   - Write clear instructions combined with thorough training examples.


2. **What are two generative AI related features of Dialogflow CX that can be used with Playbooks?** (Select two options)
   - Data stores
   - Generative AI Agents

3. **What is the purpose of the ReAct pattern?**
   - To enable LLMs to generate both verbal reasoning traces and text actions to solve various language reasoning and decision making tasks.


4. **What is a tool in the context of a playbook?** (Select two options)
   - Tools are a collection of functions that are available to the playbook and the Dialog Manager.
   - Tools are API calls, defined by a schema in the OpenAPI 3.0 format.


5. **What are two key steps in connecting a Generative Playbook with a data store?**
   - Create a Playbook tool for the Generative AI Agent
   - Select the data store in the tool user interface and save the tool.


6. **What are two powerful features of Generative Playbooks?** (Select two options)
   - Playbooks enable LLMs to access APIs and tools.
   - Playbooks can leverage LLMs for instruction-driven flow development.


7. **What are two of the limits of Generative Playbooks?** (Select two options)
   - 15k input tokens and 500 output tokens summed across a conversation turn
   - 5 LLM calls per conversation turn


---

<div align="center" style="padding: 5px;">
  <h3>📺 Don't forget to Like, Share & Subscribe!</h3>

  <a href="https://www.youtube.com/@techcps">
    <img src="https://img.shields.io/badge/YouTube-TechCPS-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube Channel">
  </a>
</div>

---

<div align="center" style="padding: 5px;">
  <h3>📱 Join the Cloud Community</h3>

  <a href="https://t.me/Techcps">
    <img src="https://img.shields.io/badge/Telegram_Channel-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel">
  </a>
  &nbsp;
  <a href="https://t.me/Techcpschat">
    <img src="https://img.shields.io/badge/Telegram_Chat-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Chat">
  </a>
  &nbsp;
  <a href="https://whatsapp.com/channel/0029Va9nne147XeIFkXYv71A">
    <img src="https://img.shields.io/badge/WhatsApp_Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Channel">
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/company/techcps/">
    <img src="https://img.shields.io/badge/LinkedIn-TechCPS-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  &nbsp;
  <a href="https://twitter.com/Techcps_/">
    <img src="https://img.shields.io/badge/TwitterX-TechCPS-000000?style=for-the-badge&logo=x&logoColor=white" alt="TwitterX">
  </a>
  &nbsp;
  <a href="https://instagram.com/techcps/">
    <img src="https://img.shields.io/badge/Instagram-TechCPS-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
  &nbsp;
  <a href="https://facebook.com/techcps/">
    <img src="https://img.shields.io/badge/Facebook-TechCPS-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">
  </a>

  <h3>Thanks for watching and stay connected 🙂</h3>
</div>

---
