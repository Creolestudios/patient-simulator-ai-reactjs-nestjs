# patient-simulator-ai-reactjs-nestjs
Patent simulator is a kind of Objective Structured Clinical Examination, where the perusing or practicing doctors can conduct an examination with an AI based patient who will likely report different symptoms every time allowing the doctors to diagnose the illnesss. 


## AI Meeting Insights App (TranscriptGpt)

## Table of Contents

1. [Introduction](#1-introduction)
2. [Project Overview](#2-project-overview)
3. [Getting Started](#3-getting-started)
4. [Code Structure](#4-code-structure)
5. [Dependencies](#5-dependencies)
6. [Deployment](#7-deployment)
7. [Usage](#8-usage)


## 1. Introduction

Welcome to Patent Simulator, a cutting-edge Objective Structured Clinical Examination (OSCE) tool designed to enhance medical professionals' diagnostic skills. With AI-based patients reporting varied symptoms in each interaction, this simulator offers a dynamic platform for doctors to hone their diagnostic abilities effectively. Immerse yourself in realistic patient scenarios and elevate your clinical expertise with Patent Simulator.


## 2. Project Overview

Patent Simulator is an innovative application aimed at providing practicing and aspiring doctors with a dynamic platform to enhance their diagnostic capabilities.


## 3. Getting Started

To get started with the OSCE-GPT, follow these steps:

### Prerequisites

Make sure you have the following installed:

- A modern web browser (e.g., Chrome, Firefox, Safari)
- An internet connection (for fetching external dependencies)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Creolestudios/patient-simulator-ai-reactjs-nestjs.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd patient-simulator-ai-reactjs-nestjs
   ```

3. **Client and Server Setup**

   * Create and Add credentials in .env file 

   ```
   PORT=

   BASE_URL=

   OPEN_AI_KEY=

   

   ```

   ## Client Setup

   ```
   npm install 

   npm start 

   ```


   ## Server Setup


   ```
   npm install 

   npm run start:dev

   ```




## 4. Code Structure

The project follows a modular and organized structure to enhance readability, maintainability, and scalability. Key components include:

- **ReactJs** The main structure of the web page designed using React Framework.
- **NodeJs** Backend Logic written in nodejs, Logic for handling user interactions, getting transcript , and giving summary as Situations, Challenges, Risks, Impacts and Solutions.
- **OpenAI** Using OpenAI api key to get summary of Situations, Challenges, Risks, Impacts and Solutions from transcript.

## 5. Dependencies

- **OpenAI** Provides different text based models like gpt-3.5,gpt-4,text-ada-embedding



## 6. Deployment

The OSCE-GPT APP is deployed and accessible online. You can use the following link to access the application: [OSCE-GPT APP](https://oscegpt.com/)

## 7. Usage

1. **Select Diesase from List:**
   - Add transcript manually or fetch from meeting

2. **Select Case:**
   - Select/Clieck on time interval for which you want to get summary for.

3. **Read About Disease types:**
   - Click the "submit" button after selecting Keywords.

4. **Tell about your disease by speaking in mic or keyboard:**
   - Click the "submit" button after selecting situations to get Challenges.

5. **wait while getting feedback:**
   - Click the "submit" button after selecting Challenges to get Risk.
