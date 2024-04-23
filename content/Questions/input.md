---
section: Questions 
nav_order: 3
title: Questions related to the GenAI input
topics: Questions; Input; GenAI
---


- **❓Where does all data used by GenAI models and tools come from and what about its copyright status?**
    - Many datasets used for the training of AI models are derived from scraping **publicly accessible and available** datasets on the internet.
        - Scraping is generally performed **without a licence from the copyright owners**, and may be contrary to the terms and conditions of the websites on which content is hosted.
        - The scrapping and extraction of relevant information from underlying datasets, which often contain copyright protected works, and thus subject to restrictions on processing under data protection law, rises potential liability for infringing copyright in the underlying training materials.
        - The scraping of text data from the internet frequently involves also the collection of a significant volume of personal data or data that relates to identifiable individuals, which is protected by the EU and UK GDPR (as well as by other data privacy regimes around the globe).
    - By contrast, some tools have been trained on **fully-licensed datasets with relevant documentation**.
- **❓Whose responsibility is to investigate for the data’s copyright status used by GenAI models/tools? The developer’s/creator’s or the user’s?**
    
    [Well, everybody’s, to be honest]
    
    The potential liability of developers of genAI models – and in some cases the users of genAI tools – for infringing third party copyright in the underlying training data depends on the specific implementation of the AI model and its training process and the source of the training datasets (see also below the TDM sections).
    
    If the datasets’ provenance and copyright status is not clearly mentioned by the developer of the AI model/ tool , then it’s really difficult to gain a deep understanding of these datasets.
    
    Dataset creators and AI developers often lack to commit to dataset transparency and recordkeeping requirements (aka standardized process for documenting datasets, their provenance and copyright status).
    
    There is currently a lack of investigatory methods able to identify all the necessary information we need to understand datasets’ status, especially in a copyright, intellectual property and data protection context.
    
    However, this is fast-developing area of research and regulation. See here for the recent [Knowledge machine's claim](https://knowingmachines.org/publications/knowing-legal-machines/essays/USCO-comments) for “evidence-based research concerning the nature of training datasets and their role in GenAI outputs, minimizing the influence of conjecture in the policymaking process” and their [proposal](https://knowingmachines.org/docs/legal_knowing_machines/Knowing_Machines_-_USCO-Comment_10-30-23.pdf) for a *training dataset investigatory tool .*
    
- **❓Can data (including GLAM collections) be mined to train an AI algorithm without asking rights holders for permission? {under development}**
    
    Yes.
    
    AI tools and models are consuming large amounts of data, including creative works and data, as part of their learning process. 
    
    There might be a number of potential scenarios here:
    
    1. **public domain datasets [the dream scenario]**
    2. **text and data mining (TDM) exceptions [the so-so scenario]**
    3. **copyright infringement [the bad scenario]**
    
- **❓How can a dataset’s holder/creator apply for an opt-out ?**
    
    **TDM opt-out technical solutions**
    
- **❓Are copies of the works/assets in the dataset stored in the trained model?**
    
    probably, yes.
    
    The legal community does not have a clear understanding of how individual works from a dataset are stored and represented in a trained model. If the individual works are represented in some specifically identifiable way, that might strengthen the case for copyright infringement. In contrast, if the works are significantly abstracted in the model, it might weaken that same case, as it is less likely that a court will find the abstracted version to be a “copy” in the same sense as when one downloads a copy of a file.
    
    Technically many training datasets do not contain the training content themselves but instead provide links for those who train systems to pull the content from external servers across the internet at the time of training. (via https://knowingmachines.org/knowing-legal-machines/legal-explainer/questions/can-gen-ai-companies-train-their-systems-on-things-i-made )
    
- **Is it legal to train AI on openly licensed digital material where attribution is required? {under development}**
    
    it depends
    
    https://creativecommons.org/2021/03/04/should-cc-licensed-content-be-used-to-train-ai-it-depends/
    
- **❓When I use GenAI products like ChatGPT, can they collect my data?**
    
    Probably, yes
    
    As you use GenAI products, the data you provide and generate becomes ‘training data’ to improve the GenAI models and make its responses more accurate.  As a result, hundreds of millions of prompts and input data are likely stored ****at present. This demand for more data has fueled the "Big Data" phenomenon over the last decade. In turn, t**his Big Data forms the core of GenAI : GenAI products leverage this wealth of data as their foundation**. 
    
    The **data privacy** concerns associated with GenAI products are not novel and echo similar issues encountered with previous machine learning technologies (’old fears, new problems’). These concerns are compounded by prior failures to enact comprehensive data regulations, that could have safeguarded personal data before the emergence of GenAI models and tools.
    
- **❓And what does ‘my data’  mean in this context?**
    
    There are a lot of different types of information about you that GenAI products collect and process when you interact with them, and the specifics often depend on which product you are using.
    
    Generally speaking, there are two categories of “user data”:
    
    - **Inputs**: Public or private data that you input into the product, including your prompts, conversations, uploaded images, voice recordings, or other inputs.
    - **Metadata**: Account-level information or data auch as
        - **Geolocation data**
        - **Network activity information**
        - **Commercial information e.g. transaction history or** account information if you purchase a subscription to the product.
        - **Contact details** , email, name, phone number
        - **Device and browser cookies**
        - **Device information,** including the name of the device, operating system, and browser you are using
        - **Log data (IP address etc.)**
        
        -OpenAI says in its privacy policy that the company discloses the types of information listed above to its “affiliates, vendors and service providers, law enforcement, and parties involved in Transactions.” 
        
        -In addition, **companies can extract information about you** if you interact with itheir social media pages, based on the aggregated user analytics made available to businesses by the likes of Facebook, Instagram, and Twitter.
        
- **❓Can I remove my personal data or copyrighted data from GenAI training datasets (**when you do not know if this data is even there)**?**
    
    
    probably not (see also the [Knowing machines extended answer](https://knowingmachines.org/knowing-legal-machines/legal-explainer/questions/can-i-remove-my-personal-data-from-genai-training-datasets) on this )
    
    For now, many [](https://www.zdnet.com/article/with-gpt-4-openai-opts-for-secrecy-versus-disclosure/)tech companies creating GenAI products do not disclose whether their models were trained with any protected content or their training sources in general. There is no foolproof protocol, guidelines or system to force companies to disclose whether, how much, and what kinds of your personal data have been used as training data for their GenAI products. Recent developments in AI copyright legislation, both in EU and UK, force AI model developers for full transparency on their training sources (see the **transparency provision at AIA** , as described above) - however, is still really difficult to achieve this.
    
    Even if there was a way, however, there is currently no legal standard route neither a technical foolproof way to express a machine-readable rights reservation ( as per **the opt-out option** at the ****Article 4 of the CDSM Directive as described above ). In addition, it’s [technically impossible](https://arxiv.org/pdf/1912.03817.pdf) to fully remove data from training datasets without influencing deep learning models in unpredictable ways. This issue is of regulatory concern for big players like Google, which announced a “[Machine Unlearning Challenge](https://blog.research.google/2023/06/announcing-first-machine-unlearning.html) between mid-July and mid-September 2023. According to Google, the challenge involved “a realistic scenario in which an age predictor has been trained on face images, and, after training, a certain subset of the training images must be forgotten to protect the privacy or rights of the individuals concerned.” 
    
- **❓What are the risks of a GenAI system saving my data?**
    
    When a genAI system or tool saves your data, the primary risk is that it will result in a **data leak or a data breach.** Even a common Q&A with ChatGPT can entail data security risks. These include:
    
    - GenAI model training from your data and sharing sensitive information, such as intellectual property or personally information
    - OpenAI itself becoming a victim of a data breach, exposing the data  users like you have submitted unintentionally.

