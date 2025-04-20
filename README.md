# Florence_2
Image analysis on Florence Model

## Files 
1. ms_coco_datadownload.ipynb - To download and store data in a particular format.

2. Analysis_of_correspondingobj.ipynb  - Calculating the accuracy, precision and recall for object detection task.

3. cococaptions.ipynb and sorted_captions_val2017.csv - Files to generate and store Ground Truth captions.

4. Florence 2 analysis. pdf - Demonstration of few results comparing model predictions(GT object detection marked in red bbox and predicted in orange bbox)

5. ground_truth and model_pred folders to store the calculated bboxes generated from the ms_coco_datadownload.ipynb file.

6. Visualizing_output - File to open and view the detected objects in given dataset alongwith model's predictions.

7. captions_val2017.json - Ground Truth captions. 

8. Image_captions_model.ipynb and generated_captions_model.csv
File to generate captions from model and storing captions in a .csv file.

9. matching_captions.ipynb - using BERT sentence transformer model('all-MiniLM-L6-v2') to calculate accuracy scores.


