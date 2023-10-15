---
title: "Publications"
---

<style>
p {
	text-align: left;
    padding-top: 0.0em;
    padding-bottom: 0.0em;
}
hr {
    display: block;
    height: 1px;
    border: 0;
    border-top: 1px solid black;
    margin: 1em auto;
    padding: 0;
}
.img-circle {
    border-radius: 20%;
}
.tag-text {
	-moz-border-radius: 15px;
	border-radius: 15px;
    border: solid 1px black;
    padding: 5px 10px;
}
.tag-text:hover {
	background-color: #F5F5F5;
}
#content {
	padding-left: 6px;
	overflow: hidden;
}
#sidebar {
	float: left;
	min-width: 144px;
	height: 100%;
	padding-left: 12px;
	padding-right: 24px;
	padding-bottom: 24px;
}
.project-description {
  max-width: 600px;
  margin: auto;
}
.readMoreBtn {
  margin-top: 0px;
  padding: 5px 15px;
  cursor: pointer;
  min-width: 110px;
  background-color: silver; /* your desired color */
  color: white;
  border: none;
  border-radius: 5px;
}
.readMoreBtn:hover {
  background-color: gray; /* your desired hover color */
}
@media only screen and (max-width: 600px) {
	#content {
		padding-left: 12px;
		float: left;
	}
}
</style>

<script>
function toggleReadMore(projectNumber) {
  var fullDesc = document.getElementById("fullDesc" + projectNumber);
  var btnText = document.getElementById("readMoreBtn" + projectNumber);

  if (fullDesc.style.display === "none") {
    fullDesc.style.display = "block";
	btnText.style.marginTop = "10px";
    btnText.innerHTML = "Collapse";
  } else {
    fullDesc.style.display = "none";
	btnText.style.marginTop = "0px";
    btnText.innerHTML = "Expand details";
  }
}
</script>


<div id="sidebar">
	<img class="img-circle" src="/images/photo.jpg" width="128px" height="128px">
	<p></p>
	<h3>Mateusz Buda</h3>
	<p><span class="tag-text">Machine Learning</span></p>
	<p><span class="tag-text">Neural Networks</span></p>
	<p><span class="tag-text">Computer Vision</span></p>
	<p><span class="tag-text">Medical Imaging</span></p>
	<p><span class="tag-text">Predictive Modeling</span></p>
	<p><span class="tag-text">Time Series Analysis</span></p>
	<p><span class="tag-text">Optimization</span></p>
	<p><span class="tag-text">Data Extraction</span></p>
</div>

