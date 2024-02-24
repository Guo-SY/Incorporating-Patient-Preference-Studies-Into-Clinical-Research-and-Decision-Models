# Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models


1. In the ChartPipeline, it includes two models: PDFigCapX model and ChartOCR



      1.1 If you just need to extract chart information, just run the code TablePipeline.ipynb

      # in the ModuleChartDataExtractionPipeline.ipynb


                  #main_chart(input_path="/content/ingresso",output_path="/content/uscita")
            
            
                  #input_path="/content/ingresso"
            
                  #output_path="/content/uscita"


  


2. In the ChartPipeline, it just run the code TablesPipe
   

     2.1 If you just need to extract table information, you can run the code ModuleChartDateExtraction.ipynb

     # in the TablesPipeline.ipynb

            # main_tables(input_path="/content/ingresso", output_path="/content/uscita")



             #input_path="/content/ingresso"
            
             #output_path="/content/uscita"



3. In the whole pipeline, just run the final code. GUI.ipynb


      %run /content/drive/MyDrive/ADSP_Project/Code/ChartPipeline/ModuleChartDataExtractionPipeline.ipynb
   
      %run /content/drive/MyDrive/ADSP_Project/Code/TablesPipeline.ipynb

      We provide a chat box for you, you just need type your inputpath and outpath, after that you could get your expected results 
      ![image](https://github.com/Guo-SY/Incorporating-Patient-Preference-Studies-Into-Clinical-Research-and-Decision-Models/assets/95298812/5e546c75-2087-4c9e-b169-9adc6770bb94)
   

   
