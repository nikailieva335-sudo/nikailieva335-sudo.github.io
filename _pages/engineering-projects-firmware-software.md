---
layout: default
title: Firmware and Software
parent: Engineering Projects
nav_order: 4
permalink: /engineering-projects/firmware/
---

# Firmware and Software

<div class="private-repo">
  <div class="repo-header">
    <svg viewBox="0 0 16 16" width="20" height="20"><path fill="currentColor" d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8z"></path></svg>
  </div>
  <h3><a href="https://github.com/nikailieva335-sudo/mhealth-tympanometer-ml-classifier" target="_blank">mHealth Tympanometer ML Embedded Classifier Training Data Processing and Model Training</a></h3>
  <p class="repo-tech"> | Python | scikit-learn | Neuton.AI | numpy | pandas | pickle | math | </p>
  <p class="repo-desc"> This project contains the data-processing pipeline used to prepare tympanometric datasets for machine learning model training, validation and evaluation. Each notebook applies a different preprocessing approach to the tympanometry data. These alternative datasets are used to compare modeling strategies and improve the accuracy and reliability of the tympanometry infection classifier.
</p>
</div>

<div class="private-repo">
  <div class="repo-header">
    <svg viewBox="0 0 16 16" width="20" height="20"><path fill="currentColor" d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8z"></path></svg>
  </div>
  <h3><a href="https://github.com/nikailieva335-sudo/tymp-ml-classifier-qemu" target="_blank">mHealth Tympanometer Neuton.AI Edge AI Model Evaluator</a></h3>
  <p class="repo-tech"> | Zephyr RTOS | C | Python | Neuton.AI | Edge AI | argparse | math | </p>
  <p class="repo-desc"> This repository evaluates Neuton.AI classification and anomaly detection models on an nRF52833 for the mHealth Tympanometer device. The project converts analysis csv data generated during training data processing into a C header file, loads the Neuton.AI model, performs inference on each test sample and pcompares the predicted output with the expected label. The evaluator outputs:

</p>
</div>

<div class="private-repo">
  <div class="repo-header">
    <svg viewBox="0 0 16 16" width="20" height="20"><path fill="currentColor" d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8z"></path></svg>
  </div>
  <h3><a href="https://github.com/nikailieva335-sudo/tymp-tip-occlusion" target="_blank">mHealth Tympanometer Tip Insertion Angle Sensor</a></h3>
  <p class="repo-tech"> | Zephyr RTOS | C | I2C | NVS | GPIO | IMU Sensor | UML | </p>
  <p class="repo-desc"> Implemented an MPU6050 IMU sensor to detect and issue a warning when the tip of the tympanometer is inserted at a wrong angle. Firmware allows for audiologist calibration and mirrors data for opposite ear.</p>
</div>

<div class="private-repo">
  <div class="repo-header">
    <svg viewBox="0 0 16 16" width="20" height="20"><path fill="currentColor" d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8z"></path></svg>
  </div>
  <h3><a href="https://github.com/nikailieva335-sudo/co2-monitor-design" target="_blank">Duke Children's Hospital CO2 Monitor Sensor Firmware</a></h3>
  <p class="repo-tech"> | Zephyr RTOS | C | I2C | SCD41 Sensor | </p>
  <p class="repo-desc"> Firmware for a CO2 monitoring wearable device for Duke Children's Hopsital. Currently embeds the SCD41 CO2 sensor on an nRF52833. </p>
</div>

<div class="private-repo">
  <div class="repo-header">
    <svg viewBox="0 0 16 16" width="20" height="20"><path fill="currentColor" d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8z"></path></svg>
  </div>
  <h3>CPAP Sleep Monitoring System</h3>
  <p class="repo-tech"> | Python | Flask | RESTful API | Tkinter | MongoDB | pytest | GitHub Actions | PEP-8 | </p>
  <p class="repo-desc">Built the patient-side GUI (Tkinter) for a sleep monitoring system simulating a CPAP device, featuring CPAP data file analysis, input validation, conditional red-text alerts for elevated apnea counts, and device reset functionality. Implemented an automatic 30-second polling loop so the GUI pulls in new CPAP pressure settings from the monitoring station on its own. Co-developed a Flask RESTful API with a MongoDB database to support patient uploads, image storage, timestamp queries, and bidirectional pressure updates between patient and monitoring stations, deployed to a Duke virtual machine. Collaborated with a teammate on the monitoring station GUI integration, wrote unit tests with pytest, and set up GitHub Actions for continuous integration.</p>
</div>

<div class="private-repo">
  <div class="repo-header">
    <svg viewBox="0 0 16 16" width="20" height="20"><path fill="currentColor" d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8z"></path></svg>
  </div>
  <h3><a href="https://github.com/nikailieva335-sudo/hormone-tracker-app" target="_blank">Hormone Tracker App — PCOS ML Training</a></h3>
  <p class="repo-tech"> | Python | Machine Learning | PyTorch | Transformers | SQLite | CustomTkinter | </p>
  <p class="repo-desc">Developed an application to log daily symptoms for PCOS patients and provide a summary of trends for clinicians. Fine-tuned a BERT model with a synthetic dataset to categorize symptoms based on user input and log into SQLite database. Project produces a doctor summary.</p>
</div>

<style>
.private-repo {
  margin: 1.5rem 0;
  padding: 1rem 1.25rem;
  border: 1px solid #444;
  border-radius: 8px;
}
.repo-header {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  margin-bottom: 0.25rem;
  flex-wrap: wrap;
}
.repo-header svg {
  flex-shrink: 0;
  color: #aaa;
}
.private-repo h3 {
  margin: 0.25rem 0 0;
  font-size: 1rem;
}
.private-repo h3 a {
  color: #e6e1e8;
  text-decoration: none;
}
.private-repo h3 a:hover {
  text-decoration: underline;
}
.private-badge {
  font-size: 0.7rem;
  color: #aaa;
  border: 1px solid #555;
  border-radius: 4px;
  padding: 0.1rem 0.5rem;
}
.repo-tech {
  margin: 0.35rem 0 0;
  font-size: 0.875rem;
  color: #999;
  font-weight: 600;
}
.repo-desc {
  margin: 0.5rem 0 0;
  font-size: 0.875rem;
  color: #ccc;
}
</style>
