# Batch mode

1. Click the **Batch Processing** button in the top-right corner of the demo page.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/-Aa8VdwgGww" allowfullscreen></iframe>
</div>


2. Select or deselect patients to be processed for a batch run.

This can be done by toggling the checkbox next to the patient number, or by using the **Select All Patients** and **Deselect All** buttons. By default, all patients are selected.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/Rcy6h60FrVo" allowfullscreen></iframe>
</div>


3. Select or deselect lesions to be processed for each patient in the batch run.

Expand the **Select Lesions** dropdown and toggle the checkbox next to each lesion, or use the **Select All** and **Deselect All** buttons. By default, all lesions are selected for each patient.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/yWZs3RlEkwg" allowfullscreen></iframe>
</div>


4. Select or deselect channel configurations to be used to run inferences.

Expand the **Select Configuration** dropdown and toggle the desired configurations, or use the **Select All** and **Deselect All** buttons. By default, only the **6 Channels High Power** configuration is selected, as it is the recommended configuration.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/dW_rWe57uKc" allowfullscreen></iframe>
</div>


5. Click the **Start Analyzing** button to start the batch run.

Wait until the loading bar reaches 100%. An Excel file will automatically be downloaded by your browser with the classification results for each selected patient and lesion. Results are also displayed in the _Outcome_ column of the table.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/dv38KACrU5w" allowfullscreen></iframe>
</div>


6. Click the **View** button next to each patient row to view individual patient files in detail.

This button is disabled until an inference has been made.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/huf_er_uxNU" allowfullscreen></iframe>
</div>


7. Once the view pop-up opens, it uses the same buttons and controls as Single Patient Mode.

Use the dropdown buttons to switch between resampled files and cropped lesion files, and between MRI modalities depending on your selected channel configuration.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/tSuEPfZe6vQ" allowfullscreen></iframe>
</div>


8. Toggle the lesion overlay and heatmap overlay checkboxes to visualize the lesion mask and saliency attention maps on top of the resampled files and cropped files, respectively.

The checkbox automatically updates depending on your selection between resampled and cropped files in the dropdown menu.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/MZl5gKiQi5Q" allowfullscreen></iframe>
</div>

<div style="display:flex; justify-content:space-between; margin-top: 48px; padding-top: 16px; border-top: 1px solid #efefef;">
  <a href="#/cest_ui-user-manual/demo-mode/single-patient" style="display:inline-flex; align-items:center; gap:6px; font-size:13.5px; font-weight:500; color:#555; text-decoration:none; padding:8px 14px; border:1px solid #e5e5e5; border-radius:7px;">← Single Patient Mode</a>
  <a href="#/cest_ui-user-manual/user-mode/README" style="display:inline-flex; align-items:center; gap:6px; font-size:13.5px; font-weight:500; color:#555; text-decoration:none; padding:8px 14px; border:1px solid #e5e5e5; border-radius:7px;">User Mode Overview →</a>
</div>

