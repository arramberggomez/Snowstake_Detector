# Custom Data Creation
- Select 100 or more images from your field sites (snowstakes should have stripes).
- Use the VIA image annotator to draw bounding boxes.
- Export the annotations as a .csv file.
- Use the annotation_convert.py through the command line to convert annotations to YOLO format.
'''
python annotation_convert.py --via_path /path/to/via/csv --save_path /path/to/save
'''
- Divide data into train and valid folders (use about 10% of total data for validation).
- Within train & valid folders: images folder and labels folder.
- Follow convention image file: image_name.jpg and corresponding label file: image_name.txt
