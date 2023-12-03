

# PROJECT - Open-Ended Image Dataset Curation and Analysis

Congratulations on completing the theoretical part and applying your knowledge in the exercises in our notebooks.

## Project Details

Now it's time for our real-life full project. This project gives you a unique opportunity to bring everything together. Over four sprints, you will work on a project that combines various elements, commands, and lessons from the CORE track. This project is the ultimate test of your skills in this AI Bootcamp. You will review the project submissions of your peers, who have also been working on the same assignment for the past two months. Your feedback and evaluation will help grade their work. Participating in all phases —submitting your project and reviewing others' work— is essential and mandatory to receive feedback and a grade on the PROJECT track.

#### Objective
Learn how to curate an image dataset on a topic you're interested in and then analyze it. By following our step-by-step tutorials, you'll be able to create an image dataset using Google Images (or another image data source of your choice) and some powerful machine learning techniques. This open-ended project lets you explore and curate images related to a theme that interests you, providing hands-on experience in dataset creation, cleaning, and analysis.

#### Instructions:

1. **Choose a Theme or Subject of Interest**: Pick a theme or subject you're interested in. It could be anything like art, animals, plants, architecture, or abstract concepts. **Think about a problem you'd like to solve using image data**.

2. **Follow the CORE Tutorials**: Go to the [tutorial notebooks](https://github.com/andandandand/image-dataset-curation/tree/main/notebooks) and follow the instructions while using them on your dataset. These tutorials will guide you in collecting images from Google and organizing them into a usable dataset.

3. **Clean Your Dataset**: As you work through the [tutorial notebooks](https://github.com/andandandand/image-dataset-curation/tree/main/notebooks), curate the images according to your chosen theme. **This is the most important part of the task and will take most of your effort.** Focus on the quality and relevance of the images. If you plan to train an image classifier later (i.e., an algorithm to label the images you've downloaded), consider issues like mislabeled or duplicated images.

4. **Document Your Process**: Record the steps you took, any challenges you faced, and how you overcame them. This will help you reflect on your learning experience.

5. **Analyze and Reflect**: After curating your dataset, analyze the collection and reflect on what you've learned. Consider questions like:
   - What did you find interesting about the process?
   - How can we visualize the data to better understand it?
   - How can this dataset be used in an analytics project?
   - What ethical and practical considerations did you have while curating the dataset?

6. **Submit Your Work**: Give your curated and analyzed dataset to your mentors along with a presentation detailing your process, reflections, and any additional insights you gained from this task.

#### Evaluation Criteria
- Quality and relevance of the curated dataset.
- Adherence to the tutorial instructions.
- Creativity in choosing the theme or subject.
- Depth of reflection and analysis in the final report.

Here's how we would structure the task into four sprints, each lasting two weeks:

---

### Sprint 1: Introduction and Theme Selection

#### Week 1:
- **Day 1-2**: Introduction to the project. Overview of what dataset curation means and why it's crucial in machine learning and computer vision.
- **Day 3-4**: Brainstorming session. Discuss potential themes or subjects that students might be interested in.
- **Day 5-7**: Finalize the theme selection and have students think about the problem they want to solve with their dataset.

#### Week 2:
- **Day 1-3**: Introduction to web scraping for image collection.
- **Day 4-7**: Students start the tutorial to scrape a small set of images as a pilot.

#### Key Deliverables:
- Theme or subject selection.
- A pilot collection of images and their embeddings from a pretrained Resnet.
- An exploratory data analysis of the embedding space.
- A written plan on how the theme will be approached and what problem it aims to solve.
- Partial documentation through a project board in Github and Jupyter notebooks.
---

### Sprint 2: Data Collection and Classification Through Active Learning

#### Week 3:
- **Day 1-7**: Follow the tutorial on the notebook to scrape images. Students should aim to collect many images.

#### Week 4:
- **Day 1-4**: Start initial dataset cleaning. Remove irrelevant or inappropriate images. Use of CLIP's zero-shot learning for classification. 
- **Day 5-7**: Introduction to FastAI and its use for image classification and active learning.

####

 Key Deliverables:
- A dataset with many classified images.
- Initial cleaning completed.
- Partial documentation through a project board in Github and Jupyter notebooks.

---

### Sprint 3: Advanced Data Cleaning and Documentation

#### Week 5:
- **Day 1-2**: Introduction to Cleanlab and its features.
- **Day 3-7**: Use Cleanlab for advanced data cleaning.

#### Week 6:
- **Day 1-4**: Begin documenting the process, challenges faced, and solutions.
- **Day 5-7**: Use of Detectron2 for object detection and image segmentation (image metadata curation).

#### Key Deliverables:
- Advanced data cleaning completed.
- Partial documentation through a project board in Github and Jupyter notebooks.

---

### Sprint 4: Deployment, Final Analysis, Reflection, and Submission

#### Week 7:
- **Day 1-4**: Deploy an image similarity model through Qdrant and a FastAPI endpoint.  
- **Day 5-7**:  Reflect on what was learned during the project. Consider ethical and practical issues.

#### Week 8:
- **Day 1-3**: Finalize the report and dataset.
- **Day 4-7**: Peer reviews and project submission.

#### Key Deliverables:
- Completed cleaned dataset 
- Analysis of classification model performance vs dataset cleanliness and size 
- Comparison of trained classifiers vs zero-shot learning with CLIP
- Final report detailing the process, reflections, and additional insights  

#### Additional Resources
* [Object-oriented programming in Python for beginners (video)](https://www.youtube.com/watch?v=JeznW_7DlB0) and [recommended reading](https://realpython.com/python3-object-oriented-programming/).
* [Hasso Plattner Institute's Data Science Bootcamp ](https://open.hpi.de/courses/datascience2023)
* [MIT's Introduction to Data-Centric AI Course](https://www.youtube.com/watch?v=ayzOzZGHZy4)
* [An alternative method to download images using Bing Image Search](https://pyimagesearch.com/2018/04/09/how-to-quickly-build-a-deep-learning-image-dataset/).
* [FastAI notebooks](https://github.com/fastai/fastbook), please look at chapters 1 and 2 to understand how to build an image classifier. The code for these experiments can run on Google Colab.
* [Detectron2](https://github.com/facebookresearch/detectron2) Check out its [starter notebook](https://colab.research.google.com/drive/16jcaJoc6bCFAQ96jDe2HwtXj7BMD_-m5) for object detection and image segmentation in the images you've downloaded and curated. Think about questions you can answer by running an object detector on your data. How about counting the number of humans in a picture? Or if there are pools in a backyard picture?
* Remember to try [Cleanlab](https://github.com/cleanlab/cleanlab) on the images you've downloaded.
* Projects from other students:
	* [Art recommendation system](https://github.com/gargimaheshwari/Wikiart-similar-art)
	* [Bike-lane safety guide](https://www.youtube.com/watch?v=nNMmz6Ei9Qg)

## Ethics
Please ensure you adhere to ethical guidelines while curating your dataset. Consider privacy concerns related to the images you're collecting. Do not download copyrighted images.


