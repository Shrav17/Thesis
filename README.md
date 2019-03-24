# Thesis
Final sem - Project

Estimation of Story points in Agile framework using Deep learning Technique

Applied methodology:
  * 14 CSV file indicating 14 open source project description
  * Input to the model : Issue Title, Issue Description
  * Output:
    For classification: Categorizing into high, medium and low based on complexity involved into it
    For Regression: Estimated story point value
    
  * Applied Glove embedding for pre-processing (Glove_300 Dimension)
  * Bidirectional RNN with GRU units, backend of Tensorflow
  
