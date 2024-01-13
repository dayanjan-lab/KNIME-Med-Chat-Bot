# KNIME-Med-Chat-Bot

## Introduction
In today's dynamic healthcare environment, the integration of technology is revolutionizing how we engage with medical data. A significant breakthrough in this field is the advent of generative AI-powered chatbots tailored for medical information. These chatbots, underpinned by robust facts and grounded in authoritative medical guidance documents, leverage advanced large language models like GPT-4 for precise and up-to-date information retrieval. However, direct integration of entire medical texts into these models is often impractical due to limitations in context window and token economy. This challenge necessitates a Retrieval Augmented Generation (RAG) methodology, enabling these AI tools to succinctly extract and provide relevant information without the need for perusing extensive documents.

Traditionally, developing such RAG-based applications for interacting with medical guidance texts requires programming skills, like proficiency in Python, which traditionally is not a part of the training program for healthcare professionals. Recognizing this gap, our team developed a solution: a chatbot developed using KNIME, a versatile no/low-code data analytics platform. This innovation simplifies the complex coding and AI integration process, making it accessible to all healthcare practitioners. By employing this user-friendly tool, professionals can now autonomously generate AI-driven applications tailored to their specific needs, enabling them to engage with any relevant medical guidance document efficiently. This application democratises access to advanced conversational information extraction technologies, enhancing the ability of healthcare professionals to interact with and leverage medical literature in their areas of expertise.

## The Utility of the Medical Information Chat Bot:
- Instant Access to Reliable Information: In critical situations, immediate access to accurate medical information can be a matter of life and death. This chat bot ensures that users receive reliable information promptly, aiding in informed decision-making.
- Empowering Patients: Patients are now empowered with the knowledge they need to engage in meaningful discussions with healthcare professionals. This newfound understanding fosters a sense of confidence and active participation in their healthcare journey.
- Supporting Healthcare Providers: Healthcare professionals benefit from the chatbot as well. By relieving them of basic inquiries, the bot allows medical staff to focus on more complex tasks, ultimately enhancing the efficiency of healthcare delivery.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites:

- **KNIME Analytics Platform (Version 5.1.1)**: Used as the core environment for building data workflows.

- **Python (Version 3.9)**: Integrated into KNIME to leverage Python libraries and machine learning capabilities.

### Installation

To install the necessary Python packages, execute the following commands in the same Python environment used in your KNIME settings:

```bash
pip install pandas
pip install openai
pip install langchain
pip install unstructured
pip install fitz
pip install PyPDF2
pip install PyMuPDF
pip install "unstructured[pdf]"
