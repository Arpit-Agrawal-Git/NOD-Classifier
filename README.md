# NOD-Classifier

#### Problem Statement:
Generating monthly appliance replacement reports is a time-consuming process, typically taking two days. The main challenge involves manually reading each observation and accurately classifying it under a pre-defined Nature of Defect (NOD) classification.

#### Solution:
To streamline this process, we implemented a Retrieval Augmented Classification approach. This method involves creating embeddings of observations from monthly reports over the past three years, as well as from the current report. By computing similarity scores between these embeddings, we can automatically assign the most similar NOD label to each observation in the current report.

#### Results:
This automation has significantly reduced the lead time for generating monthly appliance replacement reports—from two days to just 20 minutes. This improvement not only enhances efficiency but also ensures consistency and accuracy in classification across reports.


