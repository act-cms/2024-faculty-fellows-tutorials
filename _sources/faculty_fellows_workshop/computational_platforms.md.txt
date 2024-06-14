# Computational Platforms for Programming Lessons

This lesson will cover open and free computational platforms where you might run your programming lessons. 

Part of the Teaching Kit you will prepare as part of your fellowship will include instructions for other instructors on how to have students run your lessons. 
Regardless of how you plan to deliver your lessons, you will need to consider how students will run the code you provide and to provide instructions for your material to be used on an open platform.

## Quick Start - Which platform should I use?

The table below gives a comparison of the computational platforms that we will cover in this lesson.
Each platform has its own strengths and weaknesses, and the best platform for you will depend on your specific needs including the programming language you are using, the software you would like to use, and the level of control you need over the environment.

The most flexible tool among the platforms is *GitHub Codespaces*, but it requires the most configuration.
ChemCompute is the most user-friendly platform and has a wide variety of software suited specifically to molecular sciences pre-installed. 
However, it is not as flexible when it comes to custom software as GitHub Codespaces or Google CoLab.

The table below gives an overview of our recommended platforms and their features.
The platforms are on the rows, the features are on the columns, and the cells contain a checkmark if the platform supports that feature.

**Definitions:**  

- **Available Languages**: The programming languages that are available on the platform.
- **Customizable Environment**: The ability to install custom software on the platform.
- **Interface/IDE**: The interface or integrated development environment (IDE) that the platform provides.
- **Supports Collaborative Editing**: Provides the ability for multiple users to edit the same document at the same time in a way similar to Google Docs.
- **Default Python Libraries**: The Python libraries that are pre-installed on the platform.
- **GPU Support**: Whether the platform provides access to GPUs.

```{csv-table} Computational Platforms Comparison
:header-rows: 1
:file: data/computational_platforms.csv
```

## ChemCompute
**Description**: [Chemcompute](https://chemcompute.org/) is a website that allows students and instructors to log in and access environments with many pre-installed computational chemistry software packages including GAMESS/Psi4, Tinker, NAMD, and more. 
The website features ready-to-use experiments for various courses and provides a Jupyter notebook interface for writing your own code.
Notebooks on chemcompute are persistent, meaning that students can save their work and return to it later.
Compute time comes from an XSEDE allocation and the platform has CPU and GPU nodes.
ChemCompute is limited to users with a valid academic email address, and is free for academic users.

**Best For**: Instructors who want to use computational chemistry software in their lessons and want a user-friendly interface. 

## Google CoLab
[Google Colab](https://colab.research.google.com/) is a free, cloud-based platform that allows users to write and run Python code in a collaborative environment. 
It's a hosted Jupyter Notebook service that provides access to computing resources, including GPUs and TPUs, without the need for local setup. 
Colab is especially well-suited for machine learning, data science, and education.
Colab notebooks are stored in Google Drive and can be shared just like Google Docs or Sheets.
Additionally, you can connect Colab to your GitHub repository to access your notebooks directly from the platform.
By default, most Python data science packages are installed.
However, you can customize the environment by installing additional packages using pip, or even conda.

**Best For**: Instructors who want to use Python in their lessons and want to use a free platform with access to GPUs.  

## GitHub Codespaces 
[GitHub Codespaces](https://github.com/features/codespaces) is a cloud-based development environment that allows you to write, run, and debug your code directly from your browser.
As an instructor, you can create a repository with lesson or assignment materials and an environment configuration that allows your students to run the code in a Codespace.
GitHub Codespaces use a concept called containerization, which means that they are highly customizable and can be configured to include any software that you need. Every GitHub user has access to 120 core hours per month of Codespace usage for free. This increases to 180 core hours for GitHub Pro users, and verified students and instructors.

If you are a verified educator and have upgraded your organization as described in the [Classroom Code Management](classroom_code_management) lesson, the Codespaces Education benefit gives verified teachers a free monthly allowance of GitHub Codespaces hours to use in GitHub Classroom. The free allowance is estimated to be enough for a class of 50 with 5 assignments per month, on a 2 core machine with 1 codespace stored per student.

**Best For**: Instructors who want to use a flexible platform that allows them to customize the environment, integrate tightly with GitHub, and have control over the software that is available to students.

## nanoHUB
[nanoHUB](https://nanohub.org/) is a platform that provides access to simulation software and resources for nanotechnology research and education.
The website hosts a wide variety of tools and resources, including simulation tools, online presentations, and courses.
You can have your students create accounts and use the Jupyter notebook, or you can create your own persistent lesson on the platform with custom software and pre-filled notebooks.

**Best For**: Instructors who want a user-friendly interface with a wide variety of tools and resources for nanotechnology research and education. This platform will be one of the best for making your lessons widely and easily available to many students, not just at your own institution.
