# Political trends of main polish news portals

## Assumption
Polish media aren't objective and represent one of 2 mainstream political orientation.

Based on titles of the articles published on various polis news portals
we are able to classify what is the political direction represented.
The knowledge about political orientation is important because:
- we know which media we're keen to follow
- we know which of the media are objective
- we can evaluate media reliability 

# The algorithm
1. Prepare reference dataset - we often know that given media is oriented to one of the political party therefore we can select those pages and treat them as training dataset
2. Using NLP technique prepare the model of media - based on different methods we'll select the model that have highest accuracy of classification
3. Classify other selected media - we'll use the best model to classify other media for which the political direction isn't obvious
4. Analyze sentiment of the media - sentiment analysis for polish language is not yet standarized, experimental dataset will be used