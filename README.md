MoJEC (Moodle JUnit Exercise Corrector)
========================================

# Purpose
This is the git repository for the MoJEC project, developed in the Winter Semester 2016/2017 for the HFT Stuttgart Masters Software Technology studies.

# Goal
The system MoJEC enables a professor to set up Moodle exercise hand-ins for students in the HFT Stuttgarts official Moodle system, where MoJEC builds the code and runs a Junit test suite over the code. MoJEC shows the weighted JUnit test results to the respective student similar to other test results in Moodle.

# Use Cases
- A teacher should be able to upload JUnit test files when creating an assignment
- A student should be able to upload Java files to this assignment. Those files should be tested with the provided JUnit tests.
- The student should see a summary of the test results.
- The teacher should see a summary of all test results of all students, but also be able to view the detailed results.


# Important Links:
[Backend Git Repository](https://github.com/HFTSoftwareProject/MoJEC-Backend)

[Frontent Git Repository](https://github.com/HFTSoftwareProject/moodle-assignsubmission_mojec)

[Frontend Docker Configuration](https://github.com/HFTSoftwareProject/moodle-docker)

[Backend Docker Repository](https://hub.docker.com/r/hftstuttgart/mojec-backend/)

[Frontend Docker Repository](https://hub.docker.com/r/hftstuttgart/moodle/)

[Trello ToDo Board](https://trello.com/b/ZmsnM9C2/mst-software-project)

[Slack Communication Tool](https://hftmstsoftwareproject.slack.com)

[Time Tracking](https://docs.google.com/spreadsheets/d/1-MpYaloBiwruF3JKEFQNhkQHMwL48Fht-V6TLP1bQ5c/edit#gid=1436231210)

# Live System (HFT internal)
[Moodle Demo System (Docker)](http://10.40.10.5)

[Backend System (Docker)](http://10.40.10.5:8080)

[Jenkins Continuous Integration System (KVM)](http://10.40.10.57:8080)
