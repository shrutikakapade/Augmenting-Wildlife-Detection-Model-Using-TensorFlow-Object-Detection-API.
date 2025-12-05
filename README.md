<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">

</head>
<body>
<div class="container">
<h1> Wildeye AI: Drone-Powered Wildlife Detection Using TensorFlow</h1>

<p>Wildeye AI is an automated wildlife monitoring system that uses drones, deep learning, and real-time dashboards to detect and classify animals from aerial footage. Built using the TensorFlow Object Detection API, CNNs, and Plotly Dash, the system aims to revolutionize wildlife conservation by providing accurate, scalable, and non-intrusive monitoring capabilities.</p>

<h2>🚀 Project Overview</h2>
<p>Traditional wildlife monitoring methods are slow, manual, and limited in coverage. Wildeye AI solves these challenges using autonomous drone surveillance, real-time object detection, and deep learning models.</p>

<h2>🧠 Key Features</h2>
<ul>
    <li>Real-Time Wildlife Detection from drone video feeds</li>
    <li>TensorFlow-based CNN and ResNet Logistic Regression models</li>
    <li>Interactive Plotly Dash Dashboard</li>
    <li>Custom-labeled dataset + Animals-10 dataset</li>
    <li>Automated reporting and species analytics</li>
</ul>


<h2> Tech Stack</h2>
<ul>
    <li>Python, TensorFlow, Keras, Sklearn</li>
    <li>OpenCV, Plotly Dash</li>
    <li>Drones with high-resolution cameras</li>
</ul>

<div class="box">
<h2>🔄 Data Flow Diagram </h2>

<h3>🌐 System Overview</h3>
<ul>
    <li><b>Drone System → Detection System:</b> Sends real-time aerial footage.</li>
    <li><b>Detection System → Wildlife Database:</b> Stores species & tracking data.</li>
    <li><b>User Interface ↔ Detection System:</b> Real-time dashboard access and interaction.</li>
<img width="415" height="321" alt="DFD1 drawio" src="https://github.com/user-attachments/assets/d63f8eab-7f40-4425-ad26-40bb8fbffc69" />

  
</ul>

<h3>⚙️Internal Processes</h3>
<ul>
    <li><b>Data Collection → Preprocessing:</b> Extract frames, clean, resize, normalize.</li>
    <li><b>Preprocessing → Model Classification:</b> CNN/ResNet-based species prediction.</li>
    <li><b>Classification → Visualization:</b> Detected species & confidence sent to dashboard.</li>
    <li><b>Species Database ↔ Visualization:</b> Stores and retrieves historical detection data.</li>
</ul>

<img width="415" height="554" alt="DFD2 drawio" src="https://github.com/user-attachments/assets/bb76f9e2-90e7-425e-8ad1-ce492b1e1f35" />


<h3>🔧 User-Level Functions</h3>
<ul>
    <li><b>Live Video Processing:</b> Frame extraction & real-time inference.</li>
    <li><b>Species Detection:</b> Bounding boxes, labels, confidence scoring.</li>
    <li><b>Analytics Engine:</b> Graphs, counts, detection insights.</li>
    <li><b>Data Logging:</b> Stores detection events for reports.</li>
</ul>

<img width="960" height="485" alt="DFD3 drawio" src="https://github.com/user-attachments/assets/e7472382-10ef-4743-9002-4197f757c436" />

<h3>Plotly Dash Dashboard</h3>

<h3>Wildlife Detection and Analysis Interface </h3>

<img width="1166" height="650" alt="Screenshot 2025-12-05 230218" src="https://github.com/user-attachments/assets/d5a67a93-315f-4f51-8573-1badc539a05e" />

<h3>Object Detection Confidence and Object Count Analysis in Wildlife Monitoring</h3>

<img width="1164" height="666" alt="Screenshot 2025-12-05 230529" src="https://github.com/user-attachments/assets/4a1314e7-af69-4368-94f3-839fd9e52f64" />


<h3>Detection Score Visualization for Most Probable Objects Identified by Wildeye-AI</h3>
<img width="1170" height="627" alt="Screenshot 2025-12-05 230542" src="https://github.com/user-attachments/assets/cc1c3a09-95eb-4aa1-a10b-0a9fe1bad236" />


</div>
</body>
</html>
