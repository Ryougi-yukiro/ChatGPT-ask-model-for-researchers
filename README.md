# ChatGPT-ask-model-for-researchers
一个用来给科研工作者们询问chatgpt的提问模板，包括rephase refine and aimed journals

<h1>模板一：中英文翻译及论文润色</h1>	

<font color=Blue>I want you to act as an English translator, spelling corrector and writing improver. I will speak to you in any language, and you will detect the language, translate it and answer in the corrected and improved version of my text, in English. You should use artificial intelligence tools, such as natural language processing, and rhetorical knowledge and experience about effective writing techniques to reply. I want you to replace my simplified A0-level words and sentences with more beautiful and elegant, upper-level English words and sentences. Keep the meaning same, but make them more logical, concise and powerful. I want you to only reply the correction, the improvements and nothing else, do not write explanations. My first sentence/paragraph is "XXX". </font>

可以指定特定的期刊发表风格
<font color=Blue>I want you to act as an English translator, spelling corrector and writing improver. I will speak to you in any language, and you will detect the language, translate it and answer in the corrected and improved version of my text, in English. You should use artificial intelligence tools, such as natural language processing, and rhetorical knowledge and experience about effective writing techniques to reply. I want you to replace my simplified A0-level words and sentences with more beautiful and elegant, upper-level English words and sentences. Otherwise, you should modify these sentences to imitate the langualage style published in the Nature Journal. Keep the meaning same, but make them more logical, concise and powerful. I want you to only reply the correction, the improvements and nothing else, do not write explanations. My first sentence/paragraph is "XXX". </font>

<h1>模板二：根据摘要和关键词生成论文题目</h1>	

<font color=Blue>I will provide you with the abstract and key words of a scientific paper in any language and you will detect the language and reply in the same language. Your task is to provide me with the title of the scientific paper based on the abstract and key words in the same language. The title of the scientific paper should be concise, clear and informative. You should avoid using wasted words such as “a study of,” “investigation of,” “development of,” or “observations on.” Make sure the title can grip the audience immediately. My abstract is” XX" My key words are "XXX."</font>


<h1>-模板三：论文期刊匹配</h1>	

<font color=Blue>I want you to act as a scientific manuscript matcher. I will provide you with the title, abstract and key words of my scientific manuscript, respectively. Your task is analyzing my title, abstract and key words synthetically to find the most related, reputable journals for potential publication of my research based on an analysis of tens of millions of citation connections in database, such as Web of Science, PubMed, Scopus, ScienceDirect and so on. You only need to provide me with the 15 most suitable journals. Your reply should include  the name of journal, the corresponding match score (The full score is ten). I want you to reply in text-based excel sheet and sort by matching scores in reverse order.
My title is "XXX" My abstract is” XX" My key words are "XXX"</font>


<h1>-模板四：精简文字</h1>	

<font color=Blue>I want you to act as a scientific refiner.  I will provide you with a paragraph from a scientific paper. Your task is to reduce the paragraph to the required words academically. You should use artificial intelligence tools, such as natural language processing, and rhetorical knowledge and experience about effective writing techniques to reply. I want you to replace my simplified A0-level words and sentences with more beautiful and elegant, upper-level English words and sentences. Keep the meaning same, but make them more logical, concise and powerful. My first paragraph is "XXX" Please refine the  paragraph to 100 words or less.</font>


<h2>	一些碎碎念：</h2>	
这是一个检测文章生成是否是AI写作的链接 [OPENAI](https://openai-openai-detector.hf.space/)。
Step1: 引导1:

I'm going to give you some information before asking you to write an article. Do you understand?



Step2: 引导2:

When it comes to writing content, two factors are crucial, "perplexity" and "burstiness." Perplexity measures the complexity of text. Separately, burstiness compares the variations of sentences. Humans tend to write with greater burstiness, for example, with some longer or complex sentences alongside shorter ones. Al sentences tend to be more uniform. Therefore, when writing the following content I am going to ask you to create, I need it to have a good amount of perplexity and burstiness. Do you understand?


Step3: 重写指令：

using the concepts written previously, rewrite this article with a high degree of perplexity and burstiness: 

####后续不定期更新（大概率是不会更新了）
