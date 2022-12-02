What's the problem?
Part of the World Health Organization's guidance on limiting further spread of COVID-19 is to practice social distancing. As a result, schools in most affected areas are taking precautionary measures by closing their facilities. With school-aged children at home for an indeterminate amount of time, keeping them engaged, entertained, and on top of their education is important.

How can technology help?
Schools and teachers can continue to engage with their students through virtual classrooms, and even create interactive spaces for classes. As parents face a new situation where they may need to homeschool their children, finding appropriate online resources is important as well.

The idea
It's imperative that learning and creating can continue when educational institutions have to shift the way they teach in times of crises, such as the COVID-19 pandemic. Providing a set of open source tools, backed by IBM Cloud and Watson Services, will enable educators to more easily make content available for their students.


The architecture
[image](https://user-images.githubusercontent.com/109976021/205330849-c553bd94-9da9-403a-9385-d00ec29424d4.png)


The user navigates to the site and uploads a video file.
Watson Speech to Text processes the audio and extracts the text.
Watson Translation (optionally) can translate the text to the desired language.
The app stores the translated text as a document within Object Storage.
Long description
More detail is available here

Project roadmap
The project currently does the following things.
[image](https://user-images.githubusercontent.com/109976021/205330932-db44c73b-7d8c-462f-b716-339a96a6a1d2.png)

Feature 1
Feature 2
Feature 3
It's in a free tier IBM Cloud Kubernetes cluster. In the future we plan to run on Red Hat OpenShift, for example.

See below for our proposed schedule on next steps after Call for Code 2021 submission.

Roadmap

Getting started
In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

sample-react-app
sample-angular-app
Explore other projects
Live demo
You can find a running system to test at callforcode.mybluemix.net.

See the "long description" field in our submission (not in this repo) for the log-in credentials.

Built with
IBM Cloudant - The NoSQL database used
IBM Cloud Functions - The compute platform for handing logic
IBM API Connect - The web framework used
Dropwizard - The web framework used
Maven - Dependency management
ROME - Used to generate RSS Feeds
Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

Versioning
We use SemVer for versioning. For the versions available, see the tags on this repository.
