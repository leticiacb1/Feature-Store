### 🏪️ Feature Store

A **feature store** acts as a centralized repository for storing, managing, and serving ML data features, providing a unified and reliable source of data for model development and deployment.

> Features refer to data attributes or variables that are used as inputs to train and make predictions

#### Feast

Is a open-source **feature store** that organizations use to store and serve features consistently for offline training and online inference.

See more, [here](https://feast.dev/).

#### Dependencies

Create a `venv` and install dependencies

```bash
    # Create environment
    $ python3 -m venv venv  

    # Activate environment
    $ source venv/bin/activate

    # Install dependencies
    $ pip install -r requirements.txt
```

### 📌 How to use this project

```bash
  # Check file content
  # Folder experiment/notebooks
  $ python3 check_content.py
  
  # Check features
  # Folder experiment/
  $ python3 get_features.py
```
Access feast web interface:

```bash
  # Folder experiment/feature_repo
  $ feast ui
```

To learn more about Feast, visit [doc](https://docs.feast.dev/).

<br>
@2024, Insper. 9° Semester, Computer Engineering.

Machine Learning Ops & Interviews Discipline