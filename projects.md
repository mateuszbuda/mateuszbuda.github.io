---
title: "Projects"
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
	
	<div class="project-description">
		<p id="shortDesc1"><strong>Real-time Contrainer Tracking API</strong>, 2023</p>
		<div id="fullDesc1" style="display:block;">
		This project delivered an API for tracking sea container movements in real-time by scraping publicly available data.
		It successfully navigated through the complexities of bot detection and blocking systems using Scraping Fish API and employed custom-developed computer vision algorithms to solve CAPTCHAs and ensure uninterrupted data retrieval.
		It demonstrated a blend of web scraping proficiency and practical application in logistics and supply chain monitoring.
		</div>
		<!-- <button id="readMoreBtn1" class="readMoreBtn" onclick="toggleReadMore(1)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc2"><strong>Rotating Mobile Proxy and Webscraping API</strong>, 2022 - ongoing</p>
		<div id="fullDesc2" style="display:block;">
		A SaaS product under the banner of Scraping Fish, delivering a robust web scraping API.
		Managing a cluster of custom browsers, rotating proxies, JavaScript rendering, and CAPTCHAs solving.
		The innovative product operates on custom-made rotating mobile proxies.
		It offers users a seamless and efficient scraping experience, mitigating common web scraping hurdles such as IP bans and data retrieval from JavaScript-heavy pages.
		</div>
		<!-- <button id="readMoreBtn2" class="readMoreBtn" onclick="toggleReadMore(2)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc3"><strong>Forecasting Framework</strong>, 2020 - ongoing</p>
		<div id="fullDesc3" style="display:block;">
		Internal Python package with a suite of tools designed for comprehensive management of time series data, extending from initial processing to the predictive inference of machine learning models.
		Tailored to the needs of forecasting tasks, the framework enables robust time series feature engineering, training, and testing of machine learning models, including the implementation of state-of-the-art deep learning models.
		</div>
		<!-- <button id="readMoreBtn3" class="readMoreBtn" onclick="toggleReadMore(3)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc4"><strong>Multichannel Marketing Journey Optimization</strong>, 2020 - ongoing</p>
		<div id="fullDesc4" style="display:block;">
		Optimization and orchestration of customer journeys across multiple marketing channels to boost engagement and amplify product sales.
		Leveraging historical data on customer engagement, product sales, and customer demographics, the project employed time seties data modeling to enhance customer interaction and purchasing pathways.
		Furthermore, it provided insights into the efficacy of various marketing channels for specific customer.
		This endeavor not only paved the way for increased customer engagement and improved sales through personalized marketing strategies but also offered a lens into the effectiveness of different channels, facilitating data-driven decision-making in marketing initiatives.
		</div>
		<!-- <button id="readMoreBtn4" class="readMoreBtn" onclick="toggleReadMore(4)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc5"><strong>Inventory of Technical and Transportation Infrastructure</strong>, 2021 - 2022</p>
		<div id="fullDesc5" style="display:block;">
		Successful implementation of an efficient data pipeline for processing drone imagery data and development of machine learning models for object detection, semantic segmentation, as well as instance segmentation on 3D point cloud data.
		The created models were subsequently utilized by a system engineered to conduct an inventory and progress tracking on construction sites, specifically focusing on transportation and energy infrastructure.
		This innovative approach streamlined the operational oversight of construction and development projects. ensured accurate, timely, and automated updates to inventory and progress metrics.
		</div>
		<!-- <button id="readMoreBtn5" class="readMoreBtn" onclick="toggleReadMore(5)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc6"><strong>Real Estate Search Engine</strong>, 2019 - 2022</p>
		<div id="fullDesc6" style="display:block;">
		A comprehensive system for real estate data accumulation, management, and user interaction.
		Comprising a web scraping component for collecting public real estate data from the Internet and extracting structured information, API backend for managing data access alongside user and group management, while the web application facilitates users in executing real estate offer searches, creating filters, and managing notifications about newly matched offers.
		</div>
		<!-- <button id="readMoreBtn6" class="readMoreBtn" onclick="toggleReadMore(6)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc7"><strong>Machine Learning Statistical Toolkit</strong>, 2019 - 2022</p>
		<div id="fullDesc7" style="display:block;">
		Open source Python package that provides statistical functions, leveraging bootstrapping, to compute confidence intervals and p-values when comparing machine learning models to human readers.
		Designed to enhance rigor in model evaluation and empower research with robust statistical validation tools, this toolkit fosters methodological robustness in machine learning research and applications, making sophisticated statistical analyses accessible to developers and researchers alike.
		</div>
		<!-- <button id="readMoreBtn7" class="readMoreBtn" onclick="toggleReadMore(7)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc8"><strong>Computer-aided Diagnosis for Thyroid Nodules</strong>, 2018 - 2023</p>
		<div id="fullDesc8" style="display:block;">
		Research project for the detection and segmentation of thyroid nodules, with a pivotal contribution being the development of a multi-task Convolutional Neural Network (CNN) model for malignancy prediction of thyroid nodules from ultrasound (US) images, achieving radiologist-level accuracy.
		Stepping towards practical application, this system is in the pipeline for commercial deployment.
		Furthermore, in a collaboration with radiologists, the project optimized and simplified a thyroid nodule interpretation guideline system by employing a genetic algorithm, which, when tested by independent researchers globally, validated its robustness and efficacy.
		</div>
		<!-- <button id="readMoreBtn8" class="readMoreBtn" onclick="toggleReadMore(8)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc9"><strong>Computer-aided Diagnosis for Breast Cancer</strong>, 2018 - 2023</p>
		<div id="fullDesc9" style="display:block;">
		A collaborative effort with radiologists, the project involved curation and annotation of a 3D digital breast tomosynthesis dataset.
		Furthermore, a baseline cancer detection model was developed, alongside comprehensive data handling and evaluation code, all of which were made publicly available, bolstering the global collaborative research environment.
		The project also explored self-supervised learning approach, employing a strategy that utilized images without lesions to  detection method based on an image completion using Generative Adversarial Network.
		</div>
		<!-- <button id="readMoreBtn9" class="readMoreBtn" onclick="toggleReadMore(9)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<div class="project-description">
		<p id="shortDesc10"><strong>Radiogenomics</strong>, 2017 - 2020</p>
		<div id="fullDesc10" style="display:block;">
		Research project, conducted at Duke University, employing Convolutional Neural Networks (CNN) to harness critical insights into brain cancer therapy and prognosis estimates.
		This project used CNN for segmentation of brain tumors within MRI volumes, effectively extracting tumor volumetric features predictive of genomic subtypes and patient outcomes.
		Subsequent stages involved the development of a CNN model tasked with the direct prediction of tumor radiomic characteristics.
		</div>
		<!-- <button id="readMoreBtn10" class="readMoreBtn" onclick="toggleReadMore(10)">Expand details</button> -->
	</div>

	<hr style="border-top: 1px solid Gainsboro;">

	<!-- <p><strong>Second Screen iOS Application for a TV Station</strong></p>
	<p>
	An auxiliary mobile application, available on both iOS and Android, designed to extend the interactive viewer experience for a TV station.
	Enabling a real-time, two-way interaction, viewers could respond to live prompts, participate in surveys, cast votes, and send messages to be displayed during broadcasts.
	</p>

	<hr style="border-top: 1px solid Gainsboro;"> -->

	<div class="project-description">
		<p id="shortDesc11"><strong>Word Predictor</strong>, 2016</p>
		<div id="fullDesc11" style="display:block;">
		Word Predictor aimed to optimize text input on mobile platforms, providing a streamlined user experience on both iOS and Android.
		This predictive framework, implemented in C++, utilized a Hidden Markov Model to enable next-word prediction and word completion in mobile keyboard applications.
		</div>
		<!-- <button id="readMoreBtn11" class="readMoreBtn" onclick="toggleReadMore(11)">Expand details</button> -->
	</div>

	<hr />
</div>
