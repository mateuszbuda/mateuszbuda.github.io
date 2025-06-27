---
title: "Resume"
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

	Machine learning research engineer and AI product developer<br />

	<hr />

	<h3>Education</h3>
	<p><strong><a href="https://eng.pw.edu.pl" target="_blank">Warsaw University of Technology</a></strong>, Poland</p>
	<p>Doctor of Philosophy, 2021 - 2025</p>
	<p>Thesis: <i>Computer-aided image-based diagnosis: extensions of computational models with domain knowledge.</i></p>
	<p>
		Supervisors: <a href="https://ww2.mini.pw.edu.pl/wydzial/pracownicy/prac_przelaskowski_artur/" target="_blank">Artur Przelaskowski, Ph.D.</a>, <a href="https://sites.duke.edu/mazurowski/" target="_blank">Maciej A. Mazurowski, Ph.D.</a>
	</p>
 	<p>
		Examiner: <a href="https://pbiecek.github.io" target="_blank">Przemysław Biecek, Ph.D.</a>
	</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p><strong><a href="https://www.kth.se/en" target="_blank">KTH Royal Institute of Technology</a></strong>, Stockholm, Sweden</p>
	<p>Master of Science in Machine Learning, 2015 - 2017</p>
	<p>Thesis: <i>A systematic study of the class imbalance problem in convolutional neural networks.</i></p>
	<p>
		Supervisors: <a href="http://www.csc.kth.se/~atsuto/" target="_blank">Atsuto Maki, Ph.D.</a>, <a href="https://sites.duke.edu/mazurowski/" target="_blank">Maciej A. Mazurowski, Ph.D.</a>
	</p>
	<p>
		Examiner: <a href="https://www.kth.se/profile/ala" target="_blank">Anders B. Lansner, Ph.D.</a>
	</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p><strong><a href="https://eng.pw.edu.pl" target="_blank">Warsaw University of Technology</a></strong>, Poland</p>
	<p>Bachelor of Engineering in Computer Science, 2011 - 2015</p>
	<p>
		Thesis: <i>OCR system for text recognition in images of specified type.</i><br>
		Image to text API with custom OCR component and mobile application.
	</p>
	<p>
		Supervisor: <a href="https://pages.mini.pw.edu.pl/~lucknerm/en/" target="_blank">Marcin Luckner, Ph.D.</a>
		<p>
		Examiner: <a href="https://www.mini.pw.edu.pl/~homenda/index2.php" target="_blank">Władysław Homenda, Ph.D.</a>
	</p>
	</p>

	<hr />

	<h3>Research</h3>
	<p>
		<strong><a href="https://duke.edu" target="_blank">Duke University</a></strong>, Durham, NC, USA<br>
		Department of Radiology<br>
		Carl E. Ravin Advanced Imaging Laboratories
	</p>
	<p>Associate in Research</p>
	<p>January 2017 - July 2019</p>
	<p>
		<ul>
			<li>A systematic study of the class imbalance problem in convolutional neural networks.</li>
			<li>Brain segmentation in magnetic resonance images for prediction of tumor genomics.</li>
			<li>Classification of brain tumor to molecular subtypes based on magnetic resonance images using transfer learning.</li>
			<li>Deep learning for detection, segmentation, and risk level stratification of thyroid nodules in ultrasound images with multi-task learning.</li>
			<li>Applications of genetic algorithms to optimization of a system for risk stratification of thyroid nodules based on ultrasound imaging features.</li>
			<li>Detection of cancer in 3D digital breast tomosynthesis volumes using eye tracking data.</li>
			<li>Recruiting and supervising undergraduate students and preparing teaching materials.</li>
		</ul>
	</p>
	
	<hr style="border-top: 1px solid Gainsboro;">
	
	<p>Served as a reviewer for:</p>
	<p>
		<ul>
			<li><a href="https://www.journals.elsevier.com/neural-networks" target="_blank">Neural Networks</a></li>
			<li><a href="https://link.springer.com/journal/10462" target="_blank">Artificial Intelligence Review</a></li>
			<li><a href="https://www.journals.elsevier.com/computers-in-biology-and-medicine" target="_blank">Computers in Biology and Medicine</a></li>
			<li><a href="https://link.springer.com/journal/10618" target="_blank">Data Mining and Knowledge Discovery</a></li>
			<li><a href="http://www.jmlr.org" target="_blank">The Journal of Machine Learning Research</a></li>
			<li><a href="https://pubs.rsna.org/journal/ai" target="_blank">Radiology: Artificial Intelligence</a></li>
			<li><a href="https://eccv2022.ecva.net" target="_blank">European Conference on Computer Vision</a></li>
		</ul>
	</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p>Talks at conferences and seminars:</p>
	<p>
		<ul>
			<li>
				Management of thyroid nodules seen on US images: deep learning may match performance of radiologists at <a href="http://aidmed.pl" target="_blank">seminarium naukowe "Informatyka w medycynie i biologii"</a> na <a href="https://ww2.mini.pw.edu.pl" target="_blank">Wydziale Matematyki i Nauk Informacyjncyh</a> <a href="https://www.pw.edu.pl" target="_blank">Politechniki Warszawskiej</a>
			</li>
			<li>
				Radiologist-level deep learning for management of thyroid nodules based on US images at <a href="https://conference2019.mlinpl.org" target="_blank">ML in PL Conference 2019</a>
				<p style="text-align: center">
					<iframe width="560" height="315" src="https://www.youtube.com/embed/VMZnv5vWhUM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
				</p>
			</li>
		</ul>
	</p>

	<hr />

	<h3>Experience</h3>
	<p><strong><a href="https://narf.ai" target="_blank">Narf AI</a></strong>, Warsaw, Poland</p>
	<p>Co-founder</p>
	<p>January 2019 - ongoing</p>
	<p>
	<ul>
		<li>Data science consulting and AI product development.</li>
	</ul>
	</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p><strong><a href="https://www.iqvia.com" target="_blank">IQVIA</a></strong>, Warsaw, Poland</p>
	<p>Senior Machine Learning Engineer</p>
	<p>August 2019 - ongoing</p>
	<p>
	<ul>
		<li>Artificial Intelligence for Life Science Organizations.</li>
	</ul>
	</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p><strong><a href="https://scrapingfish.com" target="_blank">Scraping Fish</a></strong>, Warsaw, Poland</p>
	<p>Co-founder</p>
	<p>April 2022 - ongoing</p>
	<p>
	<ul>
		<li>Web scraping API and data extraction solution.</li>
	</ul>
	</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p><strong><a href="https://skysnap.pl" target="_blank">SkySnap</a></strong>, Warsaw, Poland</p>
	<p>Senior Machine Learning Engineer</p>
	<p>May 2021 - November 2022</p>
	<p>
	<ul>
		<li>Machine learning for processing of geospatial data.</li>
		<li>Classification and segmentation of 3D point cloud data.</li>
	</ul>
	</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p><strong><a href="https://www.withintent.com" target="_blank">Intent</a></strong> (formerly inFullMobile), Warsaw, Poland</p>
	<p>Software Engineer - iOS Applications Developer</p>
	<p>February 2015 - August 2016</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p><strong><a href="https://www.senfino.com" target="_blank">Senfino</a></strong>, Warsaw, Poland</p>
	<p>Software Engineer - iOS Applications Developer</p>
	<p>June 2014 - January 2015</p>

	<hr style="border-top: 1px solid Gainsboro;">

	<p><strong><a href="http://www.lacan.com.pl" target="_blank">Lacan Technologies</a></strong>, Warsaw, Poland</p>
	<p>Junior Network Administrator</p>
	<p>October 2011 - January 2012</p>

	<hr />

	<h3>Certifications</h3>
	<p>End-to-End Machine Learning with TensorFlow on GCP by Google - August 2020 (<a href="https://www.coursera.org/account/accomplishments/certificate/6VGX9VZVWDLY" target="_blank">6VGX9VZVWDLY</a>)</p>
	<p>Getting Started with Google Kubernetes Engine by Google - May 2019 (<a href="https://www.coursera.org/account/accomplishments/verify/BQY6FKM5BURR" target="_blank">BQY6FKM5BURR</a>)</p>
	<p>How Google does Machine Learning by Google - Spetember 2018 (<a href="https://www.coursera.org/account/accomplishments/verify/6UW3H8MVHMCZ" target="_blank">6UW3H8MVHMCZ</a>)</p>
	<p>Google Cloud Platform Big Data and Machine Learning Fundamentals by Google - Spetember 2018 (<a href="https://www.coursera.org/account/accomplishments/verify/NZSLNJFXG5TV" target="_blank">NZSLNJFXG5TV</a>)</p>
	<p>Data Science Math Skills by Duke University - July 2018 (<a href="https://www.coursera.org/account/accomplishments/verify/B29PQULU6RDY" target="_blank">B29PQULU6RDY</a>)</p>
	<p>Pattern Discovery in Data Mining by University of Illinois at Urbana-Champaign - March 2015 (<a href="https://www.coursera.org/account/accomplishments/verify/YPUDJ6JQ6E" target="_blank">YPUDJ6JQ6E</a>)</p>

	<hr />
</div>
