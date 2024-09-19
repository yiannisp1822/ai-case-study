AI Bootcamp 

Module 1 Challenge


# TITLE
**Anthropic Case Study**  
Ioannis Pagkalos  
Sept 19th 2024

## Overview and Origin

>Anthropic is an AI-driven research company focusing on increasing the safety of AI systems. Its research interests span multiple areas, including natural language, human feedback, scaling laws, reinforcement learning, code generation, and interpretability. The company's initial product is Claude, an AI helper for tasks of any size.
Anthropic envisions a future where AI systems are developed, strongly emphasizing safety, transparency, and alignment with human values. The company seeks to contribute to creating AI technologies that enhance human well-being and are trustworthy and reliable.

* Name of company  
Anthropic

* **When was the company incorporated?**  
2021

* **Who are the founders of the company?**  
Daniela Amodei, Dario Amodei.  
Other Co-founders noted (Jared Kaplan, Ben Mannm, Jack Clark)

* **How did the idea for the company (or project) come about?**  
The anthropic founders worked previously at Open AI. They left to research how to increase the safety of AI systems, focusing on the reliability of large-scale AI models, making them more interpretable, and allowing human feedback to influence the development and deployment of the models.

* **How is the company funded? How much funding have they received?** 
Anthropic has received 10 funding rounds from 51 Investors and has raised a total of $9.7B, $6.5 of which via corporate rounds from companies like Google ($2B) and Amazon ($4B).  
The initial funding round ($124M) was led by Jaan Tallinn, co-founder of Skype. Also taking part were Infotech's James McClave, Facebook co-founder Dustin Moskovitz, the Center for Emerging Risk Research, and former Google CEO Eric Schmidt.

## Business Activities

* **What specific problem is the company or project trying to solve?**  
 
 Anthropic, similar to other GenAI companies, builds agents/assistants (Claude) that can converse with the user simulating human characteristics. In traditional search, users would write a question, or specifiy what they want and would get a series of links that they would have to navigate through to find the required answer. With GenAI based on LLMS, the answer is synthesized by the model.
 Anthropic’s first product is Claude, an AI assistant similar to Chat GPT. It is based on Anthropic’s proprietary LLMs.  
 Anthropic offers consumer and enterprise versions of Claude.
 
 *Claude Enterprise:*  
 Claude Enterprise connects to a company’s internal knowledge base and can be used to generate insights, forecasts, ideas, summaries, etc., as well as to track projects, and create and share work. It has a massive 500k token context window and advanced security controls.
 
 *The consumer version of Claud comes in the following flavors:*  
 1. The free version uses Claude 3.5 Sonnet
 2. The Pro version cost $20/month and gives users 5x more usage, access to more powerful models (Claude Haiku and Claude Opus), the ability to create projects to work with Claude around a set of docs, code, or files, priority access during busy periods and early access to new features. 
 3. The Team version costs $25/month per user and includes everything in Pro + higher usage limits, the ability to share and discover chats from teammates, and a central billing and admin interface.
 
 Anthropic also offers direct API access with a limited free version for evaluation before commercial use. Once users want to commercialize applications, they need to purchase credits.

* Who is the company's intended customer? Is there any information about the market size of this set of customers?  
  
  Anthropic offers solutions to consumers and enterprises per the product descriptions above. In early 2024, it reached $200m in revenue with over 100,000 customers. Its projected annualized revenue is estimated to be $850m—$1 b for 2024. 
  The broader GenAI market is estimated to be worth $68.34B in 2024, and $491B by 2031


* What solution does this company offer that its competitors do not or cannot offer? (What is the unfair advantage they utilize?)
  
  Anthropic has positioned itself as a leader in AI safety using the Constitutional AI framework and has capabilities (such as Claude’s 500k context token window extending to 1m when all 3 models are used) that allow it to offer various services in the enterprise segment. Anthropic is also focused on security and has built best-in-class jailbreak resistance into its models, reducing the risk of the AI being manipulated to produce harmful or inappropriate content.


