# Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models

## How to prepare the code
After downloaded the code of PDFigCapX in this github repository and downloaded the code of ChartOCR in this repository: https://drive.google.com/drive/folders/11e1d-zDKTjlyr7FcyLpiuVeSG4XL0d4A?usp=sharing      , in ModuleChartDataExtractionPipeline change this following path:

 
1. Inside the Deeprule directory you have to look for the path of this 2 directory:  
      DeepRule/models/py_utils/_cpools
      DeepRule/external

   Then you have to change the path in the code you can see in the figure with these 2 path that you find and the path of the DeepRule directory
   ![1](https://github.com/Guo-SY/Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models/assets/33226736/74ab38b7-19da-497a-8871-fbbaf9e7f996)

2. Inside the PDFigCapX directory you have to look for the path of this python file: PDFigCapX/code/FigCap.py , and then you have to change the path in main_chart() with the one you found.

![2](https://github.com/Guo-SY/Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models/assets/33226736/a682e47e-f574-46c8-8bb1-855ed986fc56)

3. Inside the chartOCR_on_imgs() method you have to change the path of the DeepRule directory

![3](https://github.com/Guo-SY/Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models/assets/33226736/6f19b4bc-c575-48db-b357-402d11f85baa)



## How to run the code


1. In the ChartPipeline, it includes two models: PDFigCapX model and ChartOCR



      1.1 If you only require the extraction of chart data, simply execute the script named TablePipeline.ipynb.


   Run ./Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models/ChartPipeline/ModuleChartDataExtractionPipeline.ipynb


                  #main_chart(input_path="/content/ingresso",output_path="/content/uscita")
            
            
                  #input_path="/content/ingresso"
            
                  #output_path="/content/uscita"


  


3. In the ChartPipeline, it just run the code TablesPipe
   

     2.1 If you only require the extraction of chart data, simply execute the script named ModuleChartDateExtraction.ipynb

     Run ./Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models/ChartPipeline/TablesPipeline.ipynb

            # main_tables(input_path="/content/ingresso", output_path="/content/uscita")



             #input_path="/content/ingresso"
            
             #output_path="/content/uscita"



4. In the whole pipeline, just run the final code GUI.ipynb


      In the Final GUI.ipynb, we offer a chat box feature allowing you to input your desired input and output paths, subsequently generating the anticipated results.
   
      ![image](https://github.com/Guo-SY/Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models/assets/95298812/5e546c75-2087-4c9e-b169-9adc6770bb94)
   

   
