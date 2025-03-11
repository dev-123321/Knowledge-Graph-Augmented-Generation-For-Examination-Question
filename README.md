# Knowledge-Graph-Augmented-Generation-For-Examination-Question
Although large language models (LLMs) exhibit robust generative capabilities for common tasks, their performance significantly declines in domain-specific tasks that require specialized knowledge and advanced reasoning abilities. The Examination Question Generation (EQG) task, which helps teachers and students acquire and understand new knowledge, plays a crucial role in educational applications. Existing methods rely on manually designed rules and human intervention, resulting in limited scalability and adaptability. To address these challenges, we propose a unified framework for EQG tasks incorporating four key components: domain-specific datasets, evaluation metrics, knowledge graphs, and generation methods. Specifically, we present a knowledge graph augmented generation (KAG) method for the EQG task, which generates examination questions and answers with external knowledge and graph reasoning ability and is easily transferable to other domains. Then, we propose a keyword-guided knowledge graph construction method, where these keywords can help extract more meaningful triples and enhance connections of related entities, thereby obtaining a 2D KG. Finally, we construct two new datasets and propose new metrics from both subjective and objective perspectives. Extensive experiments demonstrate that KAG can significantly outperform state-of-the-art baselines.

We used our dataset and generation methods to establish a system that can automatically generate test papers, aiming to relieve teachers' pressure and help learners consolidate knowledge.

You should download all the files, convert relationship.json to an SQL file and import it into MySQL.，and then run the app.py file in the experiment.  

Remember to configure the API interface of your own large language model.
 
 
