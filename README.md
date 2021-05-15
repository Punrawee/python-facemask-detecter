# python-facemask-detecter
## Running the project  
1. Open terminal. Go into the cloned project directory and type the following command: ``` > python3 train_mask_detector.py --dataset dataset ```  
2. To detect face masks in an image type the following command:  ``` > python3 detect_mask_image.py --image images/pic1.jpeg ```  
3.1 To detect face masks in real-time video streams type the following command: ``` > python3 detect_mask_video.py  ``` 
3.2 To detect face masks in an image on webapp type the following command: ``` > streamlit run app.py  ``` 


requirement 
tensorflow>=2.5.0* 
keras==2.4.3 
imutils==0.5.4 
numpy==1.19.5 
opencv-python==4.5.1.* 
matplotlib==3.4.1 
argparse==1.4.0 
scipy==1.6.2 
scikit-learn==0.24.1 
pillow==8.2.0 
streamlit==0.79.0


