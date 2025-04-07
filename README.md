# prompt-engineering-openai-assignment
A hands-on project demonstrating prompt engineering skills using OpenAI GPT-4 to classify reviews, generate structured outputs, personalize emails with varied tones, and creatively name products. Developed using Python and Google Colab.
----

# 🧠 Prompt Engineering Assignment – Review Classifier with OpenAI API

This project demonstrates core concepts of **Prompt Engineering** using OpenAI's GPT-4 API. It includes real-world use cases such as classifying customer reviews, extracting structured data, generating responses in different tones, and naming products creatively.

## 🚀 Project Overview

This assignment focuses on solving practical tasks by crafting effective prompts. The model is guided through carefully designed instructions to classify reviews into categories, respond politely in multiple tones, extract data in JSON, and enhance prompt specificity.

## 🧪 Features

- ✅ Classify customer reviews into:
  - Delivery Issues
  - Product Quality
  - General Feedback
- ✅ Extract structured JSON data from review text
- ✅ Respond to customers using different tones (formal vs. casual)
- ✅ Generate creative product names based on product descriptions
- ✅ Improve prompt outputs by adding target audience and clear CTAs

## 🔧 Technologies Used

- Python (in Google Colab)
- OpenAI GPT-4 API (`chat.completions` endpoint)
- Prompt Engineering best practices

## 📚 What I Learned

This project helped me understand the **power of prompt design** and how a small change in phrasing can significantly influence LLM responses.

### ✅ Skills Demonstrated

- **Prompt Engineering**: Crafting specific instructions for zero-shot tasks.
- **OpenAI API Usage**: Integrated GPT-4 model in Python with proper message formatting.
- **Tone Adjustment**: Experimented with how tone affects LLM responses.
- **Temperature Control**: Observed the effect of `temperature` parameter on creativity.
- **Structured Data Generation**: Used prompts to extract clean JSON data.
- **Prompt Refinement**: Improved marketing output through better prompt detail.

## 📌 Key Takeaways

- Clear, detailed prompts produce more accurate and structured outputs.
- Temperature tuning is crucial for balancing between deterministic and creative outputs.
- Prompt Engineering is not just about asking; it's about **guiding the model intelligently**.

---

## 💻 How to Run

1. Clone the repository or open the notebook in Google Colab.
2. Set your OpenAI API key:

   import os
   os.environ["OPENAI_API_KEY"] = "your-api-key"

3. Install the OpenAI package if needed:
    bash
   !pip install openai

4. Run the cells and observe the model responses for different tasks.

---

## 🤖 Example Output


Review: The book I received was damaged. The cover had scratches.
Classification: Product Quality



Prompt: Suggest a name for a waterproof backpack.
Response (Temperature=1): AquaShield Voyager



## 📁 Folder Structure


📦 prompt-engineering-openai-assignment
 ┣ 📜 README.md
 ┣ 📓 prompt_assignment.ipynb

## 🧠 What I Learned

This project was completed as part of a Prompt Engineering assignment, where I explored how to design and improve prompts to guide language models effectively. Here's what I accomplished:

---

### ✅ Skills Demonstrated

- **Prompt Engineering**:
  - Designed effective zero-shot prompts for review classification and structured data extraction.
  - Iteratively refined prompts to improve model accuracy and consistency.
- **OpenAI API Integration**:
  - Successfully integrated and used the `chat.completions` API to generate responses and structured outputs.
- **Tone Manipulation**:
  - Experimented with tone control (casual vs formal) for customer support responses using prompt tuning.
- **Temperature Tuning**:
  - Understood how temperature affects creativity in outputs by generating deterministic vs. creative product names.
- **Structured Output Handling**:
  - Extracted structured JSON data from free-text reviews using targeted prompts.
- **Iterative Prompt Improvement**:
  - Enhanced a generic marketing prompt by specifying target audience, product features, and call-to-action to get better ad copy.

---

### 📌 Key Takeaways

- Prompt clarity = better results: Vague instructions lead to poor responses; specific details improve relevance.
- Temperature = control vs. creativity: Lower temperature yields predictable results, higher temperature introduces novelty.
- Prompt engineering isn’t just about asking; it’s about **asking the right way** to get the best response from an LLM.

---

### 🛠 Tools Used

- Google Colab (Python environment)
- OpenAI GPT-4 API
- JSON handling and API response parsing



## 🏁 Final Note

This assignment strengthened my skills in using GPT-4 for real-world tasks and improved my ability to think like a **prompt engineer**. I'm excited to apply these techniques in more complex AI-driven projects.

```
