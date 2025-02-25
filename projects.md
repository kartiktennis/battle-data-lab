---
layout: page
title: Our Projects
---
<div class="project-items">
    <div class="project-item">
        <div class="project-item-des">
            <a href="{{site.baseurl}}/projects/lodestar"><h2>Lodestar</h2></a>
            Keeping abreast of current trends, technologies, and best practices in statistics, visualization, and data analysis is becoming increasingly difficult even for professional data scientists, and is a hopeless endeavor for domain experts lacking time and trainingin these methods.  In this paper, we propose Lodestar, an interactive visualization notebook that allows the user to perform visual data analysis by selecting from a list of recommendations. Selecting a recommendation adds the corresponding Python code to thenotebook and executes it, thus generating new output; no programming expertise is required on behalf of the user. The recommendation mechanism is inspired by autocomplete mechanisms, where a partial query is used to show suggestions for how to finish the query. In our implementation, we derive our recommendations from a directed graph of analysis states: one manually curated from online datascience tutorials, another by automatically analyzing the Python code from a corpus of approximately 6,000 Jupyter notebooks on datascience. We demonstrate the Lodestar approach through a set of examples involving statistics, machine learning, and visualization.
        </div>
        <img class="project-item-img" src="{{site.baseurl}}/public/lodestarintro.PNG" alt="the lodestar system"/>
        <div class="caption"> Figure: Lodestar interface. The top panel (A) provides a data selection menu. (B) and (D) are recommendation panels (DESCRIPTION is selected for this notebook) combining suggested analysis steps from various sources (called advisors). (C) and (E) are analysis cells, each with multiple tabs: “Analysis Results” gives charts or tables, “Output Dataframe” and “Code Script” shows the outputs and current code block, and “What’s this analysis?” gives a brief description of the analyses. Outputs, code scripts, and charts can be exported into files by clicking on the associated buttons.
        </div>
    </div>
</div>

<div class="project-items">
    <div class="project-item">
        <div class="project-item-des">
            <h2>User Behaviour Modelling during Examination of Massive Medical Images</h2>
            Digital pathology is replacing pathological examinations performed using microscope, due to its advantage of faster examination and better collaboration among pathologists all over the world. It makes use of super-resolution whole slide images of tissues, which are maintained on a centralized server and accessed by pathologists over the internet, using a client computer (e.g., a laptop). The huge memory footprint of these images makes it difficult for pathologists to navigate and interact with them, as these images cannot be fit entirely in the main memory of the client system. A more effective approach would be to develop an image viewer that automatically and efficiently pre-fetches only the necessary parts of each image from the server, on demand. Furthermore, the system should perform this transfer of data over the network with low latency, so as to have a smooth, lag-free examination experience. We aim to predict the behaviour of pathologists during an ongoing examination session and pre-fetch the required data by training deep learning models on the interaction history of pathologists, and the tissue image itself. Using this approach, we can automatically fetch what pathologists will look for in advance, which would help in reducing perceived system delays and thus make the image browsing experience appear more interactive and smooth.
        </div>
    </div>
</div>
