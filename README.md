In attempting the dsps data competition, the model was trained with the first batch prepared by the organizers. The model was trained for 150 epochs with the data divided 15% for validation and 85% for training. The first layer was frozen in the execution of this first training stage. Following this, the second training batch of data labeled in cvat was added to the training data. In this training stage the previous last weights obtained were utilized as the initial weights for the second training stage. The data was divided into 80% for training and 20% for validation. In this stage, the model was retained for 20 epochs with the first 4 layers frozen. Test results with the final weights calculated showed a result of 65.8%


The figures below obtained from exp2 and exp3 show the training results from both training stages. 


Trainging stages results with hyperparemeter selections and optimization parameters, and labeled test data can be found in the folder labeled competition results
