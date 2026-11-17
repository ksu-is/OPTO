# OPTO - Project Roadmap
## Project Overview
OPTO is a Python photo storage optimizer designed to help organize its users photos and be able to free up storage on their device. The program will identify any duplicated pictures, analyze photo information, and be able to recommend photos for users to review and delete.
## Sprint 1 - Project Setup and Research
- [x] Verify that my program was approved by my professor
- [x] Create my OPTO repository on Github
- [x] Create and update my README.md file
- [x] Research existing Python project that also help with identifying duplicated photos.
- [x] Clone the existing project and review its code
- [x] Try to run the project using test images
- [x] Document my research and all testing results
- [x] Complete Sprint 1 review and log in D2L
## Sprint 1 Research and test results:
I spent time researching different python projects that could help me build OPTO and came across PyDuplicateFinder by sw4tk on Github (https://github.com/sw4tk/PyDuplicateFinder). I chose to test this and downloaded it and tested it in VS code. This program uses hashlib library which creates hashes of files and identifies which images are exact duplicates of each other. In VS code i created folders containing exact images in each. i ran the program using python3 main.py . The program called out the duplicated images (including one with different name) and ignored the non-duplicated images. This program helped me understand how i could use hashlib in my own program for OPTO.One flaw i noticed in this program is that the image has to be the exact duplicate file rather than photos that look similar. i inserted two of the same images that were simply just saved differently, and this program was not able to detect that it was the same image. 
## Sprint 2 - Beginning Development
- [ ] Create the main OPTO python file
- [ ] Create a folder with sample images to be used for testing
- [ ] Write code to scan a folder of photos
- [ ] Display photo names and the files size
- [ ] Research and test hashlib for being able to identify duplicated images
- [ ] Develop a basica duplicate photo detection
- [ ] Test the code and document the trial and errors

## Sprint 3 - Creating presentation
- [ ] Create a powerpoint explaining OPTO
- [ ] Explain what problem it solves
- [ ] Explain its value and benefits
- [ ] Summarize the development process
- [ ] Prepare the final project presentation
## Future improvements
- [ ] Display the duplicated photo recommendations
- [ ] Calculate the amount of storage that can be saved
- [ ] Explore a basic photo viewer for tracking user interactions
- [ ] Allow users to mark photos they want to keep
- [ ] Test, fix and document the program

## Existing Python Project Research
Repository name: add after research
repository url: add after research
what the code does: do after completing project
what i learned from reading the code: complete after reviewing code
testing results: complete after running the program
How this could help OPTO: complete after evaluations