* **Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing;you may want to search the company’s engineering blog or use sites like Stackshare to find this information).**  

  1.	Constitutional AI (CAI) is a framework developed to align AI systems with human values. Within this framework, humans provide a set of rules describing the desired behavior of the AI system, known as the "constitution". The AI system evaluates the generated output and then adjusts the AI models that are used to train it to better fit the constitution. The self-reinforcing process aims to avoid harm, respect preferences, and provide true information (wikepedia.com) (anthropic.com)
  2.	Anthropic's models (like most AI models) use transformer architecture, allowing them to process large amounts of text data, perform language tasks, and generate outputs based on various nput sequences.(Wikipedia), (Sacra)
  3.	Claude models use large context windows (Claude 3 500k), surpassing  GPT-4. This enables models to process more queries or data in one single session.(AI News), (PYMNTS.com)
  4.	Anthropic has incorporated advanced jailbreak resistance technology and robust misuse prevention mechanisms into its models, ensuring superior security for business applications compared to other generative models.. (Home), (Sacra)


## Landscape

* **What field is the company in?**

  Anthropic operates in the AI industry and specializes in developing GenAI models and associated assistants. They offer both enterprise and end consumer products based on their proprietary LLM. Anthropic competes directly with OpenAI, Gemini, and Meta's Llama (although the latter is offered as open source).


* **What have been the major trends and innovations of this field over the last 5 to 10 years?**

  The last decade saw a massive acceleration and breakthroughs leading to products that have been incorporated in many services used today. Key milestones include: 
  1. The invention of GANs (2014)
  2. Sophia the robot is activated (2016)
  3. The AI audio generator WaveNet is launched (2016)
  4. AlphaGo beats the world’s Go champion (2016)
  5. The birth of deepfakes (2017)
  6. The first ‘Transformer’ lays the technological foundation for large language models (LLMs) (2017)
  7. OpenAI releases GPT-1 (2018)
  8. AlphaFold wins protein folding contest (2020)
  9. Generative AI goes mainstream (2022)
  10. The release of ChatGPT-4 (2023)  
  
  For more details on each, please see the source: [10 AI Milestones in the Last 10 Years](https://www.rigb.org/explore-science/explore/blog/10-ai-milestones-last-10-years)  
  
  Expanding briefly on 2 of the above that were critical: 
  1. Transformer Models:
  For many years, sequence modeling and generation was done by using plain recurrent neural networks (RNNs). RNNs operate one token at a time from first to last; they cannot operate in parallel over all tokens in a sequence. Modern Transformers overcome this problem, but unlike RNNs, they require computation time that is quadratic in the size of the context window. (Wikipedia). Transformer models made Deep learning possible which revolutionized NLP.
  
  2. Generative AI: 
  A type of AI that for the first time it is capable for generating new text, images, sound, video etc when given an input prompt. It is based on LLMs that use existing data to train the model and generate new data based on the promt.


* **What are the other major companies in this field?**  

  Open AI, Microsoft (Copilot), Google (Gemini), Mistral AI, Meta  
  Cohere, AI21 Labs and Charachter


## Results

* **What has been the business impact of this company so far?**
  
  As with other GenAI companies, Anthropic’s business impact is significant but still in its very early stages. Companies utilizing the enterprise version of Claude have realized significant efficiencies in areas like knowledge sharing and processes, security, SW development, and customer support.


* **What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?**

  Key Metrics for Anthropic are:  
  
  1. Customer Numbers: MAUs, DAUs, total (100k customers)
  2. Revenue: (expected to reach 850 by year end of 2024)
  3. Tech Performance: Token context window (500k token context window can process 200k lines of code and 100-page documents in a sigle prompt)


* **How is your company performing relative to competitors in the same field?**

  Customer Numbers:
  - Open AI: millions of consumers (100m in its first month of launch) and enterprise adoption by MSFT 
  - Google: Not public – access to all of Google’s customer base (billions)
  - Meta - Llama: Open source – (350m downloads)
  
  Revenue:  
  - Open AI: Rev 2B in annual revenue as of 2023
  - Google Not Broken out
  - Meta – Llama: Revenue (not broken out – open source means minimal licencing fees at the moment)

  Tech Performance:
  - Open AI: 128k token context window
  - Google: Unclear
  - Meta: Unclear

## Recommendations

* **If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers or use your imagination!)**  
  
  Double down on ethics and safety as a differentiator. Anthropic has a good head start in the space and is a brand associated with safety. With growing concerns about the unchecked development of gen AI models (racing toward AGI), anthropic could become the go-to model for concerned consumers/enterprises. Areas such as Cybersecurity and compliance could be of particular interest given those characteristics

