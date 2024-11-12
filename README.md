# MDC-FND
This is the Official implementation of "MDC-FND: A Multimodal and Context-Driven Approach to Fake News Detection"
We present MCD-FND (Multimodal Context-Driven Fake News Detection), a multimodal fake news detection model that effectively detects false news by combining social context and contextualizing multimodal characteristics. Textual and social context characteristics are extracted using BERT, while visual features are extracted using VGG-19.
# Dataset Structure
- id: the id of the post.
- statements/title: in the case of Instagram, the news title is the post's caption.
- comments: the top 50 comments on the post.
- timestamp: the published time.
- post_url: the URL of the post.
- likes_count: number of likes on a comment.
- username: name of the user who comments on the post.
- user_profile_url: the URL of the user profile who comments on the post.
- image_id: id of the images of a post.
- label: label of the post either fake or real.
