README

Group19_Music_Genre_Prediction

* File Descriptions

File/Folder 				    | Description

Group19_presentation.mp4		| Presentation video
Group19_Presentation_Slides.pdf	| Presentation slides
Group19_Report			        | Final report
Datasets 				        | Include data files in CSV, including: (1) Raw data, (2) Cleaned data, and (3) test_output used in the ensemble model
Python codes				    | Include Python Notebook codes for: (1) Data preprocessing, (2) Data Analysis, and (3) all Neural Network Models we included in the report

 To tackle the multimodal music genre classification task, we adopted a progressive and
 systematic modeling strategy. We began by building baseline models that use only single
 modalities — a simple MLP based on audio features and a CNN based on lyrics — to
 establish reference performance levels for each modality independently. Next, we explored
 feature fusion models, combining audio and lyrics representations through concatenation and
 joint learning, aiming to leverage complementary information between modalities.
 To better capture sequential and contextual dependencies within lyrics, we implemented
 sequence models, including BiLSTM, GRU and Transformer encoder architectures. Recognizing the potential of pre-trained language models, we further fine-tuned BERT represen
tations of lyrics, and combined them with ensemble methods such as Random Forest and
 MLP classifiers.
 Through this stepwise exploration, we aim to systematically assess the impact of different
 modalities, fusion strategies, and architectural choices on the music genre classification task.
