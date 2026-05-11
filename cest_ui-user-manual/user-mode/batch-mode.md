# Batch Mode

{% stepper %}
{% step %}
Click the **Batch Processing** button in the top-right corner of the Single Patient page, or select **Batch Mode** from the User Dashboard (step 3.1.4).

{% embed url="https://youtu.be/kDkgfd8qxNk" %}
{% endstep %}

{% step %}
Select the patient folders containing the files for automated lesion classification. Either upload a new **parent patient folder** (a parent folder with multiple patient subfolders inside) using the **Upload Folder** button, or select previously uploaded folders using the **Select Patient Folders** button.

{% embed url="https://youtu.be/IB_S2kFeAus" %}
{% endstep %}

{% step %}
Select or deselect patients to be processed for a batch run. Toggle the checkbox next to the patient number, or use the **Select All Patients** and **Deselect All** buttons. By default, all patients are selected.

{% embed url="https://youtu.be/EYubCu5_7oY" %}
{% endstep %}

{% step %}
Select or deselect lesions to be processed for each patient. Expand the **Select Lesions** dropdown and toggle the checkboxes, or use the **Select All** and **Deselect All** buttons. By default, all lesions are selected for each patient.

{% embed url="https://youtu.be/UrPLHcXkmnQ" %}
{% endstep %}

{% step %}
Select or deselect channel configurations for each patient's lesion. Expand the **Select Configuration** dropdown and toggle the desired configurations, or use the **Select All** and **Deselect All** buttons. By default, only the **6 Channels High Power** configuration is selected, as it is the recommended configuration.

{% embed url="https://youtu.be/hbH1OU6GRj4" %}
{% endstep %}

{% step %}
Click the **Start Analyzing** button to start the batch run. Wait until the loading bar reaches 100%. An Excel file will automatically be downloaded by your browser with the classification results for each selected patient and lesion. Results are also displayed in the _Outcome_ column of the table.

{% embed url="https://youtu.be/KSPzAT-pWJs" %}
{% endstep %}

{% step %}
Click the **View** button next to each patient row to view individual patient files in detail. This button is disabled until an inference has been made for that patient.

{% embed url="https://youtu.be/US_oq987P-w" %}
{% endstep %}

{% step %}
Once the view pop-up opens, it uses the same buttons and controls as Single Patient Mode. Use the dropdown buttons to switch between resampled and cropped lesion files, and between MRI modalities depending on your selected channel configuration.

{% embed url="https://youtu.be/OsnIolXO5vk" %}
{% endstep %}

{% step %}
Toggle the lesion overlay and heatmap overlay checkboxes to visualize the lesion mask and saliency attention maps on top of the resampled and cropped files, respectively. The checkbox automatically updates depending on your selection between resampled and cropped files in the dropdown menu.

{% embed url="https://youtu.be/Kyq2zLGLziM" %}
{% endstep %}
{% endstepper %}
