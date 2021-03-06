# Data description
Data regarding known astrophysical jet sources, which includes data such as mass, angular momentum, and metallicity, from different central engines will be used as input for the simulated progenitor. Data will be collected from catalogues contained in NASA's archive, the High Energy Astrophysics Science Archive Research Center (HEASARC). Simulated output, including variables such as time, flux, and energy will be captured in .txt files in order to generate light curves (intensity, or total power output over time) and spectra (counts from a source as a function of energy), to be compared directly to actual observational data. To achieve these numerical results, a 3D special relativistic radiative hydrodynamic (SRHD) code will be developed using a combination of C++ and Python. Due to the compute intensive nature of these simulations, the code will be developed in such a way that leverages high-performance computing architectures. It is expected that this project will ultimately produce on the order of TBs of data. 

# Roles and responsibilities
The responsibility for data management will fall on the primary graduate student researcher and the Principle Investigator (PI). The primary researcher, will be responsible for developing and testing code, managing data, conducting the appropriate data analysis, and will commit to publicly sharing code using open platforms such as GitHub. The PI will be co-responsible for quality control, both of the data in addition to analysis techniques, in addition to data archival and preservation. 

# Data standards and metadata

As no standards yet exist, best practices will be observed throughout the course of this project.  

Code development: Code developed using Python will generally be developed using a Jupyter notebook. In that notebook, you would find a number of things including “date created”, a “date last updated” followed a detailed list of updates, as well as a written introduction to the problem at hand and the numerical schemes used. For more complicated/abstract code developed using C/C++, programs all relevant code would be kept in its own directory, with source code and documentation (including a README file, variable dictionary, user guide, and contact information) in separate directories. All code will include internal documentation (i.e., comments).  

# Storage and security
During early stages of the project, data will be stored primarily on a local computer with copies in external drives (e.g., external hard drive, flash drive). Data storage will eventually expand to include the use of cloud-based services in addition to multiple copies of external drives. 

To mitigate the risk of theft or the destruction/failure of the primary storage mechanism, three additional forms of storage will be employed: a second external hard drive, remote data storage using institutional resources, as well as remote metadata storage using GitHub. Data in external (physical and remote) storage will be reviewed annually, while storage on GitHub will be reviewed on a more frequent basis (e.g., as new content is added). 

# Access and data sharing

Some, though not all, of the algorithms developed will be made publicly available throughout the course of the project; however, any data resulting from the completed software will be made available within one year of publishing results. 

Software developed for this project will be made publically available through GitHub in the hopes that it will serve the greater community through education, outreach, and research. As a community resource, users will be encouraged to contribute to the software's capabilities (and that any modifications be made publicly available) and to acknowledge the software in any publications and/or presentations resulting from its use.  


# Archiving and preservation

Code will be made available on GitHub where the community aspect of this platform would allow for its maintenance and continued development, while the original work will be stored indefinitely in The Astrophysics Source Code Library repository. Simulation results leading to publications will be archived through the publisher as supplemental material.
