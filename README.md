Of course. After considering the CBSE pattern for Class 10 and ARTIFICIAL INTELLIGENCE (SUBJECT CODE 417)

CLASS X
SAMPLE QUESTION PAPER

Time Allowed: 40 Minutes
Maximum Marks: 20

General Instructions:

1. This question paper contains 9 questions.
2. Marks for each question are indicated against it.
3. Section A has Objective Type Questions.
4. Section B has Subjective Type Questions.
5. Section C has Case-Based/Application-Based Questions.

---

SECTION A - OBJECTIVE TYPE QUESTIONS (1 x 6 = 6 Marks)

1. Multiple Choice Questions (MCQs):
   (i) Which of the following is a metric used to evaluate a classification model's performance by measuring the ratio of correctly predicted positive observations to the total predicted positives?
       (a) Accuracy
       (b) Recall
       (c) Precision
       (d) F1 Score

(ii) In the context of Computer Vision, what is the primary purpose of 'Object Detection'?
       (a) To enhance the quality of an image.
       (b) To identify and locate objects within an image.
       (c) To classify the entire image into a single category.
       (d) To convert an image into a sketch.

2. Fill in the blanks:
   (i) A 3x3 grid used to perform operations like blurring or edge detection on an image is called a ________.
   (ii) The ________ is a single number that combines both Precision and Recall to give an overall performance measure of a model.

3. State True or False:
   (i) In a Confusion Matrix, the sum of all the elements gives the total number of predictions made by the model.
   (ii) Computer Vision enables computers to see, identify, and process images in the same way that human vision does.

---

SECTION B - SUBJECTIVE TYPE QUESTIONS (2 x 3 = 6 Marks)

4. Differentiate between Precision and Recall in the context of a model predicting whether an email is spam or not.
   (2 Marks)

5. What is the purpose of a 'Confusion Matrix'? List any two components of a 2x2 Confusion Matrix.
   (2 Marks)

6. How does a facial recognition system use Computer Vision? Name one real-world application of such a system.
   (2 Marks)

---

SECTION C - APPLICATION-BASED QUESTIONS (4 x 2 = 8 Marks)

7. Case Study: Smart Attendance System
   A school is using a smart attendance system where a camera captures a picture of the classroom, and an AI model identifies and marks the presence of students.

Based on the above, answer the following questions:
(i) Which specific field of Computer Vision is being used here: Image Classification, Object Detection, or Image Segmentation? Justify your answer.
   (2 Marks)

(ii) The model's performance report shows: High Precision but Low Recall. Explain what this means in the context of this attendance system. What is the practical consequence for the school?
   (2 Marks)

8. An AI model was built to identify images of cats and dogs. After testing on 100 images, the following data was collected:

· Correctly identified cat images: 35
· Correctly identified dog images: 50
· Images of cats mistakenly identified as dogs: 10
· Images of dogs mistakenly identified as cats: 5

(i) Create a Confusion Matrix for the given scenario. (Consider 'Cat' as the Positive class)
   (2 Marks)

(ii) Calculate the Accuracy of the model based on your confusion matrix.
   (2 Marks)

---

End of Question Paper

---

Answer Key / Marking Scheme (For Examiner's Use)

Section A (6 Marks)

1. (i) c - Precision
      (ii) b - To identify and locate objects within an image.
2. (i) Kernel (or Filter)
      (ii) F1 Score
3. (i) True
      (ii) True

Section B (6 Marks)

1. Precision: Of all emails predicted as spam, how many were actually spam. (Focus on correctness of positive predictions).
      Recall: Of all the emails that were actually spam, how many did the model correctly identify. (Focus on missing no spam).
      (1 mark for each correct definition)
2. Purpose: A table used to describe the performance of a classification model on a set of test data for which the true values are known.
      Components (Any two): True Positives (TP), True Negatives (TN), False Positives (FP), False Negatives (FN).
      (1 mark for purpose, 0.5 marks for each correct component)
3. How it works: It uses CV to capture a live image/video, detect human faces, analyze facial features (like distance between eyes, jawline), and compare them to a stored database of faces to identify a person.
      Application: Unlocking smartphones, Airport security, Facebook photo tagging.
      (1 mark for brief explanation, 1 mark for correct application)

Section C (8 Marks)

1. (i) Object Detection. Justification: The system needs to not just classify the image but also locate and identify multiple students (objects) within the classroom image.
       (1 mark for correct field, 1 mark for justification)
      (ii) High Precision: When the system marks a student present, it is very likely to be correct (very few false positives).
       Low Recall: The system is missing a significant number of students who are actually present (high number of false negatives).
       Consequence: Many students will be marked absent even though they are present, leading to inaccurate attendance records.
       (1 mark for explaining High Precision & Low Recall, 1 mark for consequence)
2. (i) Confusion Matrix (Cat as Positive):
    Predicted: Cat Predicted: Dog
   Actual: Cat TP = 35 FN = 10
   Actual: Dog FP = 5 TN = 50
   (2 marks for fully correct matrix, deduct 0.5 for each error)
   (ii) Accuracy = (TP + TN) / Total Predictions
          = (35 + 50) / 100
          = 85 / 100 = 0.85 or 85%
       (1 mark for formula/step, 1 mark for correct calculation)
