![OPEN-ARC title image](https://github.com/Infinitode/OPEN-ARC/blob/main/open-arc.jpg?raw=true)

# OPEN-ARC
## Open-source Platform for Engineering Neural Architectures and Research Collaboration

Welcome to **OPEN-ARC**, an open-source initiative to further AI research through collaboration. This repository contains base model files and folders for various problem sets, each accompanied by a challenge and linked Kaggle notebooks to run the models. Users can link their own notebooks to the challenges, share their findings, and help improve AI models to help solve problems in various fields and further research enhancement.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Available Projects](#available-projects)
- [Sharing Progress](#sharing-progress)
- [Uploading Models and Sharing Code](#uploading-models-and-sharing-code)
- [License](#license)

## Introduction
OPEN-ARC aims to democratize AI research by providing a collaborative platform where users can:
- Access and work on various AI problem sets.
- Contribute their own solutions and improvements.
- Learn from others' approaches and findings.
- Help improve AI models for real-world applications and communities.

## Installation
To get started with OPEN-ARC, clone the repository or start from your own notebook either locally or in Kaggle or Colab using the provided datasets.

```bash
git clone https://github.com/infinitode/open-arc.git
cd open-arc
```

## Usage
Each project folder contains our:
- Base model files.
- Instructions for running the models.
- Linked Kaggle notebooks for each challenge.

To run a model, navigate to the respective project folder and follow the instructions in the README.md file located there. You can also run the Kaggle notebook, either locally or in Kaggle/Colab (note that we will primarily use Kaggle Datasets, which means that you'd have to obtain the datasets either from Kaggle, or another source, in order to run the code locally or in Colab), and follow the steps inside.

We only provide the base models, and the basic code implementations, this is where the power of community comes in. You can either improve the base code, or write your own. Then, others can learn from your implementation, therefore furthering research, and helping communities world-wide.

## Contributing
We welcome contributions from the community. To contribute to the project:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push them to your branch.
4. Create a pull request detailing your changes.

To keep our community safe, please ensure your contributions adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

## Available Projects
Here are some of the current projects available in OPEN-ARC:

### Project 1: Liver Cirrhosis Stage Classification
- **Challenge:** Predict the stage of liver cirrhosis, to help medical experts quickly assess a patient's condition.
- **Dataset:** [Liver Cirrhosis Stage Classification 🩺](https://www.kaggle.com/datasets/aadarshvelu/liver-cirrhosis-stage-classification)
- **Kaggle Notebook:** [Link to Notebook](Project-1-LCSC/project-1-lcsc.ipynb)
- **Instructions:** Detailed instructions on running the model are available in the project's README.

#### Leaderboard (Top 5)

| Rank | Contributor | Architecture Type | Platform | Base Model | Dataset | Accuracy | Link |
|------|-------------|-------------------|----------|------------|---------|----------|------|
| N    | Our Model   | RandomForestClassifier             | Kaggle    | ✗        | Liver Cirrhosis Stage Classification 🩺 | 95.6%    | [Notebook](https://github.com/Infinitode/OPEN-ARC/Project-1-LCSC/project-1-lcsc.ipynb) |

---

### Project 2: Weather Type Classification
- **Challenge:** Classify the type of weather using 10 different weather data features.
- **Dataset:** [Weather Type Classification](https://www.kaggle.com/datasets/nikhil7280/weather-type-classification)
- **Kaggle Notebook:** [Link to Notebook](Project-2-WTC/project-2-wtc.ipynb)
- **Instructions:** Detailed instructions on running the model are available in the project's README.

#### Leaderboard (Top 5)

| Rank | Contributor | Architecture Type | Platform | Base Model | Dataset | Accuracy | Link |
|------|-------------|-------------------|----------|------------|---------|----------|------|
| N    | Our Model   | RandomForestClassifier             | Kaggle    | ✗        | Weather Type Classification | 91.2%    | [Notebook](https://github.com/Infinitode/OPEN-ARC/Project-2-WTC/project-2-wtc.ipynb) |

---

### Project 3: Potato Plant Disease Classification
- **Challenge:** Classify potato plant diseases based on image/vision data.
- **Dataset:** [🌱 Potato Plant Diseases Data 🍂](https://www.kaggle.com/datasets/hafiznouman786/potato-plant-diseases-data)
- **Kaggle Notebook:** [Link to Notebook](Project-3-PPDC/project-3-ppdc.ipynb)
- **Instructions:** Detailed instructions on running the model are available in the project's README.

#### Leaderboard (Top 5)

| Rank | Contributor | Architecture Type | Platform | Base Model | Dataset | Accuracy | Link |
|------|-------------|-------------------|----------|------------|---------|----------|------|
| N    | Our Model   | CustomCNN             | Kaggle    | ✗        | 🌱 Potato Plant Diseases Data 🍂 | 95.1%    | [Notebook](https://github.com/Infinitode/OPEN-ARC/Project-3-PPDC/project-3-ppdc.ipynb) |

---

### Project 4: Red Wine Quality Classification
- **Challenge:** Classify the quality of red wine based on sensory data.
- **Dataset:** [Red Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- **Kaggle Notebook:** [Link to Notebook](Project-4-RWQC/project-4-rwqc.ipynb)
- **Instructions:** Detailed instructions on running the model are available in the project's README.

#### Leaderboard (Top 5)

| Rank | Contributor | Architecture Type | Platform | Base Model | Dataset | Accuracy | Link |
|------|-------------|-------------------|----------|------------|---------|----------|------|
| N    | Our Model   | GradientBoostingClassifier             | Kaggle    | ✗        | Red Wine Quality | 72.8%    | [Notebook](https://github.com/Infinitode/OPEN-ARC/Project-4-RWQC/project-4-rwqc.ipynb) |

---

### Project 5: Terraria Weapon Name Generation
- **Challenge:** Generate Terraria weapon names based on weapon names from the official game.
- **Dataset:** [All Terraria Weapons DPS V_1.4.4.9](https://www.kaggle.com/datasets/acr1209/all-terraria-weapons-dps-v-1449)
- **Kaggle Notebook:** [Link to Notebook](Project-5-TWNG/project-5-twng.ipynb)
- **Instructions:** Detailed instructions on running the model are available in the project's README.

#### Leaderboard (Top 5)

| Rank | Contributor | Architecture Type | Platform | Base Model | Dataset | Accuracy | Link |
|------|-------------|-------------------|----------|------------|---------|----------|------|
| N    | Our Model   | SimpleRNN             | Kaggle    | ✔        | All Terraria Weapons DPS V_1.4.4.9 | 78.6%    | [Notebook](https://github.com/Infinitode/OPEN-ARC/Project-5-TWNG/project-5-twng.ipynb) |

---

### Project 6: News Headline Generation
- **Challenge:** Generate convincing news headlines based on short passages of text.
- **Dataset:** [NEWS SUMMARY](https://www.kaggle.com/datasets/sunnysai12345/news-summary)
- **Kaggle Notebook:** [Link to Notebook](Project-6-NHG/project-6-nhg.ipynb)
- **Instructions:** Detailed instructions on running the model are available in the project's README.

#### Leaderboard (Top 5)

| Rank | Contributor | Architecture Type | Platform | Base Model | Dataset | BLEU-Score | Link |
|------|-------------|-------------------|----------|------------|---------|----------|------|
| N    | Our Model   | DistilBART             | Kaggle    | ✗        | NEWS SUMMARY | 52.8%    | [Notebook](https://github.com/Infinitode/OPEN-ARC/Project-6-NHG/project-6-nhg.ipynb) |

*More projects will be added soon!*

## Sharing Progress
We encourage users to share their progress and improvements. You can do this in several ways:

1. **Local Notebooks:**
   - Save your Jupyter notebooks in the respective project folder and create a pull request with your findings and steps.

2. **Google Colab:**
   - Upload your notebooks to Colab, then share the link and a brief description in the project's issue tracker or discussion board.

3. **Kaggle Notebooks:**
   - Link your Kaggle notebooks to the respective project by creating a pull request or an issue with the notebook link and a summary of your approach and results.

4. **Notebook Documentation:**
   - Include your steps, process, and any issues encountered directly within the notebook. This documentation helps others understand your approach and learn from it.

Feel free to document your process and findings at the bottom of the project README for others to learn from and improve upon.

## Uploading Models and Sharing Code
You can also upload your trained models and code to GitHub and share the links in our repository's leaderboard. Here’s how:

1. **Upload Your Model (optional):**
   - Save your model files and code in a new repository or in a dedicated branch of your forked repository.
   - Ensure you provide clear documentation and instructions on how to use your model.

2. **Share the Link:**
   - Navigate to the `LEADERBOARD.md` file in the main repository.
   - Add an entry with your notebook's link, a brief description, and your results.
   - Create a pull request with your updates to the `LEADERBOARD.md` file.

3. **Post on the Leaderboard:**
   - Once your pull request is merged, your model and results will be visible on the leaderboard for others to view and collaborate on.

Users can quickly share their contributions and help others in the community learn and improve their models and research.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details about this repo's license.

---
<br>

We hope OPEN-ARC becomes a thriving community of developers, helping improve AI tools for communities around the world, and drive new research and technology.

Happy coding and collaborating!

~ Infinitode