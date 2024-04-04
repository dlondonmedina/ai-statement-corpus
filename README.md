# Corpus of University Statements on Generative AI

This is the corpus of University Statements on Generative AI. It contains the statements from universities from the United States, Canada, Great Britain, Australia, and New Zealand collected in late March 2024. Data was gathered with a python webscraping tool that used Google API to search for statements. It finds the first relevant result and scrapes the paragraphs out of the page. The data were then manually cleaned to remove extraneous data and to check that the content is actually an official statement on generative AI. 

The data are stored in individual text files in the `/data/` folderthat follow this format:
* Line 1: The name of the University or College
* Line 2: The URL from which the statement was scraped
* Line 3+: The contents of the statement

## Contributing
We are currently seeking contributions to this resource. To make a contribution:
1. Fork the original repository.
2. Add additional entries or modify existing entries.
3. Submit a pull request and we will review it.

We are also looking for people to collaborate on building this corpus. This means we are looking for people to commit to reviewing pull requests. We are also looking for people to help preprocess the data so that they can be shared in a state more prepared for NLP and ML tasks. Some knowledge of Python is necessary for this second task.

If you're interested in collaborating on the production of this corpus, please DM one of the administrators. 