<div id="content">

	<p>
		Jingxi Weng, Benjamin Wildman-Tobriner, <strong>Mateusz Buda</strong>, Jichen Yang, Lisa M. Ho, Brian C. Allen, Wendy L. Ehieli, Chad M. Miller, Jikai Zhang, and Maciej A. Mazurowski. <i><a href="https://doi.org/10.1016/j.clinimag.2023.04.010" target="_blank">Deep Learning for Classification of Thyroid Nodules on Ultrasound: Validation on an Independent Dataset</a></i> Clinical Imaging, 2023.
	</p>
	<p>
		<strong>Mateusz Buda</strong>, Nicholas Konz, Mateusz Buda, Hanxue Gu, Ashirbani Saha, Jichen Yang, Jakub Chłędowski, Jungkyu Park, et al. <i><a href="https://doi.org/doi:10.1001/jamanetworkopen.2023.0524" target="_blank">A Competition, Benchmark, Code, and Data for Using Artificial Intelligence to Detect Lesions in Digital Breast Tomosynthesis</a></i> JAMA Network Open, 2023.
	</p>
	<p>
		Paulina Zachar, Wojciech Ostrowski, Krzysztof Bakuła, <strong>Mateusz Buda</strong>, Maksymilian Foltyn, Radosław Palak, Konrad Sosnowicz. <i><a href="https://www.fig.net/resources/proceedings/fig_proceedings/fig2022/papers/ts02c/TS02C_zachar_ostrowski_et_al_11691.pdf" target="_blank">"Application of AI tools to the inventory of technical and transportation infrastructure based on UAV data."</a></i> FIG Congress, 2022.
	</p>
	<p>
		<strong>Mateusz Buda</strong>, Ashirbani Saha, Ruth Walsh, Sujata Ghate, Nianyi Li, Albert Święcicki, Joseph Y. Lo, Maciej A. Mazurowski. <i><a href="https://doi.org/10.1001/jamanetworkopen.2021.19100" target="_blank">A Data Set and Deep Learning Algorithm for the Detection of Masses and Architectural Distortions in Digital Breast Tomosynthesis Images.</a></i> JAMA Network Open, 2021.
	</p>
	<p>
		Albert Święcicki, Nicholas Konz, <strong>Mateusz Buda</strong>, Maciej A. Mazurowski. <i><a href="https://doi.org/10.1038/s41598-021-89626-1" target="_blank">A generative adversarial network-based abnormality detection using only normal images for model training with application to digital breast tomosynthesis.</a></i> Scientific Reports, 2021.
	</p>
	<p>
		Albert Święcicki, <strong>Mateusz Buda</strong>, Ashirbani Saha, Nianyi Li, Sujata V Ghate, Ruth Walsh, Maciej A Mazurowski. <i><a href="https://doi.org/10.1117/12.2551379" target="_blank">Generative adversarial network-based image completion to identify abnormal locations in digital breast tomosynthesis images.</a></i> Medical Imaging 2020: Computer-Aided Diagnosis.
	</p>
	<p>
		Albert Święcicki, Nicholas Said, Jonathan O'Donnell, <strong>Mateusz Buda</strong>, Nianyi Li, William A Jiranek, Maciej A Mazurowski. <i><a href="https://doi.org/10.1117/12.2551377" target="_blank">Automatic estimation of knee joint space narrowing by deep learning segmentation algorithms.</a></i> Medical Imaging 2020: Computer-Aided Diagnosis.
	</p>
	<p>
		Gourav Modanwal, Adithya Vellal, <strong>Mateusz Buda</strong>, Maciej A Mazurowski. <i><a href="https://doi.org/10.1117/12.2551301" target="_blank">MRI image harmonization using cycle-consistent generative adversarial network.</a></i> Medical Imaging 2020: Computer-Aided Diagnosis.
	</p>
	<p>
		<strong>Mateusz Buda</strong>, Ehab A AlBadawy, Ashirbani Saha, Maciej A Mazurowski. <i><a href="https://doi.org/10.1148/ryai.2019180050" target="_blank">Deep Radiogenomics of Lower-Grade Gliomas: Convolutional Neural Networks Predict Tumor Genomic Subtypes Using MR Images.</a></i> Radiology: Artificial Intelligence, 2020.
	</p>
	<p>
		<strong>Mateusz Buda</strong>, Benjamin Wildman-Tobriner, Kerry Castor, Jenny K Hoang, Maciej A Mazurowski. <i><a href="https://doi.org/10.1016/j.ultrasmedbio.2019.10.003" target="_blank">Deep Learning-Based Segmentation of Nodules in Thyroid Ultrasound: Improving Performance by Utilizing Markers Present in the Images.</a></i> Ultrasound in Medicine & Biology, 2020.
	</p>
	<p>
		<strong>Mateusz Buda</strong>, Benjamin Wildman-Tobriner, Jenny K Hoang, David Thayer, Franklin N Tessler, William D Middleton, Maciej A Mazurowski. <i><a href="https://doi.org/10.1148/radiol.2019181343" target="_blank">Management of Thyroid Nodules Seen on US Images: Deep Learning May Match Performance of Radiologists.</a></i> Radiology, 2019.
	</p>
	<p>
		Benjamin Wildman-Tobriner, <strong>Mateusz Buda</strong>, Jenny K Hoang, William D Middleton, David Thayer, Ryan G Short, Franklin N Tessler, Maciej A Mazurowski. <i><a href="https://doi.org/10.1148/radiol.2019182128" target="_blank">Using Artificial Intelligence to Revise ACR TI-RADS Risk Stratification of Thyroid Nodules: Diagnostic Accuracy and Utility.</a></i> Radiology, 2019.
	</p>
	<p>
		<strong>Mateusz Buda</strong>, Ashirbani Saha, Maciej A Mazurowski. <i><a href="https://doi.org/10.1016/j.compbiomed.2019.05.002" target="_blank">Association of Genomic Subtypes of lower-grade gliomas with shape features automatically extracted by a deep learning algorithm.</a></i> Computers in Biology and Medicine, 2019.
	</p>
	<p>
		Maciej A Mazurowski, <strong>Mateusz Buda</strong>, Ashirbani Saha, Mustafa R. Bashir. <i><a href="https://doi.org/10.1002/jmri.26534" target="_blank">Deep learning in radiology: An overview of the concepts and a survey of the state of the art with focus on MRI.</a></i> Journal of Magnetic Resonance Imaging, 2018.
	</p>
	<p>
		<strong>Mateusz Buda</strong>, Atsuto Maki, Maciej A Mazurowski. <i><a href="https://doi.org/10.1016/j.neunet.2018.07.011" target="_blank">A systematic study of the class imbalance problem in convolutional neural networks.</a></i> Neural Networks, 2018.
	</p>
	<p>
		<a href="https://scholar.google.com/citations?user=xJRY-IIAAAAJ" target="_blank">Google Scholar Profile</a>
	</p>

	<hr />
</div>
