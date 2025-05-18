---
layout: archive
permalink: /activities/
author_profile: true
title: "Activities"
---

<style>
    .timeline {
        position: relative;
        max-width: 1200px;
        margin: 0 auto;
    }
    .timeline::after {
        content: '';
        position: absolute;
        width: 4px;
        background-color: #3498db;
        top: 0;
        bottom: 0;
        left: 50%;
        margin-left: -2px;
        z-index: 1;
    }
    .year-container {
        padding: 10px 40px;
        position: relative;
        width: 100%;
        margin-bottom: 30px;
    }
    .year-title {
        text-align: center;
        font-size: 1.5em;
        color: #2c3e50;
        margin: 20px 0;
        font-weight: bold;
        position: relative;
        z-index: 2;
        background: white;
        padding: 5px 20px;
        display: inline-block;
        border-radius: 20px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        left: 50%;
        transform: translateX(-50%);
        border: 2px solid #3498db;
    }
    .activity-item {
        padding: 10px 30px;
        position: relative;
        background-color: inherit;
        width: 50%;
        margin-bottom: 10px;
    }
    .left {
        left: 0;
    }
    .right {
        left: 50%;
    }
    .left::after {
        right: -7.5px;
    }
    .right::after {
        left: -7.5px;
    }
    .activity-content {
        padding: 15px;
        background-color: #f8f9fa;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        transition: transform 0.3s ease;
    }
    .activity-content:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }
    .activity-date {
        color: #3498db;
        font-weight: bold;
        margin-bottom: 5px;
    }
    .activity-title {
        color: #2c3e50;
        margin: 0;
    }
    .activity-title a {
        color: #2c3e50;
        text-decoration: none;
        transition: color 0.3s ease;
    }
    .activity-title a:hover {
        color: #3498db;
    }
    @media screen and (max-width: 768px) {
        .timeline::after {
            left: 31px;
        }
        .activity-item {
            width: 100%;
            padding-left: 70px;
            padding-right: 25px;
        }
        .activity-item::after {
            left: 15px;
        }
        .left::after, .right::after {
            left: 15px;
        }
        .right {
            left: 0%;
        }
        .year-title {
            left: 31px;
            transform: none;
        }
    }
</style>

<div class="timeline">
    <div class="year-container">
        <div class="year-title">2025</div>
        {% include activity_template.html 
            date="Apr 30"
            title="Pariticipated in Poridhi AI Hackathon 2025"
            position="left" %}
    </div>

    <div class="year-container">
        <div class="year-title">2024</div>
        {% include activity_template.html 
            date="Nov 11"
            title="Ongoing research about Computer Vision"
            position="right" %}
    </div>

    <div class="year-container">
        <div class="year-title">2023</div>
        {% include activity_template.html 
            date="Jul 12"
            title="Published Paper: Invariant Scattering Transform for Medical Imaging"
            link="https://arxiv.org/pdf/2307.04771"
            position="left" %}
    </div>

    <div class="year-container">
        <div class="year-title">2022</div>
        {% include activity_template.html 
            date="Sep 22"
            title="Advanced to Round 2 of Meta Hacker Cup"
            position="right" %}
        {% include activity_template.html 
            date="May 17"
            title="Completed academic thesis work: ReportByte: An advanced business analytics system"
            link="../files/Research/ReportByte.pdf"
            position="left" %}
        {% include activity_template.html 
            date="Mar 26"
            title="Participated in Google Codejam '22"
            position="right" %}
    </div>

    <div class="year-container">
        <div class="year-title">2021</div>
        {% include activity_template.html 
            date="Dec 28"
            title="Co-founded AUST Programming and Infomatics Club"
            link="https://aust.edu/austpic"
            position="left" %}
        {% include activity_template.html 
            date="Apr 07"
            title="Participated in Google Codejam '21"
            position="right" %}
    </div>

    <div class="year-container">
        <div class="year-title">2020</div>
        {% include activity_template.html 
            date="Oct 15"
            title="Completed HacktoberFest in Github"
            position="left" %}
        {% include activity_template.html 
            date="Jun 25"
            title="Got invitation for Google Foobar Challenge"
            position="right" %}
        {% include activity_template.html 
            date="Apr 10"
            title="Achieved Expert Rank at Codeforces"
            link="https://codeforces.com/profile/edge555"
            position="left" %}
        {% include activity_template.html 
            date="Apr 15"
            title="Participated in Google Codejam '20"
            position="right" %}
        {% include activity_template.html 
            date="Mar 14"
            title="Placed 4th in a programming contest (EDU IUPC)"
            position="left" %}
    </div>

    <div class="year-container">
        <div class="year-title">2019</div>
        {% include activity_template.html 
            date="Oct 15"
            title="Completed HacktoberFest in Github"
            position="right" %}
        {% include activity_template.html 
            date="Sep 03"
            title="Selected as Microsoft Learn Student Ambassador"
            link="https://edge555.github.io/files/Certificates/microsoft-learn.pdf"
            position="left" %}
    </div>

    <div class="year-container">
        <div class="year-title">2018</div>
        {% include activity_template.html 
            date="Dec 26"
            title="Placed 4th in a programming contest (UIU Hacklab 1.0)"
            position="right" %}
        {% include activity_template.html 
            date="Nov 09"
            title="Participated in 10th National Undergraduate Mathematics Olympiad '18"
            link="https://edge555.github.io/files/Certificates/2018-national-math-olympiad.pdf"
            position="left" %}
        {% include activity_template.html 
            date="Oct 06"
            title="Completed Microsoft Young Bangla Internship"
            link="https://edge555.github.io/files/Certificates/2018-microsoft-young-bangla-internship.pdf"
            position="right" %}
        {% include activity_template.html 
            date="Jul 25"
            title="Selected for BACS programming camp"
            position="left" %}
        {% include activity_template.html 
            date="Jul 18"
            title="Got Most Spiritual Team award at Intra University Project Showcase Competition"
            link="https://edge555.github.io/files/Certificates/2018-most-spiritual-team-project-showcase.pdf"
            position="right" %}
    </div>
</div>