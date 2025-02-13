# URL-based Phishing Detection using the Entropy of Non-alphanumeric Characters
Phishing URL Detection
--using Lexical Features

<!---
ESDAUNG/ESDAUNG is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

This is the implementation of my paper "URL-based phishing detection using the entropy of non-alphanumeric characters". The paper is published in iiWAS2019: Proceedings of the 21st International Conference on Information Integration and Web-based Applications & Services. Paper is available @.https://doi.org/10.1145/3366030.3366064

Phishing is a type of personal information theft in which phishers lure users to steal sensitive information. Phishing detection mechanisms using various techniques have been developed. Our hypothesis is that phishers create fake websites with as little information as possible in a webpage, which makes it difficult for content- and visual similarity-based detections by analyzing the webpage content. To overcome this, we focus on the use of Uniform Resource Locators (URLs) to detect phishing. Since previous work extracts specific special-character features, we assume that non-alphanumeric (NAN) character distributions highly impact the performance of URL-based detection. We hence propose a new feature called the entropy of NAN characters for URL-based phishing detection. Experimental evaluation with balanced and imbalanced datasets shows 96\% ROC AUC on the balanced dataset and 89\% ROC AUC on the imbalanced dataset, which increases the ROC AUC as 5 to 6\% from without adopting our proposed feature.
