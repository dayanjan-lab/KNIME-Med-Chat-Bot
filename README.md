# KNIME-Med-Chat-Bot: A Low Code Solution For AI Driven Conversational Information Extraction from Clinical Practice Guidelines.

## Introduction
Clinical practice guidelines, particularly those from organizations like the American Heart Association, play a pivotal role in shaping the landscape of patient care. Formulated through meticulous analysis of current research by expert panels, these guidelines provide evidence-based recommendations. As the bedrock of clinical decision-making, they promote consistency and excellence in healthcare practices. Offering granular guidance on diagnosis, treatment, and prevention, these guidelines not only foster enhanced patient outcomes but also keep healthcare professionals abreast of the latest medical advancements. Regularly updated to mirror evolving medical insights, these guidelines are key in steering treatment plans and bolstering patient comprehension of their health issues.

In the ever-evolving realm of healthcare, technological advancements are transforming our interaction with medical data. A notable innovation in this domain is the emergence of generative AI-powered chatbots, such as Chat GPT, Claude, Bard etc., being used for medical information extraction. However, these applications need to be grounded in most uptodate clinical practice guidelines to minimize hallucinations and provide updated information beyond the training cut off. The direct incorporation of entire medical texts, such as Clinical Practice Guidelines, into these models, however, faces practical challenges due to context window limitations and token costs. To circumvent these issues, a Retrieval Augmented Generation (RAG) approach is employed, enabling these AI tools to efficiently distill and provide pertinent information without the need to sift through voluminous documents.

The traditional creation of RAG-based applications, aimed at navigating medical guidance texts, often necessitates programming skills, such as Python proficiency, which is generally not included in the training of healthcare professionals. Identifying this skill gap, our team has crafted a solution: a chatbot built using KNIME, an adaptable no/low-code data analytics platform. This breakthrough streamlines the intricate processes of coding and AI integration, making it accessible to healthcare practitioners of all backgrounds. Utilizing this intuitive platform, professionals can independently develop AI-based applications tailored to their unique needs, thereby enabling efficient engagement with any relevant medical guidance document. This tool democratizes access to sophisticated conversational information extraction technologies, significantly enhancing the capability of healthcare professionals to utilize and interact with clinical practice guidance documents in their specialized fields.

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
