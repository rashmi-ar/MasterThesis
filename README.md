# Master Thesis
User Stress Levels Detection by Physiological Sensing and Deep Learning

## Abstract

* Stress is often associated with negative emotions and thoughts, which can affect the well-being of both the mind and body.
* To gain a better understanding of stress in educational settings, this study uses various methods to detect stress levels among students. Our goal is to gain a better understanding of the complex nature of stress in educational environments.
* We conducted an experiment with 25 participants, using an Empatica E4 wristband to record their physiological signals and determine their cognitive stress levels.
* Along with the relaxed or non-stressed condition, the study employed a range of simple to complex arithmetic tasks designed to elicit three levels of response:
  1) slightly stressed or easy level
  2) stressed or medium level
  3) highly stressed or hard level.
 
## Results

* To improve LOPO prediction accuracy, a fine-tuning or user-specific data calibration approach was utilized. This approach resulted in significant improvements in accuracy for LOPO.
  1) FCN model achieving 60% accuracy (F1=0.578)
  2) ResNet model reaching 85% (F1=0.846)
  3) LSTM model achieving an impressive 91% (F1=0.911) accuracy for three-class classification.
* A prototype application has been developed that effectively displays dynamic stress fluctuations by utilizing the insights gained from prediction outcomes upon user-specific data.
* The application includes a stress meter, which enables users to visually understand their stress levels.
* It also delivers personalized alert messages to individuals based on their stress levels to ensure timely support and intervention.

The experimental design and implementation can be found on [Stress_Detection_Experiment](https://github.com/rashmi-ar/stress_detection_experiment) and [Stress Detection Finetuning](https://github.com/rashmi-ar/stress_detection_finetuning)

