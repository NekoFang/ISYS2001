This repository contains scripts for tracking various current weather data using the wttr.in API. 
The functions of the code is to forecast, as well as be able to visualise trend data for temperature and precipitation over a 3 day period. 

Documentation regarding AI conversations is found within the branch AI-Conversation

The code for the weather advisor is located in the James.Duong_weatherwise_notebook.ipynb under the Final Working Code heading
Necessary packages to run code within googlecolab are matplotlib and pyinputplus. The install and imports can be found at the start of the notebook underneath heading setup and imports
When running the code there will be 5 menu options: 
1. Check Forecast
2. Temperature Visualisation
3. Precipitation Visualisation
4. Ask a Question
5. Exit

Forecast, and the visualisation menu items will ask for an input of location and after giving a valid location will output the data or visualisations
Ask a question allows you to ask a weather question regarding either forecasting, temperature or precipitation and parse through the contents to derive the intent of the question.
Example questions would be "Is it going to be hot in Perth?", "Whats the weather like in London?", etc. 
Please feel free to experiment with the wording of questions, if the code is unable to identify the intent of the question an error message will be shown.

Whenever you feel like ending the program you can input "5", "exit" or "quit" in order to leave. 
