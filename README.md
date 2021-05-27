# A dataset of mentorship in science with semantic and demographic estimations

This is the code repository for the paper titled "A dataset of mentorship in science with semantic and demographic estimations". 

Linking [Academic Family Tree](https://academictree.org/) to [Microsoft Academic Graph](https://www.microsoft.com/en-us/research/project/microsoft-academic-graph/)

Code:

- `prepare_people.ipynb`: Normalizing researcher profiles
- `prepare_connect.ipynb`: Extracting mentor-mentee pairs
- `prepare_aft_to_mag_affil.ipynb`: Matching institutions between AFT and MAG
- `prepare_aft_to_mag_author.ipynb`: Linking AFT researchers to MAG authors
- `prepare_mag_authorship.ipynb`: Exporting authorship and paper IDs

Validations:

- `prepare_validation_paper.ipynb`: Matching validation papers with MAG
- `validate_aft_to_mag_author.ipynb`: Validating AFT-to-MAG author matching

Vector:

- `prepare_paper_author_vector_tfidf.ipynb`: TF-IDF vectors of papers and authors
