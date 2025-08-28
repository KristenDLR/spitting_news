# spitting_news

This is a an AI agent, that is capable of automously performing tasks on behalf of a user by designing its workflow and itlizing available tools.

1. Pulls relevant news articles from the Serper API with a user prompt
2. Chain 1: Calls a model to check for pre-defined logical fallacies in a pandas dataframe
3. Chain 2: Calls the model again to output the result in 2 stages of analysis

