---
layout: archive
permalink: /research-works/
author_profile: true
redirect_from:
  - /research
  - /publications
---

{% include base_path %}

<style>
    /* Main container styles */
    .research-container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
    }

    /* Section header styles */
    .section-header {
        color: white;
        padding: 20px;
        border-radius: 10px;
        margin: 0 0 30px 0;
        text-align: center;
        box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        transform: translateY(0);
        transition: transform 0.3s ease;
    }
    .section-header:hover {
        transform: translateY(-5px);
    }

    /* Publications specific styles */
    .publications-header {
        background: linear-gradient(135deg, #2c3e50 0%, #3498db 100%);
    }

    /* Projects specific styles */
    .projects-header {
        background: linear-gradient(135deg, #8e44ad 0%, #9b59b6 100%);
    }

    /* Research interests section */
    .research-interests {
        background: #f8f9fa;
        padding: 20px;
        border-radius: 10px;
        margin: 20px 0;
        border-left: 5px solid #3498db;
        animation: fadeIn 1s ease;
    }

    /* Publication card styles */
    .publication-card {
        background: white;
        border-radius: 10px;
        padding: 20px;
        margin: 20px 0;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        transition: all 0.3s ease;
        animation: slideIn 0.5s ease;
        border-left: 5px solid #3498db;
    }
    .publication-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 20px rgba(0,0,0,0.15);
    }

    /* Project card styles */
    .project-card {
        background: white;
        border-radius: 10px;
        padding: 20px;
        margin: 20px 0;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        transition: all 0.3s ease;
        animation: slideIn 0.5s ease;
        border-left: 5px solid #9b59b6;
    }
    .project-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 20px rgba(0,0,0,0.15);
    }

    /* Title styles */
    .publication-title {
        color: #2c3e50;
        font-size: 1.4em;
        font-weight: bold;
        margin-bottom: 10px;
    }
    .project-title {
        color: #2c3e50;
        font-size: 1.4em;
        font-weight: bold;
        margin-bottom: 10px;
    }

    /* Author styles */
    .authors {
        color: #34495e;
        font-size: 1.1em;
        margin-bottom: 15px;
    }

    /* Link styles */
    .action-links a {
        color: #3498db;
        text-decoration: none;
        margin-right: 15px;
        transition: color 0.3s ease;
    }
    .action-links a:hover {
        color: #2980b9;
    }

    /* Abstract and citation styles */
    .abstract, .bib {
        background: #f8f9fa;
        padding: 15px;
        border-radius: 5px;
        margin-top: 10px;
        display: none;
    }

    /* Project details styles */
    .project-details {
        color: #7f8c8d;
        font-size: 0.9em;
        margin: 10px 0;
    }
    .project-description {
        color: #2c3e50;
        margin: 10px 0;
    }
    .project-link {
        color: #9b59b6;
        text-decoration: none;
        transition: color 0.3s ease;
    }
    .project-link:hover {
        color: #8e44ad;
    }

    /* Animations */
    @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
    }

    @keyframes slideIn {
        from {
            opacity: 0;
            transform: translateY(20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    /* Responsive design */
    @media (max-width: 768px) {
        .research-container {
            padding: 10px;
        }
        .publication-card, .project-card {
            padding: 15px;
        }
    }
</style>

<div class="research-container">
    <div class="section-header publications-header">
        <h1>Publications</h1>
    </div>

    <div class="research-interests">
        <span>My research work and interests include <b>Computer Vision, NLP, GenAI and Virtual Reality</b>. Here are some of my previous works:</span>
    </div>

    <!-- Publications -->
    <div class="publication-card">
        <div class="publication-title">
            <i class='far fa-file'></i> Invariant Scattering Transform for Medical Imaging
        </div>
        <div class="authors">
            <strong>Authors:</strong> Nafisa Labiba Ishrat Huda, Angona Biswas, MD Abdullah Al Nasim, Md. Fahim Rahman, <b>Shoaib Ahmed</b>
        </div>
        <div class="action-links">
            [<a href="#" onclick="$('#neucom_abstract').toggle();return false;">Abstract</a>] 
            [<a href="https://arxiv.org/pdf/2307.04771">PDF</a>]
            [<a href="#" onclick="$('#neucom_bib').toggle();return false;">Citation bib</a>]
        </div>

        <div id="neucom_bib" class="bib">
            <pre>
                Huda, N. L., Biswas, A., Nasim, M. A., Rahman, M. F., & Ahmed, S. (2023). Invariant Scattering Transform for Medical Imaging. ArXiv. /abs/2307.04771
            </pre>
        </div>

        <div id="neucom_abstract" class="abstract">
            <p style="text-align:justify;">
                Invariant scattering transform introduces a new area of research that merges signal processing with deep learning for computer vision. Nowadays, deep learning algorithms can solve various problems in the medical sector. Medical images are used to detect diseases such as brain cancer or tumor, Alzheimer's disease, breast cancer, Parkinson's disease, and many others. During the pandemic in 2020, machine learning and deep learning played a critical role in detecting COVID-19, which included mutation analysis, prediction, diagnosis, and decision-making. Medical images like X-rays, MRI (magnetic resonance imaging), and CT scans are used for detecting diseases. Another method in deep learning for medical imaging is scattering transform. It builds useful signal representations for image classification. It is a wavelet technique that is impactful for medical image classification problems. This research article discusses scattering transform as an efficient system for medical image analysis, where it's figured by scattering the signal information implemented in a deep convolutional network. A step-by-step case study is manifested in this research work.
            </p>
        </div>
    </div>

    {% if site.author.googlescholar %}
    <div class="research-interests">
        You can also find my articles on my <a href="{{site.author.googlescholar}}">Google Scholar profile</a>.
    </div>
    {% endif %}

    <div class="section-header projects-header">
        <h1>Projects</h1>
    </div>

    <!-- Projects -->
    <div class="project-card">
        <div class="project-title">
            <i class="fa-brands fa-uncharted"></i> Rasa Chatbot
        </div>
        <div class="project-details">
            <span>Completed on: September 2021</span><br>
            <i>Rasa, NER</i>
        </div>
        <div class="project-description">
            An implementation of a customer query chatbot using Rasa. The data is safe as it can be run locally. It can be used to query about products on an E-commerce website.
            <a href="https://github.com/edge555/Rasa-Chatbot" class="project-link">GitHub Link</a>
        </div>
    </div>

    <div class="project-card">
        <div class="project-title">
            <i class="fa-brands fa-uncharted"></i> Natural Language Generation
        </div>
        <div class="project-details">
            <span>Completed on: July 2021</span><br>
            <i>T5 Model, PyTorch</i>
        </div>
        <div class="project-description">
            An implementation of Natural Language Generation using the T5 model and PyTorch, trained with the WebNLG 2020 dataset. The project can be run locally.
            <a href="https://github.com/edge555/T5-NLG-Demo" class="project-link">GitHub Link</a>
        </div>
    </div>
</div>
