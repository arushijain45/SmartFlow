# SmartFlow

Welcome to the SmartFlow repository! This repository contains a dataset consisting of five folders, each dedicated to a specific application: CAS, Customer Complaint, Passport Application, Patient Registration, and Sales Lead Generation. Each application folder contains five layout folders, each representing a different layout variation. Additionally, each layout folder contains the following files and subfolders:

- `tasks.csv`: This CSV file contains user request specific to the layout of an application. The file includes five user-requests.

- `page<n>_gt.csv`: This folder contains the ground truth data of individual pages data for the tasks. It serves as a reference for evaluating the performance of our SmartFlow.

- `page_<n>`: This subfolder contains additional files like HTML source code and validated Layout Mapping related to the nth page of the layout.

For reference we have kept screenshots of the individual pages of the webform and its corresponding layout mapping. These screenshots are named `layout<i>_page<j>.png` and `layout<i>_page<j>_layout_mapping.png`.

  ## Folder Structure

The structure of the dataset is organized as follows:

```
dataset
├── cas
│   ├── layout1
│   │   └── page_1
│   │   │   ├── source.html
│   │   │   ├── layout_mapping.json
│   │   └── page_2
│   │   │   ├── source.html
│   │   │   ├── layout_mapping.json
│   │   ├── tasks.csv
│   │   ├── page1_gt.csv
│   │   ├── page2_gt.csv
│   ├── layout2
│   ...
├── customer
│   ├── layout1
│   │   └── page_1
│   │   │   ├── source.html
│   │   │   ├── layout_mapping.json
│   │   ├── tasks.csv
│   │   ├── page1_gt.csv
│   ├── layout2
│   ...
├── passport
│   ├── ...
├── patient
│   ├── ...
└── sales
│   ├── ...
```

## Usage

Feel free to explore the dataset and utilize it for your projects. The dataset offers valuable resources for tasks related to CAS, Customer Complaint, Passport Application, Patient Registration, and Sales Lead Generation applications. The provided `tasks.csv` files can be used for RPA, data analysis or other relevant research purposes. The `ground_truth` folder serves as a reference for evaluating the performance of your models or algorithms.

Please adhere to the licensing and usage policies specified in the repository. If you use this dataset, we kindly request that you provide appropriate attribution and acknowledgment.


## Acknowledgments

We would like to acknowledge the contributors and teams involved in curating the Smartflow dataset. Without their efforts, this valuable resource would not be available. Thank you to everyone who has contributed to the dataset.

If you have any questions or need further assistance, please feel free to reach out to us.


