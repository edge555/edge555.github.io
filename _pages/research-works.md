---
layout: archive
permalink: /research-works/
author_profile: true
redirect_from:
  - /research
  - /publications
---

{% include base_path %}

<div style="border: 2px solid #2c3e50; 
            padding: 10px; 
            background-color: #f4f4f4;
            width: 100%;
            text-align: center;
            box-sizing: border-box;">
    <h1>Publications</h1>
</div>

<span> My research works and interest includes <b>NLP, LLM, GenAI</b> Here are some of my previous works,<span>
<!-- Publications-->

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on my <a href="{{site.author.googlescholar}}">Google Scholar profile</a>.</div>
{% endif %}

<i class='far fa-file'></i> [<span style="color:Blue;font-family:Trebuchet MS;">**Invariant Scattering Transform for Medical Imaging**</span>]<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors: </strong> Nafisa Labiba Ishrat Huda, Angona Biswas, MD Abdullah Al Nasim, Md. Fahim Rahman, <b>Shoaib Ahmed</b></font>
</span>
<br>

[<a style="color:red;" href="#" onclick="$('#neucom_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://arxiv.org/pdf/2307.04771)][<a style="color:red;" href="#" onclick="$('#neucom_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="neucom_bib" class="bib" style="display:none;">
	<pre>
		Huda, N. L., Biswas, A., Nasim, M. A., Rahman, M. F., & Ahmed, S. (2023). Invariant Scattering Transform for Medical Imaging. ArXiv. /abs/2307.04771
	</pre>
</div>

<div id="neucom_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			Invariant scattering transform introduces new area of research that merges the signal processing with deep learning for computer vision. Nowadays, Deep Learning algorithms are able to solve a variety of problems in medical sector. Medical images are used to detect diseases brain cancer or tumor, Alzheimer's disease, breast cancer, Parkinson's disease and many others. During pandemic back in 2020, machine learning and deep learning has played a critical role to detect COVID-19 which included mutation analysis, prediction, diagnosis and decision making. Medical images like X-ray, MRI known as magnetic resonance imaging, CT scans are used for detecting diseases. There is another method in deep learning for medical imaging which is scattering transform. It builds useful signal representation for image classification. It is a wavelet technique; which is impactful for medical image classification problems. This research article discusses scattering transform as the efficient system for medical image analysis where it's figured by scattering the signal information implemented in a deep convolutional network. A step by step case study is manifested at this research work.
		</font>
	</p>
</div>

---------
<!-- Projects-->
<div style="border: 2px solid #2c3e50; 
            padding: 10px; 
            background-color: #f4f4f4;
            width: 100%;
            text-align: center;
            box-sizing: border-box;">
    <h1>Projects</h1>
</div>
<div style="font-family: Arial, sans-serif; line-height: 1.6;">
    <i class="fa-brands fa-uncharted"></i>
    <b style="font-size: 1.3em; color: #2c3e50;">Rasa Chatbot</b><br>
    <span style="font-size: 1em; color: #34495e;">Completed on: September, 2021</span><br>
    <i style="font-size: 1em; color: #7f8c8d;">Rasa, NER</i><br>
    <p style="font-size: 1em; color: #2c3e50;">
        An implementation of a customer query chatbot using Rasa. The data is safe as it can be run locally. It can be used to query about products on an E-commerce website.
        <a href="https://github.com/edge555/Rasa-Chatbot" style="font-size: 1em; color: #2980b9; text-decoration: none;">Github Link</a>
    </p>
</div>

<div style="font-family: Arial, sans-serif; line-height: 1.6;">
    <i class="fa-brands fa-uncharted"></i>
    <b style="font-size: 1.3em; color: #2c3e50;">Natural Language Generation</b><br>
    <span style="font-size: 1em; color: #34495e;">Completed on: July, 2021</span><br>
    <i style="font-size: 1em; color: #7f8c8d;">T5 Model, PyTorch</i><br>
    <p style="font-size: 1em; color: #2c3e50;">
        An implementation of Natural Language Generation using T5 model and Pytorch. The whole process can be run locally.<br>
      <a href="https://github.com/edge555/T5-NLG-Demo"> Github Link</a> 
    </p>
</div>