# Using RETAIN Model to predict Heat Failure
## Overview
Sử dụng bộ dữ liệu MIMIC-III để training cho mô hình RETAIN dự đoán xác suất bị bệnh tim của bênh nhân.
## Table of Contents
- [Using RETAIN Model to predict Heat Failure](#using-retain-model-to-predict-heat-failure)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Folder Structure](#folder-structure)
    - [Explanation](#explanation)
  - [Usage](#usage)
## Installation
```bash
pip install -r HW4_RETAIN-lib/requirements1.txt
```
## Folder Structure
.  
├── backups  
├── HW4_RETAIN  
│   ├── HW4_RETAIN.ipynb  
│   └── img  
│       ├── retain-1.png  
│       ├── retain-2.png  
│       └── retain-3.png  
├── HW4_RETAIN-lib  
│   ├── data  
│   │   └── train  
│   │       ├── hfs.pkl  
│   │       ├── pids.pkl  
│   │       ├── rtypes.pkl  
│   │       ├── seqs.pkl  
│   │       ├── types.pkl  
│   │       └── vids.pkl  
│   ├── requirements1_post.sh  
│   ├── requirements1.txt  
│   ├── requirements2.txt  
│   ├── requirements3.txt  
│   └── requirements4.txt  
└── Readme.md  
### Explanation
- **`backups`**: Backup các file quan trọng
- **`HW4_RETAIN`**: Chứa source code chính
- **`HW4_RETAIN-lib`**: Chứa data và các cấu hình 
## Usage
Run file **`HW4_RETAIN/HW4_RETAIN.ipynb`**