# Reddit_graph_analysis

We are trying to analyse the directed connections between two subreddits (a subreddit is a community on Reddit).
We also provide subreddit embeddings. The network is extracted from publicly available Reddit data of 2.5 years from Jan 2014 to April 2017.

Subreddit Hyperlink Network: the subreddit-to-subreddit hyperlink network is extracted from the posts that create hyperlinks from one subreddit to another. We say a hyperlink originates from a post in the source community and links to a post in the target community. Each hyperlink is annotated with three properties: the timestamp, the sentiment of the source community post towards the target community post, and the text property vector of the source post. The network is directed, signed, temporal, and attributed.

Note that each post has a title and a body. The hyperlink can be present in either the title of the post or in the body. Therefore, we provide one network file for each.
