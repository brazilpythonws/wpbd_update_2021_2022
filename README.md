# Brazilian Python Workshop for Biological Data

This repository contains materials from the **4th and 5th Editions** of the Brazilian Python Workshop for Biological Data, held in 2021 and 2022, respectively. Our initiative focuses on teaching basic programming concepts and data handling techniques using popular Python libraries. The advancements and challenges encountered in these recent editions have been compiled into a manuscript, which can be accessed using the following link:

[Bridging the Python Training Gap for Bioscientists in Brazil: Improvements and Challenges](https://www.biorxiv.org/content/10.1101/2024.11.25.624749v1)

## Abstract

The rapid evolution of high-throughput technologies in biosciences has generated diverse and voluminous datasets, requiring bioscientists to develop data manipulation and analysis skills. Python, known for its versatility and powerful libraries, has become a crucial tool for managing these datasets. However, there is a significant lack of programming training for bioscientists in many countries. To address this knowledge gap among scientists in Brazil, the Brazilian Python Workshop for Biological Data was introduced several years ago, focusing on basic programming concepts and data handling techniques using popular Python libraries. Despite the progress and positive feedback from earlier editions, challenges persisted, necessitating continuous adaptation and improvement to meet the evolving needs of bioscientists.This work describes the advancements made in the 2021 and 2022 editions of the workshop and discusses new suggestions for its ongoing enhancement. Key innovations were introduced in the workshop structure and coordination, including the creation of new committees and the establishment of a Code of Conduct. Feedback forms were updated to enable real-time adjustments during the event, improving its overall effectiveness. The workshop also expanded its reach by increasing geographical diversity among participants. New didactic strategies, such as pair-teaching, Code clubs, and the integration of information and communication technologies (ICTs), were implemented to enhance learning outcomes. Programming best practices and scientific reproducibility were emphasized through talks and hands-on activities, guided by PEP8 conventions. Furthermore, efforts to enhance scientific dissemination were intensified, with an increased presence on social media and participation in international scientific events and communication networks. Finally, we present updated recommendations for students, researchers, and educators interested in organizing and promoting similar events, building on those previously described.

## Repository Structure

This repository is organized into the following main folders:

#### 1. [.../4th_Edition_WPDB_2021/](https://github.com/brazilpythonws/wpbd_update_2021_2022/tree/main/4th_Edition_WPDB_2021)
  - **Description**: Contains all the materials from the fourth edition of the Brazilian Python Workshop for Biological Data.
  - **Contents**:  
        `- Charts/: Graphs generated from the analysis of the participants' data.`  
        `- Class_Notebooks/: .ipynb files used during lessons.`  
        `- Feedback_Forms/: Virtual forms used to collect data and feedback from participants.`
     
#### 2. [.../5th_Edition_WPDB_2022/](https://github.com/brazilpythonws/wpbd_update_2021_2022/tree/main/5th_Edition_WPDB_2022)
  - **Description**: Contains all the materials from the fifth edition of the Brazilian Python Workshop for Biological Data.
  - **Contents**:  
        `- Charts/: Graphs generated from the analysis of the participants' data.`  
        `- Class_Notebooks/: .ipynb files used during lessons.`  
        `- Feedback_Forms/: Virtual forms used to collect data and feedback from participants.`

#### 3. [.../Code_of_Conduct/](https://github.com/brazilpythonws/wpbd_update_2021_2022/tree/main/Code_of_Conduct)
  - **Description**: Guidelines for the organizing team and participants during the workshop.


## GENERAL CHARACTERIZATION OF THE 2021 AND 2022 EDITIONS

  Similar to the 2020 edition, both subsequent editions were structured online with the introduction of data collection, organization, and analysis using Python through practical sessions, employing a participatory live coding format [[1]](https://doi.org/10.1371/journal.pcbi.1008090). We designed both workshops to take place around five days of immersive Python learning, with a one-day break for exercises [(S1 Table and S2 Table)](https://zenodo.org/records/14906909). They encompassed introductory sessions covering language syntax concepts and practical classes involving Python coding and programming logic. Lectures were developed using interactive Jupyter notebooks hosted in the Google Collaboratory platform (https://colab.research.google.com/). During problem-solving and presentations, instructors actively wrote and narrated the code for the students, who were encouraged to write, document, and run their own code independently and concurrently. The full description of the schedule for both editions can be found in the [Zenodo repository](https://zenodo.org/records/14906909).
  In 2021, the practical sessions involved the manipulation of tabulated data, exploratory analysis with graphs, exploration of epidemiological data [[2]](https://doi.org/10.1016/S1473-3099(20)30120-1), and biological diversity. In 2022, the practical sessions involved manipulation of tabulated data, exploratory analysis with graphs, introduction to the manipulation of biological sequences, and exploration of size measurements for three species of penguins observed on different islands in Antarctica [[3]](https://doi.org/10.1371/journal.pone.0090081). In both years, the third day of the workshop was reserved for required activities. In 2021, individual and group activities were required, whereas in 2022, only group activities were mandatory. Individual activities have become optional to reduce the workload on participants. A daily seminar related to the applied use of the Python language was given. On the fifth day, a special session called Flash Talks was held with selected participants for short presentations on their research, followed by a discussion on how the Python language could be applied to their own studies. All event communications - updates, and information throughout the event - were conducted using online platforms such as Slack (2021) and Discord (2022). For synchronous classes and presentations, we used Google Meet (https://meet.google.com/). An optional meeting preceding the workshop was scheduled with participants to clarify doubts related to the use of the platforms and as a way to minimize eventual technical complications. During the event, students were instructed to share errors and technical problems on the mentioned communication platforms (i.e., Slack or Discord) for immediate assistance from teaching assistants, for example, in solving syntax, semantics, and other general problems. As the days passed, students took it upon themselves to correct each other's mistakes and share feedback for solving exercises and technical issues among their peers.



A. Characterization of registrations

  Comparatively, an increase in enrollment was reported from the first edition (2017) until the 2022 edition (Fig 1A). A peak was observed during the first virtual edition in 2020 with 350 registrations. Because 2020 was the year of the COVID-19 outbreak and the need for social distancing and restrictions on large gatherings, many organizations and event planners opted for virtual events as a way to continue their activities while keeping participants safe [20], [21]. The pandemic has accelerated the trend of virtual events, and many organizations are likely to continue using this format in the future. As a result, there was a notable increase in the number of virtual events [20], possibly explaining the higher enrollment rate seen in Fig 1A. After 2020, there was a decrease in registrations (2021), but the number rose again for the 2022 edition, with more than 300 registrations.

<img src="https://github.com/brazilpythonws/wpbd_update_2021_2022/blob/main/Fig1_NEW.png" alt="drawing" width="900"/>

Fig 1. Evolution of the number of participants and registrations in the Brazilian Python Workshop for Biological Data. (A) The number of registrations across the editions. The peak in registrations during the 2020 edition (the first conducted in a virtual format) can likely be attributed to the implementation of social distancing measures and restrictions on large gatherings due to the COVID-19 outbreak; (B) The pie charts overlaid on the map of Brazil illustrating the expanding geographic distribution of participants selected in the workshop over the years; Note: The cumulative total of participants selected over the years was 140, distributed as follows: Southeast (104), Northeast (13), North (11), Midwest (7), and South (5).

For these editions, 37 (2021) and 40 (2022) participants were selected according to predefined criteria, based on previous recommendations [13]: (I) little or no prior knowledge of the Python programming language, (II) analysis of students’ research activities and their academic involvement, and (III) analysis of students’ expectations about the course. To create an egalitarian environment, the gender ratio among selected participants was kept proportionately equivalent (approximately 50% each).
An important aspect of the workshop conducted virtually was the deliberate inclusion of participants from all geographical regions of Brazil. In the 2021 and 2022 editions, an intentional effort to increase the number of participants from the Northeast, North, and Midwest regions was perceived in order to ensure a more equitable representation of all geographic regions across the country (Fig 1B).


#### References:

1.  Nederbragt A, Harris RM, Hill AP, Wilson G. Ten quick tips for teaching with participatory live coding. PLOS Comput Biol. 2020;16: e1008090. doi: https://doi.org/10.1371/journal.pcbi.1008090
2. 	Dong E, Du H, Gardner L. An interactive web-based dashboard to track COVID-19 in real time. Lancet Infect Dis. 2020;20: 533–534. doi: https://doi.org/10.1016/S1473-3099(20)30120-1
3. 	Gorman KB, Williams TD, Fraser WR. Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis). Chiaradia A, editor. PLoS ONE. 2014;9: e90081. doi: https://doi.org/10.1371/journal.pone.0090081


## How to Use This Repository

1. **Clone the repository**: Use `git clone` to download the repository to your local machine.
   ```bash
   git clone https://github.com/brazilpythonws/wpbd_update_2021_2022.git
   ```

2. **Navigate to the desired edition**: Choose between `4th_Edition_WPDB_2021/` or `5th_Edition_WPDB_2022/` based on your needs.

3. **Explore the materials**: Each folder contains detailed instructions, code examples, and datasets to help you follow along with the workshop content.

4. **Contribute**: We welcome contributions! If you have improvements, bug fixes, or additional resources, please open a pull request or raise an issue.

## Feedback and Support

We value your feedback! Please feel free to open an issue in this repository or contact us directly with any questions, suggestions, or concerns. Your input is crucial in helping us improve future editions of the workshop.

## License

This repository is licensed under the Creative Commons Attribution Share Alike 4.0 International. See the [LICENSE](https://github.com/brazilpythonws/wpbd_update_2021_2022/blob/main/LICENSE) file for more details.

