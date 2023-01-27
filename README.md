# Problem statement

Earthdata Cloud (EDC) Platform data and services are difficult to use with standard Machine Learning tools and services.

# Solution
Investigate, measure, report and provide recommendations on using ML in EDC.

This solution starts with understanding how this is achieved.

## Investigate
- Present documentation on how to access EDC data and services
- Present documentation on ase of usage of 
    - AWS EC2 + ML libraries
    - AWS SageMaker

  and EDC data and services

### Accessing EDC data with Jupyter Notebooks and python
[HTTPS access to data within EDC](https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/https-access.ipynb)

[S3 in-region access to data within EDC](https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/s3-access.ipynb)

[S3 in-region access to data within EDC for more than one hour](https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/s3-access-beyond-one-hour.ipynb)

### Accessing EDC data with EC2
TBD

### Using EDC data with AWS Sagemaker
TBD

## Measure
- Cost of using ML services and tooling with EDC data and services
- SageMaker cost estimates for task 4c
- EC2 + ML Libraries cost estimates for 4c
## Report
Tutorial notebook(s) showing how to use EDC data and services with ML tooling and services

| Task      | Location | Status |
| --------- | -------- | -------|
| EDC S3 data access      | https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/s3-access.ipynb       | Complete |
| EDC S3 data access with auto-refreshing STS tokens | https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/s3-access-beyond-one-hour.ipynb | Complete |
| EDC S3 data access with auto-refreshing STS tokens |https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/s3-access-beyond-one-hour.ipynb	| Complete |
| EDC HTTPS data access	| https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/https-access.ipynb |	Complete |
| ML data preparation: Using EDC data to create an Augmented Manifest File | https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/Sagemaker/data-preparation.ipynb	| Needs to be documented and parameterized |
| Sagemaker training | https://github.com/nasa-esdswg-ml/edc-notebooks/blob/main/Sagemaker/training.ipynb | Needs to be documented and parameterized |
| Sagemaker endpoint creation | TBD	| Not started |
| EC2 training | TBD | Not started |
| EC2 endpoint creation	| TBD |	Not started |

## Recommend

- BP for sizing your compute when using ML tooling
- BP for EDC S3 access
- Recommendations for improvements to EDC wrt ML
