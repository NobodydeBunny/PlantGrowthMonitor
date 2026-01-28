<h1>$\color{green}{Plant \space Growth \space Monitor}$ 🌱</h1>
<h3>Overview</h3>

Plant Growth Monitor is a Python-based computer vision project designed to monitor plant growth over time by analyzing images. The system focuses on visual indicators such as leaf count, size, and growth progression, using image processing techniques.

This project was developed as an academic and practical exploration of how computer vision can be applied to agriculture and plant science, even in small indoor environments.

<h3>Problem Statement</h3>

Manually tracking plant growth is time-consuming and subjective. Measurements like height or visual observation do not always reflect actual plant health or growth rate accurately.

This project aims to provide a simple, automated, and repeatable way to monitor plant growth using images captured at regular intervals.

<h3>Solution Approach</h3>

The system processes plant images and extracts useful growth information using image processing techniques. The core idea is to analyze plant images and quantify growth-related features such as leaf count.

<h4>Key Techniques Used</h4>
<ul>
<li>Image preprocessing (grayscale conversion, thresholding)</li>

<li>Contour detection for leaf segmentation</li>

<li>Noise removal and filtering</li>

<li>Visualization using plots and annotated images</li>
</ul>
<h4>Technologies Used</h4>
<ul>
<li>Python</li>

<li>OpenCV (image processing)</li>

<li>NumPy (numerical operations)</li>

<li>Matplotlib (visualization)</li>
</ul>
<h3>Features</h3>
<ul>
<li>Reads plant images from a dataset or folder</li>

<li>Detects and counts visible leaves</li>

<li>Visualizes detected plant regions</li>

<li>Supports repeated analysis over time for growth comparison</li>

<li>Works with images taken in indoor environments</li>

<h3>Project Structure</h3>

PlantGrowthMonitor<br>
├── images/               # Plant image dataset<br>
├── main.py               # Main image processing script<br>
├── requirements.txt      # Required Python libraries<br>
└── README.md             # Project documentation<br>

<h3>How to Run the Project</h3>
<ul><li>Clone the repository</li>
<i>git clone https://github.com/NobodydeBunny/PlantGrowthMonitor.git</i>

<li>Install dependencies</li>
<i>pip install -r requirements.txt</i>

<li>Run the program</li>
<i>python main.py</i><br>
</ul>
❗Make sure your plant images are placed in the correct folder before running the script.

<h3>Example Output</h3>
<ul>
<li>Original plant image</li><br>
<li>Processed image with detected leaves highlighted</li><br>
<li>Console or visual output showing estimated leaf count</li></ul><br>
<li>These outputs can be compared over time to observe plant growth trends.</li><br>
</ul>
<h3>Applications</h3>
<ul>
<li>Academic projects in computer vision</li>

<li>Basic agricultural monitoring</li>

<li>Indoor plant growth experiments</li>

<li>Smart farming research foundations</li>
</ul>
<h3>Limitations</h3>
<ul>
<li>Accuracy depends on image quality and lighting</li>

<li>Overlapping leaves may affect detection</li>

<li>Designed for controlled environments, not outdoor fields</li>
</ul>
<h3>Future Improvements</h3>
<ul>
<li>Improve leaf segmentation accuracy</li>

<li>Add plant height and area estimation</li>

<li>Store growth data over time</li>

<li>Create a simple GUI for ease of use</li>

<li>Extend to real-time camera input</li>
</ul>
<h3>License</h3>

This project is intended for educational and research purposes. You are free to modify and expand it for learning or experimentation.
