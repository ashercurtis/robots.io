# robots.io
Distribution of example RPA workflows that can be used as UiPath starter bots in my Foster School of Business Courses.

Each RPA solution folder will typically contain a desktop studio set of files (*.xaml and project.json) and a web studio set of files for use with UiPath Cloud (*.uip or *.uis). 

## 📂 Project Structure folders and sub-folders
└── general_topic_area/ # top=level folders, topic aligned (e.g., loops) 
    |
    ├── sub_topic_area / # bot-level folders, workflow described (per-course JSON + index.json)
    |   ├── studio_files/ 
    |   |   ├── main.xaml # project rpa solution for Studio desktop
    |   |   └── project.json # dependencies and version etc.
    |   |
    |   └── cloud_files/ 
    |       └── *.uip #name of the uip is often the same as the folder/project name
    |
    └── README.md # readme file with bot descriptions 