# Single Patient

### 1. Select the desired channel configuration

Select the desired channel configuration to run an inference using the dropdown button in the top-left corner of the left sidebar.

Files will not be resampled and populated into the viewer until a channel configuration has been selected.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/wnAfYFQkJyY" allowfullscreen></iframe>
</div>


### 2. Select the patient folder

Select the patient folder containing the files for the automated lesion classification. Either upload a new **patient folder** (not individual files) using the **Upload New Patient Folder** button, or select a previously uploaded folder using the **Select Uploaded Folder** button.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/jTeCs_AQaYk" allowfullscreen></iframe>
</div>


### 3. Verify the auto-matched modalities

Verify that all auto-matched modalities have selected the correct files. If any modality could not be auto-matched, or if a file was matched incorrectly, manually upload the appropriate file using the **Change** button inside the modality's box.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/p9xXChNtl_w" allowfullscreen></iframe>
</div>


### 4. Select the desired lesion

Select the desired lesion to run the inference on, using the same **Change** button from step 3.2.3 if the default lesion is not your intended one.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/DBwVexcoEEU" allowfullscreen></iframe>
</div>


?> While multiple lesions for the same patient can be classified, this mode only allows one lesion to be processed at a time. If a new lesion for the same patient needs to be processed, it is **strongly recommended to reload the page** by pressing **Ctrl + F5** on the keyboard, or by clicking the refresh symbol in the browser.


<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/xnWMgOZYr8w" allowfullscreen></iframe>
</div>


### 5. Select the resampled file

Select the resampled file to view in the main viewer using the dropdown selector.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/DtI_tOIjpnM" allowfullscreen></iframe>
</div>


### 6. Use the main viewer

Use the main viewer to visualize the resampled files of the selected patient. Follow the collapsible information panels for mouse and keyboard controls related to the different visualization features.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/hFYVMJaJGWY" allowfullscreen></iframe>
</div>


### 7. Toggle the lesion mask overlay

Toggle the lesion mask overlay to analyze the selected lesion.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/ghczW251ER8" allowfullscreen></iframe>
</div>


### 8. Start Processing

Click the **Start Processing** button to generate the cropped files for each selected modality. Scroll down to see the generated cropped files in the second viewer once the loading bar has finished.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/Obn4wGFhOx8" allowfullscreen></iframe>
</div>


### 9. Use the second viewer

Use the second viewer to visualize the cropped files. It has the same mouse and keyboard controls as the main viewer for all visualization features.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/qXXAISNPeqE" allowfullscreen></iframe>
</div>


### 10. Start Analyzing

Click the **Start Analyzing** button to make an inference for the selected lesion. Scroll down to see the classification outcome results once loading has finished.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/hjdNL7sM-kY" allowfullscreen></iframe>
</div>


### 11. Toggle the heatmap overlay

Toggle the heatmap overlay to produce saliency maps showing the attention the model placed on all areas of the cropped lesion file to produce the classification outcome.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/xG8uGrLI8lU" allowfullscreen></iframe>
</div>


<div style="display:flex; justify-content:space-between; margin-top: 48px; padding-top: 16px; border-top: 1px solid #efefef;">
  <a href="#/cest_ui-user-manual/user-mode/login-dashboard" style="display:inline-flex; align-items:center; gap:6px; font-size:13.5px; font-weight:500; color:#555; text-decoration:none; padding:8px 14px; border:1px solid #e5e5e5; border-radius:7px;">← Login & Dashboard</a>
  <a href="#/cest_ui-user-manual/user-mode/batch-mode" style="display:inline-flex; align-items:center; gap:6px; font-size:13.5px; font-weight:500; color:#555; text-decoration:none; padding:8px 14px; border:1px solid #e5e5e5; border-radius:7px;">Batch Mode →</a>
</div>

