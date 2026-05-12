# Batch Mode


1. Click the **Batch Processing** button in the top-right corner of the Single Patient page, or select **Batch Mode** from the User Dashboard (step 3.1.4).

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/kDkgfd8qxNk" allowfullscreen></iframe>
</div>

2. Select the patient folders containing the files for automated lesion classification. Either upload a new **parent patient folder** (a parent folder with multiple patient subfolders inside) using the **Upload Folder** button, or select previously uploaded folders using the **Select Patient Folders** button.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/IB_S2kFeAus" allowfullscreen></iframe>
</div>

!> **Warning:** Batch mode requires strict adherence to naming conventions. Unlike single patient mode, you cannot manually map files during the process. Any files that do not match the <a href="#/cest_ui-user-manual/user-mode/login-dashboard?id=file-naming-convention" style="display: inline-block; vertical-align: middle; font-size: 13px; font-weight: 500; color: #444; text-decoration: none; padding: 4px 10px; border: 1px solid #ddd; border-radius: 6px; line-height: 1.2; margin: 0 2px; background: #fafafa;">File Naming Convention Table</a> will be automatically skipped, and those results will be marked as "missing modalities." 

3. Select or deselect patients to be processed for a batch run. Toggle the checkbox next to the patient number, or use the **Select All Patients** and **Deselect All** buttons. By default, all patients are selected.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/EYubCu5_7oY" allowfullscreen></iframe>
</div>

4. Select or deselect lesions to be processed for each patient. Expand the **Select Lesions** dropdown and toggle the checkboxes, or use the **Select All** and **Deselect All** buttons. By default, all lesions are selected for each patient.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/UrPLHcXkmnQ" allowfullscreen></iframe>
</div>


5. Select or deselect channel configurations for each patient's lesion. Expand the **Select Configuration** dropdown and toggle the desired configurations, or use the **Select All** and **Deselect All** buttons. By default, only the **6 Channels High Power** configuration is selected, as it is the recommended configuration.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/hbH1OU6GRj4" allowfullscreen></iframe>
</div>


6. Click the **Start Analyzing** button to start the batch run. Wait until the loading bar reaches 100%. An Excel file will automatically be downloaded by your browser with the classification results for each selected patient and lesion. Results are also displayed in the _Outcome_ column of the table.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/KSPzAT-pWJs" allowfullscreen></iframe>
</div>


7. Click the **View** button next to each patient row to view individual patient files in detail. This button is disabled until an inference has been made for that patient.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/US_oq987P-w" allowfullscreen></iframe>
</div>

8. Once the view pop-up opens, it uses the same buttons and controls as Single Patient Mode. Use the dropdown buttons to switch between resampled and cropped lesion files, and between MRI modalities depending on your selected channel configuration.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/OsnIolXO5vk" allowfullscreen></iframe>
</div>

9. Toggle the lesion overlay and heatmap overlay checkboxes to visualize the lesion mask and saliency attention maps on top of the resampled and cropped files, respectively. The checkbox automatically updates depending on your selection between resampled and cropped files in the dropdown menu.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/Kyq2zLGLziM" allowfullscreen></iframe>
</div>

<div style="display:flex; justify-content:space-between; margin-top: 48px; padding-top: 16px; border-top: 1px solid #efefef;">
  <a href="#/cest_ui-user-manual/user-mode/single-patient" style="display:inline-flex; align-items:center; gap:6px; font-size:13.5px; font-weight:500; color:#555; text-decoration:none; padding:8px 14px; border:1px solid #e5e5e5; border-radius:7px;">← Single Patient Mode</a>
  <a href="#/cest_ui-user-manual/accounts" style="display:inline-flex; align-items:center; gap:6px; font-size:13.5px; font-weight:500; color:#555; text-decoration:none; padding:8px 14px; border:1px solid #e5e5e5; border-radius:7px;">Accounts →</a>
</div>
