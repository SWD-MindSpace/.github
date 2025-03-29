# MindSpace - School Mental Health Management System
<div align="center">
    <img src="./readme/images/logo.jpg" alt="MindSpace" height='80px'/>
    <p>MindSpace is a web application that provides mental health services for high school students and parents.</p>
</div>
<div align='center'>
<img src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=fff"> 
<img src="https://custom-icon-badges.demolab.com/badge/Microsoft%20SQL%20Server-CC2927?logo=mssqlserver-white&logoColor=white"> 
<img src="https://img.shields.io/badge/Redis-%23DD0031.svg?logo=redis&logoColor=white"> 
<img src="https://img.shields.io/badge/Docker-Yes-green"> 
<img src="https://img.shields.io/badge/Server-Yes-green"> 
<img src="https://img.shields.io/badge/API-Yes-green">
<br>
</div>

## Table of Contents
<ol start="0"> 
    <li><a href="#intro">Introduction</a></li>
    <li><a href="#tech">Tech Stacks</a></li>
    <li><a href="#uc-diagram">Use Case Diagram</a></li>
    <li><a href="#uc-diagram">Architecture Diagram</a></li>
    <li><a href="#db-design">Database Design</a></li>
    <li><a href="#screen-flow"> Screen Flow</a></li>
    <li><a href="#team-members">Team Members</a></li>
    <li>
        <a href="#app-a">Appendix A</a>
    </li>
</ol>


<a id="intro"></a>
## 0. Introduction
The increasing concern for students' mental health in Vietnamese schools highlights the need for a structured psychological support system. 
Currently, many schools lack a standardized approach to managing students' well-being. 
MindSpace aims to bridge this gap by providing a digital platform where students can access professional counseling services, schools can monitor overall student mental health trends, and psychologists can offer their expertise.

## Core Features

- **Psychological Assessments**: Students can take structured psychological tests to evaluate their mental health.
- **Supporting Programs**: Schools provide students with three free Supporting Programs through workshops and webinars for specific targets (e.g., school mental health, anxiety, etc.), featuring professional psychologists.
- **Appointment Scheduling**: Students can book sessions with licensed psychologists directly through the platform.
- **Confidential Chat System**: Secure messaging between students and an AI chatbot for follow-up support.
- **Mental Health Resources**: A curated library of self-help materials, articles, and exercises for students.
- **Administrative Dashboard for Schools**: Schools can monitor student participation and access general mental health trends (without violating privacy).
- **Psychologist Management System**: Tools for psychologists to manage their schedules, session notes, and earnings.

## Target Users

- **Primary Users**:
  - School managers
  - Students
  - Psychologists
- **Secondary Users**:
  - Parents


<a id="tech"></a>
## 1. Tech Stacks

<details>
  <summary>Client</summary>
  <ul>
    <li>Typescript</li>
    <li>Next JS</li>
    <li>React Native</li>
    <li>Hero UI</li>
    <li>Tailwind CSS</li>
    <li>Axios</li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li>ASP.NET Core Web API</li>
    <li>.NET Entity Framework</li>
    <li>ASP.NET Identity</li>
    <li>Serilog</li>
    <li>Quazt.NET Job Schedulings</li>
    <li>JWT Authentication</li>
    <li>Postman</li>
    <li>Swagger OpenAPI</li>
    <li>ASP.NET SignalR Realtime Communication</li>
    <li>Mediator Design Pattern</li>
    <li>CQRS with Clean Architecture</li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li>Microsoft Azure SQL Server</li>
    <li>Redis</li>
  </ul>
</details>

<details>
<summary>API Deployment</summary>
  <ul>
    <li>Docker</li>
    <li>Microsoft Azure Cloud Services</li>
    <li>Github Actions Auto Deployment</li>
  </ul>
</details>

<details>
<summary>Others</summary>
  <ul>
    <li>Gemini API - AI Agent Chat Service</li>
    <li>Stripe API - Payment Service</li>
    <li>WebRTC - Video Streaming Service</li>
    <li>Cloudinary File Storage - Static File Storages</li>
  </ul>
</details>

<a id="uc-diagram"></a>
## 2. Use Case Diagram
<img src="./readme/images/MindSpace-UsecaseDiagram.png" alt="MindSpace-UsecaseDiagram" />

<a id="db-design"></a>
## 3. Database Design
<img src="./readme/images/MindSpace-ERD.png" alt="MindSpace-ERD" />

<a id="architecture"></a>
## 4. Architecture Diagram
<img src="./readme/images/MindSpace-ArchitectureDiagram.png" alt="MindSpace-ArchitectureDiagram" />

<a id="screen-flow"></a>
## 5. Screen Flow

### 5.1. Student Screen Flow:
<img src="./readme/images/MindSpace-StudentScreenflow.png" alt="MindSpace-StudentScreenflow" />

### 5.2. Parent Screen Flow:
<img src="./readme/images/MindSpace-ParentScreenflow.png" alt="MindSpace-ParentScreenflow" />

### 5.3. Psychologist Screen Flow:
<img src="./readme/images/MindSpace-PsychologistScreenFlow.png" alt="MindSpace-PsychologistScreenflow" />

### 5.4. School Manager Screen Flow:
<img src="./readme/images/MindSpace-SchoolManagerScreenflow.png" alt="MindSpace-SchoolManagerScreenflow" />

### 5.5. Admin Screen Flow:
<img src="./readme/images/MindSpace-AdminScreenflow.png" alt="MindSpace-AdminScreenflow" />

<a id="team-members"></a>
## 6. Team members
- [Vu Kim Duy](https://github.com/AnonyFriday): Project Leader, Web Front-End, Back-End Developer
- [Phan Tuan Dat](https://github.com/imbatcat): Web Front-end, Back-End Developer
- [Vo Thi Mai Hoa](https://github.com/vohoa2004): Web Front-End, Back-End Developer
- [Nguyen Thi Bich Duyen](https://github.com/cuckoo01): Web Front-End Developer
- [Tran Van Tien Dat](https://github.com/datTOK): Web Front-End Developer
- [Le Minh Quan](https://github.com/QuanLM270302): Mobile Front-End Developer


<a id="app-a"></a>

# Appendix A
