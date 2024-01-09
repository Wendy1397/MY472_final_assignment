# MY472_final_assignment
This is my final assignment I choose the research question one, please read README.md! Thank you. 
1. Handling Large Files with Git LFS

This repository uses Git Large File Storage (LFS) to track large data files. To work with these files, you will need to have Git LFS installed on your system.

Installing Git LFS If you do not have Git LFS installed, please follow these instructions: Download and install Git LFS from the official website. After installation, set up Git LFS by running this command in your terminal:

git lfs install

2. Cloning the Repository

To clone the repository and download the large data files, use the following commands:

git clone https://github.com/your-username/your-repository.git 

cd your-repository 

git lfs pull

Replace https://github.com/your-username/your-repository.git with the actual URL of your repository.

3. Downloading Large Files Directly
If you download the repository as a ZIP file from GitHub, the large files will not be included. Instead, they will be represented as pointer files. To download the actual content of the large files, please use Git to clone the repository as described above.
If you're unable to use Git and Git LFS, you can manually download the large files from the following links:

all_data_df.csv <- https://drive.google.com/file/d/1-Z4one7XvNs58u3uqhcrVtUmnlkhF6NN/view?usp=share_link database/assignment4.sqlite <- https://drive.google.com/file/d/1gseJ4_9qR0U1A-MXGleDnD60T4blc7wN/view?usp=share_link

the entire repository folder is available at https://drive.google.com/drive/folders/1F0YklXfAr-IGJ8yiThSoImEVsfa9_WeZ?usp=share_link

After downloading the files, place them in the appropriate directory as indicated by the repository structure.

3. Troubleshooting
If you encounter any issues with Git LFS, please refer to the Git LFS troubleshooting documentation, or file an issue in this repository with details of your problem.
