GraniteVille Train Crash Analysis

The Graniteville train crash was an American rail disaster that occurred on January 6, 2005, in Graniteville, South Carolina.

Datasets
          
          * Patients Dataset - 1,100,000 observations with 79 symptoms
          
          
            ['abdom_discomfort', 'abdom_distension', 'agitation', 'arrhythmia',
       'blistering', 'bloody_nose', 'bradycardia',
       'cardiovascular_hypoxia_cyanosis', 'chest_discomfort', 'chest_pain',
       'chills', 'congestion', 'constricted_pupils', 'coughing_blood',
       'cyanosis_blue', 'diarrhea', 'dilated_pupils', 'dizziness',
       'drooling_salivation', 'drowsiness', 'dry_mouth_throat', 'dry_skin',
       'eye_irritation_redness', 'eye_swelling', 'fatigue_weakness',
       'frostbite', 'headache', 'hearing_loss', 'high_body_temp',
       'hypertension', 'hypotension_shock', 'impaired_vision',
       'irregular_breathing', 'itching', 'jaundice_yellow',
       'lack_of_coordination', 'light_sensitivity', 'low_body_temp',
       'lowered_mental_state', 'mouth_coughing_choking', 'mouth_irritation',
       'nasal_irritation', 'nausea', 'neurological_numbness_tingling',
       'nose_sneezing', 'pale', 'paralysis', 'peeling_exfoliation',
       'pulmonary_edema', 'rapid_breathing', 'rash', 'resp_burning_irritation',
       'respiratory_arrest', 'respiratory_coughing_choking',
       'respiratory_hypoxia_cyanosis', 'respiratory_sneezing', 'runny_nose',
       'shivering', 'shortness_of_breath', 'skin_burns_burning',
       'skin_numbness_tingling', 'skin_redness', 'skin_swelling',
       'slow_breathing', 'slurred_speech', 'spasms_seizures', 'sweating',
       'tachycardia', 'tearing', 'throat_irritation', 'tinnitus',
       'unresponsive', 'urinary_incontinence', 'urinary_pain_burning',
       'urination_bloody', 'vision_loss', 'vomiting', 'vomiting_blood',
       'wheezing']

        * chemicals dataset ( chemical ID, 79 symptoms) 
        
        ['chemical_ID', 'abdom_discomfort', 'abdom_distension', 'agitation',
       'arrhythmia', 'blistering', 'bloody_nose', 'bradycardia',
       'cardiovascular_hypoxia_cyanosis', 'chest_discomfort', 'chest_pain',
       'chills', 'congestion', 'constricted_pupils', 'coughing_blood',
       'cyanosis_blue', 'diarrhea', 'dilated_pupils', 'dizziness',
       'drooling_salivation', 'drowsiness', 'dry_mouth_throat', 'dry_skin',
       'eye_irritation_redness', 'eye_swelling', 'fatigue_weakness',
       'frostbite', 'headache', 'hearing_loss', 'high_body_temp',
       'hypertension', 'hypotension_shock', 'impaired_vision',
       'irregular_breathing', 'itching', 'jaundice_yellow',
       'lack_of_coordination', 'light_sensitivity', 'low_body_temp',
       'lowered_mental_state', 'mouth_coughing_choking', 'mouth_irritation',
       'nasal_irritation', 'nausea', 'neurological_numbness_tingling',
       'nose_sneezing', 'pale', 'paralysis', 'peeling_exfoliation',
       'pulmonary_edema', 'rapid_breathing', 'rash', 'resp_burning_irritation',
       'respiratory_arrest', 'respiratory_coughing_choking',
       'respiratory_hypoxia_cyanosis', 'respiratory_sneezing', 'runny_nose',
       'shivering', 'shortness_of_breath', 'skin_burns_burning',
       'skin_numbness_tingling', 'skin_redness', 'skin_swelling',
       'slow_breathing', 'slurred_speech', 'spasms_seizures', 'sweating',
       'tachycardia', 'tearing', 'throat_irritation', 'tinnitus',
       'unresponsive', 'urinary_incontinence', 'urinary_pain_burning',
       'urination_bloody', 'vision_loss', 'vomiting', 'vomiting_blood',
       'wheezing']
       
       
Business Objectives
 
        * To find out the right chemical to which patient was exposed as the result of this crash
    
              # There can be multiple chemicals to which the patient is exposed to.
                But in this analysis, we will consider the chemical which has most similarity
                In case of a tie, we randomly pick any anyone
                
         * To find out minimum number of symptoms , maintaining 80% accuracy.
                
                #This will help in identifying the chemical at minimum time in case of future accidents
                
Concepts Used :
 
          # Similarity metrics (Eucledian, Jaccards, Hamming, Simple Matching coefficients )
          # Sampling Techniques (Down Sampling)
          # Random Forest Classifier
          
Programming Language Used : Python
 
Libraries used  : 

            pandas 
            numpy
            seaborn
            scipy
            matplolib
            sklearn
            PythonImagingLibrary(PIL)
                
