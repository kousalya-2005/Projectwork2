## Spatiotemporal Graph Modeling of Continuous Glucose Excursions: Integrating Age-Dependent Pathophysiological Risk Metrics with Personalized Metabolic Optimization
The integration of a Hypergraph Neural Network (HGNN) within a metabolic monitoring interface, aimed at providing real-time glucose trajectory predictions and personalized lifestyle interventions for enhanced glycemic management.

## About
The HGNN-Based Metabolic Health Monitoring System is a project designed to leverage advanced Hypergraph Neural Networks (HGNN) to model higher-order spatiotemporal correlations between glucose levels, heart rate, and physical activity. Traditional glucose monitoring systems often rely on simple linear models or standard neural networks that fail to capture the complex, non-linear context of human metabolism.

This project seeks to overcome these challenges by constructing hyperedges across temporal windows, allowing the model to analyze the relationship between multiple sensors simultaneously. By integrating Explainable AI (XAI) through SHAP (SHapley Additive exPlanations), the system translates complex deep learning outputs into actionable health insights, helping users monitor their metabolic health with data-driven precision.

## Features
1. Advanced HGNN Architecture: Implements HypergraphConv layers to capture higher-order dependencies between multi-modal biometric sensors.

2. Explainable AI (XAI): Integrated SHAP engine to explain feature importance (e.g., quantifying how "Steps" or "Heart Rate" influenced a specific glucose prediction).

3. Web-Based Deployment: A Flask-based framework for a real-time, interactive monitoring dashboard.

4. Automated Technical Reporting: Generates comprehensive PDF reports including 24-hour trends and 7-day intervention protocols.

5. Low Latency Inference: Optimized for real-time sensor data processing with minimal time complexity.

## Requirements
1. Operating System: Requires a 64-bit OS (Windows 10/11 or Ubuntu) for compatibility with deep learning frameworks and CUDA.

2. Development Environment: Python 3.8 or later is required for the implementation of the metabolic monitoring system.

3. Deep Learning Frameworks: PyTorch and PyTorch Geometric (PyG) for the development and training of Hypergraph layers.

4. Data Processing Libraries: Pandas and NumPy for handling large-scale metabolic datasets; Scikit-learn for data preprocessing and evaluation metrics.

5. Web Technologies: Flask for the backend server and Chart.js for real-time glucose trajectory visualization.

6. Version Control: Git for collaborative development and code management.

7. IDE: VSCode or PyCharm for development and debugging.

8. Additional Dependencies: fpdf for report generation, shap for model interpretability, and matplotlib for performance visualization.

## System Architecture
<img width="575" height="528" alt="image" src="https://github.com/user-attachments/assets/2f40d18f-625b-4332-bd03-cf5b29882de7" />

## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Dashboard
<img width="549" height="768" alt="Screenshot 2026-02-13 101051" src="https://github.com/user-attachments/assets/2c679626-20c9-414d-805b-d73d184f5f4e" />

#### Output2 - Glucose Spike Graph
<img width="1913" height="938" alt="Screenshot 2026-02-11 232637" src="https://github.com/user-attachments/assets/6d8b0c93-32a7-4e64-85dd-06beb16c498c" />

#### Output 3 - Optimized Personalized Report
<img width="842" height="911" alt="image" src="https://github.com/user-attachments/assets/7c24ff96-f0f9-424d-ada2-40d04aac9a01" />

Detection Accuracy: 94.82%
Note: These metrics can be customized based on your actual performance evaluations.
<img width="1389" height="489" alt="image" src="https://github.com/user-attachments/assets/3b151541-1775-4cb3-b9fc-a3c4596aac24" />


## Results and Impact
The HGNN-Driven Metabolic System enhances the precision of personalized health monitoring for individuals with metabolic disorders. By utilizing deep learning and hypergraph theory, the project provides a more robust and accurate method for glucose management compared to traditional tracking approaches.

This project serves as a foundation for future developments in Automated Glucose Management and contributes to the creation of proactive and accessible digital health solutions.

## Articles published / References
[1] American Diabetes Association, "Standards of Medical Care in Diabetes—2024," Diabetes Care, vol. 47, no. Supplement_1, pp. S1-S310, 2024.
[2] Y. Feng, H. You, Z. Zhang, R. Ji, and Y. Gao, "Hypergraph Neural Networks," in Proceedings of the AAAI Conference on Artificial Intelligence, vol. 33, no. 01, pp. 3558–3565, 2019.