* **Why do you think that offering this product or service would benefit the company?**  
  
  Anthropic has built its brand on developing models with safety and ethics in mind. This can be a differentiator and is especially important when attracting enterprize customers.

* **What technologies would this additional product or service utilize?**
  
  Likely technologies for the proposed products/areas could include: 
  1. General: Natural Language Processing and Transformer Models to continue building on its capability to process large datasets and human input.
  2. Compliance/Auditing: Explainable AI
  3. Safety: Constitutional AI 
  4. Cybersecurity: Graph Neural Networks

* **Why are these technologies appropriate for your solution?**
   
   - **General**: Natural Language Processing and Transformer Models to continue building on its capability to process large datasets and human input.  
   ***Compliance/Auditing**: Explainable AI - Explainable AI is used to describe an AI model, its expected impact and potential biases. It helps characterize model accuracy, fairness, transparency and outcomes in AI-powered decision making. Explainable AI is crucial for an organization in building trust and confidence when putting AI models into production. AI explainability also helps an organization adopt a responsible approach to AI development.  

   - **Safety**: Constitutional AI (anthropic.com): Constitutional AI (CAI) is an Anthropic-developed method for aligning general-purpose language models to abide by high-level normative principles written into a constitution. Anthropic’s language model Claude currently relies on a constitution curated by Anthropic employees.  

   - **Cybersecurity**: Graph Neural Networks - In response to this escalating challenge, the field of Artificial Intelligence (AI) has emerged as a promising ally in fortifying digital defenses. Among various AI techniques, Graph Neural Networks (GNNs) have garnered significant attention and acclaim for their ability to effectively tackle cybersecurity challenges. Cybersecurity is inherently a problem of graph analysis, as malicious activities in digital systems are interconnected and can form identifiable patterns. Graphs provide an intuitive and effective representation of these complex relationships, where nodes represent entities such as devices, users, or applications, and edges capture the connections and interactions between these entities. *


* Sources  
  
  https://www.crunchbase.com/organization/anthropic  
  https://aibusiness.com/verticals/eleven-openai-employees-break-off-to-establish-anthropic-raise-124m   
  https://en.wikipedia.org/wiki/Anthropic  
  https://claude.ai/upgrade  
  https://aimagazine.com/articles/anthropic-enters-gen-ai-arena-with-claude-enterpr  
  https://www.pymnts.com/artificial-intelligence-2/2023/report-anthropic-2024-revenue-could-approach-1-billion/  
  https://getlatka.com/companies/anthropic  
  https://sacra.com/c/anthropic/  
  https://www.gfmreview.com/technology/the-meteoric-rise-of-anthropic-valuation-and-the-future-of-ai  
  https://getlatka.com/companies/anthropic  
  https://www.rigb.org/explore-science/explore/blog/10-ai-milestones-last-10-years  
  https://www.pymnts.com/artificial-intelligence-2/2023/report-anthropic-2024-revenue-could-approach-1-billion/  
  https://www.cyberpointllc.com/blog-posts/  
  https://www.pymnts.com/artificial-intelligence-2/2023/report-anthropic-2024-revenue-could-approach-1-billion/  
  https://www.ibm.com/topics/explainable-ai  
  https://www.cyberpointllc.com/blog-posts/Graphing-the-Future-Harnessing-the-Power-of-Graph-Neural-Networks-for-CyberSecurity.php  
  https://www.ibm.com/topics/explainable-ai  

