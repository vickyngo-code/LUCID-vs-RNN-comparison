# LUCID-vs-RNN-comparison
Comparison between LUCID model developed by Doriguzzi-Corin et al. (2020) and a RNN model developed by Jake Fawcett as part of his BEng degree. The source codes are included below. Primary comparison metrics are data preprocessing time, training time and detection time.

RNN source code:
https://github.com/Jake-Fawcett/NN-for-DDoS

LUCID source code:
https://github.com/doriguzzi/lucid-ddos

# Description
This project implements the two models in Google Colab as two .ipynb files. Both models were trained using the CICDDoS2019 set for 03-11 (first day). Detailed implementation and data preprocessing can be found in the uploaded report.

While the script for LUCID implementation in this repository is original, the script for the RNN came from the source repository with some minor adjustments. This includes some additional commands for printing results and graphings. If you would like to reproduce the results, make sure to adjust the datasets file directory as appropriate. For more information on the two models, refer to the source code above.

# Acknowledgements
Firstly, thank you for Dr. Roopak Sinha for being my primary supervisor for this project, as well as for my thesis. Thank you to Dr. Mahsa Mohaghegh, who has helped me come up with the primary idea for this project, alongside Dr. Sinha.

Thank you to the amazing individuals, Mr. Fawcett and Mr. Doriguzzi-Corin and his colleagues for making the codes open-source and available for all to use.

For anyone looking to reproduce the results, please feel free to do so. While this is simply an implementation and comparison of two ready made models, I hope it can provide an adequate reference for anyone who might need it.
