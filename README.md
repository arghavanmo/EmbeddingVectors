# EmbeddingVectors
This is a replication package for the article 
<a href="https://arxiv.org/abs/2207.05132"><strong>Dev2vec: Representing Domain Expertise of Developers in an Embedding Spac</strong></a>
    
This is a repository to encode the expertise of developers, learned from different source of information, into embedding vectors.<br />
These vectors are learned from three different doc2vec models. We call these models dev2vec.<br />
We use three different types of information to train these models: repositories meta-data, issue resolving history and API calls used by developers. <br />
We name these methods: dev2vec:repos, dev2vec:issues and dev2vec:APIs
