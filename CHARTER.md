<img src="artwork/OASIS-Primary-Logo-Full-Colour.png" width="200">

# RECITE Charter

## 1. Project Name

### 1.1 Full Name

REasoning for Conversation and Information Technology Exchange (RECITE) OASIS Open Project

### 1.2 Familiar Name

recite-oasis

## 2. Abstract

Conversational agents perform real-time dialogs between humans and computers, be it textual or via speech. With this proposal, a standardized formal description of dialog modeling for conversational agents is suggested for the purpose of  interoperability between different vendor solutions. 

## 3. Purpose and Scope

Conversational interfaces are evolving at a fast pace due to improvements of natural language processing techniques. Users can now have natural, almost human-like, conversations with computer systems. Such interfaces can empower the human worker and can save high costs. 

A conversational interface is typically composed of separate components performing Automatic Speech Recognition, Natural Language Understanding (NLU),  Dialogue Management, Natural Language Generation (NLG) and Speech Synthesis. Many vendors offer one or more readily built components which can be combined for creating conversational agents. Although their goals are similar, their implementations and expected input formats can differ significantly. While the market is crowded with software vendors, and standards for most of the components are well established, there is no interoperability between the dialog models. We therefore suggest creating an open standard for dialog management representation to increase compatibility. 

A dialogue representation often consists of a directed graph that guides the conversational turns in a dialogue between a human and a computer. It maps questions with the same intentions to an answer and a possible subsequent question. Slot filling is used to ensure that all the required information is available to generate an appropriate response. A standard formalization of  such dialog representations would highly increase the interchangeability of conversational agents between different vendors.

## 4. Business Benefits

Standardization of conversational technology acts as a driver for accelerating its continuous advancement. Having a common denominator will provide a platform where dialogue systems can be adapted to different purposes. Interoperability across systems and domains, furthermore, avoids lock-in and allows users to migrate their implementation from one technology to another. Ultimately, a standard enables quick adaptation to new domains, such as finance, health, or retail, and simplifies conformity with privacy and legal regulations.

## 5. Relationship to Other Projects

A starting point of the development of the proposed standard, could be the ISO Standard for Dialogue Act Annotation (Bunt et al. 2010, ISO/TS 24617-2). This standard has been developed from a descriptive point-of-view, while our focus is on setting a prescriptive standard. Here, a markup language for dialogues is defined, which is a structured collection of domain-independent, theoretically and empirically grounded communicative functions. Although this standard has been developed for academic purposes, it can be adapted to meet the needs of practical commercial implementations of conversational systems. It also provides guidelines on how it can be extended with additional functions for particular domains. A related standard, ISO/TS 24617-5, focuses on more specific aspects of conversation such as rhetorical or discourse relations. Following the ISO 24617-2, Pareti et al. 2018 presented a dialog schema that was created to support computational application by representing dialog as a graph of intents providing a structure that can be used by other conversational components (NLU & NLG).

Another relevant body of work is provided by the voice interaction community group (VoiceXML, Larson 2003). The members of this group are currently working on the interoperability for conversational interfaces and on dialogue management or ‘workflow' languages. Rasa (Bocklisch et al. 2017), an open source language understanding and dialogue management framework employs markdown to specify training dialogues.

- Bunt, Harry, et al. “Towards an ISO Standard for Dialogue Act Annotation.” In LREC’10, 2010.
- ISO/TS 24617-2: ISO standard for Dialogue Acts: https://www.iso.org/standard/76443.html, 2020
- ISO/TS 24617-5: ISO standard for Discourse structure annotation: https://www.iso.org/standard/57083.html, 2014
- VoiceXML https://www.w3.org/community/voiceinteraction/  
- Larson, James A. "VoiceXML and the W3C speech interface framework." IEEE MultiMedia 10.4 (2003): 91-93.
- Bocklisch, Tom, et al. "Rasa: Open Source Language Understanding and Dialogue Management."
- Pareti, Silvia, and et al. "Dialog intent structure: A hierarchical schema of linked dialog acts." In LREC’18. 2018.

## 6. Repositories and Licenses

MIT License (https://opensource.org/licenses/MIT)

## 7. Initial Contributions from Existing Work

Accenture has deployed an initial framework of conversational agents at a number of clients and maintains a library of domain specific conversational agents. The aim of this project is to synthesise a large number of viewpoints by reaching out to the corporate and academic contributors in conversational technology.

