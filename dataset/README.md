The following is a brief documentation of each dataset

## MTurks_ratings.csv
**id_news_article**: the id of the news article. The data visualizatios of the same id are extracted for the same news article. 

**image_url**: the URL to the image file of the data visualization.

**commons_url**: the URL to the Wikimedia Commons' page of the data visualization

**avg_rank**: the average of Amazon Mechanical Turks' ratings.

**median_rank**: the median of Amazon Mechanical Turks' ratings. 

**rank_var**: the variance of the Amazon Mechanical Turks' ratings. 

**content-WPtitle**: a feature that is used to train the ranker. It's the semantic relatedness score (as defined by Explicit Semantic Analysis) between the news article content and the title of the Wikipedia article that contains the candidate image. 

**content-caption**: a feature that is used to train the ranker. It's the semantic relatedness score between the news article content and the visualization caption written by the editors of the Wikipedia article in which the image is used (the article identified in the Stage 1). Note that even though metadata for images is sparse and can be inaccurate in the Wikimedia commons, almost all images have a caption when they are included in Wikipedia.

**title-caption**: the semantic relatedness score between the news article title and the visualization caption.
