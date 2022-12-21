<h1>Language Detector</h1>

<p>This PyQt5 based GUI application allows you to drag and drop a docx file to detect the language of its contents. The "Detect and Rename" button will detect the language of the file and rename the filename to have the language suffix.</p>

<h2>Setup</h2>

<p>To set up and use this project, follow these steps:</p>

<ol>
  <li>Create a virtual environment with the command:
  <pre><code>python -m venv venv</code></pre>
  </li>
  <li>Activate the virtual environment with:
  <pre><code>venv\Scripts\Activate</code></pre>
  </li>
  <li>Install the dependencies with pip:
  <pre><code>pip install -r requirements.txt</code></pre>
  </li>
</ol>

<h2>Usage</h2>

<p>To run the script, use the following command:</p>

<pre><code>python language_detector.py</code></pre>

<p>Alternatively, you can run the <code>language_detector.exe</code> file.</p>

<p>To use the application, simply drag and drop a docx file into the designated area. The detected language and its confidence level will be displayed. You can then click the "Detect and Rename" button to rename the file with the detected language suffix.</p>

<h2>Known issues</h2>

<ul>
  <li>The <code>langdetect</code> library may not always provide accurate language detection, particularly for short or ambiguous input texts.</li>
</ul>

<h2>Future development</h2>

<ul>
<li>Add support for detecting language of other file types, such as PDF or TXT.</li>
  <li>Allow for batch processing of multiple files at once.</li>
  <li>Implement a way to automatically move or organize the renamed files into separate folders based on their detected language.</li>
</ul>

<h2>Dependencies</h2>

<ul>
  <li>PyQt5</li>
  <li>docx2txt</li>
  <li>langdetect</li>
  <li>shutil</li>
</ul>
</ul>

<h2>Third-party libraries</h2>

<ul>
  <li><code>langdetect</code>: Library for detecting the language of a given text. (<a href="https://github.com/Mimino666/langdetect">GitHub</a>, <a href="https://github.com/Mimino666/langdetect/blob/master/LICENSE">MIT License</a>)</li>
</ul>
