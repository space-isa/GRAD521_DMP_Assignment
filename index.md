# Data description
Data regarding known astrophysical jet sources, which includes data such as mass, angular momentum, and metallicity, from different central engines will be used as the simulated progenitor (our initial setup). Such data will be captured from online astronomical catalogues. As a simulated output, light curves (intensity, or total power output over time) and spectra (counts from a source as a function of energy) are the goal as they can be directly compared to observational data. To achieve these numerical results, a 3D SRHD code will be developed using a combination of C++ and Python will be developed, as no public code is currently available. Due to the compute intensive nature of these simulations, the code will be developed in such a way that leverages high-performance computing architectures. It is expected that this project will ultimately produce on the order of hundreds of GB of data. 


# Roles and responsibilities
The responsibility for data management will fall largely on me as the primary researcher, and to a lesser extent on my advisor, who will provide basic guidance with such things as theoretical and numerical frameworks, common practices, and where to start my literature search. I will be responsible, ultimately, for developing code, managing data, conducting the appropriate data analysis, etc. My advisor, to some extent, will be co-responsible for such things as quality control-- both of the data as well as analysis techniques. Since my research question does not involve the use of human subjects, the data produced by this research project will not be sensitive or confidential; nor is my research under some sort of non-disclosure agreement that would prevent the dissemination of data. However, funding agencies, namely NSF, will require a Data Management Plan during the proposal stage, which will include plans to make data available (talking with my advisor, it appears whether it’s made freely available or made available by request seems to be to the discretion of the researcher).    
# Data standards and metadata
Code development: Code developed using Python will generally be developed using a Jupyter notebook. In that notebook, you would find a number of things including “date created”, a “date last updated” followed a detailed list of updates, as well as a written introduction to the problem at hand and the numerical schemes used. For more complicated/abstract code developed using C/C++, programs all relevant code would be kept in its own directory, with source code and documentation (including a README file) in different directories. For both languages, comments would be found throughout the code written in a way that someone not familiar with the project could follow. 

Data output: Data from simulation runs will be stored by date (e.g., in a subdirectory named 20190222) and by run (Run1, Run2,...). Each of the Run subdirectories will contain a .txt file in a doc folder containing all of the major variables of interest (density, temperature, etc.) for that specific run. 

# Storage and security
For early stages of the project, data will be stored primarily on a local computer. As the project matures, it is expected that the data from simulation runs will be larger than a computer can handle, and thus data will be stored on external hardrives. 

As a first-order security measure, data (i.e., computers) are kept in a locked office. To mitigate risks from theft, or the destruction/failure of the primary storage mechanism, three additional forms of storage will be employed: a second external hardrive, remote data storage using institutional resources, as well as remote metadata storage using GitHub. Data in external (physical and remote) storage will be reviewed annually, while storage on GitHub will be reviewed on a more frequent basis (e.g., as new content is added).   

# Access and data sharing

In my case, the data that would be shared is code and given the complexity of the project as well as the fact that this field is still developing, the final product likely wouldn’t be shared until results have been published. This would be years down the line from initial development, thus time and competition would be factors that limit the kind of transparency that would be ideal.  

# Archiving and preservation

The completed code, it will be made available on GitHub where the community aspect of this platform would allow for its maintenance and, more importantly, its continued development and use beyond my thesis project. Data in the form of simulation results will be compressed and archived and could potentially be archived long-term in a place like HEASARC or even with my institution, with the idea being that data preservation, like storage, will be external. Further conversation with my research advisor will allow me to have a better understanding of current (if any) standards/best practices. 


Repository with source code [here](https://github.com/clarallebot/GRAD521_DMPtemplate)
