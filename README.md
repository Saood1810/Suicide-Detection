# Suicide-Detection

According to the World Health Organization (WHO), approximately 703,000 people die by suicide each year. Suicide prevention is crucial, and timely detection is key. Many at-risk individuals express their feelings on social media platforms like X and WhatsApp. Detecting these signs can potentially save lives.
Thus, our topic is a form of semantic analysis whereby we detect whether a Reddit post is suicidal.

Our solution entailed training 3 models: LSTM, Bidirectional LSTM and Concurrent LSTM.LSTMs are special Artificial Neural Networks designed to recognise patterns in data sequences. They have an advantage over regular Neural Networks by having a special gated structure that allows them to remember certain information for long periods and forget irrelevant information, thus solving short-term problems. A bi-directional LSTM is an advanced version of a regular LSTM that captures information and recurrence from both forward and backward directions, which is useful for understanding sequences where context is important. The last model, Concurrent LSTM (CLSTM), combines the strengths of a Concurrent Neural Network and LSTM to process spatial and temporal data simultaneously and is often used in Video Analysis. The convolutional layers extract spatial information from input data, while the LSTM layers capture the temporal information. Although uncommon for semantic analysis, we trained a CLSTM, but we used Bidirectional LSTM Layers instead of regular LSTM layers.

All models trained had a testing accuracy of over 90%
