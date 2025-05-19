---
layout: archive
permalink: /academic/
author_profile: true
---

<style>
    /* Main container styles */
    .academic-container {
        max-width: 900px;
        margin: 0 auto;
        padding: 0 20px;
        background: #ffffff;
    }

    /* Section header styles */
    .section-header {
        text-align: center;
        padding: 20px 0;
        position: relative;
        margin: 0;
    }
    .section-header h1 {
        font-size: 2.5em;
        color: #2c3e50;
        margin: 0;
        position: relative;
        display: inline-block;
    }
    .section-header h1::after {
        content: '';
        position: absolute;
        bottom: -10px;
        left: 0;
        width: 100%;
        height: 4px;
        background: linear-gradient(90deg, #3498db, #2ecc71);
        border-radius: 2px;
    }

    /* Card container */
    .academic-list {
        display: flex;
        flex-direction: column;
        gap: 30px;
        padding: 20px 0;
    }

    /* Card styles */
    .academic-card {
        background: white;
        border-radius: 15px;
        padding: 35px;
        box-shadow: 0 10px 30px rgba(0,0,0,0.05);
        transition: all 0.3s ease;
        position: relative;
        overflow: hidden;
        border-left: 5px solid;
    }
    .academic-card:hover {
        transform: translateX(10px);
        box-shadow: 0 15px 40px rgba(0,0,0,0.1);
    }

    /* Education specific styles */
    .education-card {
        background: linear-gradient(135deg, #fff 0%, #f8f9fa 100%);
        border-left-color: #3498db;
    }

    /* Teaching specific styles */
    .teaching-card {
        background: linear-gradient(135deg, #fff 0%, #f8f9fa 100%);
        border-left-color: #2ecc71;
    }

    /* Card content styles */
    .card-title {
        font-size: 1.6em;
        color: #2c3e50;
        margin-bottom: 15px;
        font-weight: bold;
    }
    .card-subtitle {
        color: #7f8c8d;
        font-size: 1.2em;
        margin-bottom: 20px;
    }
    .card-content {
        color: #34495e;
        line-height: 1.8;
        font-size: 1.1em;
    }
    .card-content strong {
        color: #2c3e50;
    }
    .card-content a {
        color: #3498db;
        text-decoration: none;
        transition: all 0.3s ease;
        position: relative;
    }
    .card-content a::after {
        content: '';
        position: absolute;
        bottom: -2px;
        left: 0;
        width: 0;
        height: 2px;
        background: #3498db;
        transition: width 0.3s ease;
    }
    .card-content a:hover::after {
        width: 100%;
    }

    /* Teaching specific link styles */
    .teaching-card .card-content a {
        color: #2ecc71;
    }
    .teaching-card .card-content a::after {
        background: #2ecc71;
    }

    /* Section spacing */
    .section {
        margin-bottom: 40px;
    }

    /* Bullet point styles */
    .card-content li {
        list-style-type: none;
        position: relative;
        padding-left: 20px;
    }
    .card-content li::before {
        content: '•';
        position: absolute;
        left: 0;
        color: #2c3e50;
    }

    /* Responsive design */
    @media (max-width: 768px) {
        .academic-container {
            padding: 0 15px;
        }
        .academic-card {
            padding: 25px;
        }
        .card-title {
            font-size: 1.4em;
        }
        .card-subtitle {
            font-size: 1.1em;
        }
        .card-content {
            font-size: 1em;
        }
    }
</style>

<div class="academic-container">
    <div class="section">
        <div class="section-header">
            <h1>Education</h1>
        </div>

        <div class="academic-list">
            <div class="academic-card education-card">
                <div class="card-title">B.Sc. in Computer Science and Engineering</div>
                <div class="card-subtitle">Ahsanullah University of Science and Technology (AUST), Dhaka, Bangladesh</div>
                <div class="card-content">
                    <strong>CGPA:</strong> 3.081 <i>out of 4.00</i><br>
                    <strong>Thesis:</strong> <a href="../files/Research/ReportByte.pdf">ReportByte: An advanced business analytics system</a><br>
                    <i>An advanced business analytic and assistant system which provides four kinds of services <b>(Chatbot, Question answering bot, Data visualization tool, and Predictive data analysis tool)</b> built with machine learning and artificial intelligence tools.</i><br>
                    <strong>Supervisor:</strong> <a href="https://scholar.google.com/citations?user=-2fbkokAAAAJ&hl=en">Md Moinul Hoque</a>, Associate Professor, Department of CSE, AUST
                </div>
            </div>
        </div>
    </div>

    <div class="section">
        <div class="section-header">
            <h1>Teaching Experiences</h1>
        </div>

        <div class="academic-list">
            <div class="academic-card teaching-card">
                <div class="card-title">Educator</div>
                <div class="card-subtitle"><a href="https://amarischool.com/">Amar iSchool</a></div>
                <div class="card-content">
                    <strong>Course:</strong> <a href="https://amarischool.com/courses/System-Design-Course--Zero-to-Intermediate-64ea1ed8e4b00cb1044f6f2c">System Design Course : Zero to Intermediate</a><br>
                    <strong>Topics Covered:</strong> Computer Architecture, Networking Basics, Database, REST API etc
                </div>
            </div>

            <div class="academic-card teaching-card">
                <div class="card-title">Competitive Programming Trainer</div>
                <div class="card-subtitle">CSE Department (AUST), Dhaka, Bangladesh</div>
                <div class="card-content">
                    <ul>
                        <li>Taught students advanced <strong>data structures and algorithms</strong> of competitive Programming</li>
                        <li>Trained few teams for National programming contest</li>
                    </ul>
                </div>
            </div>

            <div class="academic-card teaching-card">
                <div class="card-title">Programming Workshop Conductor</div>
                <div class="card-content">
                    <ul>
                        <li><a href="https://www.facebook.com/amarischool24/videos/915637786668317">System Design Roadmap</a></li>
                        <li><a href="https://www.youtube.com/watch?v=YtDXX9l8yGk&t=2008s&ab_channel=MicrosoftLearnStudentAmbassadors-Bangladesh">Competitive Programming Beginner Guide</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>