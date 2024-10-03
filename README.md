# curriculum-design-project

This project involved designing a curriculum for a "Master of Business and Management in Data Science and Artificial Intelligence" program by analyzing job postings and extracting skills required in the job market. The key tasks were web scraping job postings from Indeed, extracting skills, and using clustering techniques to group the skills into courses. The final curriculum was designed based on two clustering approaches: hierarchical clustering and K-means clustering.

1. Data Collection and Cleaning
The dataset was collected by web scraping job postings for data-related roles from Indeed, including job postings from both Canada and the USA. The raw data was cleaned, duplicates were removed, and a lowercase version of job descriptions was created to normalize the text for analysis.

2. Exploratory Data Analysis
Hard and soft skills were extracted from the job postings. The top 200 most common words were identified using natural language processing techniques. Word clouds were generated to visualize the distribution of hard skills (e.g., Python, SQL, machine learning) and soft skills (e.g., teamwork, communication, decision making).

3. Hierarchical Clustering
Hierarchical clustering was applied to the extracted skills. A dendrogram was created to visualize clusters of related skills, and each cluster was interpreted as a course with topics that should be taught together. The clustering algorithm helped group technical skills like "Python" and "machine learning" together, forming a logical structure for the curriculum.

4. K-means Clustering
The K-means clustering algorithm was used to further refine the curriculum design. The elbow method was applied to determine the optimal number of clusters, with 11 clusters being selected. The skills were grouped based on their similarity in terms of their occurrence in job descriptions, allowing the creation of a coherent sequence of courses.

5. Final Curriculum Design
Based on the hierarchical and K-means clustering results, a sequence of 8-12 courses was proposed. Each course covered 3-8 key topics related to both technical and soft skills necessary for careers in data science, analytics, and AI. For instance, one course could focus on "Data Analysis Techniques," covering skills like Python, SQL, and machine learning, while another could cover "Business Communication and Leadership" with topics like teamwork, decision making, and communication.
