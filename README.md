# Hi there! I'm Jun-Hee Hwang

Welcome to my GitHub profile! I graduated from the University of California, San Diego with a Data Science major. I am passionate about leveraging technology to solve real-world problems, with a focus on machine learning, data science, and software development. My work spans diverse domains, including neutrino physics, greenhouse gas emissions modeling, and predictive analytics.

## Projects
- **Speech Emotion Recognition** ([GitHub](https://github.com/Junismyname/Speech-Emotion-Recognition)): Built a classifier that recognizes 7 emotions in speech across 4 datasets (12K recordings, 121 speakers). Extended a project started under the mentorship of Professor Justin Eldridge.
  - Identified data leakage (duplicate files, augmentation before the train/test split, shared speakers) that inflated accuracy by 35 points, and rebuilt evaluation on a speaker-independent split.
  - Fine-tuned WavLM and Vision Transformer models and combined them in a validation-weighted ensemble, reaching 85.2% accuracy (85.4% macro F1) on unseen speakers, up from a 63% honest baseline.
  - Compared 8 models (SVM, Random Forest, CNNs, ViT, WavLM, ensemble) and deployed them in a Streamlit app for live microphone inference.
    
- **Room Presence Detection System** ([GitHub](https://github.com/Junismyname/room-presence-yolo)):
  - Developed a real-time, fixed-camera human detection pipeline in PyTorch, engineered for hyper-accurate background subtraction and spatial coordinate regression.
  - Architected a custom Dual-Head YOLO model using a partially unfrozen MobileNetV2 backbone, splitting feature extraction into dedicated confidence and bounding box heads optimized via Generalized Intersection over Union (GIoU) and BCE losses.
  - Built an automated evaluation suite using OpenCV to benchmark custom architectures against zero-shot SOTA models (YOLO12, YOLO26), achieving 98.05% accuracy and 0.7773 Avg IoU at 60+ FPS.
    
- **LinkedIn Jobs Extractor** ([GitHub](https://github.com/Junismyname/linkedin_jobs_extractor)):
  - Developed a serverless AWS Lambda function in Python that runs weekly to scrape LinkedIn, enriches job data with AWS Bedrock for LLM-powered skill extraction and classification, and writes the structured results to the live RDS database for analysis in a Looker Studio dashboard.
  - Architected and deployed a complete, end-to-end data pipeline on AWS, using Terraform to provision a VPC, NAT Gateway, S3 bucket, and PostgreSQL RDS instance for a fully automated, event-driven workflow.
    
- **Majorana Neutrino Hunt** ([Website](https://junismyname.github.io/MajoranaNeutrinoHunt-Website/)): Applied machine learning to Particle Physics. Studied time-series waveform data from the Majorana Demonstrator, extracting features and building models to identify neutrinoless double beta decay events and study matter-antimatter asymmetry.
  - Processed over 2 million data entries, optimizing Random Forest, LightGBM, XGBoost, and CatBoost models with RandomizedSearchCV and SMOTE, achieving up to 0.9940 accuracy and 0.9671 F1-Score.
  - Enhanced model interpretability through SHAP values and feature importance analyses for robust event prediction. 
    
- **Remote CO₂ Consumption** ([GitHub](https://github.com/Junismyname/Remote-CO2-Emissions189)): Conducted an in-depth analysis on the environmental impact of remote work by examining CO₂ emissions across U.S. states from 2018 to 2021, integrating datasets from the U.S. Energy Information Administration and the Census Bureau.     
  - Findings demonstrated statistically significant emission reductions, supporting remote work policies as an effective sustainability measure.
  - Analyzed 50+ state datasets over 4 years, processed 10,000+ entries to assess remote work’s impact on CO₂ emissions, built a logistic regression model with 80.5% accuracy, and identified statistically significant emission reductions during 2020.
 
- **Power Outage Causes** ([GitHub](https://gabrielchasukjin.github.io/Power-Outage-Classification-Model/)): Built a Decision Tree model using Scikit-Learn to classify the cause of severe power outages, which could aid energy companies in developing preventive measures and response plans, enhancing grid resilience.
   - Achieved an accuracy score of 0.827 and applied GridSearchCV to find the optimal hyperparameters and improved model accuracy by 3.92% on the validation dataset resulting in a total accuracy of 0.8.

## Skills

- **Programming Languages**: Python, R, MATLAB
- **Machine Learning Frameworks**: Scikit-learn, TensorFlow, PyTorch
- **Data Analysis**: NumPy, Pandas, Matplotlib, Beautiful Soup, Pyspark, Dask, ArcGis, Looker Studio
- **Development & Operations**: AWS Cloud Platform, IBM DB2

## Experiences
    
- **Keywords Studios (Automation Engineer, Research Associate)**, May 2025 - May 2026:
  - Collaborated with a team of Data Specialists to fine-tune AI training prompts, enhancing model consistency and data accuracy in support of generative AI projects.
  - Executed data collection and annotation tasks, providing quantitative and qualitative feedback to improve AI model performance and identifying areas for process optimization.
  - Owned the end-to-end development lifecycle of enterprise tools (PRISM, PITCH, Spotlight, RA Distribution) supporting 500+ users, from requirements gathering, UI/UX, architecture, and ERD/database design through APIs, frontend, testing, and production deployment.
  - Engineered a cache-warming and prefetch system (5-hour warm-up jobs) that cut cold-start runtime from 170–274 seconds to 32 seconds, a reduction of over 80% (5–8x faster).
  - Built a lightweight SQL-like database engine on Google Apps Script with concurrent writes, foreign keys, constraints, and indexing for structured storage ahead of a full migration, plus a Gmail API integration for threaded automated notifications.
  - Resolved a critical data-deletion issue through custom logging, trigger tracing, and audit debugging, and added monitoring and debugging infrastructure that improved observability and root-cause analysis speed.
 
- **Boundary Remote Subsurface Solutions (Algorithms/Data Analytics Developer)**, June 2025 - May 2026:                            	                        		            	       		             
  - Developed API pipeline through AWS API Gateway and Lambda to automatically process geospatial data requests, storing the resulting metadata and file locations in an ODC-compatible PostgreSQL database hosted on AWS for efficient spatiotemporal querying.
  - Processed over 5,000 square kilometers of bathymetric and geological survey data, correlating it with CryoSat-2 interferometric radar altimetry measurements to create a unified hydrological and geological model for the project's primary Area of Interest (AOI).

- **GBCS Group (GHG Researcher Intern)**, June 2024 - September 2024: 
  - Developed an AI model to predict CO₂ emissions across transportation lifecycle stages.
  - Performed in-depth research on CO₂ emissions across roughly 50 diverse fleets in air, ground, and sea transport, examining emissions data across each lifecycle stage—yielding precise insights to inform sustainable fleet management practices.
  
- **Teaching & Learning Commons, University of California, San Diego (Experiential Learning Ambassador)**, April 2024 - March 2025:
  - Created quarterly data visualizations about the university’s programs/positions and departments with the most/least opportunities using Excel, Python, Pandas, and Matplotlib.
  - Identified approximately 15,000 missing data entries from the university’s official data hub, representing around 7.92% of the dataset, significantly enhancing data accuracy and operational efficiency.
    
## Certifications

- **IBM Data Engineering Professional Certificate (IBM / Coursera)** ([Show Credential](https://www.coursera.org/account/accomplishments/professional-cert/TKS3I2VAUXOQ)):
    - Issued Oct. 2025.
    - Gained hands-on experience with Data Pipelines (ETL, Airflow, Kafka), Big Data (Spark, Hadoop), Data Warehousing, SQL/NoSQL databases, and Machine Learning with Spark.
      
## Let's Connect

- **LinkedIn**: [Jun-Hee Hwang](https://www.linkedin.com/in/jun-hee-hwang/)
- **Email**: [lucasjunhee1221@gmail.com](mailto:lucasjunhee1221@gmail.com)

---

Thank you for visiting my profile! Feel free to explore my repositories and reach out if you'd like to collaborate or discuss any ideas!

