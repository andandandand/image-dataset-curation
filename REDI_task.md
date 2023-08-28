### Task: Open-Ended Image Dataset Curation

#### Objective
In this task, you will learn how to curate a dataset of images on a subject of your interest. By following a step-by-step tutorial, you will be able to create an image dataset using Google Images and some machine learning. This open-ended project allows you to explore and curate images related to a theme that intrigues you, providing a hands-on experience in dataset creation, cleaning, and management.

#### Instructions:

1. **Choose a Theme or Subject of Interest**: Select a specific theme or subject that you are interested in. It could be anything from art, animals, plants, architecture, or even abstract concepts. **Think about a problem that you would like to solve and how it would benefit from using image data**. 

2. **Follow the Image Scraping Tutorial**: Navigate to the [tutorial on PyImageSearch](https://pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/) and follow the instructions provided. This tutorial will guide you through the process of collecting images from Google and organizing them into a usable dataset.

3. **Clean Your Dataset**: As you follow the [tutorial notebooks](https://github.com/andandandand/image-dataset-curation/tree/main/notebooks), curate the images according to your chosen theme. **This is the most important part of the task and where most of your effort will go.** Pay attention to the quality and relevance of the images. If you train an image classifier, consider issues such as mislabeled or duplicated images. 

4. **Document Your Process**: Keep a record of the steps you took, any challenges you faced, and how you overcame them. This will help you reflect on your learning experience.

5. **Analyze and Reflect**: Once you have curated your dataset, analyze the collection, and reflect on what you have learned. Consider questions such as:
   - What did you find interesting about the process?
   - How can this dataset be used in an analytics project?
   - What considerations (ethical and practical) did you take into account while curating the dataset?

6. **Submit Your Work at the End of each Sprint**: Provide the curated dataset to your mentor along with a report detailing your progress, reflections, and any additional insights you gained from this task.

Here's how we will structure the task into four sprints, each lasting two weeks:

---

### Sprint 1: Introduction and Theme Selection

#### Week 1:
- **Day 1-2**: Introduction to the project. Overview of what dataset curation means and why it is crucial in machine learning and computer vision.
- **Day 3-4**: Brainstorming session. Discuss potential themes or subjects that students might be interested in.
- **Day 5-7**: Finalize the theme selection and have students think about the problem they would like to solve with their dataset.

#### Week 2:
- **Day 1-3**: Introduction to web scraping for image collection. Brief overview of the tutorial on PyImageSearch.
- **Day 4-7**: Students start following the tutorial to scrape a small set of images as a pilot.

#### Key Deliverables:
- Theme or subject selection.
- A pilot collection of images.
- A written plan on how the theme will be approached and what problem it aims to solve.

---

### Sprint 2: Data Collection and Initial Cleaning

#### Week 3:
- **Day 1-7**: Follow the PyImageSearch tutorial to scrape images. Students should aim to collect a substantial number of images.

#### Week 4:
- **Day 1-4**: Begin initial dataset cleaning. Remove any irrelevant or inappropriate images.
- **Day 5-7**: Introduction to FastAI and how it can be used for image classification.

#### Key Deliverables:
- A dataset with a substantial number of images.
- Initial cleaning completed.

---

### Sprint 3: Advanced Data Cleaning and Documentation

#### Week 5:
- **Day 1-2**: Introduction to Cleanlab and its functionalities.
- **Day 3-7**: Use Cleanlab for advanced data cleaning.

#### Week 6:
- **Day 1-4**: Begin documenting the process, challenges faced, and how they were overcome.
- **Day 5-7**: Introduction to Detectron2 and how it can be used for object detection.

#### Key Deliverables:
- Advanced data cleaning completed.
- Partial documentation.

---

### Sprint 4: Final Analysis, Reflection, and Submission

#### Week 7:
- **Day 1-4**: Complete the documentation and start the analysis of the curated dataset.
- **Day 5-7**: Reflection on what was learned during the project. Consider ethical and practical considerations.

#### Week 8:
- **Day 1-3**: Finalize the report and dataset.
- **Day 4-7**: Peer reviews and project submission.

#### Key Deliverables:
- Completed analysis using clustering or a supervised learning approach (e.g., classification, detection, segmentation).
- Final report detailing the process, reflections, and additional insights.

---

By breaking the task into these four sprints, students can gradually build their skills while staying organized and focused. The key deliverables at the end of each sprint will help ensure that everyone is on track and achieving the objectives set out in the task description.

#### Evaluation Criteria
- Quality and relevance of the curated dataset.
- Adherence to the tutorial instructions.
- Creativity in choosing the theme or subject.
- Depth of reflection and analysis in the final report.

#### Additional Resources
* [An alternative method using Bing Image Search](https://pyimagesearch.com/2018/04/09/how-to-quickly-build-a-deep-learning-image-dataset/)
* [FastAI notebooks](https://github.com/fastai/fastbook), please have a look at chapters 1 and 2 to understand how to build an image classifier. The code for these experiments can be run on Google Colab
* [Detectron2](https://github.com/facebookresearch/detectron2) Check out its [starter notebook](https://colab.research.google.com/drive/16jcaJoc6bCFAQ96jDe2HwtXj7BMD_-m5) to work with object detection and image segmentation in the images that you have downloaded and curated. Think about the questions that you can answer by running an object detector on your data. How about counting the number of humans in a picture? Or if there are pools in the picture of a backyard? 
* Try [Cleanlab](https://github.com/cleanlab/cleanlab) on the images that you have downloaded
* Projects from other students:
	* [Art recommendation system](https://github.com/gargimaheshwari/Wikiart-similar-art)
	* [Bike-lane safety guide](https://www.youtube.com/watch?v=nNMmz6Ei9Qg)
  

#### Note
Please ensure that you adhere to ethical guidelines and legal requirements while curating the dataset. Respect copyright laws and consider privacy concerns related to the images you are collecting.
